
# How to create a local repo in git and upload to Github
## Instructions for creating a local repository

* At the command line, I used mkdir inside a tmp dir to create the repo name, upload_test_repo
* I used git init to generate the git directory
* I created a local README.md file with the vim text editor 
* I staged the file with git add -A and git commit -m "comment"
* Note: Before uploading the file 'pushing', I had to create a repository inside Github first
* When creating a new repo in Github, I chose not to create a README.md file as I will upload one
* I used git remote add origin https://github.com/username/new_repo_name
* Then git push -u origin master  (not certain yet what the -u flag does)

These actions pushed a README.md file into my new repo on Github.com
 
