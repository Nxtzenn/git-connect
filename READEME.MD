 # connect basic
 ## create a new repository on the command line

    echo "# git-connect" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/skyGwork/git-connect.git
    git push -u origin main
    
`Alternatively`

  ## push an existing repository from the command line

    git remote add origin https://github.com/skyGwork/git-connect.git
    git branch -M main
    git push -u origin main
    
## view
   sel@SKY01:/mnt/d/Dev-Projects/gitconnect$ git remote -v
   origin  https://github.com/skyGwork/git-connect.git (fetch)
   origin  https://github.com/skyGwork/git-connect.git (push)
   sel@SKY01:/mnt/d/Dev-Projects/gitconnect$
