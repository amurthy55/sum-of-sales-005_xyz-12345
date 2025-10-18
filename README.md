# Sales Summary App

## Summary
This is a simple single-page application that fetches sales data from a CSV file and displays the total sales on the webpage.

## Setup
1. Clone the repository or download the files.
2. Ensure you have a local server running to serve the HTML file.
3. Place the `data.csv` file in the same directory as `index.html`.

## Usage
Open `index.html` in a web browser. The total sales will be calculated and displayed.

## Code Explanation
- The app fetches `data.csv` using the Fetch API.
- It splits the CSV data into rows and then into columns to extract the sales values.
- Each sales value is parsed using `parseFloat` after trimming whitespace to ensure valid numeric computation.
- The total sales are displayed in the `#total-sales` div.

## License
This project is licensed under the MIT License.

## Description
This app demonstrates how to fetch and process CSV data in a web application while ensuring proper numeric validation.