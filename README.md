# NYC Taxi Data Machine Learning Project

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Description](#data-description)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Modeling](#modeling)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

## Project Overview
This project focuses on analyzing and predicting patterns within NYC Taxi data. We utilize machine learning techniques to understand various aspects such as trip duration, fare prediction, and passenger demographics. Our goal is to develop models that can accurately predict and analyze taxi trips in New York City.

## Data Description
The primary dataset used in this project is the `yellow_tripdata_2022-06.parquet` file, which contains detailed information about taxi trips in NYC for June 2022. Key features include:

- `VendorID`
- `tpep_pickup_datetime`
- `tpep_dropoff_datetime`
- `passenger_count`
- `trip_distance`
- `RatecodeID`
- `store_and_fwd_flag`
- `PULocationID`
- `DOLocationID`
- `payment_type`
- `fare_amount`
- `extra`
- `mta_tax`
- `tip_amount`
- `tolls_amount`
- `improvement_surcharge`
- `total_amount`
- `congestion_surcharge`
- `airport_fee`

## Installation
To get started with this project, follow these steps:

1. Clone this repository:
   ```sh
   git clone https://github.com/dhruv-atreya/nyc-taxi-ml-project.git
   ```
2. Navigate to the project directory:
   ```sh
   cd nyc-taxi-ml-project
   ```
3. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
4. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
To run the project, follow these steps:

1. Ensure you have the necessary data file (`yellow_tripdata_2022-06.parquet`) in the project directory.
2. Run the Jupyter Notebook:
   ```sh
   jupyter notebook ML_project_07_nyc_taxi.ipynb
   ```
3. Follow the steps in the notebook to preprocess the data, train the models, and evaluate the results.

## Modeling
The project includes various machine learning models to analyze and predict taxi trip data. Key steps include:

- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training and Evaluation

Some of the techniques used are:
- Linear Regression
- Decision Trees
- Random Forest
- Gradient Boosting

## Results
The results of the analysis and predictions are documented within the Jupyter Notebook. Key findings include:

- Patterns in trip duration and distance
- Factors influencing fare amounts
- Passenger demographics and their impact on trip characteristics

## Contributing
We welcome contributions to this project! Please fork the repository and submit pull requests with your improvements. Ensure that your contributions adhere to our coding standards and include appropriate tests.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any questions or inquiries, please contact:

- **Dhruv Atreya**
- Email: [dhruvatrey@gmail.com](mailto:dhruvatrey@gmail.com)
- GitHub: [dhruv-atreya](https://github.com/dhruv-atreya)
- LinkedIn: [dhruv-atreya](https://www.linkedin.com/in/dhruv-atreya)
