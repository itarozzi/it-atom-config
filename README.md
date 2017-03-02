# it-atom-config

I use this GIT respository to share configurations and packages between
multiple  installation  installation of Atom.

I don't put packages into this repo, instead I use package-sync to
generate a packages.cson file.

https://atom.io/packages/package-sync 

I just need to remember to execute git pull and ''package-sync:sync''
command to update local package list, or ''package-sync:create-package-list'' and git commit&push to update remote repo.

