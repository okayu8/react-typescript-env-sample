# React + TypeScript （2020/12） 環境構築用

## 手順

1. yarn init -y

2. git init

3. React の導入

   `yarn add react react-dom`

4. TypeScript, webpack 関連の導入

   `yarn add -D @types/react @types/react-dom ts-loader typescript webpack webpack-cli webpack-dev-server html-webpack-plugin`

5. webpack.config.js を作成

6. tsconfig.json を作成

7. package.json に scripts を追記

8. /src/index.html を作成

9. /src/index.tsx を作成

10. サーバーで動かす `yarn start`（ビルド `yarn build`）

11. eslint, prettier を追加
    `yarn add -D @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-prettier eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks prettier`

12. .eslintrc.json, .eslintignore を作成

13. .prettierrc.json, .prettierignore を作成

14. styled-components を追加
    `yarn add styled-components`
    `yarn add -D @types/styled-components`

15. storybook を追加
    `npx sb init`
