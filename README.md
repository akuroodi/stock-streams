# stock-streams: A quick time series analysis of popular stock tickers using the novel [Matrix Profile](https://www.cs.ucr.edu/~eamonn/MatrixProfile.html) developed at UCR

# Usage
Create a virtual environment with the provided requirements file, then simply follow along in the Jupyter Notebook! 

# What is the Matrix Profile (MP)?
The matrix profile efficently _annotates_ a given time series, and using only the MP we can trivially solve a multitude of time series analysis problems including:
- motif discovery 
- discords 
- regime changes

In this example, we show how we can use the MP on multi-year stock ticker data to visualize common themes and dissonances between two stocks. 

These visualizations prove vital for a host of data analysis tasks, and due to efficiency in generating them (as opposed to a brute force pairwise comparison for example), we can utilize the MP in online streaming environments. 
