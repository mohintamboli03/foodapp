
# foddApp

foddApp is a React-based application that allows users to search for food recipes using the Spoonacular API. Users can search for recipes by name (e.g., "pasta," "pizza") and view detailed information about each recipe, including ingredients, cooking time, and instructions.

## Features

- **Search Recipes**: Users can search for recipes by name (e.g., "pasta," "pizza").
- **View Recipe Details**: Upon selecting a recipe, users can view the ingredients, cooking time, and step-by-step instructions.
- **Responsive Design**: The app is designed to be responsive and works well on mobile and desktop devices.

## Live Demo

You can view the live demo of the app here: [foddApp Live Demo](https://foodapp-woqc.onrender.com)

## Tech Stack

- **React.js**: Frontend framework for building the user interface.
- **Spoonacular API**: Used to fetch recipe data.
- **Render**: Platform used for deploying the app.

## Getting Started

To run this project locally, follow these steps:

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/foddApp.git
   ```

2. Navigate to the project directory:
   ```bash
   cd foddApp
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory and add your Spoonacular API key:
   ```bash
   REACT_APP_API_KEY=your_api_key_here
   ```

5. Start the development server:
   ```bash
   npm run dev

   ```

The app should now be running at `http://localhost:3000`.


### Environment Variables

The app requires the following environment variable to run:

```
REACT_APP_API_KEY=your_api_key_here
```

This API key is necessary for fetching data from the Spoonacular API.

## Deployment

The app is deployed on Render. To deploy your own version, follow these steps:

1. Push your project to a GitHub repository.
2. Create a new web service on [Render](https://render.com/) and connect it to your GitHub repository.
3. Set the build command to:
   ```bash
   npm install && npm run build
   ```
4. Set the publish directory to `build/`.

Render will automatically build and deploy your app.

## API Used

The app fetches recipe data from the **Spoonacular API**. You can learn more about the API here: [Spoonacular API Documentation](https://spoonacular.com/food-api).

## Contributing

Contributions are welcome! If you'd like to contribute to foddApp, follow these steps:

1. Fork the project.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
