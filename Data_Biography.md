# Data Biography

### Declaration of Authorship

I, Rongrong Xue, confirm that the work presented in this assessment is my own. Where information has been derived from other sources, I confirm that this has been indicated in the work.

Rongrong Xue

Date of signature: 26/11/2021
Assessment due date: 26/11/2021
Student Number: 20049716

_Please write your answer immediately below the level-3 headers and delete the guidance prior to submission._

---

### 1. Who collected the data?

#### 25 words; 2 points; Consider the source of the data and its relation to the underlying data generating process.

The data was gathered from Inside Airbnb[1], a website started by an activist named Murray Cox. He scrapes data from Airbnb's website and provides it to the public.

### 2. Why did they collect it?
 
Since Murray argues that Airbnb is only a verbal support of the ideals of family sharing and is threatening local housing, it is also exacerbating gentrification. In addition, some Airbnb listings are illegal and do not comply with local laws [1]. In order to quantify Airbnb's impact of short-term rentals on local housing, he collected and provided data.

### 3. How was it collected?

According to Inside Airbnb, Murray mostly used Python to write code to grab Airbnb's online open data [1]. This data is based on publicly available information gathered from the Airbnb website and represents a snapshot of the list available at a specific time because all the data is continuously updated. It includes all the available public information as well as URL links to the place. Data is collected, cleaned up, analysed, summarised, and provided via open source software [1].

### 4. What useful information does it contain?

By analysing neighbourhood information, we are able to compare the location and distribution patterns of different types of houses with hotel areas. Through the information of hosts, we can figure out how many hosts own more than one listing and whether it is the house they live in. The host’s registered date and the date the house was first reviewed can be used to identify the experienced host and the new host and may explore some features and differences between them. From the review data, we can know the total number of reviews and the average number of reviews. In addition, whether their houses can be booked instantly, which might be an indicator of Airbnb's commercialisation [2].

### 5. To what extent is the data 'complete'?

First of all, this website was established by an individual and has not been verified by any authoritative organization. Although his information is from the official Airbnb website [1], it does not guarantee that there is no wrong input information.

Secondly, the list on the official website is constantly changing [3]. Depending on the time difference and the collection period, it may have some impact on the overall analysis. Hosts may not update the calendar information in time [3], which will also have a certain impact. The unavailable dates displayed on the calendar also have different internal reasons. They may have been locked in by the hosts, or they may have been booked [3]. Therefore, we can't intuitively see how many days the house can be booked for in the whole year.

As for the location of the Airbnb listing, in the description of the Airbnb official website [4], the exact location is only provided to the guests who have confirmed the reservation. Thus, the location information is not completely accurate.

Moreover, hosts may divide their same property into different types of rooms and hang all of them on the website at the same time. This can cause confusion about whether the host has one listing or multiple listings and reduce the accuracy of Airbnb listings.

Finally, we cannot directly deduce Airbnb's actual occupancy status. Although it can be inferred from the number of reviews, there are too many uncertain factors.


### 6. What kinds of analysis would this support?

First, spatial analysis can be used to analyse the distribution of Airbnb listings, but the distance and threshold definition should be discussed to reduce the impact of inaccurate location. Then, compare it with the distribution of hotels in London.

Next, to verify whether about 80% of Airbnb hosts rent out the houses they live in, as claimed by Airbnb [5], we could analyse the owner information and the frequency distribution of the listings owned by each host.

Regarding the number of days the Airbnb room was occupied in a whole year, we can use data such as the number of available days in a year, the occupancy rate, and the average number of days of stay to deduce how many temporary accommodations exceed 90 nights per year, which violates the new law, the Deregulation Act 2015 [3].

In order to confirm whether Airbnb has affected the operations of local residents’ houses and hotels or provided an economic boost, we need to estimate the occupancy rate and profitability of Airbnb listings. Subsequently, we examine the income distribution gap between multi-listing owner hosts and one-listing hosts, as well as entire, private, and shared room rentals. Finally, we can compare the annual income and expenditure of short-term rentals on Airbnb with general long-term rentals in the neighbourhood.


### 7. Which of the uses presented in Q.6 are _ethical_?

Inside Airbnb is an individual and no-profit project. It provides and aggregates open information about Airbnb listings for everyone. To some extent, it challenges the unequal distribution of power. Fighting against a powerful group like Airbnb embodied the principles of data feminism: examine power and challenge power [6] in the field of data science.

However, because of the collection and delivery methods, what we get is a snapshot of continuously changing data. So when we analyse and visualise the data, we must declare that the data shows the last updated information for Airbnb listings in London from around 24th to 28th in  August, 2020, as this is a one-sided analysis of a specific time period. If we need to conduct a more complete study, we may need to request a full year of data to have a more comprehensive view of the situation.

At the same time, we need to explain some sensitive and subtle data and consider the range of controllable errors, such as the data for location and reviews, because we are not only looking at the data itself but also its context, which makes the data meaningful. Not just in the data collection or analysis stage, context also plays an important role in the communication of results.

For the research on hosts' Airbnb income, although the information is obtained from Airbnb's official public data, privacy and consent issues arise when people provide information publicly but do not agree to participate in research projects. Especially on the projection map on Inside Airbnb, we can see the estimated income of each listing, which should be private information. 

Assuming that you rent a room, you will know the exact address, and you are very likely to meet the host in person. If you get to know his or her Airbnb income through Inside Airbnb, the landlord has no privacy at all. If someone maliciously utilises it, serious consequences can be caused. As discussed by Kate Crawford and Megan Finn in "The Limits of Crisis Data" [7], what power do people have to shape how their data will be collected and used? The intention of Inside Airbnb is to benefit the city and its residents, but how can it guarantee that the benefits outweigh the risks and the legality of processing?


## Bibliography
[1]"Inside Airbnb. Adding data to the debate.", Inside Airbnb, 2021. [Online]. Available: http://insideairbnb.com/behind.html. [Accessed: 26- Nov- 2021].

[2]"Inside Airbnb Data Dictionary", Google Docs, 2021. [Online]. Available: https://docs.google.com/spreadsheets/d/1iWCNJcSutYqpULSQHlNyGInUvHg2BoUGoNRIGa6Szc4/edit. [Accessed: 26- Nov- 2021].

[3]"Inside Airbnb. Adding data to the debate.", Inside Airbnb, 2021. [Online]. Available: http://insideairbnb.com/about.html. [Accessed: 26- Nov- 2021].

[4]Airbnb, 2021. [Online]. Available: https://www.airbnb.co.uk/help/article/2141/customise-your-map-location. [Accessed: 26- Nov- 2021].

[5]"Airbnb Economic Impact", The Airbnb Blog - Belong Anywhere, 2021. [Online]. Available: https://blog.atairbnb.com/economic-impact-airbnb/#london-edinburgh. [Accessed: 26- Nov- 2021].

[6]C. D'Ignazio and L. Klein, "1. The Power Chapter", Data Feminism, 2021. [Online]. Available: https://data-feminism.mitpress.mit.edu/pub/vi8obxh7/release/4?readingCollection=0cd867ef. [Accessed: 26- Nov- 2021].

[7]K. Crawford and M. Finn, "The limits of crisis data: analytical and ethical challenges of using social and mobile data to understand disasters", GeoJournal, vol. 80, no. 4, pp. 491-502, 2014. Available: 10.1007/s10708-014-9597-z [Accessed 26 November 2021].


## Appendix 

