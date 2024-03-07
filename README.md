# Knowledge Based Recommendation  
  
**Introduction**  
  
This project focuses on building a knowledge-based recommendation system for skincare products based on user preferences. The motivation of this project is to make consumer shopping experience quick and easy by successfully recommending top products from the wide variety of products available in the market. Consumers of skincare products are often faced with huge challenge of choosing from variety of options. In this project I attempted to develop a system that uses predictive analytics to recommend products to users by matching them to highly rated products and similar users. The recommendation system is an interactive tool, that will be asking user to give their preferences and it will recommend products by finding products that are highly satisfying to customers as well as how closely user matches to the customers who had similar issues or problems.  
  
**Data Sources**  

Data was scraped from [Sokoglam.com](www.sokoglam.com)  
   
**Methods**  
  
The methods applied for this was cosine similarity and sentiment analysis. It attempts to match user based on user preference to the top-rated products (based on sentiment analysis) and then uses similarity score to match with the reviews. The weighted score of both methods is then use to recommend top products.
