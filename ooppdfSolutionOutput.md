

# TASK 1: Compute candlestick data
To complete this task, you need to be able to compute candlestick data from the
temperature data for a particular location in Europe between 1980-2019. Here is an
example of the fields needed for candlestick data:
Date        Open High Low Close
1980-01-01 -1.249 20 -3 -1.200
1981-01-01 -1.200 25 -2 -1.300
1982-01-01 -1.300 27 -1 -1.400
1983-01-01 -1.400 28 -1 -1.350
1984-01-01 -1.350 24 0 -1.450
Please note the dataset contains temperature data collected at an hourly rate for each
European country (columns with two-character prefixes, i.e., GB, FR, ES, etc.). However,
the example table above might be the candlestick data for the ‘yearly temperature of GB’.
To compute those fields:
• Open: the average mean temperature per time frame (i.e., year) in the previous time
frame.
• Close: the average mean temperature per unit in this time frame (same as Open, but
for the current time frame).
• High: highest temperature value seen this time frame.
• Low: lowest temperature value seen this time frame.
You should implement the candlestick data computation using a function which returns the
following data type:
std::vector<Candlestick>
Note that it returns a vector of Candlestick objects. You will need to define your own
Candlestick class that is suitable for representing candlestick data. 
.
![WhatsApp Image 2024-07-06 at 16 09 50](https://github.com/user-attachments/assets/d4e66e05-bbda-41b0-acd1-0d6ec1ad15af)


![WhatsApp Image 2024-07-06 at 15 57 34](https://github.com/user-attachments/assets/8816c2c9-8c1e-4681-94c5-24a36facf2d5)






https://github.com/user-attachments/assets/fb4e2620-52bb-46c6-be49-d17502456eee

