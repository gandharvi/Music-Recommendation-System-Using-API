# Song Recommendation System

## Overview

This project implements a hybrid song recommendation system using data from the Spotify API. It provides personalized song recommendations based on user input and combines content-based filtering with popularity metrics.

## Features

- Check if a song exists in the dataset.
- Retrieve details for the input song.
- Generate hybrid recommendations based on content and popularity.
- Display recommended songs along with their details.

## Technologies Used

- Python
- Pandas
- Spotipy (Spotify API wrapper)

## Setup

### Prerequisites

- Python 3.x
- Required libraries:
  - pandas
  - spotipy

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/song-recommendation-system.git
   cd song-recommendation-system
   ```

2. Install the required libraries:
   ```bash
   pip install pandas spotipy
   ```

### Configuration

1. **Spotify API Credentials**: Create a Spotify Developer account and set up an application to get your `CLIENT_ID` and `CLIENT_SECRET`. 

2. **Access Token**: Ensure you have a method to obtain a Spotify access token for API requests.

3. **Data Preparation**: Load your dataset into a Pandas DataFrame named `music_df` with the required columns (`Track Name`, `Artists`, `Album Name`, `Release Date`, `Popularity`, etc.).

