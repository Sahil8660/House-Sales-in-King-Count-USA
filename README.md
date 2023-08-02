# Data Analysis with Python - House Sales in King County, USA

This repository contains a data analysis project using Python to explore and analyze house sales data in King County, USA. The dataset used in this project includes information about various real estate properties sold in King County, such as house prices, features, and location details.

## Table of Contents

1. [Introduction](#introduction)
2. [Dependencies](#dependencies)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Data](#data)
6. [Analysis](#analysis)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

The goal of this project is to perform an in-depth data analysis of house sales in King County using Python. We will use popular libraries like Pandas, NumPy, Matplotlib, and Seaborn for data manipulation, visualization, and analysis.

## Dependencies

To run this project, you will need the following dependencies:

- Python 3.x
- Jupyter Notebook (optional but recommended)

All the necessary packages will be listed in the `requirements.txt` file.

## Installation

To set up the project on your local machine, follow these steps:

1. Clone this repository:

   ```
   git clone https://github.com/your-username/Data-Analysis-House-Sales-King-County.git
   cd Data-Analysis-House-Sales-King-County
   ```

2. (Optional) Create a virtual environment and activate it:

   ```
   python3 -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

## Usage

To run the data analysis, open the Jupyter Notebook using the following command:

```
jupyter notebook
```

This will launch Jupyter in your web browser. Open the `House_Sales_King_County.ipynb` notebook and execute the cells one by one to view the analysis results.

## Data

The dataset used in this project can be found in the `data` directory. It is a CSV file named `house_sales_king_county.csv` containing information on various house sales in King County.

The dataset includes the following columns:

- `id`: Unique identifier for each property
- `date`: Date when the property was sold
- `price`: Sale price of the property
- `bedrooms`: Number of bedrooms in the property
- `bathrooms`: Number of bathrooms in the property
- `sqft_living`: Total living area (in square feet)
- `sqft_lot`: Total lot area (in square feet)
- `floors`: Number of floors in the property
- `waterfront`: Whether the property has a waterfront view (0 = No, 1 = Yes)
- `view`: How many times the property was viewed
- `condition`: Overall condition rating of the property
- `grade`: Overall grade given to the property
- `sqft_above`: Total area above ground (in square feet)
- `sqft_basement`: Total basement area (in square feet)
- `yr_built`: Year the property was built
- `yr_renovated`: Year the property was last renovated
- `zipcode`: ZIP code of the property
- `lat`: Latitude coordinate of the property
- `long`: Longitude coordinate of the property
- `sqft_living15`: Average living area of the 15 closest properties (in square feet)
- `sqft_lot15`: Average lot area of the 15 closest properties (in square feet)

## Analysis

The Jupyter Notebook contains a step-by-step analysis of the house sales data, including data cleaning, visualization, and insights derived from the data. The analysis aims to answer various questions related to the house sales trends, property features, and their impact on prices.

## Contributing

Contributions to this project are welcome! If you have any ideas, bug fixes, or improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. You can find the details in the [LICENSE](LICENSE) file.

---

Happy data analysis! If you have any questions or need further information, feel free to contact us. We hope you find this project helpful and insightful in exploring house sales in King County.
