# RestaurantChooser
Restaurant Chooser

Welcome to Restaurant Chooser! This application helps groups of people decide where to eat by considering individual preferences and restaurant filters for an optimal choice.

Features

Group Decision Making: Collect preferences from all participants to find a suitable restaurant.

Custom Filters: Apply filters such as cuisine type, price range, location, and more.

User-Friendly Interface: Easy-to-use interface for quick decision-making.

Real-Time Updates: See changes in preferences and filters in real-time.

Requirements
Node.js (version 14 or higher)
npm or yarn
Expo CLICK
Android Studio (for Android emulator)
Xcode (for iOS simulator, only on mac OS)

Installation and launch
Clone the repository:
git clone [URL of your repository]
cd restaurant-chooser
Install the dependencies:
npm install
# or
yarn install
Launch the app:
npx expostart

The structure
of the restaurant-chooser application/
├── assets/              # Images and icons
├── components/          # Reusable components
│   ├── CustomButton.js
│   └── CustomTextInput.js
├── screens/            # Application Screens
│   ├── PeopleScreen.js
│   ├── RestaurantsScreen.js
│   └── DecisionScreen.js
├── navigation.js # Application Navigation
├── App.js # Root Component
└── package.json # Dependencies and Scripts
