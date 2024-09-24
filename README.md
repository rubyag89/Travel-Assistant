# Travel-Assistant
**Travel Assistant**
Travel Assistant is a chatbot specifically designed to assist users with travel-related inquiries. By integrating data about destinations, flights, accommodations, and local activities into a large language model (LLM), this chatbot provides insightful information and personalized advice for planning trips, booking travel services, and navigating unfamiliar destinations.

**Features**
Interactive chatbot interface for travel-related questions.
Extensive database of destinations, flight options, accommodations, and activities.
Personalized travel itineraries and recommendations based on user preferences.
Real-time information on flights, hotels, and local attractions.
Support for various languages and cultural insights.

**Installation**
To get started with Travel Assistant, follow these steps:

**Clone the repository:**
git clone https://github.com/rubyag89/travel-assistant.git
cd TravelAssistant

Install the Gaia Node by running the following command:
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash

Run the following command to update your config.json to run with a small language model:
gaianet init --config https://raw.githubusercontent.com/harishkotra/Gaia-8G/refs/heads/main/config_8g.json

**Start the node:**
gaianet start

**How to Use**
Open your web browser and navigate to the generated link.
Start interacting with the chatbot by typing your travel-related questions (e.g., searching for flights, booking hotels, creating personalized itineraries, or getting recommendations for local attractions).

**License**
This project is licensed under the MIT License. See the LICENSE file for details.
