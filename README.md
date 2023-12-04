# YouTube Video Downloader using Flask and Pytube

This project is a web application built with Flask that allows users to download YouTube videos. It utilizes the Pytube library to fetch and download videos from YouTube based on user input.

## Features

- **Download:** Enter a YouTube video URL and download the video in various available formats.
- **Supported Formats:** Download videos in different resolutions and formats provided by YouTube.
- **Fast and Easy:** Simple interface for downloading videos directly from YouTube.

## Prerequisites

Before setting up and running the application, ensure you have:

- Python 3.x
- Flask (`pip install Flask`)
- Pytube (`pip install pytube`)

## Setup

1. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

2. Start the Flask application:

    ```bash
    python app.py
    ```

## Usage

1. Access the web application via a web browser using the provided URL (usually `http://127.0.0.1:5000`).

2. Enter a valid YouTube video URL into the input field.

3. Click the **Download** button to see available formats and resolutions for the video.

4. Choose the desired format and resolution, then click the **Download** button to initiate the download.

## Additional Notes

- Ensure the YouTube video URL provided is valid and accessible.
- Pytube might not support certain videos due to YouTube's restrictions or formats that aren't downloadable.
- Customize the app's UI, add features like video conversion, support for playlists, or quality selection.
- Respect YouTube's terms of service and use the application responsibly.

