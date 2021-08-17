# Starbucks Capstone Challenge

This challenge is the final capstone project for the Udacity Data Science Nanodegree Program. 

The Structure of the project is the following:

- [Starbucks Capstone Challenge](#starbucks-capstone-challenge)
  - [1. Introduction](#1-introduction)
    - [1.1 Overview](#11-overview)
    - [1.2 The Data](#12-the-data)
    - [1.3 Problem Statement](#13-problem-statement)
    - [1.4 Requeriments & Files Information](#14-requeriments--files-information)
  - [2. Pre-processing](#2-pre-processing)
  - [3. Data Exploration and Visualizations](#3-data-exploration-and-visualizations)
  - [4. Modeling](#4-modeling)
  - [5. Conclusions](#5-conclusions)

## 1. Introduction

### 1.1 Overview

The aim of this project is to conduct a complete data science pipeline from real raw data provided by Starbucks. 

You can follow all the code in the included Python Notebook or in this [Medium article](https://www.medium.com).

### 1.2 The Data

The provided data consits of three different json files with the following information:

**portfolio.json**: Information about the different offers sent to clients.
- id (string) - offer id
- offer_type (string) - type of offer ie BOGO, discount, informational
- difficulty (int) - minimum required spend to complete an offer
- reward (int) - reward given for completing an offer
- duration (int) - time for offer to be open, in days
- channels (list of strings)

**profile.json**: Information about the different clients.
- age (int) - age of the customer
- became_member_on (int) - date when customer created an app account
- gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
- id (str) - customer id
- income (float) - customer's income

**transcript.json**: Interactions of clients with Starbucks.
- event (str) - record description (ie transaction, offer received, offer viewed, etc.)
- person (str) - customer id
- time (int) - time in hours since start of test. The data begins at time t=0
- value - (dict of strings) - either an offer id or transaction amount depending on the record

### 1.3 Problem Statement 

The objective is to analyze the different offers and try to explain how effective they are for increasing the number/amount of transactions with Starbucks. 
Finally, we will try to predict for a specific user and offer if the transactions will increase or be completed.

### 1.4 Requeriments & Files Information

**Requeriments:**

- Python
- Numpy
- Pandas
- Matplotlib
- Sklearn

**Files:**

- Notebook.ypnb: Python Notebook with all the code
- Visualizations: Folder with all presented images

## 2. Pre-processing

Before we begin to extract conclusions, we have to rearrange the data so we can know if a client has actually seen the offer within the offer duration period to know if
the offer could have any impact in the client behaviour.

In this section also basic cleaning activities were performed.

## 3. Data Exploration and Visualizations


## 4. Modeling



## 5. Conclusions


