**Music Recommendation System using Spotify API**

**Overview:**
This repository contains code for a music recommendation system that utilizes the Spotify API to extract music data and provide personalized recommendations based on user input. The system employs a hybrid approach, combining content-based filtering and popularity-based scoring to generate relevant recommendations.

**Key Features:**

1. **Accessing and Tokenization:** The system authenticates with the Spotify API using client credentials and obtains an access token for data extraction.

2. **Spotify Music Data Extraction:** It fetches music data from a specified playlist, including track information such as name, artists, album, release date, and audio features like danceability, energy, and tempo.

3. **Data Preprocessing:** The extracted data is processed and normalized using techniques like Min-Max scaling to prepare it for recommendation algorithms.

4. **Content-Based Recommendations:** Based on the input song provided by the user, the system calculates similarity scores using cosine similarity on audio features and suggests similar songs from the playlist.

5. **Hybrid Recommendation System:** It integrates content-based recommendations with popularity-based scoring, considering factors like release date and track popularity to provide more personalized and diverse recommendations.

**Repository Structure:**

- **`music_recommendation.ipynb`**: Jupyter Notebook containing the code for the music recommendation system.
- **`README.md`**: Markdown file providing an overview of the project, setup instructions, and usage guidelines.
- **`requirements.txt`**: Text file listing the required Python packages and their versions for running the code.
- **`LICENSE`**: License file specifying the terms of use for the project.

**Usage:**

1. Clone the repository to your local machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Obtain your Spotify API client ID and client secret and replace them in the code.
4. Run the `music_recommendation.ipynb` notebook to execute the recommendation system.
5. Follow the instructions within the notebook to input a song and receive personalized recommendations.

**Contributing:**

Contributions to the project are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request following the project's contribution guidelines.

**License:**

This project is licensed under the [MIT License](LICENSE).

**Disclaimer:**

This project is for educational and demonstration purposes only. It does not store any user data and solely relies on the Spotify API for music recommendations.

**Acknowledgements:**

- This project utilizes the Spotipy library for interacting with the Spotify API.
- Special thanks to Spotify for providing access to their API for developers to build innovative applications.