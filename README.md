# (Dataset Exploration)
## by (Olamidayo Mimiola)


## Dataset
The dataset provides information regarding the returns and attributes of different 
stores types owned by an individual. There are 4990 entries of 10 stores with the different items 
stocked in them. The dataset and feature documentation can be found [here] (https://zindi.africa/competitions/dsn-pre-bootcamp-hackathon-the-excellent-store-challenge/data)

## Summary of Findings

In my exploration, I found that the range of values in the Item_store_return is large,
so I used a log transform to view the data. I noticed majority of the  return price 
falling below N10,000 and few above N10,000. Then a peak in frequency is seen at 
around N8,000. I also found that there was a relationship between the Item price and their returns.
The higher the price, the higher their returns. I saw that the four store types were mostly
stocked with Snack Foods, Fruits and Vegetables.

I saw that Small and Medium sized stores were not stocked with items with prices less than N220. 
Most of the high priced items are in the small sized store. But on studying the Medium sized store,
many items are within the price 250 and 500 and their returns are high compared to the other store sizes.
Interestingly, The High store sizes were stocked with items with the least price. 
No wonder the returns were not high.

Interestingly, I expected that the visibility of the item would also mean higher returns 
but the opposite is the case as the less visible items had higher returns than the more visible ones


## Key Insights for Presentation

For my presentation, I focus on just the relationship between the Item Price and the Returns.
I start by introducing the Return variable, followed by the distribution of the Item Price
and then showing the relationship between them using a scatterplot. 
I also included the distribution of the Item prices among the store sizes, giving an 
understanding why a store size has more returns than the rest