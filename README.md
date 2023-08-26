# Solution for "GoDaddy - Microbusiness Density Forecasting" Competition

## Goal of the Competition

The goal of this competition is to predict monthly microbusiness density in a given area. You will develop an accurate model trained on U.S. county-level data.

Your work will help policymakers gain visibility into microbusinesses, a growing trend of very small entities. Additional information will enable new policies and programs to improve the success and impact of these smallest of businesses.

## Approach
Train 1 model for all areas and use it for recursive forecasting: predicting next day based on predictions of the previous days. During experiments Random Forest have shown the best results.
