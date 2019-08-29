Tanzanian Water Pumps
==============================

The Tanzanian Ministry of Water recently conducted a survey of over 60 thousand water pumps that had been installed around the country over the last several decades.  The Ministry knew what kind of pumps existed, which organizations had installed them, and how the pumps were managed.  The survey added one last important detail to the existing knowledge: did the pumps still work? 

In this project, I use the [fast.ai](https://www.fast.ai/) deep learning library for one of its newest applications: predictive modeling on tabular data.  I compare its performance against the incumbent best tool in the field, gradient boosting with [XGBoost](https://xgboost.readthedocs.io/en/latest/). At least for this dataset, XGBoost achieves a higher accuracy and remains a system to be reckoned with.

You can find a long-form description of this project [on my website](https://www.martinalarcon.org/2019-06-01-water-pumps/).

The folder `Docker` contains everything you need to reproduce the computing environment that I used for these calculations. For more details on how to create a Docker container from a Dockerfile and operate within it, see [Reproducible data science with Docker and Luigi](https://www.martinalarcon.org/2019-06-08-reproducible-science/).