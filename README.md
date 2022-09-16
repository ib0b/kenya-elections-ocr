
# Kenya Elections OCR
This repo contains Form34A tallies from the Kenya August 2022 eleciton. This data has been collected via crowdsourcing and is not the official results. For official results please see the [Independent Electoral and Boundaries Commission website](https://www.iebc.or.ke/)

This data is provided for education purposes only.

## Introduction
In August 2022, elections were held in Kenya to decide the next leaders, the main one being the presidential elections.

The way elections work is, that there are **46,229 polling centers** where elections take place. After the voting period ends (typically around 5pm on election day) the polling station officials commence counting of votes.

They then record the tally manually on a physical form. This form is referred to as Form 34A.
See blog [post here](https://bob.africa/using-ai-to-verify-kenya-election-results/).

## Task
Train an OCR model that correctly identifies the hand written digits. Use the data in this repo ~ ***forms-export.csv***
A sample pipeline looks like this.

**Download Images -> Crop Images -> Train an OCR model -> Analyse Accuracy -> Submit results here**

Get the images from the IEBC website [here](https://forms.iebc.or.ke/#/downloads?contest=34)

When cropping images, you may have to crop individual numbers as most OCR models using deep learning can only read one line at a time.

## Submit
To submit feel free to create an issue, and share you results and methodology. 
Please note that the data is truncated and only **30,000** out of the **46,000** forms are provided. This is to enusre no cheating, once submitted you can share you model weights, also a jupyter or colab notebook if possible and I will run on a test the remaining data.

## Prizes
In this economy, we do it the for the glory.

<img width="300" alt="bud" src="https://user-images.githubusercontent.com/18010106/190708607-a633ad4e-0962-4a1e-b58d-9e8029471ee6.png">
