# <img src="https://github.com/user-attachments/assets/29e30d03-8334-46b6-a9f0-2331c28dd6de" alt="logo-bg" width="100" /> DragonBall Characters App

Welcome to the DragonBall Characters App repository! This interactive application, built with React 19, allows users to explore and manage their favorite DragonBall characters. The app is designed to be fully responsive and adheres to a design proposed in Figma. It offers a range of features including character search, filtering, and detailed views, all while ensuring a smooth and engaging user experience.

## Overview

The DragonBall Characters App is divided into two main views: the Characters List and the Character Details view. Each view is designed to provide a seamless and intuitive experience for users as they navigate through the app.

### <img src="https://github.com/user-attachments/assets/0488e9ab-80ea-483b-a3b4-5a6a7a721eab" alt="logo-bg" width="20" /> Characters List View

Upon launching the app, users are greeted with the Characters List view. This view displays the first 50 characters from the DragonBall universe, fetched from an external API. The interface is clean and follows the design guidelines set in Figma, ensuring a visually appealing layout.

#### Key Features:

- *Logo and Favorites Icon*: At the top of the page, users will find the DragonBall logo and an icon indicating the number of favorite characters. The favorites icon updates dynamically as characters are added or removed from the favorites list.
- *Search Bar*: A search bar allows users to search for characters by name. For example, typing "Goku" will filter the list to show all characters with "Goku" in their name. The search results update in real-time, providing immediate feedback.
- *Results Counter*: Below the search bar, a counter displays the number of characters matching the search criteria. This counter updates automatically as the user types.
- *Character List*: The main section of the view displays a list of characters, each with an image, name, and an option to add the character to favorites. Clicking on a character redirects the user to the Character Details view.
- *Favorites Management*: Users can add characters to their favorites by clicking the heart icon next to each character. The icon changes color to indicate the character has been added to favorites, and the favorites counter at the top updates accordingly. Users can also remove characters from their favorites, with changes persisting across different views.

#### Favorites Filter:

- By clicking the favorites icon at the top, users can filter the list to show only their favorite characters. To return to the full list, users simply click the DragonBall logo.

### <img src="https://github.com/user-attachments/assets/0488e9ab-80ea-483b-a3b4-5a6a7a721eab" alt="logo-bg" width="20" /> Character Details View

When a user clicks on a character from the list, they are taken to the Character Details view. This view provides an in-depth look at the selected character, following the design guidelines from Figma.

#### Key Features:

- *Logo and Favorites Icon*: Similar to the Characters List view, the top of the page features the DragonBall logo and a favorites icon. Clicking the logo redirects the user back to the main list, while the favorites icon shows the user's favorite characters.
- *Character Information*: The main section displays the character's image, name, and description. Users can add the character to their favorites from this view as well.
- *Comics/Transformations List*: Below the character information, a list of the character's transformations is displayed, ordered by release date or KI. Only the first 20 items are shown to keep the view concise and manageable.

## Additional Features

- ✅*Testing*: The application includes comprehensive testing to ensure all functionalities work as expected.
- ✅*Responsiveness*: The app is designed to be fully responsive, providing a seamless experience across different devices and screen sizes.
- ✅*Code Quality*: Linters and formatters are used to maintain high code quality and consistency.
- ✅*State Management*: Efficient state management ensures smooth interactions and data persistence across different views.

## Getting Started

To get started with the DragonBall Characters App, follow these steps:

1. *Clone the repository*:
   sh
   git clone https://github.com/your-username/dragonball-characters-app.git
   
2. *Navigate to the project directory*:
   sh
   cd dragonball-characters-app
   
3. *Install dependencies*:
   sh
   npm install
   

## Running the App

To start the application in development mode, use the following command:
sh
npm start


To run tests and ensure everything is working correctly:
sh
npm test


To build the application for production:
sh
npm run build
