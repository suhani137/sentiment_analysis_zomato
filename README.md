Sentiment analysis of Zomato restaurant reviews: A model predicting sentiment for a restaurant based on the amenities provided.

1. Data was collected from Zomato website for 252 most popular restaurants in and around Connaught Place in Delhi. For each restaurant, 10 most recent reviews, cost for two and hours of operations were captured.
2. Along with that, rating given by customer for each review was also taken into account. In total, 2,520 reviews were collected.
3. For each restaurant, ctaegorial variables with Yes/No: Zomato Gold, ongoing promotions, online ordering, quick bites, casual dining, bakery, café, sweet shops, beverage shop,  fine dining, lounge, full bar available, live sports screening, live entertainment, valet parking, indoor seating, outdoor seating, nightlife, smoking area, serves alcohol, buffet, breakfast, brunch, wheelchair accessible, desserts and bakes, vegetarian only, WiFi, kid friendly, above 18 only, takeaway only and delivery only.
4. After classifying each of the 2,520 reviews as positive or negative, the model determines what factors lead to a positive or negative perception about a restaurant. 
5. Taking sentiment (positive/negative) as the target variable, and rest 37 variables related to amenities as independent, algorithms including, decision tree, random forest, naive bayes, logistic regression and support vector machine were used.
