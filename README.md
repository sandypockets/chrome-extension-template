# React.js Chrome Extension Template
A quick way to get started building Chrome Extensions with React and Tailwind CSS.

## Getting started
This project was developed and tested with `Node 14.17.0` and `yarn 1.22.15`.

1. Click **Use this template**.
2. Clone the repository.
3. Install dependencies by running:
```shell
yarn install
```
4. Build the extension by running:
```shell
yarn build
```
5. In your browser, go to `chrome://extensions/` and enable developer mode.
> Click the Chrome menu icon and select Extensions from the Tools menu. Ensure that the "Developer mode" checkbox in the top right-hand corner is checked.
6. Click **Load unpacked**.
7. Upload the `build/` directory from the project.

### Making changes
The `manifest.json` file is located in the `public/` directory. For the most part, the extension functions like a normal React app. Make changes in the `src/App.js` file. After making a change, you need to:

1. Rebuild the app:
```shell
yarn build
```
2. Refresh the extension upload. In your browser, go to `chrome://extensions/`. Click the refresh icon on your extension's card.

## Dependencies
* @testing-library/jest-dom `^5.11.4`
* @testing-library/react `^11.1.0`
* @testing-library/user-event `^12.1.10`
* react `^17.0.2`
* react-dom `^17.0.2`
* react-scripts `"4.0.3`
* web-vitals `^1.0.`

## Dev Dependencies
* autoprefixer `9.0.0`
* postcss `7.0.0`
* tailwindcss `npm:@tailwindcss/postcss7-compat@^2.2.17`