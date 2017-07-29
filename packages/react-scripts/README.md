### What is this:
  fork of [create-react-app scripts settings](https://github.com/facebookincubator/create-react-app/tree/master/packages/react-scripts) with addition of browsersync and SASS (node-sass-chokidar) into workflow.

#### disclaimer:
  please note that I use node-sass-chokidar in package.json like this:
  ````
  "node-sass": "https://github.com/michaelwayman/node-sass-chokidar/tarball/master",
  ````
  reason is pointed in create-react-app manual - [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-a-css-preprocessor-sass-less-etc)

### How to use it:
pass a name of desired custom react-scripts to `--scripts-version` key like so:

````
  create-react-app my-app --scripts-version rulsky-react-scripts
````


### npm registry
  link to npmjs: [rulsky-react-scripts](https://www.npmjs.com/package/rulsky-react-scripts)


### Original documentation:
  in facebook's repo - [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/README.md)
