ionic-todo
==========================

The source code from official Ionic Book Todo app
Merged with [ionic-app-base](https://github.com/driftyco/ionic-app-base)

- [Ionic Tutorials](http://ionicframework.com/docs/guide/)

## Installation

To use this project as is, first clone the repo from GitHub, then run:

```bash
$ cd ionic-todo
$ sudo npm install -g cordova ionic gulp
$ npm install
$ gulp install
```

## Testing your App

At this point you can go to [Chapter 4: Testing your App](http://ionicframework.com/docs/guide/testing.html)

Keep in mind that this is the built out app, with all the code from 
[Chapter 5: Building out your App](http://ionicframework.com/docs/guide/building.html) already included.

## Updating Ionic

To update to a new version of Ionic, open bower.json and change the version listed there.

For example, to update from version `1.0.0-beta.6` to `1.0.0-beta.7`, open bower.json and change this:

```
"ionic": "driftyco/ionic-bower#1.0.0-beta.6"
```

To this:

```
"ionic": "driftyco/ionic-bower#1.0.0-beta.7"
```

After saving the update to bower.json file, run `gulp install`.

Alternatively, install bower globally with `npm install -g bower` and run `bower install`.
