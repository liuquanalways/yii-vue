# yii-vue

Personally, I think that it's a bad idea to insert php code in html.
This is a framework which combines Yii2 and Vue， so that we can Attend to each one's own duties.


## Requirements

vue-cli

## Usage

```bash
composer create-project --prefer-dist yiisoft/yii2-app-basic your-project

cd your-project

vue init webpack web-dev

npm install

```

update the webpack build configuration file: web-dev/config/index.js

```
index: path.resolve(__dirname, '../dist/index.html'),
assetsRoot: path.resolve(__dirname, '../dist'),
```

```
index: path.resolve(__dirname, '../../web/index.html'),
assetsRoot: path.resolve(__dirname, '../../web/'),
```

```
npm run build
```
