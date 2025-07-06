# API-INTEGRATION-AND-DATA-VISUALIZATION
COMPANY : CODTECH IT SOLUTIONS

NAME : MAYANK RAJ

INTERN ID :CT06DF1345

DOMAIN : PYTHON PROGRAMMING

DURATION : 6 WEEKS

MENTOR : NEELA SANTOSH





# **🌦️ WeatherSnap – Real-Time Multi-City Weather Dashboard using Python and Seaborn**

---

## 🔍 **Project Overview**

**WeatherSnap** is a Python-based project that fetches and visualizes real-time temperature data from multiple global cities using the OpenWeatherMap API. The main objective of this project is to demonstrate the integration of live data from public APIs with Python programming and to present the data visually using powerful data visualization libraries such as Seaborn and Matplotlib.

This project is ideal for students, developers, and data enthusiasts who are interested in working with real-world data, creating dashboards, or learning how to work with APIs. It’s a simple, yet effective tool that highlights how live weather data can be processed and displayed for easy interpretation.

---

## ⚙️ **How It Works**

The project begins by defining a list of cities such as New York, London, Tokyo, Delhi, Sydney, Ranchi, and others. For each city, the program makes a request to the OpenWeatherMap API, retrieves the current weather information, and extracts the temperature in Celsius from the JSON response.

The extracted data is then stored in Python lists and visualized using the Seaborn library. A bar chart is generated to compare the temperatures across different cities. The chart is color-coded using the `coolwarm` color palette, making it easy to distinguish between cooler and warmer locations. The final chart is both displayed and saved as an image file (`weather_dashboard.png`) for sharing or documentation purposes.

---

## 🛠️ **Tools and Libraries Used**

The following tools and libraries are used to build this project:

* **Programming Language**: Python 3
* **API Service**: OpenWeatherMap ([https://openweathermap.org/](https://openweathermap.org/))
* **Python Libraries**:

  * `requests` – for making HTTP API calls and handling responses
  * `matplotlib` – for generating visual plots
  * `seaborn` – for improved and styled data visualization

All libraries used are open-source and widely adopted in the Python data science ecosystem.

---

## 💡 **Applications**

This project has several real-world and academic applications. It can be used as:

* An **educational tool** to demonstrate API integration and data visualization.
* A **portfolio project** to showcase Python skills involving live data processing and presentation.
* A **base model** for a more advanced real-time weather dashboard or a web app using frameworks like Streamlit or Flask.
* A quick tool to **monitor and compare** current weather across multiple locations for travelers or researchers.

With added features like humidity, wind speed, or forecast trends, this project can be extended into a full-scale analytics tool or weather-monitoring system.

---

## ▶️ **How to Use**

1. Clone or download the repository.
2. Install the required Python libraries using pip:

   ```
   pip install requests matplotlib seaborn
   ```
3. Sign up at [OpenWeatherMap](https://openweathermap.org/api) and get a free API key.
4. Replace the placeholder in the code with your actual API key.
5. Run the Python script:

   ```
   python weather_dashboard.py
   ```
6. The script will display temperature values in the console and generate a bar chart showing the comparison.

---

## ✅ **Conclusion**

WeatherSnap is a lightweight but powerful project that clearly demonstrates the use of live APIs, data extraction, and visualization in Python. It’s easy to set up, beginner-friendly, and highly customizable. Whether you're a student learning Python or a developer exploring API data pipelines, WeatherSnap is a valuable and practical project to build and showcase.


