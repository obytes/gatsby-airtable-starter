# Gatsby Airtable starter

[![Netlify Status](https://api.netlify.com/api/v1/badges/2735e4a9-8d6c-47b8-b559-b2cbb8051f2b/deploy-status)](https://app.netlify.com/sites/gatsby-starter-airtable/deploys)

## Features

- Static content fetched from Airtable
- Dynamic content with CRUD operations with Airtable REST API
- Well structured files/folders
- Custom React Hooks
- Custom Helpers instead of using third party libraries
- Dynamic & Static containers
- Global state management ready with useReducer & useContext
- Dummy auth but ready to add real requests

## Prerequisites

[Yarn](https://yarnpkg.com/en/)
[Airtable Account](https://airtable.com/invite/r/HZvSWsO8)

> Using my referral link will get me \$10 in credit

Please create a new file `.env.development` and put these env variables

> You will have to create another `.env.production` file to build locally

```bash
GATSBY_AIRTABLE_API_KEY=<<Your Aitable API KEY here>>
SCENES_BASE_ID=<<Your Aitable Base Id here>> (You can change the name of this env if you wish, but make sure to change it within the code as well)
```

## Installing

Installing the dependencies

```bash
yarn
```

## Start the dev server

```bash
yarn start
```

## Delete the previous cached fetched data

```bash
yarn reset
```

## Build

```bash
yarn build
```

## Built with

- Gatsby
- @reach/router
- VSCode
- styled-components
- And these useful JavaScript libraries & Gatsby plugins [package.json](package.json)

## License

// To be decided later on