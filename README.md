# Machine-Learning


![image](https://github.com/ikafit808/Machine-Learning/assets/142754993/5955727d-1790-43b7-b9cc-7b027f0ecbd4)



## Background
For this Challenge, you’ll assume the role of a financial advisor at one of the top five financial advisory firms in the world. Your firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, your firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.

The speed of these transactions gave your firm a competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. You’re thus planning to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. To do so, you’ll enhance the existing trading signals with machine learning algorithms that can adapt to new data.

## What You're Creating
You’ll combine your new algorithmic trading skills with your existing skills in financial Python programming and machine learning to create an algorithmic trading bot that learns and adapts to new data and evolving markets.

In a Jupyter notebook, you’ll do the following:

Implement an algorithmic trading strategy that uses machine learning to automate the trade decisions.

Adjust the input parameters to optimize the trading algorithm.

Train a new machine learning model and compare its performance to that of a baseline model.


## Instructions
The steps for this Challenge are divided into the following sections:

Establish a Baseline Performance

Tune the Baseline Trading Algorithm

Evaluate a New Machine Learning Classifier

Create an Evaluation Report

Establish a Baseline Performance
In this section, you’ll run the provided starter code to establish a baseline performance for the trading algorithm. To do so, complete the following steps.

NOTE
The provided CSV file contains open, high, low, close, and volume (OHLCV) data for a Morgan Stanley Capital International (MSCI)–based emerging markets exchange-traded fund (ETF) that iSharesLinks to an external site. issued. Investments in emerging markets make up an important aspect of a well-diversified investment portfolio. That’s because the included equities have potentially higher long-term returns, even though they carry more risk.

Open the provided Jupyter notebook, restart the kernel, and then run the cells that correspond with the following steps:

Import the OHLCV dataset into a Pandas DataFrame.

Generate trading signals by using short- and long-window SMA values.

Split the data into training and testing datasets.

Use the SVC classifier model from the SKLearn support vector machine (SVM) learning method to fit the training data and make predictions based on the testing data. Review the predictions.

Review the classification report that’s associated with the SVC model predictions.

Create a predictions DataFrame that contains “Predicted”, “Actual Returns”, and “Strategy Returns” columns.

Create a cumulative return plot that shows the actual returns vs. the strategy returns. Save a PNG image of this plot. This will serve as a baseline against which to compare the effects of tuning the trading algorithm.

Write your conclusions about the performance of the baseline trading algorithm in the README.md file that’s associated with your GitHub repository. Support your findings by using the PNG image that you saved in the previous step.

Tune the Baseline Trading Algorithm
In this section, you’ll tune, or adjust, the model’s input features to find the parameters that result in the best trading outcomes. (You’ll choose the best by comparing the cumulative products of the strategy returns.) To do so, complete the following steps:

Tune the training algorithm by adjusting the size of the training dataset. To do so, slice your data into different periods. Rerun the notebook with the updated parameters, and record the results in your README.md file. Answer the following question: What impact resulted from increasing or decreasing the training window?

Choose the set of parameters that best improved the trading algorithm returns. Save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document your conclusion in your README.md file.

## Evaluate a New Machine Learning Classifier
In this section, you’ll use the original parameters that the starter code provided. But, you’ll apply them to the performance of a second machine learning model. To do so, complete the following steps:

Import a new classifier, such as AdaBoost, DecisionTreeClassifier, or LogisticRegression. (For the full list of classifiers, refer to the Supervised learning pageLinks to an external site. in the scikit-learn documentation.)

Using the original training data as the baseline model, fit another model with the new classifier.

Backtest the new model to evaluate its performance. Save a PNG image of the cumulative product of the actual returns vs. the strategy returns for this updated trading algorithm, and write your conclusions in your README.md file. Answer the following questions: Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?




