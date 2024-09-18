# Meal Ordering System

A simple web application that fetches meals based on a main ingredient using the [MealDB API](https://www.themealdb.com/api.php). Users can create orders, view incomplete orders, and mark them as complete. The application uses JavaScript to handle fetching meal data, managing orders, and interacting with the browser’s session storage.

## Features

- **Fetch Meals by Ingredient**: Allows users to enter a main ingredient and fetch meal options from the MealDB API.
- **Random Meal Selection**: Automatically selects a random meal from the fetched list.
- **Order Management**: Users can create orders, view incomplete orders, and mark them as complete.
- **Session Storage**: Uses session storage to persist orders and last order number across page reloads.

## Technologies Used

- **HTML**: For the basic structure of the application.
- **JavaScript**: For interacting with the MealDB API, handling orders, and managing session storage.
- **MealDB API**: Provides meal data based on the main ingredient.

## How to Use

1. **Open the HTML File**:
   Open the `mealDB.html` file in a web browser.

2. **Create Orders**:
   - Enter the main ingredient for your meal when prompted.
   - The application fetches meal options from the MealDB API and selects a random meal.
   - Confirm the order or continue ordering.

3. **Manage Orders**:
   - After ordering, the application prompts you to mark incomplete orders as complete.
   - Enter the order number to mark an order as complete or enter `0` to skip.

## Code Explanation

- **`fetchMeals(mainIngredient)`**:
  Fetches meals from the MealDB API based on the provided main ingredient.

- **`selectRandomMeal(meals)`**:
  Randomly selects a meal from the list of fetched meals.

- **`displayAndCompleteOrders(orders)`**:
  Displays incomplete orders and allows users to mark them as complete.

- **`init()`**:
  Initializes the application by handling user prompts for ordering, managing session storage, and calling the order management function.

## Example

Here's an example of how the application works:
1. Enter `chicken` as the main ingredient.
2. The application fetches meals containing chicken and randomly selects one.
3. Place the order and choose whether to continue ordering.
4. After ordering, you can mark incomplete orders as complete.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- **MealDB API** – For providing a free API to fetch meal data.
- **JavaScript** – For implementing the functionality and interacting with the API and session storage.

---

Thank you for exploring the Meal Ordering System! Feel free to modify and enhance the application as needed.
