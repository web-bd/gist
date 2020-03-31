## NPM Start for Offline app
* Change `package.json` file as follows
* Run App `npm start`
* For `angular`
```json
"scripts": {
    "ng": "ng",
    "start": "node node_modules/.bin/ng serve",
    "build": "node node_modules/.bin/ng build",
    "test": "node node_modules/.bin/ng test",
    "lint": "node node_modules/.bin/ng lint",
    "e2e": "node node_modules/.bin/ng e2e"
  }
```

* For `React`
```json
"scripts": {
    "start": "node node_modules/.bin/react-scripts start",
    "build": "node node_modules/.bin/react-scripts build",
    "test": "node node_modules/.bin/react-scripts test",
    "eject": "node node_modules/.bin/react-scripts eject"
  }
```

* For `Vue`
```json
"scripts": {
    "start": "node node_modules/.bin/vue-cli-service serve",
    "build": "node node_modules/.bin/vue-cli-service build",
    "lint": "node node_modules/.bin/vue-cli-service lint"
  }
```
