# candle-stick-reinfordement-based
Build a self-adapting AI that predicts the next candlestick (or its direction) using reinforcement learning (RL). The model will learn from historical data and continue adapting as new data arrives.

# Prerequesits
This script was written for Python 3.11 and was executed in MicroSoft Visualstudio Coder.
All needed dependencies *should* be listed in requirements.txt and can be installed with   
    `pip install -r requirements.txt`  
To be able to retriev data from Alpha Vantage you need to singh in to https://www.alphavantage.co/support/#api-key, request a key and enter it to LOCAL_KEY = "" in data_import.ipynb
# How2 run the script
To get everything up and running execute the Jupiter Labs file in the order
1. notebooks/data_import.ipynb - to download the data (enter you key up fron like described in pre-requisit)
2. notebooks/rl_environment.ipynb to train the model and store it. After that you can play with the model with
3. notebooks/test_the_model.ipynb. Here also some visulaization was done