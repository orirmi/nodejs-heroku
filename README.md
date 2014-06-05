nodejs-heroku
=============

1. create local repo with Procfile and package.json deps (npm init, git init/add/commit, ...)
2. run 
```bash
$ heroku init
```
3. push to heroku
```bash
$ git push heroku master
```
4. add postgres addon
```bash
$ heroku addons:add heroku-postgresql:dev
```
