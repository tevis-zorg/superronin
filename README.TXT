git hub pages

In this repos, learn about how to use git hub pages to host for the display of the project that i created.
we can depoloy it by open up our existing repos, go to setting, then go the the pages icon, choose build and depoloyment
choose the branch that we wanted to deploy, and then hit save.(we can choose which branch to focused on without affecting another branch.)

    1. 1stly, i create the repo which i want to work on by using "git clone 'ssh_link'"
        creating the index.html file to start (because the github pages only read the html file. the ejs is not working
        and for the JSX need more configuration that i haven't know yet)
    
    2. by using "git add ." which mean adding all files that i work on to put it inside the repo that i preffered, and
        "git commit -m 'message'" to commit the file that i work on.
        
    3. and the i'm adding some of the styling for the repo, with the branc of the main repo called styling. so what i've done is,
        "git checkout -b styling" to create the branch called styling, made css file called "style.css" and made some styling within,
        after finish on a simple styling, add the changes to the branch "git add ." to add all the changes, then "git commit -m 'commit_message'"
        and then push the file into the existing repo with "git push origin styling" because i'm working on that branch.
        
    4. for sometimes, we working on the branch as the main project in order to not disturb the runs of the main one,
        so here i learn to work on the branch called "branch-site" created by done "git checkout -b branch-site", adding file called
        "contact.html", made a simple linked tag content, add it "git add ." commit, "git commit -m 'commit message'"
        and push it inisde the repo "git push origin main 'branch-name'".
        
    NOTE : we cannot directly see the changes that we commit and push directly. we must compare and then create the pull request
            for it. and merge the changes which we made. to the side that we working on.