# Weston's Git Guide

### Introduction
Git is a distributed version control system. If you don't know what version control is, [go do a little reading](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) before actually learning git. The "distributed" part basically means that instead of a single server hosting the code repository for everyone, each user has their own individual copy of the repo which they can make changes to regardless of any network connection. 

### Quick Reference
##### [git clone](http://git-scm.com/docs/git-clone)
+ Clone remote repository
  + `git clone <git url>`
    + e.g. `git clone https://github.com/wwselleck/weston-guides`
+ Clone remote repository into directory with custom name
  + `git clone <git url> [new name]` 
    + e.g. `git clone https://github.com/wwselleck/weston-guides programming-guides`

##### [git add](http://git-scm.com/docs/git-add)
+ Add single file to index
  + `git add <file path>`
    + e.g. `git add src/hello-world.js`
+ Add all files in working tree to index
  + `git add -A`
+ Add all changed files in working tree to index, ignoring new files
  + `git add -u`


#### Commiting
`git commit 
