# Recipe Application

A React-based recipe application that fetches and displays recipes using the Spoonacular API.

## Features
- Search for recipes by ingredients or keywords
- Browse random recipes
- View recipes by category
- Detailed recipe pages with ingredients and instructions

## Tech Stack
- React.js
- Spoonacular API
- CSS for styling

## Folder Structure
```
public/
  favicon.ico
  index.html
  logo192.png
  logo512.png
  manifest.json
  robots.txt

src/
  components/
    Category.jsx
    Random.jsx
    Search.jsx
    Veggie.jsx
  pages/
  App.css
  App.js
  index.css
  index.js
  logo.svg
  reportWebVitals.js
  setupTests.js

README.md
package.json
package-lock.json
```

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/recipe-app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd recipe-app
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Create a `.env` file in the root directory and add your Spoonacular API key:
   ```sh
   REACT_APP_SPOONACULAR_API_KEY=your_api_key_here
   ```
5. Start the development server:
   ```sh
   npm start
   ```

## Usage
- Enter an ingredient or dish name in the search bar to find recipes.
- Browse through categories or get random recipes.
- Click on a recipe to view detailed instructions and ingredients.

## API Reference
This app uses the [Spoonacular API](https://spoonacular.com/food-api). Make sure to sign up and get an API key to use the application.

