![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Data Preparation 


## Introduction

In this lab you will work with the dataset that has some issues. Please do everything to be sure that it is ready for the further work.

## Getting Started

In this lab you will learn the data preparation techniques.
Here is the dataset: https://docs.google.com/spreadsheets/d/1CYSDJooG0_58AzbYNRwvtC3gXIUhZNg1/edit?usp=sharing&ouid=109198901319062172979&rtpof=true&sd=true

## Tasks
### Part 1: Upload the data
### Part 2: Analyze your data and create a plan for data preparation
### Part 3: Data cleansing  (missing values, outliers, duplicates, data consistently)
### Part 4: Encode categorical data
### Part 5: Upload the deliverables to GitHub


## Deliverables

- Code in Python
- Readme file with your plan, approaches and summary


After having an overview of the data, I drop the column Department because it's always the same
department. I transformed every number to an integer and all to lower case. I decide to replace 
missing values with the most frequent values because it's not gonna change a lot our data but we have
to take into account that we're gonna have two more clients which have Manager as a profession 
and two more clients with the oldest age. It depends on the case, but maybe it's better to remove
them, but we're on time to do it if we want to.
I used ordinal encoding for the column risk and labels for the column profession.

- Prepared dataset in csv format

## Submission

Upon completion, add your deliverables to git. Then commit git and push your branch to the remote.

## Resources

[Pandas - data preparation] https://towardsdatascience.com/essential-commands-for-data-preparation-with-pandas-ed01579cf214

[Pandas] https://realpython.com/python-data-cleaning-numpy-pandas/
