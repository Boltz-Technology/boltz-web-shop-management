# 线上店 Background Management System

## Repo Clone

- Install the latest stable version of node before clone repo

- Clone the project repo

  `git clone git@github.com:Boltz-Technology/boltz-web-shop-management.git`

  `yarn`

### Project Directories Usage

- components: common used components
- screens: web application pages. If the page needs to break into several children components which only used for this page, put them inside the `widgets` folder. For example:
  - `Home` Page folder
    - `widgets` folder
    - `Home.js`
- utils:  helper function modules.
- ...


## Project Run

### Start the project

`yarn dev`      # Run the development server at http://localhost:4000 by default


### ESLint Chcker and Fix

- See lint results: `yarn lint`

- Fix lint errors: `yarn lint-fix`



## Rferences and Resources

- [Semantic UI Docs](https://semantic-ui.com/introduction/getting-started.html)
- [ESLint recommended rules](https://eslint.org/docs/rules/)
- Scaffolded from [boilerplate](https://github.com/altafino/react-webpack-5-tailwind-2)
