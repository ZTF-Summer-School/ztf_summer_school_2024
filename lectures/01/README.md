## Welcome to Day 1!

Today, we'll be working on 2 different things:
- In the morning: Filtering a whole night of ZTF alerts, getting familiar with the data while looking for interesting objects.
- In the afternoon: We'll be working on training a machine learning model to classify objects in the ZTF alerts, based on Nabeel Rehemtulla's BTSbot model, which identifies objects of interest for the Bright Transient Survey, enabling automtated follow-up and classification.



1. **ZTF Alert Filtering:** The dataset you'll need has been added as a git submodule (which is simply a reference to another git repository, so that you don't necessarily have to download the data when cloning this repository). To get the data, you'll need to run the following commands in your terminal:
```bash
git submodule init && git submodule update
```

Then, you'll need to create a python virtual environment with the solution of your choice (conda, venv, etc.) and install the requirements:
```bash
pip install -r requirements_ztf_alert_filtering.txt
```

If you need help with this, please refer to the help/ directory, or simply ask one of the instructors.

Also, here is the ZTF alert schema if you need to figure out the meaning of a field from the alerts: https://zwickytransientfacility.github.io/ztf-avro-alert/schema.html

2. **Machine Learning Model Training:** *Will be added before the afternoon session.*

Have fun! 🚀


##### Troubleshoot:

If you are having issues downloading the dataset properly, or you get an error in the notebook saying the file is corrupted, it is likely because `git lfs` is not installed on your system. You can either install it, or just `cd ztfsummerschool_alert_data`
to get in the right folder, and download the files with `wget https://github.com/Theodlz/ztfsummerschool_alert_data/raw/main/ztf_alerts_2460474.5.parquet` (for the alerts), and `wget https://github.com/Theodlz/ztfsummerschool_alert_data/raw/main/ztf_alerts_2460474.5_prv_candidates.parquet`.

Worst-case scenario if none of the above works for you: just download them from github's webpage in your browser at: https://github.com/Theodlz/ztfsummerschool_alert_data. You can just click on each file, that will open a page with a download button in the top right-hand corner. Make sure to move these files to the same directory `ztfsummerschool_alert_data`, under `lecture/01`.
Last resort is to just go to the git repo where the data is: 
