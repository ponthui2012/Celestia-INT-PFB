# Create a UI for Submitting PayForBlob Transactions	

## Description

Create a UI for allowing users to submit PayForBlob Transactions. You can check out the Node tutorial here. It shows you how you can call the API in order to submit a PFB transaction, and how to retrieve the data by block height and namespace.

## Directions

> Submission is limited to only 1, do not submit more than one.
> Create a UI for submitting a PFB transaction.
> Ensure it is open source and share the Github repository as well.

## Step by step install App Python

1) Install the required dependencies:
```
pip install -r requirements.txt
```
2) Specify in the ```config.py```

> DEFAULT_NODE_URL = 'http://127.0.0.1:26659'
> DEFAULT_GAS_LIMIT = 80000
> DEFAULT_FEE = 2000

3) Run script:
```
python app.py
```

if you using python3
```
python3 app.py
```
4) Go to http://your.id.address/ and create PayForBlob transaction.

Official live UI website: http://46.38.236.126/