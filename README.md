# OACollectiveAction

## Requirements
- NPM >3.0.0
- we can do this on OS X with `sudo port install npm5`
- vue & vue cli [found here](https://vuejs.org/v2/guide/installation.html)
notice you may need `sudo` perms

## How to update / run the website:
- git pull lastest version
- run `npm install` in root dir. if you run in to errors delete the `node-moduals` folder and re run `npm install`
- to run use `npm run dev`


## To deploy the website:
- checkout a new branch of the lastest code.
- run `npm run build`
- you should now have a dist folder. Go to the index.html and remove the `/` in the beginning of every script and link tag’s `src` attribute.
---------
### resources 
- https://medium.com/@mwolfhoffman/deploying-to-github-pages-with-vue-webpack-cli-5b2ba17f14a0


