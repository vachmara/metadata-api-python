## Python Metadata API for OpenSea Creatures

### About

Forked from [ProjectOpenSea Api](https://github.com/ProjectOpenSea/metadata-api-python). 

This is a very simple sample Python Flask app for serving the ERC721 metadata for the [OpenSea creatures ERC721 contracts](https://github.com/ProjectOpenSea/opensea-creatures/), as specified in the [OpenSea developer docs](https://docs.opensea.io/docs/2-adding-metadata).

## Requirements

### Python 3
You'll need a machine with Python 3 installed.

### ~~Google Cloud Storage~~
~~You'll need a Google Cloud Storage account with a project, bucket, and credentials.~~

### IPFS storage
_Next implementation_

## Setup


Create a virtualenv with Python3 and run `pip install -r requirements.txt`. 

## Running

Run the API with `python app.py` and hit http://localhost:5000/api/creature/1
