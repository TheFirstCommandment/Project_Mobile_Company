# Project_Mobile_Company

Project description
.
(to the content). Clients are offered two tariff plans: Smart and Ultra. In order to adjust the advertising budget, the commercial department wants to understand which plan brings in more money. You will do a preliminary analysis of the tariffs on a small sample of customers. You have the data of 500 "Megaline" (name of the company) users at your disposal: who they are, where they come from, what tariff they use, how many calls and messages each sent in 2018. You need to analyze customer behavior and draw a conclusion - which tariff is better.

*Description of tariffs:*

Tariff Smart:

Monthly fee: 550 rubles.
Included 500 minutes of talk time, 50 messages and 15 GB of Internet traffic
Fee for services above the tariff package: One minute of talk time: 3 rubles
Message: 3 rubles
1 Mb of Internet traffic: 200 rubles
Tariff Ultra:

Monthly fee: 1950 rubles
3000 minutes of talk time, 1000 messages and 30 GB of Internet traffic are included
Cost of services over the tariff package: 1 minute of talk time: 1 ruble
message: 1 ruble
1 GB of Internet traffic: 150 rubles
Please note: "Megaline" always rounds up the values of minutes and megabytes. If the user only spoke for 1 second, a whole minute is counted in the tariff.

Data description (to content)

Table users (information about users):

user_id - unique identifier of the user
first_name - user's name
last_name - user's last name
age - user's age (years)
reg_date - tariff activation date (day, month, year)
churn_date - date when user discontinued the tariff (if value is missing, then tariff was active at the moment of data uploading)
city - user's city of residence
tariff - name of tariff plan
Table calls (information about calls):

id - unique number of call
call_date - date of the call
duration - duration of the call in minutes
user_id - identifier of the user who made the call.
Table messages (information about messages):

id - message number
message_date - message date
user_id - identifier of the user who sent the message
Table internet (information about internet sessions):

id - unique session number
mb_used - amount of the Internet traffic spent during the session (in megabytes)
session_date - date of the Internet session
user_id - user ID
Tariffs table (information about tariffs):

tariff_name - tariff name
rub_monthly_fee - monthly subscription fee in rubles
minutes_included - number of minutes of conversation per month, included in the subscription fee
messages_included - number of messages per month included in the monthly subscription fee
mb_per_month_included - amount of the Internet traffic included in the subscription fee (in megabytes)
rub_per_minute - the cost of a minute of conversation over the tariff package (for example, if the tariff has 100 minutes
of conversation per month, then 101 minutes will be charged)
rub_per_message - cost of sending a message over the tariff package
rub_per_gb - the cost of one additional gigabyte of Internet traffic above the tariff package (1 gigabyte = 1024 megabytes)
