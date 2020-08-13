# UTK COVID-19 data

This repository contains my data collected from [UTK's](https://utk.edu) public [COVID-19 dashboard](https://veoci.com/veoci/p/form/4jmds5x4jj4j#tab=entryForm) and the Jupyter Notebook I am using to do so.

The [screenshot-and-ocr](https://github.com/jeremydmoore/utk_covid-19/blob/master/notebooks/screenshot-and-ocr.ipynb) notebook contains steps to screenshot and OCR the dashboard.

Currently I am only collecting data in the form of PNG screenshots and text files in the [data directory](https://github.com/jeremydmoore/utk_covid-19/tree/master/data). The files are named ```YYYY-MM-DD_HHMM``` with the HHMM in a 24-hr clock followed by either ```_screenshot``` or ```_covid-text```.

Once I have collected more datapoints, I will begin parsing the COVID-19 text data.

As of 2020-08-13, the dashboard I was pulling my data from is no longer active because the UTK facilities folks are able to clean areas so quickly space closing no longer need to be announced, simply cordoned off for cleaning and then re-opening: https://veoci.com/veoci/p/form/4jmds5x4jj4j#tab=entryForm

There are numbers on https://www.utk.edu/coronavirus/guides/data-monitoring-and-contingency-options, but they are presented via Google Studio graphs/charts that have different metrics.

You can download CSV files from a Google Studio graph/chart, though, so I will investigate using Selenium to pull this data when time permits.
