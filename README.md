
# Fitness Exercises App

Welcome to the **Fitness Exercises App**, a modern React application designed to help users explore and perform a wide range of exercises. This project leverages two powerful APIs, **ExerciseDB** and **YouTube Search** from RapidAPI, to deliver a comprehensive fitness experience. With features like exercise categories, muscle group selection, video tutorials, and similar exercise recommendations, this app is a perfect addition to your portfolio!



## Features

- **Exercise Categories & Muscle Groups**: Browse exercises by category and target specific muscle groups.
- **Over 1000 Exercises**: Access a vast database of exercises with detailed instructions.
- **Exercise Details**: Get comprehensive information about each exercise, including instructions and benefits.
- **Related YouTube Videos**: Fetch and display related exercise videos directly from YouTube.
- **Similar Exercises**: Discover exercises similar to the one you're viewing to diversify your workout routine.
- **Responsive Design**: Built with Material UI (v5) for a sleek, responsive user interface.
- **Advanced React Practices**: Implemented using modern React concepts like hooks, state management, and optimized file structures.

## Tech Stack

- **React**: Frontend framework.
- **Material UI (v5)**: For styling and UI components.
- **RapidAPI**: Data fetching from ExerciseDB and YouTube Search APIs.
- **JavaScript (ES6+)**: Logic and interactions.
- **Axios**: For API requests.

## Demo

![Home](public/Screenshot2024-07-02094827.png)

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/patilnikhil805/fitness-exercises-app.git
   cd fitness-exercises-app
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Set up environment variables**:

   Create a `.env` file in the root of your project and add your RapidAPI keys:

   ```env
   REACT_APP_RAPIDAPI_EXERCISEDB_KEY=your_exercisedb_key
   REACT_APP_RAPIDAPI_YOUTUBE_KEY=your_youtube_search_key
   ```

4. **Run the app**:

   ```bash
   npm start
   ```

   The app should now be running on `http://localhost:3000`.

## API References

- **[RapidAPI ExerciseDB](https://rapidapi.com/justin-WFnsXH_t6/api/exercisedb/)**
- **[RapidAPI YouTube Search](https://rapidapi.com/h0p3rwe/api/youtube-search-and-download/)**

## Folder Structure

```bash
.
├── public
├── src
│   ├── assets           # Static assets like images and icons
│   ├── components       # Reusable components
│   ├── pages            # Page-level components
│   ├── utils            # Utility functions and helpers
│   ├── services         # API service files
│   └── styles           # Custom stylesheets
├── App.js               # Main app component
├── index.js             # Entry point of the application
└── .env                 # Environment variables
```

## Contribution

Contributions are welcome! If you'd like to contribute, please fork the repository, create a new branch, and submit a pull request.

1. Fork the project
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
.
- **RapidAPI** for providing the exercise and YouTube data.
