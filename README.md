# spotify_recommendation_system
## Description
The Spotify Recommendation System is designed to recommend songs based on a given Spotify URL or an artist's profile link. Users can choose to use either the Spotify API or a machine learning model for generating recommendations.

## Features
- Recommend songs based on a Spotify track URL.
- Recommend songs based on an artist's profile link.
- Option to use Spotify API or a machine learning model for recommendations.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/spotify_recommendation_system.git
    cd spotify_recommendation_system
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Obtain Spotify API credentials by creating a developer account on the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/).
2. Set up your environment variables with your Spotify API credentials:
    ```bash
    export SPOTIFY_CLIENT_ID='your_client_id'
    export SPOTIFY_CLIENT_SECRET='your_client_secret'
    ```
3. Run the recommendation script:
    ```bash
    python recommend.py --url <spotify_url> --method <api_or_ml>
    ```
## NOTE
set up a virtual environment to avoid version collision between packages like numpy,streamlit and protobouf... etc

## API Reference
This project uses the [Spotify Web API](https://developer.spotify.com/documentation/web-api/) to fetch song and artist data.

## Machine Learning Model
The machine learning model is trained on a dataset of songs and their features. It uses collaborative filtering and content-based filtering techniques to generate recommendations.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/yashtachi/spotify_recommendation_system/blob/main/README.md) file for details.
