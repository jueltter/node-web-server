# node-web-server

```bash
# to test locally
node server.js
nodemon server.js
npm start
npm test
```

```bash
# to config github
# to list ssh keys
ls -al ~/.ssh
# to generate a ssh key
ssh-keygen -t rsa -b 4096 -C 'stalin.amagua@outlook.com'
# to start up ssh agent program
eval `ssh-agent -s`
# to add a ssh key
ssh-add ~/.ssh/id_rsa
# associate the ssh key with your github account
# to test configuration
ssh -T git@github.com
```

```bash
# to config heroku
# after install heroku command-line tools (https://devcenter.heroku.com/articles/heroku-cli)
heroku --help
# to loign into your heroku account
heroku login
# to associate a ssh key with your heroku account
heroku keys:add
# to list your associated ssh keys
heroku keys
# to remove a ssh key
heroku keys:remove
# to test configuration
ssh -v git@heroku.com
```

```bash
# to deploy to heroku
heroku create
git push heroku
heroku open
```