## 學習資源

[simple-tailwind-starter](https://github.com/bradtraversy/tailwind-course-projects/tree/main/simple-tailwind-starter)

## 安裝環境

[Tailwind CSS CLI](https://tailwindcss.com/docs/installation)

專案初始化

```shell
npm install
```

安裝 Tailwind CSS

```shell
npm i -D tailwindcss
```

初始化 Tailwind CSS 產生 tailwind.config.js

```shell
npx tailwindcss init
```

配置 tailwind.config.js

```javascript
module.exports = {
  content: ['./*.html'],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

手動建置 input.css 並輸入內容

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

package.json 建立 cli 指令

```shell
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```

## 官方說明

[Tailwind CSS 功能與指令](https://tailwindcss.com/docs/functions-and-directives)
