# dual


# how to do it 

## first config files 

### .ssh/config  

```
# narangyawali
Host github.com
	HostName github.com
	User git
	IdentityFile ~/.ssh/id_rsa
	IdentitiesOnly yes

# lluciferr
Host github.com-l
	HostName github.com
	User git
	IdentityFile ~/.ssh/id_ed25519_lucifer
	IdentitiesOnly yes

```

###  git config --list 

```

user.email=nryng123@gmail.com
user.name=naran gyawali
alias.a=add .
alias.cm=commit -m
alias.pom=push origin main
init.defaultbranch=main
core.editor=vim
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
remote.origin.url=git@github.com:lluciferr/dual.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.main.remote=naranorigin
branch.main.merge=refs/heads/main
user.email=n.gya054@gmail.com
user.name=chirag kumar
remote.naranorigin.url=git@github.com:narangyawali/dual.git
remote.naranorigin.fetch=+refs/heads/*:refs/remotes/naranorigin/*
remote.vorigin.url=git@github.com-l:lluciferr/dual.git
remote.vorigin.fetch=+refs/heads/*:refs/remotes/vorigin/*

```
- gist 

remote.naranorigin.url=git@github.com:narangyawali/dual.git
for 
	HostName github.com

----

remote.vorigin.url=git@github.com-l:lluciferr/dual.git
for 
	HostName github.com-l

---- 


