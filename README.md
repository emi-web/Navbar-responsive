![Preview](./images/navbarresponsive1.jpg)
![Preview](./images/navbarresponsive2.jpg)

# Responsive Navbar with React

## Overview

This project is a responsive navigation bar built using React. It includes a hamburger menu (burger button) that allows users to toggle the visibility of navigation links, making it suitable for both desktop and mobile devices.

## Features

* Responsive design for different screen sizes
* Interactive hamburger menu
* Clean and reusable React components
* Styled using CSS / styled-components
* Simple and user-friendly UI

## How It Works

The application is built using React functional components. The main idea is to control the visibility of the navigation links using React state.

* A `Navbar` component contains the logo/title and navigation links.
* A `BurgerButton` component is used to toggle the menu on smaller screens.
* The menu visibility is controlled using `useState`.

When the burger button is clicked:

* The state changes (`true` / `false`)
* A CSS class (e.g. `active`) is added or removed
* This class controls whether the menu is visible or hidden

## Technologies Used

* React
* JavaScript (ES6)
* CSS / styled-components

## Project Structure

```
src/
 ├── components/
 │    ├── Navbar.jsx
 │    ├── BurgerButton.jsx
 ├── App.jsx
 ├── main.jsx
```

## Example Logic

```javascript
const [active, setActive] = useState(false);

<button onClick={() => setActive(!active)}>
  ☰
</button>
```

This toggles the menu visibility by switching the `active` state.

## Future Improvements

* Add animations for smoother transitions
* Integrate React Router for navigation between pages
* Improve accessibility (ARIA labels, keyboard support)

## Author

Emiliano Rivas

```
```
