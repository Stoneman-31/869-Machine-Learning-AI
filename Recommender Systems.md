# Recommender Systems
# Should refer to Uncle Steve's Slides

![image](https://user-images.githubusercontent.com/106495355/208036314-99cf86b7-06db-4242-a210-ec61af22ad38.png)

![image](https://user-images.githubusercontent.com/106495355/208035482-a8394cc3-670e-447b-9272-7381d97eaf13.png)


### Goals of a RS
- Increase product sales
- Increase click through rates
- Increase conversions
- Increase user engagement
- Improve customer experience

### General Approach
- Show the most popular items
- Humans manually curate a list of their favourite items
- Show new items
- Show items that have increased the most in popularity in some time period
- Show items that are most popular in the current time of year

### Existing Tools and Packages

![image](https://user-images.githubusercontent.com/106495355/208033183-31d04fcc-4f23-46b1-a131-478e62b9e558.png)

### Utility Matrix

![image](https://user-images.githubusercontent.com/106495355/208034090-87a41721-4115-41aa-af05-b168996d2d8c.png)

### How to give rating?
Explicit Rating : Users inentionally give rating
- Rating a movie 1-5
- Liking an insta post
- Disliking a song on Google Play Music

Interval: Values come from a discrete set of ordered numbers
- E.g.,{1,2,3,4,5}
- E.g.,{-2,-1,0,1,2}

Binary: user specifies like or dislike
- E.g., {0,1}

Unary rating: user specifies like, but no way to specify dislike

![image](https://user-images.githubusercontent.com/106495355/208034559-53a97d78-c82f-4816-a7d4-2cbda9c25975.png)

## Collaborative Filtering
### Collaborative filtering techniques use utility matrix to predict ratings of un-rated items
- User-based: If person A and person B share an opinion on one item, then they might share an opinion on a different item
- Item-based: If item A and item B are liked by the same people, then they might have something in common
### CF uses utility matrix to build a ML model. 
- Regression, especailly KNN
- Association Rules
- Graph Analytics
- Matrix decomposition/ Factor Analysis

![image](https://user-images.githubusercontent.com/106495355/208035254-be03e140-30ba-408b-b1f3-e342a30eb08c.png)



