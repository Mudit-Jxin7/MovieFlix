# Movie Searching App

This is a Movie Searching App that allows users to search for movies using a third-party API. The app is built using HTML, CSS, and JavaScript, and it leverages the power of a third-party API to fetch movie data and display it to the user.

## Features

- Search for movies by title
- View detailed information about each movie, including title, release year, plot, and poster image
- Display a list of search results with movie titles and poster images

 ## URL 
https://curious-fairy-744522.netlify.app/

## Technologies Used

- HTML5: Used for structuring the web page.
- CSS3: Used for styling the web page and making it visually appealing.
- JavaScript (ES6+): Used for handling user interactions, making API requests, and dynamically updating the page content.
- Third-Party API: Utilized to fetch movie data and display it to the user.

## Usage

1. Clone the repository or download the source code files.

```
git clone https://github.com/Mudit-Jxin7/MovieFlix.git
```

2. Open the project folder in your preferred code editor.

3. In the project folder, locate the `index.html` file and open it in a web browser.

4. Enter the desired movie title in the search bar and click the search button or press Enter.

5. The app will make a request to the third-party API and display the search results.

6. Click on a movie title or poster image to view detailed information about the selected movie.

## Configuration

The app requires an API key from a third-party movie database API to function properly. Follow the steps below to configure the API key:

1. Visit the website of a movie database provider and sign up for an account.

2. Obtain an API key from the provider's developer portal or API documentation.

3. In the project files, locate the JavaScript file named `script.js`.

4. In the `script.js` file, find the variable named `apiKey` and replace the placeholder value with your actual API key.

```javascript
const APIURL = "https://api.themoviedb.org/3/discover/movie?sort_by=popularity.desc&api_key=YOUR_API_KEY";
```

5. Save the changes to the `script.js` file.
