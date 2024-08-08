# Cricket Data Analytics: Best 11 Players Selection

## Project Overview
This project utilizes data from the T20 World Cup to identify the best 11 cricket players. The project involves data scraping from ESPNcricinfo, data cleaning and transformation using Pandas, and creating interactive dashboards in Power BI to make data-driven decisions.

## Project Structure
The repository is structured as follows:

- `data/`
  - Contains raw and processed data files.
- `scripts/`
  - Includes all the Python scripts for data scraping, cleaning, and transformation.
- `notebooks/`
  - Jupyter notebooks used for data analysis and transformation.
- `dashboards/`
  - Power BI files for interactive data visualization.

## Getting Started

### Prerequisites
- Python 3.x
- Pandas
- Jupyter Notebook
- Power BI Desktop
- Bright Data account (for web scraping)

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/cricket-data-analytics.git
    cd cricket-data-analytics
    ```

2. Install the required Python packages:
    ```bash
    pip install pandas jupyter
    ```

3. Set up your Bright Data account and download the necessary web scraping scripts.

### Data Scraping
1. Navigate to the `scripts/` directory:
    ```bash
    cd scripts
    ```
2. Run the web scraping script to collect data from ESPNcricinfo:
    ```bash
    node scrape_data.js
    ```

### Data Cleaning and Transformation
1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Navigate to the `notebooks/` directory and open `data_transformation.ipynb`.
3. Run all the cells to clean and transform the data.

### Building Dashboards
1. Open Power BI Desktop.
2. Load the processed CSV files from the `data/` directory.
3. Use the provided `.pbix` file in the `dashboards/` directory to build and customize your dashboards.

## Key Features
- **Data Scraping:** Extract match results, scorecards, and player information from ESPNcricinfo.
- **Data Cleaning & Transformation:** Utilize Python and Pandas for data processing.
- **Interactive Dashboards:** Create insightful visualizations in Power BI to assist in selecting the top 11 players.

## Skills Demonstrated
- Web Scraping
- Data Cleaning
- Data Transformation
- Data Visualization
- Sports Data Analysis
- Dashboard Design

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any questions or inquiries, please contact [Hriday Bhagtani](mailto:hridayparas@gmail.com).

---
*Cricket analytics project using T20 World Cup data for selecting the best 11 players via Power BI.*
