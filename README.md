# 

How to run site?

* prepare system 
** install latest node (maybe in nvm -- node version manager)

* Install `antora` (3.1.7+) 

From scratch

1. `node -e "fs.writeFileSync('package.json', '{}')"` -- create empty package
2. `npm i -D -E @antora/cli@3.1 @antora/site-generator@3.1` -- install `antora` packages

Or if files `package-lock.json` and `package.json` exists -- just `npm install` (node package manager, install packages from configurations) 

* Build the site!

* `npx antora --fetch antora-playbook.yml`