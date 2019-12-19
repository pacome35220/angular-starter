# angular-starter

> Template repository using Angular, and many npm packages to automate stuff

It also and above all contains configurations for very usefull tools i use for my dev workflow :

### [Commitizen](github.com/commitizen/cz-cli)

* `npm run commit`, prompt you to fill out any required commit fields at commit time, to format your commits messages. With [husky](github.com/typicode/husky) and [lint-staged](github.com/okonet/lint-staged), it also run linters on git staged files.

### [Prettier](github.com/prettier/prettier)

* `npm run prettify`, lint all files following rules wrote in `.prettierrc`

### [Conventional-changelog / standard-version](https://github.com/conventional-changelog/standard-version)

* `npm run release`, automate versioning and CHANGELOG generation, with semver.org and conventionalcommits.org
