# 環境構築

```bash
npx create-react-app react-todo --template typescript --use-npm

$ code react-todo

$ touch .env
# .gitignore に .env を追加

$ touch .prettierrc
# 実装

$ npm i @tanstack/react-query@4.28.0\nnpm i @tanstack/react-query-devtools@4.28.0\nnpm i zustand@4.3.6\nnpm i @heroicons/react@2.0.16\nnpm i react-router-dom@6.10.0 axios@1.3.4
$ npm install -D tailwindcss\nnpx tailwindcss init
# index.css に tailwindcss の初期設定をコピペ

$ npm start
```
