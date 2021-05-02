# reading-notes2
## To see which remote servers you've got got configured, you could run the git remote command. It lists the short names of every remote deal with you’ve specified. If you’ve cloned your repository, you need to at the least see origin – this is the default name Git gives to the server you cloned from: ##

$ git clone https://github.com/schacon/ticgit
Cloning into ticgit
remote: Reusing existing pack: 1857, done.
remote: Total 1857 (delta 0), reused 0 (delta 0)
Receiving objects: 100% (1857/1857), 374.35 KiB | 268.00 KiB/s, done.
Resolving deltas: 100% (772/772), done.
Checking connectivity... done.
$ cd ticgit
$ git remote
origin
##You also can specify -v, which indicates you the URLs that Git has saved for the short name for use whilst analyzing and writing to that remote:##

$ git remote -v
origin https://github.com/schacon/ticgit (fetch)
