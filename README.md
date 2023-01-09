#Flight delays and cancellation from 2004 to 2008
Flights details for american carriers over 5 years



## Dataset

The dataset regroups information about flights departure and arrivals for many american airlines. It is mainly useful to compare delays and cancellations and estimate the volume of flights for a certain period/season
the dataset is divided on csv files by year , free to download from : https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7

Due to the size of the dataset, three steps are needed to analyze the data:

1) Execute a cleaning loop over the csv files
2) store in a mySQL database
3) explore the data

## Summary of Findings

- There's more delay in arrivals than in departure. It is more probable to have a delay in arrival than to arrive on time and both delays kept increasing each year from 2004 to 2008
- the main delays are more or less one hour from the departure/ arrival time
- Summer and holiday seasons are the periods with the highest delays
- Security check has the shortest delays whereas late air craft and carrier cause the longest delays. let's see how frequent is each type of delay
- Long distance flights are more in time, but it can also be due to the fact that short distance flights are more frequent 
- day of the week doesn't affect delays
- only 7 days appears on the top 30 of the most crowded days and days with the highest delays. it appears that delays are not directly correlated to the number of fligts,it could be due to the lower number of stuff or more passengers in the planes
-  top 4 destinations with arrival delays are: MQT, DUT, SOP, ACK
- top 4 orgins with departure delays are: FMN, OGD, CKB, CYS
- Delays are more frequent for flights deparitng between 6pm and midnight , even though it has less flights than 6 am to 6pm  departure time

## Key Insights for Presentation

- over 5 years, 3 airports showed the highest count of cancellation : ORD, ATL , DFW
- In general delays kept increasing over the course of 5 years for both arrivals and departues
- Among the delays reason, nas and late air craft are the most common and those causin the longest delays
-Among the 30 top carrier-origin with the highest delays,  OO and OH are the two carriers with the highest number of delay.

