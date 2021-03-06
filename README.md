# Project Name

> RGI Reviews Module

## Related Projects

  - https://github.com/lokisscepter/pvl-proxy
  - https://github.com/lokisscepter/3-Hz-service
  - https://github.com/lokisscepter/bschaaf1017-service

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)

## Usage

> first, run 'npm install dependencies' to install everything required to run the app
> 'npm run build' will build a production bundle of this service with webpack
> 'npm run seed' will define the mySQL connection, create the db, dropping it if it already exists, define the tables, and finally seed them with the generated information
> 'npm run start' will start up the server
> server output is currently set to localhost:3000
> in order for the module to render, it requires a local index.html on your proxy featuring a div with the id of 'reviews-module'
> the output filepath will be "http://localhost:3000/bundle.js"
> the ajax request in index.jsx is based on theoretically selecting an item, which would theoretically set state with a reference to that item's id#
> currently the ajax request is based on index.jsx's state which I have pre-set to the number 20, because I like the number 20

## Requirements
-see package.json dependencies


### Installing Dependencies

From within the root directory:

```
npm install dependencies
```

