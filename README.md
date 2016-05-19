![](https://dl.dropboxusercontent.com/s/lwsewhpqj6wv06r/banner-128-raleway.png?dl=0)
---
# dotBind [![Travis-Ci Build Status](https://travis-ci.org/deluxe-pug/dotBind.svg?branch=dev)](https://travis-ci.org/deluxe-pug/dotBind)

DotBind is a software engineer's notebook. Capture cool code snippets while browsing the web or track solutions to bugs. Never forget code again.

Download the chrome extension.

Check out the web app @ [www.dotbind.io](http://www.dotbind.io)

## Team Members (v. 1.0)
[![Michelle He](https://dl.dropbox.com/s/u38k1c4csex03o2/michelle.png?dl=0)](https://github.com/michelleheh)

[![Liam Hatcher](https://dl.dropboxusercontent.com/s/n92n81dm90q4nrp/liam.png?dl=0)](https://github.com/lhatcher)

[![Connie Cheung](https://dl.dropboxusercontent.com/s/m3z08dtqxlpb69o/connie.png?dl=0)](https://github.com/conniedaisy)

[![Kevin Nguyen](https://dl.dropboxusercontent.com/s/wyebxbavnc7ihk7/kevinwin.png?dl=0)](https://github.com/kevinwin)


## Technology Stack, APIs, and Third-party Tools
- [React](https://facebook.github.io/react/) for rendering views and [Redux](https://github.com/reactjs/redux) for managing state
- [Node.js](https://nodejs.org/en/) and [Express](http://expressjs.com/)
- [Passport](http://passportjs.org/) and [Github Oauth](https://developer.github.com/v3/oauth/)
- [Nodal](http://www.nodaljs.com/) & [Postgres](http://www.postgresql.org/) for creating a RESTful API
- [Amazon Web Services](https://aws.amazon.com/) for deployment
- [Elastic Search](https://www.elastic.co/)
- [Ace Editor](https://ace.c9.io/#nav=about)
- Github's [Octodex](https://octodex.github.com/)
- [Travis CI](https://travis-ci.org/), [Mocha](https://mochajs.org/), and [Chai](http://chaijs.com/) for TDD
- [Webpack](https://webpack.github.io/) & [Babel](https://babeljs.io/) for using next-generation JavaScript, today 
- [AirBnb's style guide](https://github.com/airbnb/javascript)


## Folder & File structure
```
                                  +-------+
                                  |dotBind|
                                  +---+---+
                                      |
           +--------------------------+------------------------+
           |                                                   |
           v                                                   v
        +--+---+                                            +--+---+
        |client|                                            |server|
        +--+---+                                            +--+---+
           |                                                   |
      +----+-----+                                        +----+-----+
      |          |                                        |          |
      v          v                                        v          v
    +-+-+     +--+---+                                 +--+---+    +-+-+
    |app|     |chrome|                                 |static|    |api|
    +-+-+     +------+                                 +--+---+    +-+-+
      |                                                   |          |
      v                                                   v          v
+-----+-----+                                      +------+-----+  +-+---+
|Redux/React|                                      |Node/Express|  |Nodal|
+-----------+                                      +------------+  +-----+

```

The repo is divided into 2 main folders, `client` and `server`.
Each main folder is divided into respective subfolders.

`app` is the container for the Redux/React web app

`chrome` holds the html/cs/js and configuration files needed to build the chrome extension

`static` represents a static file server which serves up files inside `app`

`api` is the container for the RESTful API server



## Setting up your development environment

1. Install all dependencies inside app, static and api.
2. Install Elastic Search
3. Set a webpack watch and build. Run `npm run build` inside the `app` folder
4. Install the chrome folder inside extensions
5. Run the nodal api server and the static server

## Schema Design

## React/Redux

## Elastic Search

## Static file Server

## Nodal API server

