

# 🍽️ Meals App


The **Meals App** is a Flutter-based mobile application that provides users with a wide variety of meal recipes, organized by categories. Users can browse different meals, view detailed recipes, and mark their favorite dishes. The app demonstrates clean UI practices, state management, and the use of complex routing and navigation to deliver an intuitive user experience.

## ✨ Features
- **Browse Recipes by Category**: Explore a wide variety of meal recipes, categorized for easy browsing (e.g., Italian, Quick & Easy, Vegetarian, etc.).
- **Detailed Meal Information**: View comprehensive details of each meal, including ingredients, steps, and preparation time.
- **Favorite Meals**: Mark meals as favorites and access them quickly through the favorites section.
- **Filters**: Set dietary preference filters (e.g., gluten-free, vegan, vegetarian, lactose-free) to tailor the meal selection.
- **Responsive UI**: A clean and responsive design that works seamlessly across Android and iOS devices.
- **Efficient Navigation**: Leverages Flutter’s powerful navigation tools with custom routing and dynamic screens.

## 🛠️ Tech Stack
- **Framework**: Flutter
- **Language**: Dart
- **State Management**: Riverpod
- **Navigation**: Named Routes with Dynamic Data Passing
- **Data Storage**: Local JSON Data.

## 📚 Project Structure

Here's a brief overview of the key components of the project:

```bash
lib/
├── models/               # Data models (Meal, Category)
├── screens/              # UI Screens (Category Meals, Meal Details, Filters, Tabs)
├── widgets/              # Reusable widgets (Meal Item, Category Grid, Main Drawer)
├── dummy_data.dart       # Mock data for the app
├── main.dart             # Main entry point with routing setup
└── providers/            # Provider for managing state (Favorites, Filters)
```

- **Models**: Defines the structure of the data (meals, categories).
- **Screens**: The different screens in the app, including category meals, meal details, and filters.
- **Widgets**: Reusable components like the meal item card, category grid, and main drawer.
- **Provider**: Used to manage favorites and dietary filters globally across the app.

## 🚀 Installation & Usage

Follow these steps to get the app running on your local machine:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Mehak1524/Meals_App_Flutter.git
   cd Meals_App_Flutter
   ```

2. **Install the dependencies**:
   ```bash
   flutter pub get
   ```

3. **Run the app**:
   ```bash
   flutter run
   ```

Make sure you have Flutter installed. If not, refer to the official [Flutter documentation](https://flutter.dev/docs/get-started/install) to get started.

## 🧠 Key Concepts Demonstrated

- **Provider for State Management**: The app uses `Riverpod` to handle the favorite meals and dietary filter states efficiently across different screens.
- **Custom Routing & Navigation**: The app makes use of named routes for navigation and dynamic data passing between screens.
- **Complex UI Components**: Custom reusable widgets like `MealItem`, `CategoryItem`, and `MainDrawer` showcase Flutter's powerful UI capabilities.
- **Local Data Storage**: All meal and category data is fetched locally from `dummy_data.dart`, mimicking a real-world API call or database integration.

## 🌱 Future Improvements

- **API Integration**: Replace the local data source with an API to fetch real-time meal recipes and updates.
- **User Accounts**: Add user authentication for personalized favorites and dietary preferences.
- **Dark Mode**: Implement a dark mode for better accessibility and user experience.
- **Animations**: Add smooth transitions and animations for a more engaging UI experience.

## 🛡️ License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
