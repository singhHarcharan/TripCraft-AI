# AI-Powered Travel Planning Agent

## 🌟 Overview
An intelligent travel planning assistant that helps users plan their trips by considering weather conditions, hotel preferences, and travel dates. The system integrates with various APIs to provide personalized travel recommendations and booking suggestions.

## 🎯 Project Goal
The primary goal of this project is to create an AI-powered travel planning system that simplifies trip planning by automating the process of finding optimal travel dates based on weather conditions, suggesting suitable accommodations, and assisting with travel arrangements.

## ✨ Features

### 1. Intelligent Trip Planning
- Extracts travel details from natural language queries
- Processes complex travel requirements and preferences
- Provides personalized travel recommendations

### 2. Weather-Aware Scheduling
- Suggests optimal travel dates based on preferred weather conditions
- Considers seasonal variations and weather forecasts
- Helps avoid unfavorable weather conditions

### 3. Hotel Recommendations
- Suggests hotels based on user preferences
- Filters accommodations by ratings and amenities
- Considers location and proximity to points of interest

### 4. Travel Arrangement Assistance
- Flight booking suggestions
- Hotel reservation assistance
- Itinerary generation

## 🛠️ Technologies Used

### Core Technologies
- **Python**: Primary programming language for the application
- **OpenAI API**: Powers the natural language understanding and processing capabilities
- **RAG (Retrieval-Augmented Generation)**: For context-aware responses and information retrieval
- **Vector Database**: For efficient storage and retrieval of travel-related data

### API Integration
- **HTTPX**: Modern HTTP client for making API requests to external services
- **Google Generative AI**: For advanced AI capabilities and content generation
- **Weather API**: For fetching and analyzing weather data (as indicated by weather service files)

### Data Management
- **JSON**: For structured data interchange and configuration
- **Python-dotenv**: For secure environment variable management
- **ChromaDB**: Vector database for storing and retrieving contextual information

### Development Tools
- **Git**: Version control and collaboration
- **Pip**: Python package management
- **Environment Variables**: For secure configuration management

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- OpenAI API key
- Required Python packages (install via `pip install -r requirements.txt`)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/trip-planner-agent.git
   cd trip-planner-agent
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env
   # Edit .env and add your API keys
   ```

### Usage
Run the application:
```bash
python app.py
```

## 🤖 How It Works
1. The system processes natural language queries to extract travel details
2. It analyzes weather conditions for the desired destination
3. Suggests optimal travel dates based on preferences
4. Recommends suitable accommodations
5. Assists with booking arrangements

## 📂 Project Structure
```
├── Services/               # Service modules
├── WEATHER_SETUP_SIMPLE.md # Weather service setup guide
├── app.py                 # Main application entry point
├── index.py               # Core functionality implementation
├── requirements.txt       # Python dependencies
└── run.sh                 # Utility script for running the application
```

## 📝 Notes
- The project is currently in development with some features marked for future implementation
- The system is designed to be extensible for additional travel services
- Error handling and input validation are implemented throughout the application

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.