# Movie Recommender System

## Project Description
This is a content-based movie recommender system built using machine learning techniques. The system recommends movies based on the similarity of movie features, providing personalized suggestions to users. It leverages a similarity matrix computed from movie data to find movies that are most similar to a selected movie.

The application is built with Streamlit for an interactive user interface and uses The Movie Database (TMDb) API to fetch movie posters dynamically.

## Features
- Content-based filtering using movie feature similarity
- Interactive movie selection via a dropdown menu
- Recommendations of 5 similar movies based on the selected movie
- Display of movie posters fetched from TMDb API alongside movie titles

## Installation

### Requirements
- Python 3.x
- Streamlit
- pandas
- requests
- pickle (standard library)

### Installing Dependencies
You can install the required Python packages using pip:

```bash
pip install streamlit pandas requests
```

## Usage

### Running the App
Run the Streamlit app using the following command:

```bash
streamlit run app.py
```

### Using the App
- Select a movie from the dropdown list.
- Click the "Recommend" button.
- View the recommended movies along with their posters.

## Data Files
- `movie_dict.pkl`: Contains the movie dataset used for recommendations.
- `similarity.pkl`: Contains the precomputed similarity matrix used for content-based filtering.

## API Information
The app uses The Movie Database (TMDb) API to fetch movie posters. An API key is embedded in the app to access the TMDb service.

## License
This project is open source and available under the MIT License.
