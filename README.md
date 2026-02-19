# QuestForge ![Build Status](https://img.shields.io/badge/build-passing-brightgreen) ![Version](https://img.shields.io/badge/version-1.0.0-blue)

## Project Description
QuestForge is a web application that empowers game developers to create and manage dynamic quests tailored to player preferences and behaviors. By leveraging AI and advanced data storage, QuestForge enhances player engagement and replayability. The application also features real-time analytics to track player progress and interactions, making it an essential tool for modern game development.

## Features
- 🎮 Dynamic quest generation based on player preferences
- 🤖 Integration of AI-driven NPC dialogues using LangChain
- 📊 Real-time player progress tracking and analytics

## Tech Stack
### Frontend
- React.js

### Backend
- FastAPI
- LangChain

### Database
- QdrantDB
- Pinecone

## Installation
To set up QuestForge locally, follow these steps:

- Clone the repository
bash
git clone https://github.com/arun-kumar-codes/questforge
- Navigate to the project directory
bash
cd questforge
- Install the required dependencies
bash
pip install -r requirements.txt
- Install frontend dependencies
bash
cd frontend
npm install
- Start the backend server
bash
uvicorn main:app --reload
- Start the frontend application
bash
npm start
## Usage
Once the application is running, navigate to `http://localhost:3000` in your web browser to access QuestForge. You can start creating quests and managing player interactions through the intuitive user interface.

## API Documentation
For detailed API documentation, please refer to the [API Documentation](https://github.com/arun-kumar-codes/questforge/wiki/API-Documentation).

## Testing
To run the tests for QuestForge, execute the following command in the project directory:
bash
pytest
## Deployment
For deploying QuestForge, follow these steps:

- Build the frontend application
bash
cd frontend
npm run build
- Deploy the backend using your preferred cloud service (e.g., AWS, Heroku, etc.) and ensure the environment variables are set correctly.

## Contributing
We welcome contributions to QuestForge! Please follow these guidelines:

- Fork the repository
- Create a new branch for your feature or bug fix
- Commit your changes
- Push to your branch
- Open a pull request

For more details, please refer to the [CONTRIBUTING.md](https://github.com/arun-kumar-codes/questforge/blob/main/CONTRIBUTING.md). 

Thank you for your interest in QuestForge! Happy coding! 🚀