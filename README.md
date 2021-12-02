

## Installation
To get this running you will need Python and Pip installed already. Once that is done you will have to install pipenv which you do by opening up your terminal and entering the command
`pip install --user pipenv`

You will now need to download and unzip the code. You do that by clicking the green *Code* button in the upper right corner of the Github page and selecting *Download ZIP*. Once downloaded you unzip to a folder of your choice.

Now you need to go the folder you unzipped the code in using your terminal—if your terminal is open in a different directory at the moment you can use the `cd` command to navigate there.

When you're in the directory you can install the dependencies of the code by running `pipenv install` and finally start up the notebook by running `pipenv run jupyter-lab`. The notebook should now open up in a browser window.

## Usage

To use the notebook you will need to do three  things
1. Create a CSV file with tweets where the header for the tweet column is `text` and place that csv file in the `data` folder
3. Add your API token to where it says `api_token = ""`. If you do not have one there are instruction at hf.co/settings/token
2. Add the name of your csv file to where it says `csv_file = 'sample.csv'`
Once you're done with this setup you can run all the cells in order and you should end up with a file called `out/tweets_with_sentiment.csv`
## CSV formatting
