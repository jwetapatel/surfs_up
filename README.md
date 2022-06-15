
# surfs_up

# Purpose

The purpose of this project was to collect data for a potential investment in a surf shop in Oahu, Hawaii.

1. Explain the structures, interactions, and types of data of a provided dataset.
2. Differentiate between SQLite and PostgreSQL databases.
3. Use SQLAlchemy to connect to and query a SQLite database.
4. Use statistics like minimum, maximum, and average to analyze data.
5. Design a Flask application using data

# Overview 

The business concept is a combination surf and ice cream shop and the potenetial investor wanted to know weather and precipitation data throughout the year on the island. For the challenge, the data was parsed from a SQLite file and analyzed for the months of June and December.

# Results

Here are the basic statistics for the two months in comparison: June (F°) December (F°) in Hawaii

![june_temp](https://user-images.githubusercontent.com/96400887/173908185-c207d057-bb65-49af-81b7-1d7c8f66d5a7.png)  ![dec_tem](https://user-images.githubusercontent.com/96400887/173908332-4023c2c2-fae8-4e5b-a914-be1203ad9428.png)


- We get to this conclusion looking at either the averages or even the max temps above: Avgs: -June: 74.9° F -December: 71.0° F Max Temp: -June: 85.0° F -December: 83.0° F

- Also worth saying, the max temps aren't excessive either, otherwise the heat would be a problem if it were consistently in the 90-100° F range.

- Most different is our basic stats is the minimum temperature, where in June (winter) it is 64.0° F, almost 10°s more than the minimmum temp recorded in December at 56° F

# Summary

In order to provide a more end-user friendly statitsics analysis, I created histograms for both the June and Decmeber Results.

#### June Month Histograms

- June had 1700 counts of data with an average temperature of 75 degrees Farenheit.
- The minimum temperature was 65 degrees and the maximum was 85 degrees.


![june_temp_hist layout](https://user-images.githubusercontent.com/96400887/173909017-adbaea3b-3d5f-4932-adf5-e43411399e3e.png)


#### December Month Histograms

- December had just over 1500 counts of data with an average temperature of 71 degrees Farenheit.
- The minimum temperature was 56 dgrees and the maximum was 83 degrees.

![dec_temp_hist layout](https://user-images.githubusercontent.com/96400887/173909037-591b7dc7-32ab-412a-8c56-9ef289b1f70e.png)

- The results showed that weather in Oahu is fairly stable year round with temperatures ranging from roughly 56 to 85 degrees Farenheit from June to December.
- As per above data and analysis I would recommend opening the surf shop in Oahu as this seems like a great location with moderate temperatures great for surfing and ice cream.

