# Market Scope

Market Scope is a comprehensive AI-Powered Market Detective tool designed to provide insights into your competition. By leveraging modern technologies like Flask, React, OpenAI, and Google APIs, it uncovers valuable information about your competitors such as their main products or services, business strategies, and market perception.

This tool conducts deep-dive searches using Google's Custom Search API, segmenting the obtained data into manageable chunks for further analysis. It uses OpenAI's advanced NLP models to generate an informative report, delivering data-rich insights to your fingertips.

## Table of Contents

1. [Features](#features)
2. [Setup Instructions](#setup-instructions)
3. [Usage Instructions](#usage-instructions)
4. [Deployment Instructions](#deployment-instructions)

## Features

### Search Company Name

- You may search multiple company names by seperating the names with a comma

<a href="https://github.com/keshao728/pls-hire-me"><img src="https://imgur.com/6eKxii3.gif" title="source: imgur.com" /></a>

### Report

- Generates a report for the company's main products or services, business strategies, and market perception

<a href="https://github.com/keshao728/pls-hire-me"><img src="https://imgur.com/SntGku7.gif" title="source: imgur.com" /></a>

## Getting Started

These instructions will guide you through the process of setting up and running the application on your local machine for development and testing purposes.

### Prerequisites

Ensure you have the following installed on your local development machine:

- Python 3.8 or later
- Node.js and npm
- Flask
- React

Also, make sure to acquire API keys for OpenAI, Google APIs and Programmable Search Engine ID and store them in a `.env` file, an `.env.example` is provided at the `/app` of the project directory.

## Setup Instructions

### Backend

The backend is a Python Flask application.

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/keshao728/pls-hire-me.git
   ```

2. Navigate to the backend directory:

   ```bash
   cd app
   ```

3. Install Python dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Create the local server env file, replace the key to your API keys:
   ```sh
   cp .env.example .env.local
   ```
5. Start the application:
   ```bash
    python app.py
   ```
   This will start the server on localhost:5003. The server endpoint is `/process`, which accepts POST requests.

### Frontend

The frontend is a React application.

1. Navigate into the frontend directory:
   ```bash
   cd react-app
   ```
2. Install Node.js dependencies:
   ```bash
   npm install
   ```
3. Start the application
   ```bash
    npm start
   ```
   This will start the React application and open it in your default web browser at http://localhost:3000.

## Usage Instructions

- Open your web browser and go to http://localhost:3000 (or the port you configured for your React app).
- You'll see an input field where you can enter the names of the companies you want to investigate, separated by commas.
- After entering the company names, click the 'Submit' button.
- The application will then generate a report for each company, which will include information about their main product or service, business strategy, and market perception.

## Deployment Instructions

- Work in progress

Note: Don't forget to secure your API keys before deploying the application to a production environment.
