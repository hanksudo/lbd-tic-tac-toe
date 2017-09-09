# lbd-tic-tac-toe

Learning by doing - made [tic-tac-toe](https://www.wikiwand.com/en/Tic-tac-toe) game by [ReactJS](https://facebook.github.io/react/)

[Demo](https://hanksudo.github.io/lbd-tic-tac-toe/)

## Debug

    yarn start
    
- F5 in VSCode to debug

## Deploy to github page

```bash
yarn build
yarn add --dev gh-pages
yarn deploy
```

- [Reference](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#github-pages)

## Challeges

1. Display the move locations in the format "(1, 3)" instead of "6".
2. Bold the currently-selected item in the move list.
3. Rewrite Board to use two loops to make the squares instead of hardcoding them.
4. Add a toggle button that lets you sort the moves in either ascending or descending order.
5. When someone wins, highlight the three squares that caused the win.