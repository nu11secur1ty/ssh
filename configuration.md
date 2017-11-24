# Generate ssh key
```
ssh-keygen -t rsa -b 4096 -C "example@mail.com"

```

# Adding your SSH key to the ssh-agent

```
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa

```

# Adding a new SSH key to your GitHub account

```
cat ~/.ssh/id_rsa.pub
```
- copy the key and paste into your account ssh field

# Test

- Turn on SSH connection for your repository

# We recommend every repository include a README, LICENSE, and .gitignore.
# …or create a new repository on the command line

```
echo "# testssh" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:nu11secur1ty/testssh.git
git push -u origin master
```
# …or push an existing repository from the command line
```
git remote add origin git@github.com:nu11secur1ty/testssh.git
git push -u origin master
```
# …or import code from another repository






