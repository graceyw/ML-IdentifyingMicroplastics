# Identifying Types of Plankton with Machine Learning

## What is this?
#### Determine application and data set
We developed a machine learning model that identifies the kind of plankton displayed in an image. To train our convolutional neural network, we used a dataset of over 200,000 images of 65 kinds of plankton, which we got from the Woods Hole Oceanographic Institute's Open Access Server. The dataset can be found [here](https://darchive.mblwhoilibrary.org/handle/1912/7341).

## Why does it matter?
About half of the world's oxygen is produced by plankton. Plankton is at the center of many climate change researchers' projects of how to reduce carbon in the earth's atmosphere. Understanding what kinds of plankton appear in different parts of the world at various times of the year could contribute to this important research.

## Important considerations
Every model has limitations. Here are a few important ones to acknowledge before we get into how it works:
- The images we used were all collected in the same location (by Martha's Vineyard, MA, USA)
- The data is organized by year and we only used one year (2014, the most recent)

## How does it work?

#### Preprocessing
First we spent some time exploring and preprocessing the dataset. We found that the data is organized by year and then by category within year. We chose to start with the most recent dataset, which was from 2014, and picked the 9 categories of plankton with the most images, to give our dataset the We then looked through and found the types of  downsampled the 

#### Convolutional Neural Network 

#### Analyzing Our Success

#### Visualizing an Activation Gradient

## Possible Next Steps
- Expanding to more categories of plankton (right now we're only working with 9, but there are over 50 types cataloged in the 2014 dataset alone). This would be more challenging because we chose to work with the plankton with the most images (at least 1000) but many categories of plankton had orders of magnitude less than that.
- Expanding to additional year's datasets (we worked with 2014 and expanded to 2013, but there there are datasets dating back to 2006)
- If there were timestamps on the data, it could be interesting to analyze how types of plankton vary seasonally
