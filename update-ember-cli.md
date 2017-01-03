_stolen from: https://emberigniter.com/update-latest-ember-data-cli/_

__upgrade to latest version of ember-cli__

```
> npm uninstall -g ember-cli
> npm cache clean && bower cache clean
> npm install -g ember-cli@X.Y.Z
```

__upgrade to latest version of ember & ember-data__

```
> rm -rf node_modules bower_components dist tmp
> npm install --save-dev ember-cli@X.Y.Z
> bower install
> ember init
```

_a quick version check will tell us if this went alright:_

```
> ember -v

ember-cli: X.Y.Z
node: A.B.C
```

_launching the app we can verify our Ember and Ember Data versions are properly set up:_

```
> ember server

Livereload server on http://localhost:49152
Serving on http://localhost:4200/
````

_... then check the console output_

__done!__
