# Climate Change Impact on Crop Growth (ML)

## Description
This project aims to analyze the impact of climate change on crop growth using machine learning techniques. The objective is to develop a model that predicts how various climate factors, such as temperature, precipitation, and humidity, can influence crop yields. The project uses historical data and machine learning models to understand patterns and forecast future crop growth under different climate scenarios.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/username/climate-change-crop-growth.git
    ```

2. Navigate to the project directory:
    ```bash
    cd climate-change-crop-growth
    ```

3. Create a virtual environment (optional but recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Once you've installed the dependencies, you can start using the machine learning model to predict crop growth based on climate data.

1. **Train the Model**: To train the model with historical data, run:
    ```bash
    python train_model.py
    ```

2. **Make Predictions**: Once the model is trained, use it to make predictions based on new climate data:
    ```bash
    python predict_crop_growth.py --temperature 30 --precipitation 100 --humidity 60
    ```

3. **Evaluate Model**: To evaluate the performance of the model, run:
    ```bash
    python evaluate_model.py
    ```

## Dataset

The dataset used in this project contains historical climate data and corresponding crop yield data. It includes features like:
- Temperature (°C)
- avg_rainfall_per_annum (mm)
- Humidity (%)
- Soil moisture content
- Crop yield (kg/ha)

You can download the dataset from [Dataset Link](https://search.app/edRAeJyMTD7RR1eZ6 ) or use your own data.

## Model

This project uses the following machine learning techniques:
- **Linear Regression** (for predicting crop yields based on climate factors)
- **Random Forest Regressor** (for capturing non-linear relationships)
- **SVM**
- **LASSO**  


## Contributing

We welcome contributions to improve the project! Here's how you can contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-name`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the contributors of the [scikit-learn](https://scikit-learn.org/) library for machine learning algorithms.
- Data used in this project was sourced from [Crop Yield Data](https://example.com).
- Special thanks to [Climate Data Source](https://search.app/edRAeJyMTD7RR1eZ6 ) for providing climate data.
