---
title: "Combining satellite imagery and machine learning to predict poverty"
subtitle: "Science, 353 (6301), 790-794"
date: 2016-08-19
url: /research/jeanetal2016
author: ["Neal Jean","Marshall Burke","Michael Xie","Matthew Alampay Davis","David B. Lobell","Stefano Ermon"]
description: "Placeholder description." 
summary: "We train a convolutional neural network to identify low-level features of image data useful for classification tasks. We then assign the CNN the related task of condensing high-resolution daytime satellite images into lower-dimensional vectors of features covariant with the areas’ corresponding night-time luminosities, which we consider imperfect proxies for levels of economic activity. Ridge regression models then relate these feature vectors to data from representative household surveys conducted in Uganda, Tanzania, Nigeria, Malawi, and Rwanda to generate fine-scale “poverty maps”, regionally disaggregated estimates of the distribution of consumption expenditure and asset wealth. Cross-validation analyses show that our transfer learning method compares favorably to existing and expensive methods at out-of-sample prediction, suggesting potential applications for interventions targeting poverty in data-scarce areas. We emphasize our pipeline uses only public data and software, enabling cheap replication and potential scalability to help address the infrequency and prohibitive expense of household surveys." 
cover:
editPost:
    URL: "https://doi.org/10.1126/science.aaf7894"
    Text: "Science"

---

---

##### Summary

We train a convolutional neural network to identify low-level features of image data useful for classification tasks. We then assign the CNN the related task of condensing high-resolution daytime satellite images into lower-dimensional vectors of features covariant with the areas’ corresponding night-time luminosities, which we consider imperfect proxies for levels of economic activity. Ridge regression models then relate these feature vectors to data from representative household surveys conducted in Uganda, Tanzania, Nigeria, Malawi, and Rwanda to generate fine-scale “poverty maps”, regionally disaggregated estimates of the distribution of consumption expenditure and asset wealth. Cross-validation analyses show that our transfer learning method compares favorably to existing and expensive methods at out-of-sample prediction, suggesting potential applications for interventions targeting poverty in data-scarce areas. We emphasize our pipeline uses only public data and software, enabling cheap replication and potential scalability to help address the infrequency and prohibitive expense of household surveys.

![](/papers/PovertyMap.png)


##### Paper and supplementary material

+ [Official link](https://www.science.org/doi/10.1126/science.aaf7894)
+ [Ungated link](/papers/JeanEtAl2016.pdf)
+ [Non-technical video summary](http://www.youtube.com/watch?v=DafZSeIGLNE)
+ [Replication files](https://github.com/nealjean/predicting-poverty)
+ Authors' blog posts:
    + [Summary](http://www.g-feed.com/2016/08/economics-from-space.html)
    + [Genesis](http://www.g-feed.com/2016/08/risk-aversion-in-science.html)
    + [Update](http://www.g-feed.com/2017/02/targeting-poverty-with-satellites.html)
+ [Lab website](http://sustain.stanford.edu/predicting-poverty)

[![Non-technical animated summary"](https://img.youtube.com/vi/DafZSeIGLNE/hqdefault.jpg)](https://youtu.be/DafZSeIGLNE)

##### Some press

+ [Science](http://science.sciencemag.org/content/353/6301/753), [Stanford](https://news.stanford.edu/2016/08/18/combining-satellite-data-machine-learning-to-map-poverty/), [Washington Post](https://www.washingtonpost.com/news/wonk/wp/2016/08/24/how-satellite-images-are-helping-find-the-worlds-hidden-poor/?noredirect=on&utm_term=.ad5ca2f277da), [BBC](https://www.bbc.co.uk/news/science-environment-37122748), [Scientific American](https://www.scientificamerican.com/article/2016-world-changing-ideas/), [The Atlantic](https://www.theatlantic.com/technology/archive/2016/08/can-satellites-learn-to-see-poverty/497153/), [The Onion](https://www.theonion.com/satellite-images-could-predict-poverty-1819563263), [Bill Gates](https://twitter.com/BillGates/status/773188644014350336), [CGDev critique](https://www.cgdev.org/blog/can-we-measure-poverty-outer-space)