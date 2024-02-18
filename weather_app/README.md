
# Current Weather Website 🌤️

This project is a simple web application that allows users to check the current weather conditions for any city. It uses the OpenWeatherMap API to fetch weather data and displays it to the user in a friendly and engaging interface.

## Features

- Users can input a city name to retrieve and display current weather conditions.
- Displays weather conditions such as temperature, humidity, pressure, and wind speed.
- Shows different icons based on the current weather condition (e.g., sunny, rain, clouds).
- Responsive design for a great experience on both desktop and mobile devices.

## Technologies Used

- Flask: A micro web framework written in Python.
- OpenWeatherMap API: Provides weather data, including current weather, forecasts, and historical data.
- HTML/CSS: For structuring and styling the web page.
- Requests: A simple, yet elegant HTTP library for making API calls.

## Setup and Installation

### Prerequisites

- Python 3.x
- pip (Python package installer)

### Installation Steps

1. **Clone the repository**: Clone this project to your local machine.

    ```bash
    git clone <repository-url>
    ```

2. **Create a virtual environment** (optional, but recommended):

    ```bash
    python -m venv myenv
    ```

    Activate the virtual environment:

    - On Windows:

        ```bash
        myenv\Scripts\activate
        ```

    - On macOS and Linux:

        ```bash
        source myenv/bin/activate
        ```

3. **Install the requirements**: Navigate to the project directory and install the necessary packages.

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Flask application**:

    ```bash
    python app.py
    ```

    The application will start running on `http://127.0.0.1:5000/`.

## Usage

- Open your web browser and go to `http://127.0.0.1:5000/`.
- Enter a city name in the input field and click "CHECK" to retrieve the weather information.
- The weather information for the requested city will be displayed on the screen.

## Customization

You can customize the application by modifying the HTML/CSS files under the `templates` and `static` directories to change the appearance of the web page.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgements

- OpenWeatherMap API for providing the weather data used in this project.
- Flask for the web framework to build this application.
- Requests library for making API calls.

