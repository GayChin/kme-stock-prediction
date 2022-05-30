# Stock-Prices-Prediction-ML-Flask-Dashboard

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project).
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Contents](#contents)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)

<!-- ABOUT THE PROJECT -->
## About The Project
## Demo
![Demo](https://github.com/Zeeshanahmad4/Stock-Prices-Prediction-ML-Flask-Dashboard/blob/master/pics/ezgif.com-video-to-gif.gif)

## Code
![Code](https://github.com/Zeeshanahmad4/Stock-Prices-Prediction-ML-Flask-Dashboard/blob/master/pics/code.PNG)

## Dashbord
![Output-Data](https://github.com/Zeeshanahmad4/Stock-Prices-Prediction-ML-Flask-Dashboard/blob/master/pics/Capture3.PNG)


## Prediction result
![predic](https://github.com/Zeeshanahmad4/Stock-Prices-Prediction-ML-Flask-Dashboard/blob/master/pics/Capture1.PNG)

## Models evaluation
![evaluation](https://github.com/Zeeshanahmad4/Stock-Prices-Prediction-ML-Flask-Dashboard/blob/master/pics/Capture2.PNG)
![evaluation](https://github.com/Zeeshanahmad4/Stock-Prices-Prediction-ML-Flask-Dashboard/blob/master/pics/Plot.png)

### Built With
* [Python](https://www.python.org/)
* [matplotlib](https://matplotlib.org/)
* [sklearn](https://scikit-learn.org/)
* [flask](https://flask.palletsprojects.com/en/2.1.x/)
* [keras](https://keras.io/)

## Models and algorithms

```
├── SVR
├── linear_regression
├── random_forests
├── keras
├── KNN
├── decision_trees
├── elastic_net
├── LSTM_model

```

### Prerequisites

### Installation
1. Clone the repo
```sh
git clone https://github.com/GayChin/kme-stock-prediction.git
```

2. Install python packages
```sh
pip install matplotlib
pip install sklearn
pip install flask
pip install KNN
pip install tensorflow
pip install keras
```

<!-- USAGE EXAMPLES -->
## Usage

This program predicts the price of several stock for a specific day using the Machine Learning algorithm called Support Vector Regression (SVR) Linear Regression.
Importing flask module in the project is mandatory
An object of Flask class is our WSGI application.


## Contents

```
├── app.py
├── train_models.py
├── utils.py
├── individual_stocks_5yr

All model training csv data files are stored in individual_stocks_5yr directory. 
You may customize the trained data by adding or remove from the directory.
```

<!-- ROADMAP -->
## Roadmap
See the [open issues](https://github.com/GayChin/kme-stock-prediction/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/ExtraFeatures`)
3. Commit your Changes (`git commit -m 'Add some ExtraFeatures`)
4. Push to the Branch (`git push origin feature/ExtraFeatures`)
5. Open a Pull Request

<!-- LICENSE -->
## License
Distributed under the MIT License. See `LICENSE` for more information.