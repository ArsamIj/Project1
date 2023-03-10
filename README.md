## Consumer Trends in a Post Pandemic Society
# A study on health and hygiene trend in a post-pandemic market, with focus on PPE, its use, and its sentiments within Canada

The Covid pandemic has greatly impacted consumer behavior, with many people changing their purchasing habits and preferences. This study intends to examine the impact of the pandemic on consumer behavior in Canada, with a particular focus in personal hygiene products. The study will show what new health trends were created during the Covid Pandemic, and how they have fared a year after the lockdowns have ended.

An analysis is performed to understand consumer trends in a post-Covid world. The analysis focuses on health and hygiene, in particular regarding the use and sentiment over PPE. The Analysis covers (3) individual perspectives;
1.	Consumer Sentiment on PPE and Personal Hygiene based on online search trends
2.	Business Reactions to Adopting PPE as Part of the Mandatory Health Protocol
3.	Price Trends in online markets for specific PPE – Masks

The analysis is based on Canadian datasets recorded at multiple points over 2018 – 2023.

# Part #1 Sentiments

Using third party google APIs provided by APIFY, data is gathered based on search trends of individuals identifying their search history by PPE related items. The main (4) focus points are masks, hand sanitizers, latex gloves and hand soap.
The data is graphed over a period spanning 2018 onwards and the search terms are characterized as sentiments of people looking for PPE. The data identifies periods where the search terms are used to show peaks and dips in people’s interest towards PPE and evaluates how that trend has shifted pre-Covid to post-Covid.

We have a time series for each item's Google search trend from February 2018 to February 2023, separating the two product groups for a clearer picture. As you can see, public interest in the two groups of products increased dramatically as the covid pandemic spread and consumers sought to protect themselves. Surprisingly, we see that interest in hand sanitizers experienced the sharpest increase and decrease, and despite the fact that we've all seen the sanitising campaigns, and hand sanitizers are now available in most public spaces, google searches for this item quickly returned to pre-covid levels by the end of 2020.

Another noteworthy takeaway is the interest in face masks. The elevated volatility of searches in most of 2020 illustrates the controversy surrounding this item. When the first case of covid is identified in Canada on January 25, 2020, we can expect a surge in interest in these products. Following that, on March 11, 2020, the WHO declared covid to be a pandemic, causing a surge in interest in all of these items. These four pie charts were taken 12 months apart. As we can see, the proportional interest in PPE products only lasted during 2020, beginning with the first covid case in Canada, where we see interest shift towards PPEs after the first covid case, but interest quickly shifted back to pre-pandemic proportions by January 2021 and remained relatively constant thereafter.
Then we examined the average search levels between the dates of the four pie charts. As we can see, the average for all items increased by up to sixfold in 2020, and while interest faded in 2021, search levels remained elevated compared to pre-covid levels, implying that interest in these products is sticky and may influence consumers in this post-pandemic society for some time.


# Part #2 Businesses

Using Government of Canada Open Statistics Database, an analysis of Canadian businesses is provided to showcase how businesses reacted upon mandatory PPE adoption as healthy services direction. The data shows the number of businesses affected and future employment rates within Canada.
This part is to highlight the use of gathering CSV data from a reliable data source (canada.gov) and cleaning thousands of rows of data to show data significant to the report. By utilizing lessons learned in previous modules, data were extracted from the raw CSV file and displayed on a data frame cleanly. A simple pie plot chart was also created to sufficiently highlight the gathered data for ease of use.

# Part #3 Mask Prices

Using AMZ Scout retrieved price indexes ranging from 2021 to 2023 for Bestsellers-Top 10 Face Masks, a bar graph is generated to highlight the disparity between the top performing brands in Face Masks on Amazon, the largest online retailer.
The brands are then individualized and are represented by line graphs outlining their price changes over the given timeline. Their maximum price variance and percent change is provided on the saved graph figures.

The data shows a high percentage of brands that started in 2021 saw a very long period of price fluctuation (fluctuations provide on associated figures (Part_3_Mark_Prices/figures)). The fluctuations slowed down and allowed the prices to be normalized only after start to mid 2022. This stability is an indication that generalrepsonse to PPE is become casual as the public is becoming numb to covid protocols post mandatory PPE wearing rule lifts. However a larger size of data and a lookahead of the next few years is require dto conclude that. 

# Conclusion

•	The general public is still very reactive to PPE protocols whether its to show compliance or defiance, and we will continue to see this as the world face changes

•	Although demand has tapered off for the business sector significantly, the pandemic may have created a new trend as businesses are now opting to promote a voluntary PPE policy in the workplace. Whether this becomes a permanent practice is yet to be determined

•	PPE price fluctuation has decreased within the top brands, however current price points for PPE brands that emerged over COVID have changed drastically, and we can see that from the percent change shown

