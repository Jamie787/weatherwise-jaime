# 🌦️ WeatherWise - Intelligent Weather Analysis & Advisory System

**Author:** Jaime  
**Course:** Programming Fundamentals  
**Project:** Weather Advisor Application

---

## 📋 Project Overview

WeatherWise is a comprehensive Python application that combines real-time weather data retrieval with natural language processing to create an intelligent weather advisory system. Users can check current weather, view forecasts, analyze weather patterns through visualizations, and ask questions in plain English.

---

## ✨ Features

### Core Functionality
- **Real-Time Weather Data**: Retrieve current conditions for any location worldwide
- **Multi-Day Forecasts**: Get detailed 5-day weather forecasts with hourly breakdowns
- **Data Visualizations**: Professional charts showing temperature trends and precipitation patterns
- **Natural Language Interface**: Ask weather questions in everyday language
- **Intelligent Responses**: Get contextual, helpful answers with actionable advice

### Technical Highlights
- Modular, well-organized code structure
- Comprehensive error handling and input validation
- Professional data visualizations using matplotlib
- Sophisticated NLP using regex patterns and context-aware responses
- Interactive menu system using pyinputplus
- Integration with fetch-my-weather and hands-on-ai packages

---

## 🚀 Getting Started

### Prerequisites

- Python 3.12 or higher
- Google Colab (recommended) or Jupyter Notebook
- Internet connection for weather data retrieval

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Jamie787/weatherwise-jaime.git
   cd weatherwise-jaime
   ```

2. **Install required packages:**
   ```bash
   pip install fetch-my-weather hands-on-ai pyinputplus matplotlib requests
   ```

3. **Open the notebook:**
   - For Google Colab: Upload `weatherwise_complete.ipynb` or `starter_notebook.ipynb`
   - For local Jupyter: Run `jupyter notebook` and open the file

### Quick Start

1. Open the notebook in your environment
2. Run the installation cell to install required packages
3. Execute all cells in order
4. When you reach the "Run the Application" section, execute that cell
5. Follow the interactive prompts to explore weather data!

---

## 📖 Usage Examples

### View Current Weather
```
Select option 1 from the menu
Enter a location (e.g., "London", "New York", "Tokyo")
View detailed current conditions including temperature, humidity, wind, and more
```

### Ask Natural Language Questions
```
Select option 6 from the menu
Ask questions like:
- "Should I bring an umbrella tomorrow?"
- "What's the temperature going to be like this week?"
- "Is it good weather for hiking tomorrow?"
- "Will it rain in Paris this weekend?"
```

### View Visualizations
```
Select options 3-5 to see:
- Temperature trends over the forecast period
- Precipitation chances throughout the day
- Combined dashboard with both metrics
```

---

## 🗂️ Project Structure

```
weatherwise-jaime/
├── weatherwise_complete.ipynb    # Complete implementation
├── starter_notebook.ipynb        # Template with starter code
├── ASSIGNMENT.md                 # Full assignment specification
├── README.md                     # This file
├── ai-conversations/             # AI interaction logs
│   ├── conversation1.txt         # Weather data function development
│   ├── conversation2.txt         # Visualization development
│   ├── conversation3.txt         # NLP implementation
│   ├── conversation4.txt         # UI design
│   ├── conversation5.txt         # Testing and integration
│   └── before-after-example.txt  # Code improvement examples
├── submission/
│   ├── checklist.md             # Submission checklist
│   └── reflection_complete.md   # Project reflection
└── resources/                    # Supporting documentation
    ├── assignment-summary.md
    ├── fetch-my-weather-llm-guide.md
    └── [other guides]
```

---

## 🧪 Testing

The notebook includes comprehensive tests for all components:

1. **Weather Data Retrieval Test**: Validates API integration
2. **Visualization Tests**: Generates sample charts
3. **NLP Tests**: Parses and responds to various question types
4. **Error Handling Tests**: Verifies graceful failure handling
5. **Integration Test**: Exercises complete application workflow

Run all test cells before using the main application to ensure everything works correctly.

---

## 🛠️ Technical Implementation

### Weather Data Component
- Uses `fetch-my-weather` package for API access
- Structures raw API responses into clean dictionaries
- Extracts current conditions, area information, and forecasts
- Includes comprehensive error handling

### Visualization Component
- Creates professional charts using matplotlib
- Temperature visualizations show max, min, and average trends
- Precipitation charts use color coding for risk levels
- Proper date/time formatting for readability

### Natural Language Processing
- Regex-based location extraction
- Dictionary-based attribute and time period identification
- Context-aware response generation
- Optional AI enhancement using hands-on-ai

### User Interface
- Menu-driven interaction using pyinputplus
- Input validation prevents errors
- Clear, organized information display
- Emoji-enhanced visual appeal

---

## 📚 Dependencies

- **fetch-my-weather**: Weather data API wrapper
- **hands-on-ai**: Optional AI conversation enhancement
- **pyinputplus**: Input validation
- **matplotlib**: Data visualization
- **requests**: HTTP requests
- **Standard library**: os, re, datetime, typing

---

## 🎓 Learning Outcomes

This project demonstrates:
- **API Integration**: Working with external weather services
- **Data Visualization**: Creating informative, professional charts
- **Natural Language Processing**: Parsing and understanding user intent
- **User Interface Design**: Building intuitive interactions
- **Error Handling**: Anticipating and managing edge cases
- **Code Organization**: Structuring maintainable, modular code
- **AI Collaboration**: Effective use of AI development tools

---

## 🤝 AI Development Process

This project was developed with extensive AI assistance, documented in the `ai-conversations/` folder. The development process demonstrates:

- Intentional prompting techniques
- Iterative refinement of code
- Strategic use of AI for learning and development
- Critical evaluation of AI-generated solutions
- Before-after comparisons showing code improvement

See the `before-after-example.txt` for detailed examples of how intentional prompting improved code quality.

---

## 📝 Assignment Requirements

✅ All core requirements completed:
- Weather data retrieval with 5-day forecast
- Two data visualizations (temperature and precipitation)
- Natural language question parsing and response generation
- User-friendly menu interface
- Comprehensive error handling
- Well-documented, modular code

✅ Intentional AI prompting documented:
- 5 detailed conversation logs
- Before-after code examples
- Reflection on AI development process

---

## 🔮 Future Enhancements

Potential improvements for future versions:
- Historical weather data analysis
- Weather alerts and notifications
- Location-based activity recommendations
- Multi-location comparison features
- Custom visualization themes
- Integration with calendar applications
- Weather-based outfit suggestions

---

## 📄 License

This project was created as a course assignment for educational purposes.

---

## 👤 Author

**Jaime**  
Programming Fundamentals Student  
October 2025

---

## 🙏 Acknowledgments

- **fetch-my-weather package**: Simplified weather data access
- **wttr.in service**: Underlying weather data provider
- **AI Development Tools**: Claude AI for development assistance
- **Course Instructor**: For comprehensive assignment design and support

---

## 📧 Contact

For questions or feedback about this project, please refer to the course LMS or GitHub repository issues.

---

**⭐ If you found this project helpful, please consider giving it a star on GitHub!**
