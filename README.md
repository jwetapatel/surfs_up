
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

We received W. Avy's data on Hawaii weather collections as a sqllite file, which can be found in this repository. We were able to quickly and succinctly compare values for June and December, meaning we could do this for other months using different queires and mayde for other locations if W. Avy has other datasets for the other islands he's thinking about of if we could find one ourselves.

Here are the basic statistics for the two months in comparison: June (F°) December (F°) in Hawaii

![june_temp](https://user-images.githubusercontent.com/96400887/173908185-c207d057-bb65-49af-81b7-1d7c8f66d5a7.png)  ![dec_tem](https://user-images.githubusercontent.com/96400887/173908332-4023c2c2-fae8-4e5b-a914-be1203ad9428.png)









- We get to this conclusion looking at either the averages or even the max temps above: Avgs: -June: 74.9° F -December: 71.0° F Max Temp: -June: 85.0° F -December: 83.0° F

- Also worth saying, the max temps aren't excessive either, otherwise the heat would be a problem if it were consistently in the 90-100° F range.

- Most different is our basic stats is the minimum temperature, where in June (winter) it is 64.0° F, almost 10°s more than the minimmum temp recorded in December at 56° F
