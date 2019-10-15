# gitattributes
gitattributes

Custom file base on:

https://github.com/alexkaratarakis/gitattributes/blob/master/Java.gitattributes
https://github.com/alexkaratarakis/gitattributes/blob/master/Common.gitattributes
https://github.com/alexkaratarakis/gitattributes/blob/master/.gitattributes

Change End of Line
https://help.github.com/es/articles/configuring-git-to-handle-line-endings

$ git add . -u
$ git commit -m "Saving files before refreshing line endings"
$ git add --renormalize .  # Update index with renormalized files
$ git status               # Show the files that will be normalized
$ git commit -m "Introduce end-of-line normalization"

--renormalize feature with Git v2.16 and higher

Update git on Debian
https://linuxize.com/post/how-to-install-git-on-debian-9/

Always renormalize
https://gist.github.com/robert-claypool/6c9812e8c8831e131a12
