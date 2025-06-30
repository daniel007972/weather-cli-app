# Weather CLI App ☀️🌧️

Welcome to the Weather CLI App, a simple yet powerful command-line application built in Python. This app fetches and displays real-time weather data using the OpenWeatherMap API. Whether you want to check the weather by city name or zip code, this tool has you covered. You can also save your favorite locations, reload your last search, and manage your saved locations effortlessly.

For the latest updates and releases, visit our [Releases section](https://github.com/daniel007972/weather-cli-app/releases).

---

## 🔧 Features

- 🌆 **Search Weather**: Get current weather data by **City Name** or **Zip Code**.
- 📊 **Weather Details**: View essential information including **Temperature**, **Feels Like**, **Humidity**, and **Conditions**.
- ⭐ **Favorites**: Save your favorite locations for quick access.
- 📂 **Last Search**: Easily reload the last searched location.
- ❌ **Delete Favorites**: Remove any saved location whenever you want.
- 🧠 **Smart Error Handling**: The app uses JSON and text files for data persistence and handles errors gracefully.

---

## ▶️ How to Run

To get started with the Weather CLI App, follow these steps:

### 1. Clone the Repository

Open your terminal and run the following commands:

```bash
git clone https://github.com/your-username/weather-cli-app.git
cd weather-cli-app
```

### 2. Set Up Your API Key

To access weather data, you need an API key from OpenWeatherMap. Follow these steps:

- Open `config.py`.
- Replace `None` with your OpenWeatherMap API key:

```python
def get_api_key():
    return "your_api_key_here"
```

### 3. (Optional) Set Units

You can customize the units of measurement. In the same `config.py` file, set the units to `"imperial"` for Fahrenheit or `"metric"` for Celsius.

### 4. Run the Application

Once you have set up the API key, you can run the application:

```bash
python main.py
```

---

## 📦 Installation

To install the necessary packages, you can use `pip`. Make sure you have Python 3 installed on your system.

```bash
pip install requests
```

This command will install the `requests` library, which the application uses to make API calls.

---

## 🛠️ Usage

After running the application, you can interact with it via the command line. Here are some commands you can use:

1. **Search by City Name**: Type the city name and hit enter.
2. **Search by Zip Code**: Type the zip code and hit enter.
3. **View Favorites**: Type `favorites` to see your saved locations.
4. **Reload Last Search**: Type `reload` to fetch the last searched weather data.
5. **Delete Favorite**: Type `delete <location>` to remove a saved location.

---

## 📄 Configuration

The configuration for the app is straightforward. You can modify the following settings in the `config.py` file:

- **API Key**: Your OpenWeatherMap API key.
- **Units**: Set the units to either `"imperial"` or `"metric"` based on your preference.

---

## 🌐 API Information

This application uses the OpenWeatherMap API to fetch weather data. You can find more information about the API and how to obtain your API key on the [OpenWeatherMap website](https://openweathermap.org/).

### API Endpoints

The main endpoint used in this application is:

```
https://api.openweathermap.org/data/2.5/weather
```

You will need to append your query parameters, including your API key, city name, or zip code.

---

## 📂 File Structure

Here’s a brief overview of the file structure of the Weather CLI App:

```
weather-cli-app/
│
├── main.py            # Main application file
├── config.py          # Configuration file for API key and settings
├── requirements.txt    # List of required packages
└── README.md          # This documentation
```

---

## 📖 Example Output

When you run the application and search for a city, the output will look something like this:

```
Weather in London:
Temperature: 15°C
Feels Like: 14°C
Humidity: 80%
Conditions: Cloudy
```

You can see how easy it is to get the weather information you need.

---

## 🔄 Error Handling

The app includes basic error handling. If you enter an invalid city name or zip code, the application will notify you with a clear message. 

Example:

```
Error: City not found. Please check the name and try again.
```

This ensures that you can easily troubleshoot any issues that arise.

---

## 📥 Contributing

Contributions are welcome! If you would like to improve the Weather CLI App, feel free to fork the repository and submit a pull request. Here are some ways you can contribute:

- Fix bugs
- Add new features
- Improve documentation

Before contributing, please make sure to read the [Contributing Guidelines](CONTRIBUTING.md).

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## 🌟 Acknowledgments

- Thanks to [OpenWeatherMap](https://openweathermap.org/) for providing the weather data API.
- Thanks to all contributors who help make this project better.

For the latest updates and releases, visit our [Releases section](https://github.com/daniel007972/weather-cli-app/releases).

---

## 🛠️ Topics

This project covers various topics, including:

- API
- CLI
- File I/O
- JSON
- OpenWeatherMap
- Project
- Portfolio
- Python
- Python 3
- Terminal App
- Weather

---

Thank you for checking out the Weather CLI App! We hope you find it useful for your weather needs.