# Backup Your Twitter Info
Use this notebook to back up your Twitter info. 

## Setup
Assumptions: you have Python 3.9+ installed, you have Poetry installed to manage dependencies, and you have a Twitter developer account.

If you need help installing Python, follow the instructions here: https://www.python.org/downloads/

If you need help installing Poetry, follow the instructions here: https://python-poetry.org/docs/#installation

If you need to get a Twitter developer account, follow this guide here: https://developer.twitter.com/en/docs/basics/getting-started

### Install Dependencies
```bash
poetry install
```

### Activate Poetry Shell
```bash
poetry shell
```

### Start Jupyter
```bash
jupyter lab
```

### Set Environment Variables
```bash
export TWITTER_API_KEY=<YOUR TWITTER API KEY>
export TWITTER_API_SECRET=<YOUR TWITTER API SECRET>
export TWITTER_ACCESS_TOKEN=<YOUR TWITTER ACCESS TOKEN>
export TWITTER_ACCESS_SECRET=<YOUR TWITTER ACCESS SECRET>
export TWITTER_BEARER_TOKEN=<YOUR TWITTER BEARER TOKEN>
```

### Add your Twitter username to the notebook
Look for the cell with this code `TWITTER_USERNAME = "YOUR_TWITTER_USERNAME"`
and replace `YOUR_TWITTER_USERNAME` with your Twitter username.


### Run the notebook
Run the notebook and wait for it to finish. It will take a while to download all of your data. You'll have 2 CSV files 
after it runs, one with your followers, and one with your following.