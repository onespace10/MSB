# Docker image building

```
docker build -t daya123/nginx5 .

build -t daya123/nginx5 .

$ vi Dockerfile
$ docker build -t daya123/nginx5 . 
$ docker images
$ docker push daya123/nginx5
```

# To upload for git web
```
user@DAYA MINGW64 ~/MSB
$ git init (Caution : Initial Only)
Initialized empty Git repository in C:/Users/user/MSB/.git/

user@DAYA MINGW64 ~/MSB (master)
$ git add -A

user@DAYA MINGW64 ~/MSB (master)
$ git commit -m "Newly modified dockers"
[master (root-commit) 477bace] Newly modified dockers     
 AA files changed, BB insertions(+)

user@DAYA MINGW64 ~/MSB (master)
$ git remote add origin https://github.com/onespace10/MSB.git

user@DAYA MINGW64 ~/MSB (master)
$ git push -u origin master
Enumerating objects: CC, done.
Counting objects: 100% (CC/CC), done.
Delta compression using up to 8 threads
Compressing objects: 100% (DD/DD), done.
Writing objects: 100% (CC/CC), 17.23 KiB | 1.72 MiB/s, done.
Total CC (delta 9), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (D/D), done.
To https://github.com/onespace10/MSB.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
```

# MSB
https://github.com/onespace10/MSB.git
