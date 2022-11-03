This sections consists of raw data, Python scripts to run the experiments, R scripts for data analysis, and figures that are generated while performing data analysis.

- *Data Analysis*: This folder consists the final CSVs file for both the treatments with 200 repetitions. It also has all the R scripts used for all the phases(data extration, data exploration, normality tests, and hypothesis testing) of  data analysis.
- *Scripts*: It contains all the Python scripts needed to handle the events(before run, before experiment, before close, after launch, after experiment, etc) of the experiment.
- *Experiments*: It contains config files and Python scripts needed to run the experiment.
- *pythonscripts*: It has individual Python scripts to remove ads and analytics from each 10 web apps.
- *Figures*: It contains all the diagrams that are generated while performing data analysis
- *Raw data*: It consists all the data that are generated during the experiments. This is the data on which we are doing data extraction before performing data analysis.
- *proxy: In the folder we have a certificate to be installed in the client device. before running the proxy servery we need to update our device's proxy setting to "manual" and set a "localhost:8081" port. and finaly, In order to run the proxy server we use the following commands:
  - /mitmweb : to run the proxy server without script
  - /mitmweb -s prepared_script.py : to run the proxy with script that intercepts and edits the response. 
