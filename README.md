# Text Analysis of Scientific Abstracts

This repository contains analysis scripts and highlights from a project I completed in a Computational Linguistics class at Washington University in St Louis. The primary goal of this project was to evaluate the reproducibility of psychological research by applying text-based analysis to abstracts, and understand whether linguistic signatures in the abstracts could provide useful information about whether a study would be replicated or not.

The Jupyter notebook goes over code that performs latent semantic analysis on the abstracts and then uses different classifiers to predict replication. The later parts of the code also calculate lexical diversity and parts-of-speech for each abstract, which are later used as predictors in analyses.

The R file goes over the specific regression models that use some of this data to examine whether any linguistic signatures in the abstracts can predict reproducibility.

For more information, please refer to the [preprint](http://abhilashak.weebly.com/uploads/5/9/6/0/59603701/kumar_reproducibility.pdf) where I describe the original motivation and the analyses methods in detail.
