# **Sephora Products Reviews**
## **Data**
The dataset was collected via Python scraper in March 2023 and contains:
- Information about all beauty products (over 8,000) from the Sephora online store, including product and brand names, prices, ingredients, ratings, and all features.
- User reviews (about 1 million on over 2,000 products) of all products from the Skincare category, including user appearances, and review ratings by other users
## **ML Techniques used**
- TFidf to identify common themes in reviews 
- Market Basket analysis to find products that can be bundled together
- Products clustering to identify groupings
- Reviews clustering to understand how ratings, price, and sentiment affect reviews' groupings
- Sentiment analysis to identify customer pain points and strengths to leverage

## **Results Summary**
- Strong associations include Products and their mini sizes and Products within the same category suggesting these should be placed next to each other in stores
- Common themes found with TFIDF suggest that skincare products are highly discussed and special attention should be given to that category.
- Sentiment Analysis results revealed that Skincare products provoke very diverging customer opinions meaning that Sephora should further explore how to serve the needs of customers with different skin tones and skin types.
- Feedback count variables influence reviews' clustering the most. Sentiment scores have a minimal influence on the clustering and the price point only mattered for highly priced products
- The products clustering had 4 groups:  Cluster 0 has premium fragrances with high prices and ~4.3 ratings; Cluster 1 features many affordable products with mixed quality; Cluster 2 offers a diverse range of mid-priced items with ratings from 3.8 to 5; Cluster 3 contains fewer products but the highest reviews, indicating strong customer engagement.

Check the presentation to see some cool visuals.
