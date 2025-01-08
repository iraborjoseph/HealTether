# HealTether

**User List Flutter Application**
**Overview**
This is a simple Flutter application that fetches data from an external API and displays it in a list. It implements basic state management using the Provider package and handles loading, data, and error states. The app fetches a list of users and displays their names, emails, and a placeholder avatar image.

**Features**
Fetches data from the JSONPlaceholder API.
Displays user name, email, and a placeholder avatar image in a ListView.
Implements state management using the Provider package.
Handles three states:
Loading: Displays a loading spinner while data is being fetched.
Data: Displays the list of users once data is fetched.
Error: Displays an error message in case the API request fails.
Includes pull-to-refresh functionality.
Optional search functionality to filter users based on their names.


**Getting Started**
**1. Prerequisites**
Ensure you have the following installed:

Flutter SDK (version >=3.4.3 <4.0.0)
A code editor such as VS Code or Android Studio
Dart SDK (comes with Flutter SDK)

**2. Clone the Repository**
To clone the project, run the following command:

git clone <https://github.com/iraborjoseph/HealTether>

**3. Install Dependencies**
Navigate to the project directory in your terminal and run the following command to install the necessary dependencies:
flutter pub get

**4. Run the Project**
Once the dependencies are installed, use the following command to run the project:
flutter run

lib/
├── models/            # Data models like User class
├── providers/         # State management (UserProvider)
├── screens/           # Screens like UserListScreen
├── services/          # API service to fetch data (ApiService)
└── widgets/           # Utility widgets like snackbars
