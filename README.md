# NYC Traffic Data Analysis

## Overview
This project contains parsers, queries, and dashboards associated with NYC Open Data collision data. It is designed to help users ingest and analyze traffic collision data using a Falcon LogScale instance.

## Features
- Data preparation and cleaning
- Interactive visualizations
- User-friendly interface for data input
- Parsers for ingesting data into Falcon LogScale

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python packages: pandas, matplotlib, seaborn
- Access to a Falcon LogScale instance

### Installation
1. Clone the repository:
   git clone https://github.com/cyberjack256/NYC-Traffic-Data-Analysis.git
2. Navigate to the project directory:
   cd NYC-Traffic-Data-Analysis
3. Install the required packages:
   pip install -r requirements.txt

### Usage

#### 1. Download the CSV Data
- Visit the [NYC Open Data site](https://opendata.cityofnewyork.us/).
- Search for "Motor Vehicle Collisions - Crashes" dataset.
- Download the dataset in CSV format.

#### 2. Prepare the Data
1. Open the Jupyter notebook:
   jupyter notebook nyc_collision_data_preparation.ipynb
2. Run the notebook cells:
   - The notebook will prompt you to enter the path to your collision data file (in CSV format).
   - Example:
     Please enter the path to your collision data file (CSV format): /path/to/your/data.csv
3. Follow the instructions in the notebook to complete the data preparation and analysis.

#### 3. Ingest Data into Falcon LogScale
1. Import the package (.zip) file included in this repository.
2. Use the parser in the packate files to ingest the prepared CSV data into your Falcon LogScale instance.

### Enhancements
- **User Input for File Path**: In the near future, the notebook will allow users to input the path to their collision data file, making it more flexible and user-friendly.

### Contributing
As always, I welcome contributions to improve this project. Please fork the repository and submit pull requests for any enhancements or bug fixes.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Contact
For any questions or feedback, please contact [cyberjack256](https://github.com/cyberjack256).

