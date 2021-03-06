# ECMA-262 Book

**ECMA-262, the ECMAScriptÂ® Language Specification.**

This is a minimal Electron application based on the [Quick Start Guide](https://electronjs.org/docs/latest/tutorial/quick-start) within the Electron documentation.

A basic Electron application needs just these files:

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - A web page to render. This is the app's **renderer process**.

You can learn more about each of these components within the [Quick Start Guide](https://electronjs.org/docs/latest/tutorial/quick-start).

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/yongyuanliu2022/ecma262book.git
# Go into the repository
cd ecma262book
# Install dependencies
npm install
# Run the app
npm start
```

## To Build

```bash
# forge
npx electron-forge import
# make
npm run make
```

## ECMA-262

```bash
# Clone this repository
git clone https://github.com/tc39/ecma262
```