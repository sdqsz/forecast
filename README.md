# Skycast

\<div align="center"\>
\<img src="skycast/images/logo\_icon.ico" alt="Skycast logo" width="120" /\>
\<p\>Your friend to view the weather\</p\>
\<p\>\<a href="[https://t.me/psevdocoders](https://t.me/psevdocoders)"\>💬 Telegram channel\</a\>\</p\>
\</div\>

Skycast is a simple and fast application for viewing weather by coordinates. No data tracking or unnecessary features.

## Table of Contents

  - [Requirements](https://www.google.com/search?q=%23requirements)
  - [Installation](https://www.google.com/search?q=%23installation)
  - [Usage](https://www.google.com/search?q=%23usage)
  - [API](https://www.google.com/search?q=%23api)
  - [GUI Description](https://www.google.com/search?q=%23gui-description)
  - [For Developers](https://www.google.com/search?q=%23for-developers)
  - [License](https://www.google.com/search?q=%23license)
  - [Contacts](https://www.google.com/search?q=%23contacts)

## Requirements

  - Python 3.13+
  - Git
  - Dependencies from `requirements.txt`

## Installation

1.  Install Python: [python.org](https://www.python.org/downloads/).
2.  Clone the repository:
    ```bash
    git clone https://github.com/omniuser209/skycast.git
    cd skycast
    ```
3.  Create and activate a virtual environment:
      - Windows: `python -m venv venv` and `venv\Scripts\activate`
      - Linux/macOS: `python3 -m venv venv` and `source venv/bin/activate`
4.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  Run the application:
    ```bash
    python UI_thread.py
    ```
2.  Enter the coordinates (e.g., `55.7558, 37.6173` for Moscow) in the right panel.
3.  Click "Refresh".
4.  Example result:
      - City: Moscow
      - Temperature: 20°C
      - Weather: Clear
      - Humidity: 60%
      - Wind Speed: 5 m/s

## API

Skycast uses the [Open-Meteo API](https://open-meteo.com/) to retrieve weather data. The parameters used are:

  - latitude, longitude: Coordinates of the location.
  - Data: temperature, humidity, wind speed, weather description.

## GUI Description

### Main Elements:

  - Coordinate input field: For specifying latitude and longitude.
  - Weather display area:
      - City name
      - Current temperature
      - Weather description (clear, cloudy, etc.)
      - Humidity
      - Wind speed
      - Weather icon

### Features:

  - Dark and light themes.
  - Input validation for coordinates.
  - API error handling.
  - Support for two languages: Russian, English.

## For Developers

  - Codestyle: Follow PEP 8.
  - Project Structure:
      - `UI_thread.py`: Main file to run the GUI.
      - `requirements.txt`: List of dependencies.
      - `skycast/images/`: Icons and images.
  - `.gitignore`: Ignores `venv/`, `__pycache__/`, `.env`.
  - Contributing:
    1.  Create a branch: `git checkout -b feature/branch-name`
    2.  Commit your changes: `git commit -m "Added a feature"`
    3.  Push to the branch: `git push origin feature/branch-name`
    4.  Create a Pull Request.

## License

Copyright (c) 2025 [Omniuser209]

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.

Questions and suggestions: [psevdocoders.dev@gmail.com](mailto:psevdocoders.dev@gmail.com)
Telegram: [t.me/psevdocoders](https://t.me/psevdocoders)

*Last updated: 2025-06-04*