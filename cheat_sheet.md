git init             = initialise version control in a directory
git add              = add a file to be version controlled
git status           = get the status of the files/versions in a directory
git log              = show a log of all versions
git commit -a        = take a snapshot of the files in the directory (new version)
git diff             = get the difference between file in directory and in repository
git checkout file    = bring a file back to your directory (HEAD)
git checkout version = bring a version from the repository back to your directory (HEAD)
git checkout -b new-branch = create a new branch
git checkout branch-name = move HEAD to the latest version of the branch
git branch            = list your current branches
git rm (-r)           = remove a file or directory
git mv                = move (rename) a file or directory
git push              = push changes from local .git to cloud .git
git pull              = pull changes from cloud .git to local .git and checkout latest
git clone             = clone a repository from the cloud

git status / git commit -a / git push


== Rename master to main ==
git checkout -b main
git branch -d master
===========================

Coffee break - come back at 3.45pm :-)

                   HEAD (main)
                     o (main)
        woof  meow   |
master   o--o--o--o--o   
            |
            o new-branch
            | cat -> dog
            o
           
       ~~~~~~~~~~~~~~~~~~~~~~
       
       GitHub    .git
       
       main o--o--o--o--o--o
       
       
    main   o--o--o--o--o--o--o
                       |
    add_tigers         o--o--o
