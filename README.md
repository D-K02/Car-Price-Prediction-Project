# README

## Car Price Prediction Project

This project aims to predict car prices based on various features using machine learning techniques. The dataset used for this project contains information about different car models, including their specifications and market prices.

### Dataset

The dataset used in this project is `CarPrice_Assignment.csv`, which includes the following columns:

- **car_ID**: Unique identifier for each car.
- **symboling**: Insurance risk rating.
- **CarName**: Name of the car.
- **fueltype**: Type of fuel used (gas/diesel).
- **aspiration**: Aspiration type (std/turbo).
- **doornumber**: Number of doors (two/four).
- **carbody**: Body style (convertible, sedan, hatchback, etc.).
- **drivewheel**: Drive wheel type (fwd/rwd/4wd).
- **enginelocation**: Location of the engine (front/rear).
- **wheelbase**: Wheelbase measurement.
- **carlength**: Length of the car.
- **carwidth**: Width of the car.
- **carheight**: Height of the car.
- **curbweight**: Weight of the car.
- **enginetype**: Type of engine.
- **cylindernumber**: Number of cylinders in the engine.
- **enginesize**: Size of the engine.
- **fuelsystem**: Fuel system type.
- **boreratio**: Bore ratio of the engine.
- **stroke**: Stroke length of the engine.
- **compressionratio**: Compression ratio of the engine.
- **horsepower**: Horsepower output of the engine.
- **peakrpm**: Peak revolutions per minute.
- **citympg**: Miles per gallon in the city.
- **highwaympg**: Miles per gallon on the highway.
- **price**: Market price of the car.

### Project Overview

1. **Data Preprocessing**:
   - Handled missing values by filling numerical columns with their mean and categorical columns with their mode.
   - Visualized outliers using boxplots and identified outliers using the Z-score method.

2. **Outlier Handling**:
   - Removed outliers based on Z-scores to clean the dataset for better model performance.

3. **Skewness Handling**:
   - Applied Box-Cox transformation to reduce skewness in numerical features.

4. **Feature Encoding**:
   - Utilized One-Hot Encoding to convert categorical variables into a numerical format suitable for regression analysis.

5. **Model Implementation**:
   - Implemented various regression algorithms including Linear Regression, Decision Tree Regressor, Random Forest Regressor, Gradient Boosting Regressor, and Support Vector Regressor.

6. **Hyperparameter Tuning**:
   - Performed hyperparameter tuning on the Random Forest model using Grid Search to optimize its performance.

7. **Model Evaluation**:
   - Compared model performance using metrics such as R-squared, Mean Squared Error (MSE), and Mean Absolute Error (MAE).

### Results

The Random Forest model emerged as the best-performing model, demonstrating a significant ability to predict car prices accurately. Hyperparameter tuning further improved its performance metrics.

### Requirements

To run this project, you will need:

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - scipy

### Installation

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

### Usage

1. Clone this repository to your local machine.
2. Ensure you have all dependencies installed as listed above.
3. Run the Jupyter Notebook or Python script to execute the project.

### License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

Feel free to modify any sections as needed to better fit your project's specifics or personal preferences!

Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/34812455/127c4ab1-4cdc-4101-9724-3bdccb154778/CarPrice_Assignment.csv
