# React/Office-Ui-Fabric/Flex Layout [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-green.svg)](https://github.com/matthewvilhauer/react-uifabric-flex-layout/compare)
Component for applying a basic app layout structure to a [create-react-app](https://facebook.github.io/create-react-app/) project using flex and [office-ui-fabric-react](https://github.com/OfficeDev/office-ui-fabric-react) components developed by Microsoft

## Guides

- [flex](https://developer.mozilla.org/en-US/docs/Web/CSS/flex) - flex, CSS property overview | MDN
- [create-react-app](https://create-react-app.dev/) – How to develop apps bootstrapped with Create React App.
- [office-ui-fabric-react](https://developer.microsoft.com/en-us/fabric) - The React-based front-end framework for building experiences for Office and Office 365.

react-uifabric-flex-layout works across all modern broswers (Chrome, Firefox, Edge, IE, etc.)<br>
If something doesn’t work, please [file an issue](https://github.com/matthewvilhauer/react-uifabric-flex-layout/issues/new).<br>

## Install

```sh
cd my-app
npm install react-uifabric-flex-layout
npm start
```
## Usage

```jsx
import Layout from 'react-uifabric-flex-layout';

function App() {
  return (
    <div className="App">
      <Layout>
        <div className="appHeader"></div>
        <div className="navBar"></div>
        <div className="homePage"></div>
      </Layout>
    </div>
  );
}
```

## License

Create React App is open source software [licensed as MIT](https://github.com/facebook/create-react-app/blob/master/LICENSE).
