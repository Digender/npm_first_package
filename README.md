Installing from git  repo

```npm i https://github.com/strongloop/express```



Installing from Gist
It will basically require a package.json or it wont work

```npm i gist:<gist_hash> ```
#works like charm



Install from folder
Assuming you already have a package in a local directory

```npm i ./<path_to_the_folder> #works like charm```




```registry.nomjs.org/lodash``` json version

```npm.im/lodash``` shortcut



Searching for package
```npm search lodash```


Pruning
```npm list --depth 0```

```npm prune``` removes extraneous packages

```npm prune <pakage_name>``` removes extraneous packages

```npm prune --production``` #removes dev dependencies



Npm repo Command
```npm repo lodash``` #shortcut to open in npm website for package



Upgrade npm
```npm i npm@latest -g``` #run with admin previlages only



Using Simple Scripts
``` 
"scripts": {
    "test": "",
    "start": "",
}

##docs.npmjs.com/misc/scripts  //links for other scripts
 ```




 Create Your Own Package

 1. Login to https://npmjs.com/login
 2. Confirm the email
 3. Go to cmd and type ```npm adduser``` followed by your ```username``` and ```password```
 4. Go to your local, repo make its updated and is on git with latest code
 5. Then type command ```npm publish```
 6. Your package should get published successfully


 Updating versions

 ```npm udpate patch```

 ```npm udpate minor```

 ```npm udpate major```