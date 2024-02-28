# what is version control?

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

# what is git?

Git is a distributed version control system (DVCS) designed to handle everything from small to very large projects with speed and efficiency. It allows multiple developers to collaborate on projects, tracking changes made to files, and coordinating work seamlessly.

# install git

<!-- download git  --> https://git-scm.com/download/win

# your identity

$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com

# initialize git

git init

# watch out for U - Untracked, M - Modified, A - Added

Untracked Unstage Stage
git add {file or command add . or add --all}
git status
git commit -m "first commit"
git log
git push -u origin main or git push or git push --set-upstream origin main
git clone
git pull
