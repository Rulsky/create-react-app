### What is this:
  fork of [create-react-app scripts settings](https://github.com/facebookincubator/create-react-app/tree/master/packages/react-scripts) with addition of browsersync and SASS (node-sass-chokidar) into workflow.

#### disclaimer:
  please note that I tried to use node-sass-chokidar in package.json like this:
  ````
  "node-sass": "https://github.com/michaelwayman/node-sass-chokidar/tarball/master",
  ````
  because of this reason [pointed in create-react-app manual](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-a-css-preprocessor-sass-less-etc)

  But it didn't work.

### How to use it:
pass a name of desired custom react-scripts to `--scripts-version` key like so:

````
  create-react-app my-app --scripts-version rulsky-react-scripts
````


### npm registry
  link to npmjs: [rulsky-react-scripts](https://www.npmjs.com/package/rulsky-react-scripts)


### Original documentation:
  in facebook's repo - [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/README.md)
