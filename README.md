# Useful git commands:

### Creating a repository online for the <b>first time</b>!
```sh
$ touch README.md
$ git init
$ git add README.md  #adds everything from local to staging
$ git commit -m "first commit"
$ git remote add origin https://github.com/kevinog/kevin.git
$ git push -u origin master
# put in username $ password
```
### When adding on to your repository online with changes
```sh
$ git add .
$ git commit -m 'waht has changed'
$ git push
# put in username and password
```
### No more username and password for every push
```sh
$ git remote set-url origin github@github.com/username/yourReponame.git