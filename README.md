# Whist Tournament Maker

Generate games for a whist tournament.
The Angular app is published at [ross.grattafiori.dev/wtm](https://ross.grattafiori.dev/wtm/).

## Develop

Install the dependency versions recorded in [package-lock.json](package-lock.json), then start the development server:

```sh
npm ci
npm start
```

Open `http://localhost:4200`.
Use `npm run build` for a production build and `npm test` for the configured Karma tests.
Scripts live in [package.json](package.json).

## Publish

The configured GitHub Pages deployment command is `npx ng deploy --base-href=/wtm/`.
Run it only when ready to publish.
The deployment target is defined in [angular.json](angular.json).

Scheduling references: [Durango Bill's whist blocks](https://www.durangobill.com/BridgeCyclicSolutions.html) and [DeVenezia's whist tables](https://www.devenezia.com/downloads/round-robin/index.html).
Scoring and multiplayer participation remain future ideas.
