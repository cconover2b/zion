- ^^**# I need to add each username as a collaborator under Settings and Collaborators**^^
- 
- Cloning 
    - ```python
git clone https://github.com/cconover2b/zion.git
``` 
    - ```python
cd zion
``` 
- Add and Commit to Git
    - - Add a testing line to the README.md
    - ```python
git add README.md
``` 
    - ```python
git commit -m "Added a line"
``` 
    - **I got an auth error**
        - ```python
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'growthemp@GrowthPC2.(none)')

``` 
        - ```python
growthemp@GrowthPC2 MINGW64 ~/Documents/python-projects/zion (main)
$ git config --global user.email "cconover2@gmail.com"

growthemp@GrowthPC2 MINGW64 ~/Documents/python-projects/zion (main)
$ git config --global user.name "Craig Conover"

``` 
        - ```python
$ git commit -m "Added a line of code."

``` 
        - - I had to login with my browser and then it worked perfect. 
- 
- To remove as file from cached on Git
    - if you have added a file or committed a file, to get it from being tracked so you can add it to another branch or something like that. 
    - ```python
git rm --cached <file>

ex:
git rm --cached test2.py
``` 
- 
- Add a New Branch and Add, Commit, and Push
    - ```python
$ git branch craig
```
    - ```python
$ git checkout craig
Switched to branch 'craig'

``` 
    - ```python
git add test.py
``` 
    - ```python
git commit -m "Added a test file"

``` 
    - ```python
git push -u https://github.com/cconover2b/zion.git

``` 
- 
- Pull Requests 
    - On Github.com click "Compare & pull request" 
    - - Add any comments you want and click Pull request
    - 
- Merge 
    - On GitHub.com click on "Pull Requests"
    - Click on the ones that are open
    - If no conflicts then press "Merge pull request" 
    - Then "Confirm merge"
    - 
    - With Conflicts
        - [Git merge conflicts | Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts) 