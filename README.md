# Opinionated Coder
My name is _Gian Carlo_ a.k.a. #gicappa# and I'm an opinionated coder. My opinions comes after more than 15 years of development and architectures of systems 

## IDE & Editors
## Application Structures
## Architectures
In this section I will present a bunch of architectures that can be built using chef over different server systems:
* AWS
* Digital Ocean
* Docker

## Hints & Snippets ToolBox
### GIT
#### Remove branches no longer on remote
```git gc --prune=now``` do the trick
```git fetch -p```
#### Rename a branch
````git branch -m <oldname> <newname>````

If you want to rename the current branch, you can simply do:

````git branch -m <newname>````

#### Chaching GIT credential for https access
```git config --global credential.helper osxkeychain```
or for linux
```git config --global credential.helper "cache --timeout=3600"```

http://stackoverflow.com/questions/5343068/is-there-a-way-to-skip-password-typing-when-using-https-github

# SysAdmin
## iotop 
http://www.cyberciti.biz/hardware/linux-iotop-simple-top-like-io-monitor/

# Opening a HTTP server on the curren directory
python -m SimpleHTTPServer
