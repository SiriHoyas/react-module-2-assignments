# Lesson Tasks

## Task 1 - Basic classes

1. Create a new CRA. Replace App.js with the following:

```js
function App() {
  return <div>Hello world</div>;
}

export default App;
```

2. Create a new stylesheet in /src/ called styles.css

3. Add the following style to style.css:

```css
body {
  background-color: lightblue;
}
```

4. Import your stylesheet into App.js at the top of the file with import './style.css'. When you save the file, the App should have a light blue background.

5. Create a new class called .text. Give it a color property of #fff.

6. Add a new p element with the text Paragraph 1. Give this p element a class (className) property with a value of text. Make sure this p element is in-between the <div> elements in App.js. You should now have a p element with white text.

## Task 2 - CSS Modules

1. Create a new CRA. Replace App.js with the following:

```js
function App() {
  return <div>Hello world</div>;
}

export default App;
```

2. Create a new stylesheet in /src/ called App.module.css
3. Add the following style to style.css:

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100px;
  width: 100px;
  background: red;
  color: white;
}
```

4. Import your stylesheet into App.js at the top of the file with import styles from './App.module.css'.

5. Add the container style to your div in App.js. This will cause the container to look like a red box with white text

## Task 3 - SASS

1. Create a new CRA or use one you’ve already created. Replace App.js with the following:

```js
function App() {
  return <div></div>;
}

export default App;
```

2. Add SCSS/SASS to your project using npm or yarn.

3. Create a new stylesheet in /src/ called styles.scss.

4. Add custom styling to ensure that SASS is working as intended.

## Task 4 - styled-components

You are going to apply a theme to an app, create a styled-component, use a theme value and then lastly, use props to change a styled-component.

1. Create and implement a theme for your app. You only need to have one value in your theme, such as a primary color.

2. Create a `<button>` styled-component and call it in your app.

3. Add the theme value you created to your `<button>` styled-component.

4. Create a boolean value and pass it to your styled-component, then alter your styling of the `<button>` styled-component based on this boolean value passed as a prop.
