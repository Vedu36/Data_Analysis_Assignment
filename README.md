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

![Avg duration and Avg rating for dish](https://github.com/user-attachments/assets/3883228d-66da-4ee4-b714-4b85bbe5f89e)

### 2. Most Popular Dishes
The most popular dishes were Grilled Chicken and Spaghetti, each ordered 4 times, while the least popular dish was Oatmeal.

![most popular dish](https://github.com/user-attachments/assets/a853fc8b-2e9f-448b-a989-a957091c58d0)

### 3. Most Common Dishes for Each Meal Type
- Dinner: Grilled Chicken and Spaghetti
- Lunch: Caesar Salad
- Breakfast: Pancakes

![comman dishes for each meal](https://github.com/user-attachments/assets/c69e26d6-d4d1-4765-b23b-cba86fcf4624)

### 4. Popular Times for Orders
Most orders were placed at night, and the least common time was the morning.

![popular time for the order](https://github.com/user-attachments/assets/b4d86d2e-acab-474b-afc9-472b261e538b)

### 5. Favorite Times or Type of Orders
Dinner was the most favorite time for orders, while breakfast was the least favorite.

![favorite time for orders](https://github.com/user-attachments/assets/ea9ae5bf-f7a5-479f-9d9e-e6956e08257d)

### 6. Average Amount Spent on Each Dish
The most costly dish was Spaghetti, while the least costly was Oatmeal.

![avg amount spend](https://github.com/user-attachments/assets/940f6abd-bfe6-4e0d-9797-53302ed02087)

### 7. Order Status Distribution
- 87.5% of orders were completed.
- 18.5% of orders were incomplete.
- 2 orders were canceled.

![order status](https://github.com/user-attachments/assets/309379af-debe-4426-85df-ef7712e16ccd)

### 8. Age Distribution by Meal Type
- Age group 31-36 prefers breakfast.
- Age group 30-35 prefers lunch.
- Age group 28-35 prefers dinner.

![boxlpot 1 age and mead type](https://github.com/user-attachments/assets/16e9c42d-c5d4-42cc-b4f0-c3d529962b28)

### 9. Age Distribution by Dish
- Age group 28-36 prefers Spaghetti.
- Age group 28-32.5 prefers Caesar Salad.
- Age group 27-33 prefers Grilled Chicken.
- Age group 32-38 prefers Pancakes.
- Age group 34-39 prefers Veg Burger.
- Age group 35 prefers Oatmeal.

![boxplot 2 age and dishes](https://github.com/user-attachments/assets/2f0f0a54-183d-4e22-a8fe-9a34dff626bb)

### 10. Number of Orders by Location
- New York, Los Angeles, and Chicago had the highest number of orders (3 each).
- Austin, Boston, and Miami had the lowest number of orders (1 each).

![location and no  orders](https://github.com/user-attachments/assets/706eeccd-6185-4e62-8392-0da2c3e6aa4b)

### 11. Correlation Analysis
- Correlation coefficient between Session Rating and Order Rating: 0.6126840351430513
- Correlation coefficient between Cooking Session Duration and Session Rating: 0.6894845315580719

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
