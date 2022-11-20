# Amazon_Vine_Analysis

## Overviw of the analysis:

The purpose of this project was to analyze Amazon reviews to identify if there is any bias between the reviews writen from members of Amazon Vine program or non members. Vine memebers are to publish reviews of some products which sell in amazon and this companys pay a fee to amazon. To determin if any biases exist between members and non members, I was asked to choose and extract a dataset  to analyse the results. I chose the Electronics category for this analysis and will identify the percentage of 5 star ratings to total ratings in order to identiy if any bias exists. 

## Results

This dataset contained over 3 million reviews but we are mainly interested in helpfull reviews. Because of this I filtered the dataset by 
- Count total of votes is equal or greater than 20. 
- Percent of helpful botes to taotal votes is equal or grater than 50%. 

Whit this filters I was able to reduce the amount of reviews from 3 million to around 50k. 

<img width="1079" alt="Screen Shot 2022-11-20 at 14 16 09" src="https://user-images.githubusercontent.com/108498940/202924061-cde525ec-36fd-4b45-8644-c0733364e051.png">


### How many Vine reviews and non-Vine reviews were there?

Only 2.1% of the reviews where Vine members, the other 97.9% where non members

<img width="1069" alt="Screen Shot 2022-11-20 at 14 17 42" src="https://user-images.githubusercontent.com/108498940/202924124-d8a9d5ee-8f53-4b18-896c-b55bd9321d11.png">

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

Members made a total of 454 five star rating reviews from the total of 1,080 reviews that they made. Non members made 23,034 five star reviews out of 49,659 total reviews. 

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

42% of the total member reviews where five star and 46.4 of the total non members reviews where five stars. 

## Summary 

The results show that there is no bias between paied ratings and non paid ratings. Numbers from vine members and non members where very similar with Vine memebers having a smaller number of five star ratings. We could probably assume that Vine members are a little more critical and analytic when making their review which might make them more helpful for the consumers. To prove this hypothesis I included all of the data rather than filtering it to have more data that supports this hypothesis. 
