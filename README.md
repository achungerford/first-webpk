# first-webpk
small project for first attempt using webpack

#### steps taken
1. new repo on GH, Node .gitignore, MIT license
2. git clone, cd into repo
3. in VS Code terminal: `npm init -y`
4. `npm install --save-dev webpack webpack-cli`
5. create directories: src, public
6. create files in dirs: src/index.js, public/index.html
7. add script tag in `<head>` of index.html `src="../src/index.js"`
8. in `package.json` under `"scripts"` add `"build": "webpack`