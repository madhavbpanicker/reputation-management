# reputation-management

This project is about running a dashboard for viewing and managing brand and product reputation.

## Algorithm For Reputation Impact Score Settling:

The different factors to take into consideration are:
- Sentiment score via. using polarity, intensity, emotion analysis and relevance.
- Competitor Mentions: polarity and intensity
- Volume and Reach via. Domain Authority, number of mentions (obtained from API)
- User and content attributes: Popularity of the User/Anonimity and hence, reliability of the opinions
- Depth of Feedback: Analyze detailed reviews versus brief mentions or comments.
- Topic Focus: Identify specific themes (e.g., product quality, customer service, marketing campaigns) discussed in relation to the brand

[Documentation for ScraperAPI and Google Search JSON API use](Documentation/GSR-ScraperAPI-Usage.md)
The steps of Google Searching and web scraping, as well as web data filtering is automated, now. The program runs across 10 different car brands and gets through roughly 600 results in 6 hours, to prevent reaching a paywall with ScraperAPI.
