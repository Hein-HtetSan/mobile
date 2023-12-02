

# Notedly - Mobile Application

This repository contains code examples for the React Native mobile application chapters of [_JavaScript Everywhere_](https://www.jseverywhere.io/) by Adam D. Scott, published by O'Reilly Media

## Configuration

```shell
$ cp config.example.js config.js
```

## Set Env variable

```js
const ENV = {
    dev: {
        API_URI: `http://${localhost}:4000/api`
    },
    prod: {
        API_URI: `https://your-api-uri/api`
    }
};
```

## To Run the Application

When developing locally, you can start the app by running:

```shell
$ npm start
```

## Host the Code

```shell
$ git remote set-url origin YOUR_GIT_REPO_URL
$ git push -u origin master
```

## Related Repositories

- [API 🗄️ ](https://github.com/Hein-HtetSan/api)
- [Web 💻 ](https://github.com/Hein-HtetSan/web)
- [Desktop 🖥️](https://github.com/Hein-HtetSan/desktop)


