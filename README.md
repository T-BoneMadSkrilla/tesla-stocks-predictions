# PyTorch Tesla Stocks Price Predictions

PyTorch Tesla Stock Predictions using 2 neural nets, one with an LSTM layer and one with a 2 day look back.

The networks are stored and available in case you want to run them for inference or additional training. The stock price data was pulled from Yahoo and is located in the file ```TSLA-2014-12-27-2019-12-27.csv```. There are 2 jupyther notebook files, one showing how the network was trained and one showing how to load the network files, the data, and how to use them to make inferences.

Following libraries have been used for this project:
pandas, matplotlib, numpy, pytorch, sklearn, pickle

You can install them by running:
```pip install pandas matplotlib numpy pytorch sklearn pickle```

### Contribute

Feel free to file issues on github, open pull requests with improvements, or reach out with suggestions to dusan.stanojevic.cs@gmail.com.