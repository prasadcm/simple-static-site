# A sample application to demonstrate the hosting of static site

## How to run

Make sure you have latest version of npm, node installed globally.
You can use nvm to use manage multiple versions of node.
`nvm list`

`npm run start`

## How to test

Open <http://localhost:3001> on any browser.

## Best practices

- Git ignore by .gitignore
- No package-lock.json. Always use latest. Refer .npmrc
- Linting for .md, html, css
- format the code using prettier
- Github actions
- VS code settings

## Packages used

- markdownlint, markdownlint-cli - linting readme files
- npm-run-all - To run `run-s` command in package script which runs sequentially
- htmlhint - linting html files
- lint-staged - Along with husky to lint and format the code before commit
- husky - Pre commit hook for code formatting
- prettier - Format the code
- stylelint, stylelint-config-standard - Linting css fines
