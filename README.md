# Cryptocurrency-Analysis-Using-Python

## Overview
A Python program analysing three different cryptocurrencies : Bitcoin, Ether and Litecoin. Here I had used the last one year data : 27/02/2020 - 27/02/2021


## Technical Aspect

1. Data Collection : Collect the price data of each cryptocoins of last one year from 28/02/2020 - 27/02/2021. You can download the dataset from my github from [here](https://github.com/mpfouziya/Cryptocurrency-Analysis-Using-Python/tree/main/dataset). 
2. Preprocess the data : As I am doing the analysis on the closing price of each cryptocoins, we need to extract only the closing price of each coins from each dataset and scale it.
3. Analyse and visualize the price variation of each coins. Following graph shows the price variation.
<p align="center">
<img width="500" alt="postgreSQL" src="https://user-images.githubusercontent.com/37532698/109411578-907f3380-79bc-11eb-8bd5-b5188a43ee1e.jpg"></p>
4. Find whether there is any correlation for the price variance of each coin. My findings say that the price variation is highly correlated.
5. Analyse the fluctuations of Daily Simple Returns from each coin.
 <p align="center">
<img width="500" alt="postgreSQL" src="https://user-images.githubusercontent.com/37532698/109411791-eb655a80-79bd-11eb-9de9-ad531b2b5f2e.jpg"></p>
The graph shows that Ether is having obvious high and low spikes wen considering Daily Simple Returns.
6. Finally find how a dollar investment in each coins ends up (whether it is a loss or profit) after one year.
<p align="center">
<img width="500" alt="postgreSQL" src="https://user-images.githubusercontent.com/37532698/109411800-f5875900-79bd-11eb-8a16-6fd013a74dda.jpg"></p>
The graph shows that from the past one year data investment in Ether is profitable compared to Bitcoin and Litecoin.
    

## Installation
The Code is written in Python 3.9.1 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img width="159" alt="postgreSQL" src="https://user-images.githubusercontent.com/37532698/108682128-5f5cba00-7509-11eb-9ab4-2cc02f7971c0.png">](https://www.postgresql.org/) [<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) <img width="80" alt="html" src="https://user-images.githubusercontent.com/37532698/108952721-77584900-7683-11eb-8dec-5376533d43cf.png"> <img width="64" alt="css" src="https://user-images.githubusercontent.com/37532698/108952837-a4a4f700-7683-11eb-8740-e044f1e34651.png"> 



