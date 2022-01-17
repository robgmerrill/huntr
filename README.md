# Huntr

### Track Your Job Search

Project in Action - [Hunter](https://www.huntr.live/)

#### Setup React App

- create 'client' folder
- open terminal
- cd client
- npx create-react-app .
- npm start

### Cleanup Create React App

- in src remove
- App.css
- App.test.js
- logo.svg
- reportWebVitals.js
- setupTests.js
- fix App.js and index.js

### Title and Favicon

- change title in public/index.html
- replace favicon.ico in public
- resource (favicons)[https://favicon.io/]

#### Normalize.css and Global Styles

- CSS in JS (styled-components)
- normalize.css
- small CSS file that provides cross-browser consistency in the default styling of HTML elements.
- [normalize docs](https://necolas.github.io/normalize.css/)

```sh
npm install normalize.css
```

- import 'normalize.css' in index.js
- SET BEFORE 'index.css'
- replace contents of index.css

#### Landing Page

- for now Landing.js
- create component (snippets extension)
- setup basic return

```js
<h4>Landing Page<h4>
```

- import logo.svg and main.svg
- import Landing in App.js and render

#### Styled Components

- CSS in JS
- Styled Components
- have logic and styles in component
- no name collisions
- apply javascript logic
- [Styled Components Docs](https://styled-components.com/)

```sh
npm install styled-components
```

```js
import styled from "styled-components";

const El = styled.el`
  // styles go here
`;
```

- no name collisions, since unique class
- vscode-styled-components extension
- colors and bugs
- style entire react component

```js
const Wrapper = styled.el``;

const Component = () => {
  return (
    <Wrapper>
      <h1> Component</h1>
    </Wrapper>
  );
};
```

- only responsible for styling
- wrappers folder in assets
