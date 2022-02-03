# I need to add each username as a collaborator under Settings and Collaborators

Cloning 
    git clone https://github.com/cconover2b/zion.git 
    cd zion 
Add and Commit to Git
    - Add a testing line to the README.md
    git add README.md 
    git commit -m "Added a line" 
    I got an auth error
        Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'growthemp@GrowthPC2.(none)')
 
        growthemp@GrowthPC2 MINGW64 ~/Documents/python-projects/zion (main)
$ git config --global user.email "youremail@gmail.com"


$ git config --global user.name "Craig Conover"
 
        $ git commit -m "Added a line of code."

 
        - I had to login with my browser and then it worked perfect. 

To remove as file from cached on Git
    if you have added a file or committed a file, to get it from being tracked so you can add it to another branch or something like that. 
    git rm --cached <file>

ex:
git rm --cached test2.py 

Add a New Branch and Add, Commit, and Push
    $ git branch craig
    $ git checkout craig
Switched to branch 'craig'
 
    git add test.py 
    git commit -m "Added a test file"
 
    git push -u https://github.com/cconover2b/zion.git
 
        After you have pushed once you can just use git push going forward
        git push 

Pull Requests 
    On Github.com click "Compare & pull request" 
    - Add any comments you want and click Pull request
    
Merge 
    On GitHub.com click on "Pull Requests"
    Click on the ones that are open
    If no conflicts then press "Merge pull request" 
    Then "Confirm merge"
    
    With Conflicts
        [Git merge conflicts | Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts) 
