# An analysis of Covid-19 on how it affected the public in China

Covid 19 is a worldwide pandemic starting from January 2019. 
We are investigating the following four dimensions of people’s
perceptions surrounding the COVID-19 outbreak in China:
- Groups of people who are concerned (who care)
- Reasons of concerns (why people care)
- Discussion topics about COVID-19 (what are people talking about)
- Discussion topics with a timeline (when people are concerned)

## Dataset
The data are from China's most popular social media, Sina Weibo

"Hot Searches" is a function provided by Sina Weibo, which will be updated every minute and display the most trending topics that have the top discussion volume. As the "Hot Searches" ranking is calculated and released officially by Sina Weibo, the dataset is much more persuasive and can provide more insights due to the heat volume of data. With the help of a third party website which records down all the Sina Weibo’s "Hot Searches" every minute, we are able to crawl the past "Hot Searches" data from this website.

The data of "Hot Searches" scraped from the platform consist of content of top searches, start and end time when certain search topics are in the ranking list, and heat volume. Each month has around 2,800 - 3,000 rows of hot search data without duplication. Hence, about 8,700 rows of hot searches data are scraped for January, February and March.

Among the hot searches, we selected some significant incidents with high discussion volume for economic, political and social aspects for different points in time. After that, we scraped the comments from the incident posts with at least 8,000 comments. We selected 2 incident posts per aspect per month and scraped around 600 - 800 comments per post. In total, we had 18 posts to scrape and received about 15,000 rows of comment data.
