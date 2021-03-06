# \<etools-page-refresh\>

A button that will clear your app data(locaStorage and dexieDBs) then refresh the page discarding page cached elements.

## Usage

```html
<etools-page-refresh></etools-page-refresh>
```

When you press the button locaStorage will be cleared and dexie databases deleted and page will reload.

## Install

```bash
$ bower install --save etools-page-refresh
```

## Preview element locally

Install needed dependencies by running: `$ bower install`.
Make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `$ polymer serve` to serve your element application locally.

## Linting the code

Innstall local npm packages (run `npm install`)
Then just run the linting task

```bash
$ npm run lint
```
You should also use polylint. If you don't have Polylint installed run `npm install -g polylint`.
Then just run the linter on each file you wish to check like so

```bash
$ polylint -i filename.html
```
At the moment polylint crashes if it encounters a missing import. If that happens, temporarily comment out such imports and run the command again.

## Running Tests

You need to have `web-component-tester` installed (if not run `npm install -g web-component-tester`)
```bash
$ wtc
```
or
```bash
$ wtc -p
```
