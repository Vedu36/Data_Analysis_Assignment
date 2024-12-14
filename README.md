# Cooking Sessions and Order Analysis

## Objective

The objective of this analysis is to analyze datasets related to user behavior, cooking preferences, and order trends. This analysis aims to derive insights that can help improve business decisions and customer satisfaction.

## Data Description and Methods

We worked with three datasets: `UserDetails`, `CookingSessions`, and `OrderDetails`.

- **UserDetails**: Contains details about users, including User ID, User Name, Age, Location, Registration Date, Phone, Email, Favorite Meal, and Total Orders.
- **CookingSessions**: Contains information about cooking sessions, including Session ID, User ID, Dish Name, Meal Type, Session Start, Session End, Duration (mins), and Session Rating.
- **OrderDetails**: Contains details about orders, including Order ID, Order Date, Order Status, Amount (USD), Time of Day, and Rating.

Through the analysis, we discovered that `Meal Type` and `Time of Day` are somewhat correlated: Breakfast refers to morning, lunch refers to day, and dinner refers to night.

## Analysis Results and Interpretation

### 1. Relationship Between Average Duration and Average Rating for Different Dishes
We found that the dish with the longest average cooking duration is Grilled Chicken, which also received the highest rating. Conversely, the dish with the shortest average cooking duration is Oatmeal, which received the lowest rating.

![Relationship Between Average Duration and Average Rating for Different Dishes](path_to_image)

### 2. Most Popular Dishes
The most popular dishes were Grilled Chicken and Spaghetti, each ordered 4 times, while the least popular dish was Oatmeal.

![Most Popular Dishes](path_to_image)

### 3. Most Common Dishes for Each Meal Type
- Dinner: Grilled Chicken and Spaghetti
- Lunch: Caesar Salad
- Breakfast: Pancakes

![Most Common Dishes for Each Meal Type](path_to_image)

### 4. Popular Times for Orders
Most orders were placed at night, and the least common time was the morning.

![Popular Times for Orders](path_to_image)

### 5. Favorite Times or Type of Orders
Dinner was the most favorite time for orders, while breakfast was the least favorite.

![Favorite Times or Type of Orders](path_to_image)

### 6. Average Amount Spent on Each Dish
The most costly dish was Spaghetti, while the least costly was Oatmeal.

![Average Amount Spent on Each Dish](path_to_image)

### 7. Order Status Distribution
- 87.5% of orders were completed.
- 18.5% of orders were incomplete.
- 2 orders were canceled.

![Order Status Distribution](path_to_image)

### 8. Age Distribution by Meal Type
- Age group 31-36 prefers breakfast.
- Age group 30-35 prefers lunch.
- Age group 28-35 prefers dinner.

![Age Distribution by Meal Type](path_to_image)

### 9. Age Distribution by Dish
- Age group 28-36 prefers Spaghetti.
- Age group 28-32.5 prefers Caesar Salad.
- Age group 27-33 prefers Grilled Chicken.
- Age group 32-38 prefers Pancakes.
- Age group 34-39 prefers Veg Burger.
- Age group 35 prefers Oatmeal.

![Age Distribution by Dish](path_to_image)

### 10. Number of Orders by Location
- New York, Los Angeles, and Chicago had the highest number of orders (3 each).
- Austin, Boston, and Miami had the lowest number of orders (1 each).

![Number of Orders by Location](path_to_image)

### 11. Correlation Analysis
- Correlation coefficient between Session Rating and Order Rating: 0.6126840351430513
- Correlation coefficient between Cooking Session Duration and Session Rating: 0.6894845315580719

![Correlation Analysis](path_to_image)

### 12. Daily Order Trend
On average, there were 2 orders per day.

## Recommendations and Conclusion

### Business Recommendations

1. **Enhance Menu Offerings**: Given the popularity of Grilled Chicken and Spaghetti, consider adding variations of these dishes to maintain customer interest.
2. **Focus on High-Quality Cooking Sessions**: The correlation between longer cooking durations and higher ratings suggests that investing in high-quality, time-intensive cooking sessions can lead to better customer satisfaction.
3. **Optimize Cooking Times for Lower-Rated Dishes**: Improve the preparation process for dishes like Oatmeal, which received lower ratings.
4. **Targeted Promotions**: Implement promotions for popular dishes like Grilled Chicken and Spaghetti to drive more sales.
5. **Collect Customer Feedback**: Gather feedback specifically for the least popular and lower-rated dishes to guide improvements.

### Conclusion

By leveraging these insights and recommendations, the business can enhance customer satisfaction, optimize menu offerings, and drive growth and profitability.
