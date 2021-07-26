# Express-Template
Boilerplate for Express based apps. Upon downloading/cloning create an .env file for ENV. Variables and a babel.config.json file. In the .babelrc file add the following:

```javascript
{
  "presets": ["@babel/preset-env"]
}
```

For updating npm dependencies use the following commands:

To discover dependencies that are out of date
```javascript
npm outdated
```
To perform safe dependency upgrades
```javascript
npm update
```
To upgrade to the latest major version of a package, if need be.
```javascript
npm install <packagename>@latest
```
To upgrade all dependencies to their latest major versions
```javascript
npx npm-check-updates -u 
npm install
```
