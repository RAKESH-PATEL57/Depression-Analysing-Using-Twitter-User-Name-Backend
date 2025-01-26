# Depression Analysis Backend

This repository contains the backend code for the Depression Analysis project. It provides APIs to fetch tweets from Twitter and analyze their content using Google Gemini AI to determine if the user may be experiencing signs of depression.

## Technologies Used

- **Node.js:** A JavaScript runtime for building scalable and efficient server-side applications.
- **Express.js:** A minimalist framework for creating robust APIs.
- **Axios:** For making HTTP requests to external APIs.
- **dotenv:** For managing environment variables securely.
- **Google Gemini AI:** Used for analyzing the sentiment and tone of tweets.
- **Twitter API:** Fetches recent tweets of a given username for analysis.
- **CORS:** Handles cross-origin requests from the frontend.

## Features

- **Fetch Tweets:** Retrieves recent tweets of a user via the Twitter API.
- **Sentiment Analysis:** Analyzes the tone and sentiment of tweets using Google Gemini AI.
- **Error Handling:** Robust error messages for common issues like invalid usernames, missing API tokens, or rate limits.
- **CORS Enabled:** Ensures the API can be accessed by the frontend application.

## How It Works

1. A username is sent to the `/analyze/:username` endpoint.
2. The backend fetches recent tweets from the Twitter API.
3. The tweets are sent to the Google Gemini AI model for analysis.
4. A sentiment analysis result is returned to the frontend.

## Installation and Setup

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/RAKESH-PATEL57/Depression-Analysing-Using-Twitter-User-Name-Backend
