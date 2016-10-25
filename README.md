# \<etools-page-refresh\>

A button that will clear your app data(locaStorage and dexieDBs) then refresh the page discarding page cached elements.

## Usage

You can supply a config object to specify what data you want to clear.
For example:
```javascript
// somewhere in your polymer element
this.config = {
  localStorage: true,
  dexieDbs: ['dexieDBName1','dexieDBName1']
}
```

```html
<etools-page-refresh config="[[config]]"></etools-page-refresh>
```

When you press the button locaStorage will be cleared and dexieDBs deleted and page will reload.

## Install

TODO: bower package? 

## Preview element locally
Install needed dependencies by running: `$ bower install`.
Make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `$ polymer serve` to serve your element application locally.

## Running Tests

You need to have `web-component-tester` installed (if not run `npm install -g web-component-tester`)
```bash
$ wtc
```
or 
```bash
$ wtc -p
```
