# Citizen Services AI Chatbot

## Project Overview
A conversational AI assistant designed to help citizens access government services and information through natural language interactions. Built with Node.js and Gemini AI technologies.

## Key Features
- Natural language processing for citizen queries
- Multi-lingual support
- Integration with government service APIs
- Secure authentication
- Analytics dashboard

## Installation
```bash
git clone https://github.com/Ayush12708/Citizen_Services_ai_chatbot.git
cd Citizen_Services_ai_chatbot
npm install
```

## Configuration
1. Create `.env` file:
```env
API_KEY=your_gemini_api_key
PORT=3000
```

## Usage
Start the development server:
```bash
npm start
```

Access the chatbot at:
`http://localhost:3000`

## API Endpoints
| Endpoint | Method | Description |
|----------|--------|-------------|
| `/api/chat` | POST | Process user queries |
| `/api/services` | GET | List available services |

## Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request
