## Installation

```
npm install or yarn
```

## Running

Set up generated files:

```
npm run update-schema or yarn run update-schema
npm run build or yarn run build
```

Start a local server:

```
npm start or yarn start
```

## Developing

Any changes you make to files in the `js/` directory will cause the server to
automatically rebuild the app and refresh your browser.

If at any time you make changes to `data/schema.js`, stop the server,
regenerate `data/schema.graphql`, and restart the server:

```
npm run update-schema
npm run build
npm start
```
