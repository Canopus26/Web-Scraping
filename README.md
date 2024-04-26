# Web-Scraping

Working with Web Scrapers / Langchain agents to fetch data from different sources for a particular company.
I have used Reliance Industries Ltd. (RIL) to find the latest news for RIL in the last 24 hours. This includes any posts on twitter, any news website, or any mention of RIL on any public internet. The data has been structured as follows:
1.	The final output is list of dictionaries.
2.	Each dictionary item includes the following keys:
a.	source: the source url where the data was scraped.
b.	text: the scraped text.
