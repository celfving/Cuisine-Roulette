# Cuisine Roulette

## Set Up

### Repo 

When prompted by the GitHub online interface, add a "README.md" file and a Python-flavored ".gitignore" file during the repo creation process. Additionally, choose a software license, and include a corresponding file called "LICENSE" or "LICENSE.md" in the root directory of your repo. 

### Yelp Fusion API

Use the following link to set up your app and obtain your personalized API key: 
https://www.yelp.com/developers/documentation/v3/authentication

### .Env

In your text editor, create a .env file containing the following information: 
```sh
USER_NAME=""
API_KEY=""
```
Specify a username of your choice, for example "John".
Paste your personalized API key in the API_KEY field in between the quotes.

### Requirements.txt

In your text editor, create a requirements.txt file containing the following information: 
```sh
python-dotenv
requests
```

### Anaconda Environment

In your command line, use the following code to activate your Anaconda environment: 
```sh
conda create -n Cuisine-env python=3.8 
conda activate Cuisine-env
```

Once you've created your Anaconda envrionment, use the following code to install the necessary packages: 
```sh
pip install -r requirements.txt
pip install pytz
pip install requests
```

To run your code, use the following:
```sh
python Cuisine-Roulette.py
```