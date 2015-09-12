# Weston's Git Guide

### Introduction
Git is a distributed version control system. If you don't know what version control is, [go do a little reading](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) before actually learning git. The "distributed" part basically means that instead of a single server hosting the code repository for everyone, each user has their own individual copy of the repo which they can make changes to regardless of any network connection. 

### Quick Reference
##### [Cloning](http://git-scm.com/docs/git-clone)
+ Clone remote repository
  + `git clone <git url>`
    + e.g. `git clone https://github.com/wwselleck/weston-guides`
+ Clone remote repository into directory with custom name
  + `git clone <git url> [new name]` 
    + e.g. `git clone https://github.com/wwselleck/weston-guides programming-guides`

#### Commiting
`git commit 
