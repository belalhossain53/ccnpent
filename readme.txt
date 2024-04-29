$ git config --global user.name belalhossain53
$ git config --global user.email belalhossain53@gmail.com
$ git init 
$ touch app.py
$ touch netauto.py
$ git status
$ git add -A
$ git commit
 Initial commit
 :wq
$ git status
# After file modification
$ git add -A
$ git commit -m "Second commit"
$ git remote add origin git@github.com:belalhossain53/ccnpent.git
# SSH connection
$ ssh-keygen -t rsa -b 4096 -C "belalhossain53@gmail.com"
$ eval "$(ssh-agent -s)"
$ ssh-add ~/Desktop/ccnpent/ent
$ git status
$ git add -A
$ git commit -m "Third commit"
$ cat ent.pub 
$ git status
$ git push -u origin main

# 63402855+belalhossain53@users.noreply.github.com