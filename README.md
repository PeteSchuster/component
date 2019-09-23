# @rei/component
This is a template for building REI components using `@vue/cli` with the legacy [init](https://github.com/vuejs/vue-cli/tree/v2#vue-cli--) command.

### Usage
``` bash
$ npm install -g @vue/cli
$ npm install -g @vue/cli-init
$ vue init rei/component your-component-name
$ cd your-component-name
$ npm install
$ npm run dev
```

### CLI Options
|options | description
| ---- | ---- |
|`name`| Component name - write in kebab-case, used throughout project, so choose wisely! |
|`description`| Component description |
|`author`| Your name and email address |
|`addComponents`| Add sample Vue.js components with Cedar dependencies |


### About Example and Development Files
* An example component is optionally auto-generated with Cedar component examples and example Cedar Token usage.
* A local development environment for building and testing props and styles from external components will be setup.

### What's Included

- `npm run dev`: `@rei/febs` runs the dev server and environment

- `npm run build`: build `ES Modules` and `CommonJS` export files with `rollup`.

### Development

- Install vue-cli: `npm install -g @vue/cli @vue/cli-init`
- Make changes inside `/template` and push the branch to GitHub
- Run `vue init rei/component#NAME-OF-YOUR-BRANCH-HERE some-test-project`, then inspect the generated project.
