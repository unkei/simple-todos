METEOR TUTORIAL
===============

CMD + SHIFT + V to show markdown preview in VS code.

This file is generated at later step to record the meteor commands by the command. Unfortunatly not modified step by step.

```
git log --oneline > README.md
```

The following command also generates good looking log on git.
```
git log --oneline --graph --decorate --name-status
```

COMMANDS
--------
### ef860c2 initial commit.
```
meteor create simple-todos      # to create the app
```
```
cd simple-todos
meteor                          # to run the app
```
### 066fd09 added react and ToDo jsx.
```
meteor npm install --save react react-dom
```
### b22496c added collection/mongo DB.
```
meteor npm install --save react-addons-pure-render-mixin
meteor add react-meteor-data
```
```
meteor mongo                    # to run mongo db console
db.tasks.insert({ text: "Hello world!", createdAt: new Date() });
```
### 4ab9feb added ios platform.
```
meteor install-sdk ios
meteor add-platform ios
meteor run ios
```
### d2acedd added user authentication.
```
meteor add accounts-ui accounts-password
```
### b99d829 security with methods.
```
meteor remove insecure
```
### 893f9b1 removed autopublish.
```
meteor remove autopublish
```
### 34f5821 filtering data with publish and subscribe.
```
meteor npm install --save classnames
```
### Testing
```
meteor add practicalmeteor:mocha    # to add a test driver for Mocha
```
```
meteor test --driver-package practicalmeteor:mocha  # to run app in test mode
```

