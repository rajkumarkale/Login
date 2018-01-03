
### Installation of project

You need to install Grunt globally:

```sh
$ npm install -g grunt-cli
```
followed by

```sh
$ npm install 
$ bower install
```
For running the app
```sh
$ grunt serve    for development
```
For test the dist
```sh
$ npm start  
```
For building the app
```sh
$ grunt build:dist 
`````


### Development

Want to contribute? Great!

* Fork it!
* Clone it!
* Push it!
 
  Fork it from top right corner

Open your favorite Terminal and run these commands.

First:
```sh
$ git clone 'your repo'
```

Second :
```sh
$ git add .
```
Next:
```sh
$ git commit "comments on changes you made"
```
Next:
```sh
$ git push origin 'your branch name'
```
Give pull request to main repo

### Deployment
Need Heroku toolbelt installed

First:
Build the app in ur repo
```sh
$ git build:dist
```
Copy img folder from src to dist

Second :
Paste the dist in public folder

And in wrapper open terminal
```sh
$ git add .
```
Next:
```sh
$ git commit "comments on changes you made"
```
Next:
```sh
$ git remote add 'remote-name' 'remote-address'
```
Next:
```sh
$ git push remote-name master:master
```
Done with Deployment
