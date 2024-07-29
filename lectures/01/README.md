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

2. **Machine Learning Model Training:** *Will be added before the afternoon session.*

Have fun! 🚀
