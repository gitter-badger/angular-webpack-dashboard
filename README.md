# Just another Angular Dashboard 

[![Join the chat at https://gitter.im/Drathal/angular-webpack-dashboard](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Drathal/angular-webpack-dashboard?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Build Status](https://travis-ci.org/Drathal/angular-webpack-dashboard.svg)](https://travis-ci.org/Drathal/angular-webpack-dashboard) 
[![Codacy Badge](https://api.codacy.com/project/badge/1f843886f2c74fc5a7ffee387077ddf0)](https://www.codacy.com/app/drathal/angular-webpack-dashboard)
[![Coverage Status](https://coveralls.io/repos/Drathal/angular-webpack-dashboard/badge.svg?branch=master&service=github)](https://coveralls.io/github/Drathal/angular-webpack-dashboard?branch=master)
[![Dependencies](https://david-dm.org/Drathal/angular-webpack-dashboard.svg)](https://david-dm.org/Drathal/angular-webpack-dashboard)

A little frontend to play around with: angular 1.x, material design, webpack and other nice things.

## requirements
  * [git](https://git-scm.com/)
  * [node.js](https://node.js/)
  * [Java](https://java.com/download/) only for selenium tests
   
## install
    git clone https://github.com/Drathal/angular-webpack-dashboard.git
    cd angular-webpack-dashboard
    npm install

## build & start
### production
    npm run build
    npm run start
    
Open in Browser at: localhost:8888    
    
### development
    npm run build:dev
    
Open in Browser at: localhost:8080    

## FAQ

#### Where can i change the port for the dev server?
You chan change the `port` variable, inside `webpack/webpack.make.js`.

#### Where can i change the port for the production server?
You chan change the `port` variable, inside `server.js`.

