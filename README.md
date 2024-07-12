### React Theme Switcher App

This is a simple React application that allows you to switch between light and dark themes using a theme provider and a theme button component.

#### Technologies Used:
- React
- HTML/CSS (styled with Tailwind CSS)
- Context API for state management

#### Features:
- **Theme Switching**: Toggle between light and dark themes with a click of a button.
- **Responsive Design**: The application is designed to be responsive and works well across different screen sizes.

#### Components:
1. **ThemeBtn**: Component responsible for rendering the theme switch button.
2. **Card**: Placeholder component for demonstrating content in different themes.


#### Notes:
- Make sure to include Tailwind CSS in your project for proper styling.
- The `ThemeProvider` from `./contexts/Theme` provides the current theme mode (`themeMode`), and functions (`lightTheme`, `darkTheme`) to switch themes.

This application serves as a basic demonstration of implementing theme switching functionality using React and Context API.
