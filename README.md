# Streamlit-Based-Movie-Recommender-System-Using-Python 🎬

Welcome to the **Streamlit-Based Movie Recommender System** repository! 
link to app:  https://geoffrey-movie-recommendation-python-app.streamlit.app/ 
This project showcases an interactive movie recommendation app, built using Python and Streamlit, that allows users to discover new movies based on their preferences. Dive into the world of recommendation systems and explore how data science can be used to enhance user experiences.

## Features 🌟

- **Interactive User Interface**: Users can select a movie from a dropdown menu and instantly receive recommendations for similar movies along with their posters.
- **Real-Time Recommendations**: Utilizes cosine similarity and pre-trained models to provide quick and accurate movie suggestions.
- **Custom Components**: Includes a custom image carousel component built with modern frontend technologies for a sleek and engaging UI.
- **TMDb API Integration**: Fetches movie details and posters from the TMDb API to provide rich information for each recommendation.

## Tech Stack 💻

- **Streamlit**: Used to build the interactive web app.
- **Python**: Backend logic for handling recommendation algorithms.
- **TMDb API**: For retrieving movie details and posters.
- **React**: Frontend component for the image carousel.
- **CSS**: Custom styles for a polished look and feel.

## Installation 🚀

To get started with the project, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/streamlit-movie-recommender.git
   cd streamlit-movie-recommender
   ```

2. **Install the required Python dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

3. **Build the frontend assets**:
   Navigate to the `frontend` directory and install the required npm packages, then build the frontend:
   ```sh
   cd frontend
   npm install
   npm run build
   ```

4. **Run the Streamlit app**:
   Navigate back to the root directory and start the Streamlit server:
   ```sh
   cd ..
   streamlit run app.py
   ```

5. **Access the app**:
   Open your browser and go to `http://localhost:8501` to view and interact with the movie recommender system.

## Directory Structure 📁

```
streamlit-movie-recommender/
├── app.py                      # Main application script
├── requirements.txt            # Python dependencies
├── frontend/
│   ├── public/
│   │   ├── build/
│   │   │   ├── bundle.css      # Compiled CSS
│   │   │   ├── bundle.js       # Compiled JS
│   ├── src/                    # Source files for the custom frontend component
│   ├── package.json            # NPM dependencies
│   ├── webpack.config.js       # Webpack configuration
└── README.md                   # Project documentation
```

## Troubleshooting 🛠️

If you encounter any issues, ensure that:
- The `bundle.css` and `bundle.js` files exist in the `frontend/public/build/` directory after running the frontend build command.
- All dependencies are correctly installed.
- You are running the app from the root directory.

For additional help, please open an issue in the repository.

## Contributing 🤝

We welcome contributions! If you would like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgements 🙏

- **Streamlit** for providing an excellent framework for building data apps.
- **TMDb API** for access to comprehensive movie data.

## Contact 📧

For any questions, feel free to reach out via [email](mailto:your.email@example.com) or open an issue on GitHub.

---

Thank you for checking out the Streamlit-Based Movie Recommender System! We hope you find it useful and enjoyable. Happy coding! 😊

---

Feel free to customize the description to better match your project and personal preferences.
