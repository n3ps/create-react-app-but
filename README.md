# create-react-app-but

React doesn't come with a CLI. The closest thing right now is `create-react-app` but it's all or nothing for the most part.

The goal of this guide is to summarize different ways to customize create-react-app without the hassle of manually setting up everything from scratch.

## I want use create-react-app but...

### Use TypeScript instead of JavaScript
- `$ create-react-app my-app --scripts-version=react-scripts-ts`
- Or add the package and update npm scripts

### Use Sass instead of CSS
1. Add and configure `node-sass-chokidar`, reference: [official docs](https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-a-css-preprocessor-sass-less-etc)
2. Update npm scripts

### Use Mobx instead of `setState`
- [todo]

### Use Ava instead of Jest
- [todo]

