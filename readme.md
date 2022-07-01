# Test for COVID 19 using Chest X-Rays!

A web app that takes in a X-Ray image in some digital format and then runs a deep Neural Network for classifying whether the given X-Ray image signify a possible COVID-19 case.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system, the app aims at rapid testing and classification of potential COVID-19 patients.

### Prerequisites

What things you need to install the software and how to install them

```
1. tensorflow
2. keras
3. sklearn
4. Flask
```
To install all dependencies run the following:
```
pip install -r requirements.txt
```

Run app.py 
```
python app.py
```
And Launch yuor Browser and go to : http://localhost:5000/

## Overview

![Alt text](./extras/normal_up.png?raw=true "Normal Upload")

![Alt text](./extras/normal_res.png?raw=true "Normal Result")

![Alt text](./extras/covid_up.png?raw=true "Covid Upload")

![Alt text](./extras/covid_res.png?raw=true "Covid Result")

## Performance of The model

![Alt text](./results.png?raw=true "Performance")


## Additional Notes

## Built With

* Python 
* Flask 
* HTML 
* CSS 
* JavaScript 
* tensorflow
* keras

## Architecture

* The model uses a deep Conv-Net based base model for feature extraction (specific for X-Ray images) and then uses those features to fine tune the base model to predict the risk factor for the potential patients

## Version Info

Version : 1.0.0

## Authors

* **Suchet Aggarwal** - *IIIT-Delhi* - [Other Work](https://github.com/Suchet-Agg)

## Acknowledgments

* [Data Set Used](https://github.com/ieee8023/covid-chestxray-dataset)
