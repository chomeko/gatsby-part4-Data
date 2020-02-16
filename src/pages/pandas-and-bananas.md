---
title: "データからプログラムでページを作成する"
date: "2020-02-14"
---

# チュートリアル
インストール＆起動
- npx create-react-app react-tutorial

- npm start

deploy
- npm run build

## チュートリアル開始

- Square（正方形のマス目）
- Board（盤面）
- Game

- データを Props 経由で渡す
```js
renderSquare(i) {
  return <Square value={i} />;
}
```


<iframe width="560" height="315" src="https://www.youtube.com/embed/4SZl1r2O_bY" frameborder="0" allowfullscreen></iframe>