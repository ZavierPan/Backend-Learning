# Express Locallibrary Tutorial

```
# ./backend-learning
# create project
express express-locallibrary-tutorial --view=pug

# install package
cd express-locallibrary-tutorial
npm install

# run
SET DEBUG=express-locallibrary-tutorial:* & npm start
```

```
# install nodemon then can monitor for any change and automatically restart the server
npm install --save-dev nodemon
```

```
# modify package.json
  "scripts": {
    "start": "node ./bin/www",
    "devstart": "nodemon ./bin/www"
  },

# run 
SET DEBUG=express-locallibrary-tutorial:* & npm run devstart
```