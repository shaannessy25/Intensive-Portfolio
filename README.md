# Shaan's Portfolio

[![Build Status](https://travis-ci.com/EmaSuriano/gatsby-starter-mate.svg?branch=master)](https://travis-ci.com/EmaSuriano/gatsby-starter-mate)
[![eslint](https://img.shields.io/badge/eslint-enabled-green.svg)](https://eslint.org/)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
![Dependencies status](https://david-dm.org/EmaSuriano/gatsby-starter-mate.svg)
[![This project is using Percy.io for visual regression testing.](https://percy.io/static/images/percy-badge.svg)](https://percy.io/Ema-suriano/gatsby-starter-mate)
[![Netlify Status](https://api.netlify.com/api/v1/badges/f532a32d-4fc1-441d-aa28-cdc5e2c2e79c/deploy-status)](https://app.netlify.com/sites/gatsby-starter-mate/deploys)

![Gatsby Starter Mate logo](./media/logo.png)


The target audience are Developers 💻 and Tech Writers ✍️.

### [Check the Demo ✨](https://gatsby-starter-mate.netlify.com/)


## Why? 🤔

In case you are looking for a quick setup portfolio or upgrade your current, you have to definitely try Mate!

This starter is totally content based on [Contentful](https://contentful.com), which is a headless CMS where you can write the content for your page. In summary, Contentful is the Model when Gatsby with React is the View.

At the same time, as this portfolio is written with Gatsby is extremely easy to add more than one source of data! For example, the demo comes with an integration of [Medium](https://medium.com) posts based on a user name ✌️

## Features 🛠

- [Gatsby](https://www.gatsbyjs.org/)
- [Rebass](https://rebassjs.org/): styled component system
- [React Awesome Reveal](https://github.com/dennismorello/react-awesome-reveal)
- Typescript
- CMS Integration with [Contentful](https://contentful.com)
- PWA ready
- SEO
- Responsive design
- Icons from [font-awesome](https://fontawesome.com/)
- [Netlify](https://www.netlify.com) Deployment Friendly
- Medium integration
- Social sharing (Twitter, Facebook, Google, LinkedIn)
- Developer tools:
  - `eslint`
  - `prettier`
- Google Analytics integration
- End to End with Cypress:
  - A11y testing with [Axe](https://www.deque.com/axe/)
  - Visual Testing with [Percy](https://percy.io/)


## Screenshot and Design 🖼

As the starter is a SPA it only has two routes:

- `/`: main page with the sections of `Home`, `About me`, `Projects` and `Writing`.
- `/404`: error page for unexpected route.

| Section  |                            Screenshot                            |
| -------- | :--------------------------------------------------------------: |
| Home     |   ![Home](media/screenshots/photographer.test.js/Landing.png)    |
| About me |  ![About me](media/screenshots/photographer.test.js/About.png)   |
| Projects | ![Projects](media/screenshots/photographer.test.js/Projects.png) |
| Writing  |  ![Writing](media/screenshots/photographer.test.js/Writing.png)  |



## Building your site 📦

As we are dealing with environment variables, the `.env` file is excluded from `.gitignore` file. Therefore, in order to deploy the website you have to send `SPACE_ID` and `ACCESS_TOKEN` with the `build` command.

```bash
SPACE_ID=xxxxx ACCESS_TOKEN=yyyyy yarn build
```

The result will be stored inside the `public` folder, so you can upload to your web host. I highly suggest using this starter with Netlify when you can define which command will build the project and also send the environment variables inside the website configuration.

