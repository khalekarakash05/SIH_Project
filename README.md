# SIH Smart Farmer

[Visit the live website](https://sih-smart-farmer.vercel.app/)

[GitHub Repository](https://github.com/khalekarakash05/SIH_Project/)

## Overview

SIH Smart Farmer is a web application designed to bridge the gap between farmers and agricultural researchers. The platform allows farmers to upload images of diseased crops, which are then analyzed by scientists or researchers. Researchers provide one-to-one solutions for each farmer, helping them address crop diseases effectively and improve agricultural productivity.

## Features

- **Crop Disease Detection**: Farmers can upload images of diseased crops.
- **Researcher Dashboard**: A dedicated dashboard for scientists and researchers to analyze crop diseases and provide tailored solutions.
- **One-to-One Interaction**: Enables personalized recommendations and feedback for each farmer.
- **Data Insights**: Collects and organizes data for better understanding of prevalent crop diseases.

## Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Machine Learning**: Image analysis for disease detection (if applicable)
- **Hosting**: Vercel, Render
- **APIs**: External APIs for weather and other related data

## Installation

To run the project locally, follow these steps:

# Backend Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/khalekarakash05/SIH_Project.git
2. Navigate to the project directory:

   ```bash
   cd SIH_Project/SIH_Backend
3. Install dependencies:

   ```bash
   npm install
4. Create a .env file and add the required environment variables:

   ```bash
   CLOUD_NAME= dmodqkrlx
   API_KEY=
   API_SECRETE=
   DATABASE_URL=
   JWT_SECRETE=
   PORT =


5. Start the development server:

    ```bash
    npm run start
    

  # FrontEnd Installation


1. Navigate to the project directory:

   ```bash
   cd SIH_Project/SIH_Frontend
2. Install dependencies:

   ```bash
   npm install
3. Create a .env file and add the required environment variables:

   ```bash
   REACT_APP_API_URL=<backend_api_url>
   REACT_APP_WEATHER_API_KEY=<weather_api_key>
   REACT_APP_IMAGE_UPLOAD_API_KEY=<image_upload_api_key>

4. Start the development server:

    ```bash
    npm run start

## Contributing
# We welcome contributions to improve the platform. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push them to your fork.
4. Submit a pull request to the main branch.
