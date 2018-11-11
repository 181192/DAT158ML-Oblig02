# DAT158ML-Oblig02 - TalkingData AdTracking Fraud Detection Challenge

Fraud risk is everywhere, but for companies that advertise online, click fraud can happen at an overwhelming volume, resulting in misleading click data and wasted money. Ad channels can drive up costs by simply clicking on the ad at a large scale. With over 1 billion smart mobile devices in active use every month, China is the largest mobile market in the world and therefore suffers from huge volumes of fradulent traffic.

TalkingData, China’s largest independent big data service platform, covers over 70% of active mobile devices nationwide. They handle 3 billion clicks per day, of which 90% are potentially fraudulent. Their current approach to prevent click fraud for app developers is to measure the journey of a user’s click across their portfolio, and flag IP addresses who produce lots of clicks, but never end up installing apps. With this information, they've built an IP blacklist and device blacklist.

While successful, they want to always be one step ahead of fraudsters and have turned to the Kaggle community for help in further developing their solution. In their 2nd competition with Kaggle, you’re challenged to build an algorithm that predicts whether a user will download an app after clicking a mobile app ad. To support your modeling, they have provided a generous dataset covering approximately 200 million clicks over 4 days!

Link to the kaggle competition [https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection](https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection)

## Before browsing this Jupyter Notebook

When browsing through this notebook I recommend using the toc2 extension for a table of content and
the Collapsible Headings extension to be able to collapse the headings. It's a very helpful tool when browsing though
a large notebook.
![jupyter_ext](https://raw.githubusercontent.com/181192/DAT158ML-Oblig02/master/pictures/notebook_ext.png)

## To install the jupyter extentions

To install the current version simply type

```shell
conda install -c conda-forge jupyter_contrib_nbextensions

# Or if not using conda
pip install jupyter_contrib_nbextensions
```

Install javascript and css files

```shell
jupyter contrib nbextension install --user
```

Installing the Jupyter Nbextensions Configurator

```shell
conda install -c conda-forge jupyter_nbextensions_configurator

# Or if not using conda
pip install jupyter_nbextensions_configurator
```

```shell
jupyter nbextensions_configurator enable --user
```

Then go to `<base_url>/nbextensions`, probably `localhost:8888/nbextensions`.

Then enable the extentions (Table of Content (2) and Collapsible Headings).
