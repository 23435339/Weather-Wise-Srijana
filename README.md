 🌦️ WeatherWise Template

 📘 Overview
Weather Wise is a Python-based weather forecasting advisor that retrieves real-time weather data through the wttr.in API. It allows users to ask weather-related questions in natural language, view 3-day forecasts, and visualize temperature, rainfall, and wind trends using data-driven charts.
Developed as part of an academic assignment, this project demonstrates modular programming, API integration, data visualization, and AI-assisted development through ChatGPT.

⚙️ Features
* Retrieves accurate 3-day weather forecasts using the wttr.in API
* Displays temperature, rainfall, and wind speed charts using matplotlib
* Accepts natural-language weather questions (e.g., “Will it rain tomorrow?”)
* Performs input validation using pyinputplus for reliable interaction
* Handles API errors and missing data gracefully
* Provides a menu-based interface for simple user navigation

🧠 AI Assistance
AI tools, primarily ChatGPT  were used strategically during development to support:
* Selecting and comparing APIs (wttr.in vs. OpenWeatherMap)
* Designing pseudocode for the parse_weather_question() function
* Simplifying the user interface from widgets to a loop-based menu system
* Fixing Matplotlib blocking issues when displaying charts
The AI-assisted approach ensured that the final design was clear, error-free, and modular while maintaining academic originality.

🧩 Technology Stack
Category	Tools / Libraries
Language	Python 3.x
API	wttr.in (free, no key required)
Data Handling	requests
User Input	pyinputplus
Visualization	matplotlib
AI Support	ChatGPT, 

▶️ How to Run

Clone or download the repository:

Install required libraries:

Run the app: (or open the notebook in JupyterLab / Google Colab)

📊 Data Visualizations
* Temperature Trend Line Chart: Shows min and max daily temperatures
* Precipitation Bar Chart: Displays daily rainfall data
* Wind Speed Chart: Visualizes changes in wind speed over 3 days
* All visualizations are rendered interactively without freezing the menu (non-blocking mode).

📂 Project Structure


ai-conversations
Six-step methodology
ai-conversations 1
ai-conversations 2
ai-conversations 3
ai-conversations 4
ai-conversations 5
before and after example
how-to-log-ai-conversations.txt
resources
ai-tips-tricks.md
assignment-summary.md
before-after-example.md
fetch-my-weather-llm-guide.md
hands-on-ai-llm-guide.md
prompt-by-method-step.md
python-intentional-prompting.md
sample-prompting-journey.md
template-repository-beginners-guide.md
submission
checklist.md
reflection.md
.gitignore
ASSIGNMENT.md
README.md
starter_notebook.ipynb

💡 Future Enhancements
* Add support for multi-word city names (e.g., “New York”)
* Implement a combined temperature–rainfall visualization
* Introduce speech-based input or GUI widgets
* Log all user interactions into a history file for insights

Author: Srijana Panday
Institution: Curtin University, 
 Date: 22 October 2025
 Project: Weather Wise 
