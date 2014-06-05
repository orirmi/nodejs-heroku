nodejs-heroku
=============


create initial package.json
```bash
$ npm init
```

create procfile 
```bash
echo web: node index.js > Procfile
```

create local repo
```bash
$ git init
```

make initial commit
```bash
git add . && git commit -m "Initial commit"
```

create heroku app 
```bash
$ heroku apps:create myapp
```

push to heroku
```bash
$ git push heroku master
```
add postgres addon
```bash
$ heroku addons:add heroku-postgresql:dev
```
