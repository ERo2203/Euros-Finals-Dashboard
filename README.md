# Euros-Finals-Dashboard
 The dataset contains detailed event data and player stats from The UEFA Euros finals Spain v England
 
Sure, here's a README file for your `EurosFinal Dashboard.ipynb` Jupyter Notebook. This README will provide a clear and concise overview of the project, how to set it up, and how to use it.

---

### EurosFinal Dashboard

This repository contains a Jupyter Notebook (`EurosFinal Dashboard.ipynb`) for analyzing and visualizing performance metrics from a football match, using event data extracted from a provided HTML file.

## Dataset

The dataset includes detailed event data and player statistics from a football match, focusing on metrics like shots, passes, tackles, interceptions, dribbles, and expected Threat (xT) values.

## Features

- Extracts JSON data from an HTML file.
- Calculates key performance metrics for specified players.
- Visualizes metrics using bar graphs.
- Utilizes `mplsoccer` for advanced football data visualization.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/EurosFinal-Dashboard.git
   cd EurosFinal-Dashboard
   ```

2. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Place the match HTML file (e.g., `Spain 2-1 England - European Championship 2024 Live.html`) in the root directory or specify its path in the notebook.
2. Open the Jupyter Notebook:
   ```sh
   jupyter notebook EurosFinal Dashboard.ipynb
   ```
3. Run the notebook cells to:
   - Extract and process data from the HTML file.
   - Calculate performance metrics for specified players.
   - Generate visualizations for the analyzed data.

## Analysis Steps

1. **Extract JSON Data**: Parse the HTML file to extract relevant JSON data.
2. **Process Data**: Convert JSON data into DataFrames, calculate xT values, and create short names for players.
3. **Calculate Metrics**: Compute metrics such as shots, passes, tackles, interceptions, dribbles, and xT values for specified players.
4. **Visualize Data**: Create bar graphs to display performance metrics.

## Example

The notebook includes example code to calculate and visualize the performance metrics for the following players:
- L. Yamal
- N. Williams
- J. Bellingham
- M. Cucurella
- C. Palmer

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements

Special thanks to the `mplsoccer` library for providing tools to create football data visualizations.

---

Feel free to customize this README to better suit your project's specifics and any additional instructions or information you want to include.
