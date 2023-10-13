# MinesweeperJS

A quick JavaScript implementation of the [Minesweeper game](https://en.wikipedia.org/wiki/Minesweeper_(video_game)) 💣

## Usage

To play the game, just open a cell with a single click and flag it with a right click.

### Development

Clone the repository on your computer. You must have [Node.js](https://nodejs.org) (> v4) and [Yarn](https://yarnpkg.com/lang/en/docs/install) installed:

```bash
git clone git@github.com:gabrielecanepa/minesweeper.js.git
cd minesweeper.js
yarn install
```

Make sure you have `./node_modules/.bin` in your `$PATH`. This way you can run a server with:

```bash
webpack-dev-server
```

### Scripts

Some scripts are provided in your `package.json`.

- Start a local server on port `8080`:

  ```bash
  yarn start
  ```

- Lint all JavaScript, CSS and SCSS files:

  ```bash
  yarn lint
  ```

- Build the static files:

  ```bash
  yarn build
  ```

- Push the static files to the `gh-pages` branch and deploy to [GitHub Pages](https://pages.github.com):

  ```bash
  yarn deploy
  ```

## License

[MIT](LICENSE)
