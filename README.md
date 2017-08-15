## Storybook Sample App

Sample project to play with [React Storybook](https://github.com/storybooks/storybook) and snapshot testing.

It contains examples for performing structural test on the same component using:
* [Jest + Enzyme](https://github.com/solepano/myapp/blob/master/src/components/TicketsPage.test.js#L6)
* [Jest Snapshot Testing](https://github.com/solepano/myapp/blob/master/src/components/TicketsPage.test.js#L44)
* [Built in Jest Snapshot Testing using Storyshots](https://github.com/solepano/myapp/blob/master/src/storyshots.test.js)

## To run it locally

*Install*

```sh
npm i
```

*Run storybook*

```sh
npm run storybook
```

Runs the Storybook in the development mode.
Open http://localhost:6006 to view it in the browser.
The page will reload if you make edits.

*Run tests*:

```sh
npm test
```

Launches the test runner in the interactive watch mode.

*Build static version of Storybook*:

```sh
npm run build-storybook
```

It will generate a static version of the Storybook and put it in the `.out` folder.


-------

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

Below you will find some information on how to perform common tasks.<br>
You can find the most recent version of this guide [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).
