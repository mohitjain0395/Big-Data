# Big-Data

Objective
By using the provided HDP tools and techniques, the students will process the data to create
their own analytics reports and create a visual presentation that will benefit decision-makers.
This virtual lab-based course will use truck fleet data to refine and analyse trucking movement
in order to meet the organizational goal of better understanding risk. The use case involves
geographic data, vehicles, average mileage, gas consumption, events, risk factors, and other
supporting information.
Each truck has been equipped to with devices to log location and event data. These events
are streamed back to a datacentre where students will process the data and revise truck
movements to increase safety.


Business Objective
Accidents caused by large trucks remain one of the leading causes of injuries and deaths in
the United States. The objective is identifying dangerous commercial truck drivers
nationwide
Upon completing this lab, the student will be able to answer common business questions
related to the trucking business, such as:
Which truck has the highest risk factor based on geographic location and time?

Steps taken-
1- First made all the tables in Impala in HDFS using VMware and loading all the tables (collected from different sources).
2- Solved the wrong data (total miles) present in risk factor table using Pig Script
3- Connected tableau with Impala and joined geolocation, risk factor and trucks table and rectified the risk factor column by calculating it 
using the formula 'events/totmiles*1000000' and visualized the risky truck drivers based on different paramenters
4- Performed logistic regression to validate risk factors
