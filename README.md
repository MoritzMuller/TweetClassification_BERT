# Tweet Classification with BERT
Tweet classification with Google's BERT language model

In this quick tutorial, I show how to use Google's BERT language model to classify Tweets. More specifically, I show how to run this operation via Google's Colab online service, which let's users use TPU computation engines, which is very helpful particularly when using the large pre trained BERT models. 

For much more context of how this was done, please find my open access publication that resulted from this here: https://www.sciencedirect.com/science/article/pii/S0740624X22000156. In this publication, I use the output from the Tweet classification to test whether the choice of communication style increases Twitter audience engagement. To contextualize where the BERT classification fit in the workflow, here is the strategy that I followed:
1. Access the Twitter API to download thousands of Tweets by regulatory agencies of the EU (in R)
2. Clean and format the Tweets and pass them to Google Colab for classification (Python/Jupyter Notebook) (this tutorial)
3. Hyperparameter tuning and model evaluation until result is optimized (Python/Jupyter Notebook)
4. Use classifified Tweet data to test whether communication style impacts how much users engage with each Tweet (as measured by likes of the Tweet), using mixed linear regression models

This tutorial only shows the basics of how to import the data to Google Colab and how to import and fine tune the various BERT models to keep things simple. Model outputs can be significantly improved if one performs hyperparameter tuning and extensive model evaluation.

