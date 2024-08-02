
      My Project 9

# Movie Queue Manager

## Description

This project is a simple implementation of a movie queue manager using JavaScript. It demonstrates various JavaScript concepts, including arrow functions, higher-order functions like `map` and `filter`, and object methods. The application allows users to manage a movie queue by adding, removing, and displaying movies in the queue.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Example Output](#example-output)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/JimiL555/My-Project-9.git
    ```

2. Navigate to the project directory:
    ```bash
    cd My-Project-9
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```

## Usage

To run the script and see the output of the movie queue manager:

1. Open a terminal and navigate to the project directory.

2. Run the following command:
    ```bash
    node index.js
    ```

## Code Structure

### `index.js`

- **funnyCase Function**
  - Converts each letter in a string to the opposite case of the previous letter.
  - Example: `"You can't just do whatever you want all the time!"` becomes `"yOu cAn't jUsT Do wHaTeVeR YoU WaNt aLl tHe tImE!"`.

- **map Function**
  - A custom implementation of the `map` function that applies a callback to each element of an array.
  - Example: Doubling the numbers in an array `[1, 2, 3, 4, 5]` results in `[2, 4, 6, 8, 10]`.

- **filter Function**
  - A custom implementation of the `filter` function that filters elements of an array based on a callback.
  - Example: Filtering even numbers from an array `[1, 2, 3, 4, 5]` results in `[2, 4]`.

- **netflixQueue Object**
  - Manages a queue of movies with methods to watch, add, and print the queue.
  - Methods:
    - `watchMovie()`: Removes the last movie from the queue.
    - `addMovie(movie)`: Adds a new movie to the front of the queue.
    - `printQueue()`: Prints the current list of movies in the queue in reverse order.

## Example Output

yOu cAn’t jUsT Do wHaTeVeR YoU WaNt aLl tHe tImE!
[ 2, 4, 6, 8, 10, 12, 14, 16, 18, 20 ]
[ 2, 4, 6, 8, 10 ]
Printing movie queue!

	4.	Fight Club
	5.	Eternal Sunshine of the Spotless Mind
	6.	The Matrix
	7.	Mr. Nobody

Watched a movie!
Printing movie queue!

	3.	Eternal Sunshine of the Spotless Mind
	4.	The Matrix
	5.	Mr. Nobody

Adding a movie!
Printing movie queue!

	4.	Black Swan
	5.	Eternal Sunshine of the Spotless Mind
	6.	The Matrix
	7.	Mr. Nobody
  
  ## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the ISC License. See the [LICENSE](LICENSE) file for details.