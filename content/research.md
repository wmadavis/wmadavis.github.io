---
title: "Research"
aliases: /research/
url: /research/
disableAnchoredHeadings: false
description: "Page for published and in-progress research projects"
showToc: true
TocOpen: true
UseHugoToc: true

---

### Large potential reduction in economic damages under UN mitigation targets

**[Marshall Burke](https://web.stanford.edu/~mburke/), Matthew Alampay Davis, [Noah S. Diffenbaugh](https://profiles.stanford.edu/noah-diffenbaugh) (2018)**  
*Nature, 557, 549-553*

We present an empirical framework for evaluating the economic benefits of the 2015 Paris Agreement’s temperature targets of 1.5°C and 2.0°. Our findings decompose the large uncertainties involved in such projection exercises and stress the inequity in impacts: it is a stark result that poorer countries that have historically contributed least to carbon emissions have the most the gain from mitigation of global warming.

![Figure 4: The impact of global warming on global GDP per capita, relative to a world without warming, for different forcing levels.](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41586-018-0071-9/MediaObjects/41586_2018_71_Fig4_HTML.jpg)

#### Paper materials and links

+ Paper links: [(official](https://doi.org/10.1038/s41586-018-0071-9) $\cdot$ [ungated)](/papers/BurkeDavisDiffenbaugh2018.pdf)
+ [Replication files](https://github.com/wmadavis/BDD2018)
+ [ECHO Lab website](https://www.stanfordecholab.com/)

##### Press

[Nature critique](https://www.nature.com/articles/d41586-018-05198-7) $\cdot$
[Stanford](https://news.stanford.edu/2018/05/23/reducing-emissions-save-trillions/) $\cdot$
[Bloomberg](https://www.bna.com/money-fewer-woes-n57982093114/) $\cdot$
[CBS (TV)](https://www.youtube.com/watch?v=29c7dTBEdcA) $\cdot$
[The Guardian](https://www.theguardian.com/environment/2018/may/23/hitting-toughest-climate-target-will-save-world-30tn-in-damages-analysis-shows) $\cdot$
[Reuters](https://www.weforum.org/agenda/2018/05/strict-curbs-on-global-warming-would-buoy-world-economy) $\cdot$
[The Hill](https://thehill.com/opinion/energy-environment/389550-paris-agreement-goals-could-save-trillions-in-avoided-climate) $\cdot$
[Yahoo](https://www.yahoo.com/news/fighting-climate-change-could-save-172228421.html) $\cdot$
[Axios](https://www.axios.com/climate-change-paris-agreement-economic-costs-gdp-127aea31-085a-487d-b8b8-b1e7a2befcca.html) $\cdot$
[The New Yorker](https://www.newyorker.com/news/news-desk/the-false-choice-between-economic-growth-and-combatting-climate-change) $\cdot$
[Business Insider](https://www.businessinsider.com/climate-change-capitalism-economic-threat-worse-than-depression-2019-2?r=US&IR=T) $\cdot$
[Rolling Stone](https://www.rollingstone.com/politics/politics-news/why-the-green-new-deal-is-cheap-actually-965794/) $\cdot$
[The Daily Show](https://www.youtube.com/watch?v=40JS3W4um7o)

##### Citations

[New York Times](https://www.nytimes.com/2018/10/15/climate/trump-climate-change-fact-check.html?smid=tw-nytimes&smtyp=cur) $\cdot$
[The Guardian](https://www.theguardian.com/us-news/2018/oct/15/fact-check-donald-trumps-claims-versus-climate-science) $\cdot$
[Governors of New York, California, and Washington](https://www.usatoday.com/story/opinion/2018/06/01/climate-change-work-continues-trumps-paris-retreat-governors-column/661059002/) $\cdot$
[IPCC Special Report on Global Warming of 1.5°C (SR15)](https://www.ipcc.ch/sr15/chapter/chapter-3/) $\cdot$
[MSNBC (TV)](https://www.msnbc.com/morning-joe/watch/-we-are-entering-into-an-unprecedented-climate-1445411907673?fbclid=IwAR1pVWunxrM0UWURQKo06aSEMqZPFG6dZ_PZS4VDxbbn7u2cONwY_OaT5MY) $\cdot$
[“The Uninhabitable Earth” by David Wallace-Wells](https://www.penguinrandomhouse.com/books/586541/the-uninhabitable-earth-by-david-wallace-wells/) $\cdot$
[Rezo](https://www.nytimes.com/2019/05/25/world/europe/rezo-cdu-youtube-germany.html) $\cdot$
[Bernie Sanders](https://berniesanders.com/issues/the-green-new-deal/) $\cdot$
[US House Committee on Financial Services](https://financialservices.house.gov/calendar/eventsingle.aspx?EventID=404231#Wbcast03222017) $\cdot$
[IPCC Sixth Assessment Report (AR6-WGII)](https://www.ipcc.ch/report/ar6/wg2/)

---

### Combining satellite imagery and machine learning to predict poverty

**[Neal Jean](https://nealjean.com/), [Marshall Burke](https://web.stanford.edu/~mburke/), [Michael Xie](https://cs.stanford.edu/~eix/), Matthew Alampay Davis, [David B. Lobell](https://fse.fsi.stanford.edu/people/david_lobell), [Stefano Ermon](https://cs.stanford.edu/~ermon/) (2016)**  
*Science, 353 (6301), 790-794*  

We train a convolutional neural network to identify low-level features of image data useful for classification tasks. We then assign the CNN the related task of condensing high-resolution daytime satellite images into lower-dimensional vectors of features covariant with the areas’ corresponding night-time luminosities, which we consider imperfect proxies for levels of economic activity. Ridge regression models then relate these feature vectors to data from representative household surveys conducted in Uganda, Tanzania, Nigeria, Malawi, and Rwanda to generate fine-scale “poverty maps”, regionally disaggregated estimates of the distribution of consumption expenditure and asset wealth. Cross-validation analyses show that our transfer learning method compares favorably to existing and expensive methods at out-of-sample prediction, suggesting potential applications for interventions targeting poverty in data-scarce areas. We emphasize our pipeline uses only public data and software, enabling cheap replication and potential scalability to help address the infrequency and prohibitive expense of household surveys.  

![](/papers/PovertyMap.png)

#### Paper materials and links

+ Paper links: [(official](https://doi.org/10.1126/science.aaf7894) $\cdot$ [ungated)](/papers/JeanEtAl2016.pdf)
+ Replication files: [(code and data](https://github.com/nealjean/predicting-poverty) $\cdot$ [closed issues)](https://github.com/nealjean/predicting-poverty/issues?q=is%3Aissue+is%3Aclosed)
+ Authors' blog posts: [summary](http://www.g-feed.com/2016/08/economics-from-space.html) $\cdot$ [genesis](http://www.g-feed.com/2016/08/risk-aversion-in-science.html) $\cdot$ [update](http://www.g-feed.com/2017/02/targeting-poverty-with-satellites.html)
+ [Sustain Lab website](http://sustain.stanford.edu/predicting-poverty)
+ [Non-technical animated video summary](https://www.youtube.com/watch?v=DafZSeIGLNE)

##### Press

[Science](http://science.sciencemag.org/content/353/6301/753) $\cdot$
[Stanford](https://news.stanford.edu/2016/08/18/combining-satellite-data-machine-learning-to-map-poverty/) $\cdot$
[The Washington Post](https://www.washingtonpost.com/news/wonk/wp/2016/08/24/how-satellite-images-are-helping-find-the-worlds-hidden-poor/?noredirect=on&utm_term=.ad5ca2f277da) $\cdot$
[BBC](https://www.bbc.co.uk/news/science-environment-37122748) $\cdot$
[Scientific American](https://www.scientificamerican.com/article/2016-world-changing-ideas/) $\cdot$
[The Atlantic](https://www.theatlantic.com/technology/archive/2016/08/can-satellites-learn-to-see-poverty/497153/) $\cdot$
[The Onion](https://www.theonion.com/satellite-images-could-predict-poverty-1819563263) $\cdot$ [Bill Gates](https://twitter.com/BillGates/status/773188644014350336) $\cdot$
[CGDev](https://www.cgdev.org/blog/can-we-measure-poverty-outer-space)

---

### Work in progress

#### Global inequality in the climate century

+ Early version (2019) supervised by [Elizabeth Baldwin](http://elizabeth-baldwin.me.uk/) and [David F. Hendry](https://www.nuffield.ox.ac.uk/people/profiles/david-hendry/) named Oxford’s first ‘exceptional’-class (mark of 80+) graduate economics thesis in at least four years
+ Revised version (2023) supervised by [Suresh Naidu](https://sites.santafe.edu/~snaidu/) awarded Columbia’s Wueller Prize for runner-up best pre-dissertation proposal

#### Environmental disruption of gendered violence and cultural persistence (with [Tanushree Goyal](https://www.tanushreegoyal.com/))

#### Climate change and political transition

#### Elite capture and the political economy of descriptive and substantive representations