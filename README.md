# TripAdvisor Recommendation Engine

## Introduction
TripAdvisor is the world's largest travel platform, providing millions of users with recommendations for hotels, restaurants, and attractions. In this project, we aim to build a recommendation system that can suggest the most relevant places to users based on their interests.

## Methodology
Our recommendation system is based on a combination of the user's preferred interests, the destination's average ratings, as well as the VADER Sentiment & SpaCy Similarity Scores. Our system also allows the user to input his/her preferred country to visit. Based on these factors, our system displays the top recommended destination.

To implement this system, we scraped a large dataset of user ratings and reviews from TripAdvisor and used it for this purpose. Our recommendation system also suggests further destinations based on how similar it is to the top recommendation. Thinking from a user's point of view, we also show the closest places to the top recommended place in case the user wants to travel to nearby destinations.

VADER is a lexicon and rule-based sentiment analysis tool that is sensitive to both polarity (positive/negative) and intensity (strength) of emotion. We also  Content-Based Filtering, on the other hand, uses information about the places themselves, such as the type of cuisine, location, and user-generated reviews, to make recommendations.

## Conclusion
Our TripAdvisor Recommendation System is designed to make travel planning easier and more efficient by providing users with personalized recommendations based on their interests. We believe that the techniques used in this system provides an effective solution for generating accurate and relevant recommendations.
