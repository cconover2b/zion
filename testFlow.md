**## I need to add each username as a collaborator under Settings and Collaborators**

**## Cloning**

```python
git clone https://github.com/cconover2b/zion.git
```

cd zion

**## Add and Commit to Git**

- Add a line to the [README.md](http://README.md) just for testing

```python
git add README.md
```

git commit -m "Added a line"

### I got an auth error

Author identity unknown

- ** Please tell me who you are.

Run

git config --global user.email "you@example.com"

git config --global user.name "Your Name"

to set your account's default identity.

Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'growthemp@GrowthPC2.(none)')