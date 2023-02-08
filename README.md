# CapstoneProject
Udacity's Nanodegree capstone project

## Table of Contents

1. Introduction
2. File Descriptions
3. Installation
4. Instructions
5. Further resources
6. Acknowledgements
    
## Introduction
This Project is part of Udacitys Data Scientist Nanodegree. It countains contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. The data represent user interaction with offers send over the app. 

The aim of the project is to find a model that predicts if a user completes an offer. 

## File description

The dataset contains three files in the data subfolder: profile.json, portfolio.json and  transcript.json with the following columns:

### portfolio.json

- id (string) - offer id
- offer_type (string) - type of offer ie BOGO, discount, informational
- difficulty (int) - minimum required spend to complete an offer
- reward (int) - reward given for completing an offer
- duration (int) - time for offer to be open, in days
- channels (list of strings)

### profile.json

- age (int) - age of the customer
- became_member_on (int) - date when customer created an app account
- gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
- id (str) - customer id
- income (float) - customer's income

### transcript.json

- event (str) - record description (ie transaction, offer received, offer viewed, etc.)
- person (str) - customer id
- time (int) - time in hours since start of test. The data begins at time t=0
- value - (dict of strings) - either an offer id or transaction amount depending on the record

## Installation 

The code is written in Python 3

The code was written on Python 3.8.

The code can be found in this Github Repo https://github.com/anni-kaffeekanni/CapstoneProject

## Instructions

Runn the jupyter notebook to perform the necessary data preparation steps and train the model.

## Further resources

A Blogpost to this project is available on Medium https://medium.com/@ak_gossmann/analyzing-starbucks-rewards-mobile-online-app-user-interactions-edb1517211a7

## Acknolegements

Acknowlegements to Udacity for providing the project support. 
