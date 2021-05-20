# cra-template-tailwind-enzyme-ts

My own custom [Create React App](https://github.com/facebook/create-react-app) template for React 17 with TypeScript 4.2 which uses:
- [Tailwind CSS](https://www.npmjs.com/package/tailwindcss)
- [PostCSS](https://www.npmjs.com/package/postcss) and [PostCSS CLI](https://www.npmjs.com/package/postcss-cli)
- [Autoprefixer](https://www.npmjs.com/package/autoprefixer)
- [Enzyme](https://www.npmjs.com/package/enzyme)
- [Enzyme 17 Adapter](https://www.npmjs.com/package/@wojtekmaj/enzyme-adapter-react-17)
- [React Test Renderer](https://www.npmjs.com/package/@wojtekmaj/enzyme-adapter-react-17)
- [GH-Pages](https://www.npmjs.com/package/gh-pages)

To use and setup, run these commands:

    npx create-react-app my-cool-app --template tailwind-enzyme-ts
    
    cd my-cool-app

    npm run setup

Individual setup commands are:
- `setup:css` - Installs Tailwind, PostCSS and CLI, and Autoprefixer
- `setup:test` - Install Enzyme, Enzyme Adapter 17, and React Test Renderer
- `setup:misc` - Install GH-Pages

To setup eslint, run this command:

    npm run eslint

Don't forget to run `npm start` before coding so the Tailwind CSS files are setup!