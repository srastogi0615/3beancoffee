**1)**

**Column meanings** 
&nbsp;&nbsp *order_id* - Signifies a unique order i.e. there may be multiple items purchased within the same order
&nbsp;&nbsp *quantity* - The number of items purchased in that order
&nbsp;&nbsp *item_name* - The base name of the item order does not include varieties
&nbsp;&nbsp *choice_description* - The type or variety of the item ordered e.g. burrito can be made with different ingredients
&nbsp;&nbsp *item_price* - The total cost of the item(s) ordered

**Row Meaning**
&nbsp;&nbsp Each row signifies the number and cost of the total unique item(s) in an order

**Code:**
&nbsp;nbsp Sumit Rastogi@LAPTOP-ARARHRFE MINGW64 ~/Documents/Data Science/DS-SEA-07/data (master) $ head chipotle.tsv
&nbsp;nbsp Sumit Rastogi@LAPTOP-ARARHRFE MINGW64 ~/Documents/Data Science/DS-SEA-07/data (master) $ tail chipotle.tsv

**2)** 1834, $ tail chipotle.tsv

**3)** 4623, $ wc chipotle.tsv

**4)** Chicken Burrito which has 553 vs. Steak Burrito which has 368. $ grep -c 'Steak Burrito' chipotle.tsv , $ grep -c 'Chicken Burrito' chipotle.tsv

**5)** Black beans are more popular they are in 282 orders versus Pinto beans which are in 105 orders. $ grep 'Chicken Burrito' chipotle.tsv | grep -c 'Black Beans'; $ grep 'Chicken Burrito' chipotle.tsv | grep -c 'Pinto Beans'

**6)**

1. ./data/airlines.csv
1. ./data/Airline_on_time_west_coast.csv
1. ./data/bank-additional.csv
1. ./data/bikeshare.csv
1. ./data/chipotle.tsv
1. ./data/citibike_feb2014.csv
1. ./data/drinks.csv
1. ./data/drones.csv
1. ./data/hitters.csv
1. ./data/icecream.csv
1. ./data/imdb_1000.csv
1. ./data/mtcars.csv
1. ./data/NBA_players_2015.csv
1. ./data/ozone.csv
1. ./data/pronto_cycle_share/2015_station_data.csv
1. ./data/pronto_cycle_share/2015_trip_data.csv
1. ./data/pronto_cycle_share/2015_weather_data.csv
1. ./data/rossmann.csv
1. ./data/rt_critics.csv
1. ./data/sms.tsv
1. ./data/stores.csv
1. ./data/syria.csv
1. ./data/time_series_train.csv
1. ./data/titanic.csv
1. ./data/ufo.csv
1. ./data/vehicles_test.csv
1. ./data/vehicles_train.csv
1. ./data/yelp.csv

1. Code: $ find . -name *.csv o- -name *.tsv

**7)** 55, $ grep -r -i "dictionary" . | grep -c -i "dictionary"
