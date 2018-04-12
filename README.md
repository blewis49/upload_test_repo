# How to create repositories (repos) with git and Github
## Creating a local repo and then uploading it to Github with git

* From your Github account, create a new repository - do not initialize with a README.md file
* At the command line, use the mkdir inside the tmp dir to create the repo name, upload_test_repo
* I used git init to generate the git directory
* I created a local README.md file with the vim text editor 
* I staged the file with git add -A and git commit -m "comment"
* Note: Before uploading the file 'pushing', I had to create a repository inside Github first
* When creating a new repo in Github, I chose not to create a README.md file as I will upload one
* I used git remote add origin https://github.com/username/new_repo_name
* Then git push -u origin master  (not certain yet what the -u flag does)

These actions pushed a README.md file into my new repo on Github.com
<<<<<<< HEAD

This is a test line to verify my reinstall works and I can push to github. 
=======
 
## Creating a repo by "forking" or cloning a repo from github

* copy the URL from the repo on github
* navigate to a directory on your local machine
* use the command git clone URL
* navigate to this new repo directory on your machine to add or edit files
>>>>>>> da86ab48009183736a456f3dbb94cd89ef8757b7
