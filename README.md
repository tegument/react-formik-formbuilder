# react-formik-formbuilder - A FormBuilder for React using Formik

This is a simple FormBuilder to create JSON configuratble forms using Formik with custm Fields supporting Material-UI and React-Native with react-native-paper

## Basic Usage

```
yarn add react-formik-formbuilder
```

## Development

### Common Tasks

* Developing - **npm start** - Runs the development server at *localhost:8080* and use Hot Module Replacement. You can override the default host and port through env (`HOST`, `PORT`).
* Creating a version - **npm version <x.y.z>**.
* Publishing a version - **npm publish** - Pushes a new version to npm and updates the project site.

### Testing

The test setup is based on Jest. Code coverage report is generated to `coverage/`. The coverage information is also uploaded to codecov.io after a successful Travis build.

* Running tests once - **npm test**
* Running tests continuously - **npm run test:watch**
* Running individual tests - **npm test -- <pattern>** - Works with `test:watch` too.
* Linting - **npm run test:lint** - Runs ESLint.

### Documentation Site

The boilerplate includes a [GitHub Pages](https://pages.github.com/) specific portion for setting up a documentation site for the component. The main commands handle with the details for you. Sometimes you might want to generate and deploy it by hand, or just investigate the generated bundle.

* Building - **npm run gh-pages** - Builds the documentation into `./gh-pages` directory.
* Deploying - **npm run deploy-gh-pages** - Deploys the contents of `./gh-pages` to the `gh-pages` branch. GitHub will pick this up automatically. Your site will be available through *<user name>.github.io/<project name>`.
* Generating stats - **npm run stats** - Generates stats that can be passed to [webpack analyse tool](https://webpack.github.io/analyse/). This is useful for investigating what the build consists of.

## Highlighting Demo for the Site

```js
<FormBuilder name="MyForm" />
```

## License

*react-formik-formbuilder* is available under MIT. See LICENSE for more details.
