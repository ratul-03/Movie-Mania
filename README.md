# Movie Mania - Movie Reviews

Movie Mania is an application that displays movie reviews. It fetches movie review data and shows statistics such as the total number of movies, total reviews, and average ratings. It also displays the movie title, rating, review content, and the reviewer details.

## Features
- Displays total number of movies, total reviews, and average rating.
- Lists individual movie reviews including title, rating, and review content.
- Shows the reviewer's name and the date the review was posted.

## Technologies Used
- JavaScript (ES6+)
- HTML5
- CSS (TailwindCSS for styling)

## How It Works
1. **Initialization**: The `init` function fetches movie review data and triggers the painting of statistics and movie data.
2. **Statistics**: The `paintStatistics` function calculates the total number of movies, total reviews, and average rating from the movie review data.
3. **Movie Data**: The `paintMovieData` function loops through the review data and displays each movie's title, rating, review content, and reviewer details.

## Setup
To set up the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/movie-mania.git
    ```

2. Navigate to the project directory:
    ```bash
    cd movie-mania
    ```

3. Open the `index.html` file in your browser to view the project.

## Project Structure
```plaintext
movie-mania/
├── data.js               # Contains movie review data and logic to fetch it.
├── index.html            # Main HTML file
├── script.js             # Main JavaScript file with the logic
└── styles.css            # Styling for the project
```

## Contributing
Feel free to fork the repository and submit issues or pull requests. Contributions are welcome!

## License
This project is open-source and available under the MIT License.
