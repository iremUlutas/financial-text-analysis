# financial-text-analysis
A start to find relations between human readable data about companies and their stock price changes.

Please run the notebooks in the following order:
crawler2006-2012.ipynb  - generates the reports, dates_to_check and report_dates files for years prior to 2012
crawl.ipynb             - generates the reports, dates_to_check and report_dates files for years after 2012
populate.ipynb          - put the data into the right format and show histograms
train.ipynb             - feed the data into the calculation methods
