# my_document
自分自身が勉強したこと、コマンド、どんなことができるのか等をまとめたメモをここに記載します。







(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint: 	git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint: 	git branch -m <name>
Initialized empty Git repository in /Users/kounoteruki/GitCommand/.git/
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % mkdir Comman
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % mkdir Command
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % rm -r Comman
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % ls
Command
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git init
Reinitialized existing Git repository in /Users/kounoteruki/GitCommand/.git/
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git add .
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git commit -m "コマンドフォルダを作成"
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'origin'
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % ls
Command
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git remote add origin git@github.com:teruteru0/my_document.git
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'github.com:teruteru0/my_document.git'
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % ls
Command
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git init
Reinitialized existing Git repository in /Users/kounoteruki/GitCommand/.git/
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git add .
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git commit -m "コマンドフォルダを作成"
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git remote add origin git@github.com:teruteru0/my_document.git
error: remote origin already exists.
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git push -u origin master                                     
error: src refspec master does not match any
error: failed to push some refs to 'github.com:teruteru0/my_document.git'
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git brahch
git: 'brahch' is not a git command. See 'git --help'.

The most similar command is
	branch
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git branch
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand %     git push --set-upstream origin master

error: src refspec master does not match any
error: failed to push some refs to 'github.com:teruteru0/my_document.git'
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git pull origin develop
fatal: couldn't find remote ref develop
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git pull origin master
fatal: couldn't find remote ref master
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git branch
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git fetch
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
Unpacking objects: 100% (3/3), 723 bytes | 361.00 KiB/s, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
From github.com:teruteru0/my_document
 * [new branch]      main       -> origin/main
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % ls
Command
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git pull origin master
fatal: couldn't find remote ref master
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand %     git push --set-upstream origin master

error: src refspec master does not match any
error: failed to push some refs to 'github.com:teruteru0/my_document.git'
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git push -u origin master                
error: src refspec master does not match any
error: failed to push some refs to 'github.com:teruteru0/my_document.git'
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git remote add origin git@github.com:teruteru0/my_document.git
error: remote origin already exists.
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git init                                                      
Reinitialized existing Git repository in /Users/kounoteruki/GitCommand/.git/
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git add .                                                     
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git commit -m "コマンドフォルダを作成"                        
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git addd
git: 'addd' is not a git command. See 'git --help'.

The most similar command is
	add
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % ls
Command
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git remote add main git@github.com:teruteru0/my_document.git
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git push -u origin main                       
error: src refspec main does not match any
error: failed to push some refs to 'github.com:teruteru0/my_document.git'
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git push -u main main  
error: src refspec main does not match any
error: failed to push some refs to 'github.com:teruteru0/my_document.git'
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand %     git push --set-upstream origin master

error: src refspec master does not match any
error: failed to push some refs to 'github.com:teruteru0/my_document.git'
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand %  git fetch
$ git merge origin/master
zsh: command not found: $
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand %  git fetch
git merge origin/master 
merge: origin/master - not something we can merge
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand %  git fetch
git merge origin/main 
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % ls
Command		README.md
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git remote add main git@github.com:teruteru0/my_document.git
error: remote main already exists.
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git push -u origin main                                 
error: src refspec main does not match any
error: failed to push some refs to 'github.com:teruteru0/my_document.git'
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git branch             
* master
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % git push -u origin master
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/teruteru0/my_document/pull/new/master
remote: 
To github.com:teruteru0/my_document.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
(base) kounoteruki@kounoterukinoMacBook-Pro GitCommand % 

