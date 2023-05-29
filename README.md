# Random Joke Generator

This is a simple web application that generates random jokes. Each time the user clicks the "Get Random Joke" button, a joke is fetched from an API and displayed on the page. The application is built using HTML, CSS, and JavaScript.

## Features

- Fetches random jokes from an external API.
- Filters out jokes with potentially offensive content.
- Displays the fetched joke on the webpage.
- Provides a button to fetch a new random joke.

## Usage

To use the Random Joke Generator, simply open the `index.html` file in a web browser. The page will load, and a random joke will be displayed. To get a new joke, click the "Get Random Joke" button.

## Files

The application consists of three files:

### 1. `index.html`

This is the main HTML file that structures the webpage. It includes references to the CSS and JavaScript files, as well as the necessary HTML elements to display the joke and button.

### 2. `style.css`

This CSS file contains the styles for the webpage. It defines the appearance of the wrapper, text elements, button, and overall layout.

### 3. `script.js`

The JavaScript file contains the logic for fetching random jokes from the API and updating the webpage. It handles the button click event and manipulates the DOM to display the fetched joke.

## Dependencies

The application relies on the following external resources:

- [Rubik](https://fonts.google.com/specimen/Rubik) font from Google Fonts.
- The [JokeAPI](https://jokeapi.dev/) is used to fetch random jokes. It filters out potentially offensive content based on the specified blacklist flags.

Please ensure that you have an internet connection to load these external resources.

## Acknowledgments

The Random Joke Generator application is created as a sample project and is not affiliated with any particular organization or individual. It serves as a demonstration of how to fetch data from an API and update the DOM dynamically.

Feel free to modify and enhance the code to suit your needs and have fun generating random jokes!
