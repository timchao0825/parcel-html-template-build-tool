# parcel-html-template-build-tool


## 📚Project Infomation

- **Platform**: compatible with **> IE 11** and ** > iOS Safari 9**

- **Language**: ECMAScript 6+ transpiled by [Babel 7](https://babeljs.io/)

- **Coding Style**: [Recommended](https://standardjs.com) (with [ESLint](https://eslint.org/) & [Prettier](https://prettier.io/) & [StyleLint](https://stylelint.io/))

- **Bundler**: [Parcel.js bundler](https://parceljs.org/)

- **Preprocess**: scss/sass

## 🛠File Structure

```shell
├── assets            # site assets
├── images            # images file
├── js                # js file
├── template          # 如需組建或模板，可新增在此資料夾
├── scss              # style file
    └── setting       # scss設定檔，或是共用style可新增在此資料夾
├── .gitignore
├── .posthtmlrc
├── .editorconfig
├── .eslintignore
├── .eslintrc.js
├── .prettierrc.js
├── .stylelintrc.js
├── package.json
└── README.md
```

## Notice

```
如果要使用template，請在template資料夾裡面新增
html使用時，語法為<include src="xxx.html"></include>

html 載入scss請在.js裏面使用import方式載入（請參考範例）
```

## 🍛Requirements

To run this project, you’ll need to install [Node.js](https://nodejs.org/en/). The latest version of Node.js is recommended.

The dependencies of this project are managed with npm (see installation guide [here](https://www.npmjs.com/get-npm)). However you can simply use the node package manager, npm for your dependency management.

## ⬇Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload
$ npm run dev

# build for production
$ npm run prod

```

## 🎫 Licence

Copyright © 2023 Tim Chao
