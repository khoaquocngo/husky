# husky

- Install husky

  ```bash
  npx husky-init && npm install
  ```

- Enable Git hooks

  ```bash
  npx husky install
  ```

- To automatically have Git hooks enabled after install, edit package.json

  ```bash
  npm pkg set scripts.prepare="husky install"
  ```

- Create a hook

  ```bash
  npx husky add .husky/pre-commit "npm test"
  ```

- Source: https://typicode.github.io/husky/getting-started.html#install