---
title: express notebook
date: 2017-04-19 17:57:37
tags: 
- node
- js 
- express
---

## Quick Start

### Install
```
npm install express-generator -g
express myapp --view=ejs
npm install
# Run the myapp on Windows
SET DEBUG=myapp:* & npm start

# Run myapp on Linux/Mac OS X
DEBUG=myapp:* npm start

```

### Add nodemon
```
npm install --save-dev nodemon
```
### package.json
```
"scripts": {
    "start": "node ./bin/www",
    "devstart": "nodemon ./bin/www"
  }

#npm run devstart 
```
[Link](http://www.jianshu.com/p/c5baef64563a)
