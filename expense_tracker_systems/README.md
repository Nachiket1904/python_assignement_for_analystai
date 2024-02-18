
# Expense Tracker 💰

A comprehensive Expense Tracker application that allows users to input, categorize, and visualize their daily expenses over time. Built with Streamlit, this app features an intuitive web interface where users can interact with their financial data through various visualization types including pie charts, bar charts, and line charts. The app supports data input and provides insights into spending patterns, aiding users in better financial planning.

## Features

- User-friendly web interface for entering and editing expenses.
- Support for categorizing expenses and detailed descriptions.
- Visualization of spending patterns through pie charts, bar charts, and line charts.
- Ability to emphasize specific expense categories in visualizations.
- Options to download the entered expense data as CSV or Excel files.

## Installation

Ensure you have Python and pip installed on your system before proceeding with the following steps:

1. **Clone the repository**: Clone the project repository to your local machine.

    ```bash
    git clone <repository-url>
    ```

2. **Navigate to the project directory**:

    ```bash
    cd <project-directory>
    ```

3. **Install required Python packages**: Install the Python packages needed for the project, including Streamlit, pandas, numpy, plotly, and pyxlsb.

    ```bash
    pip install streamlit pandas numpy plotly pyxlsb
    ```

## Usage

To run the Expense Tracker app, execute the following command in your terminal from the project directory:

```bash
streamlit run app.py
```

The command starts the Streamlit server and opens the app in your default web browser. Use the sidebar options to input expenses, select visualization types, and download your data.

## Project Structure

- `app.py`: The main application file containing Streamlit app logic.
- `requirements.txt`: A file listing the necessary Python packages for easy installation.


## Future Enhancements

- Integration with databases for persistent storage of expense data.
- Implementation of user authentication to support multiple users.
- Enhanced data analytics features to provide more detailed insights into spending habits.

## Acknowledgements

- Streamlit: For providing an amazing framework to build web apps with ease.
- Plotly: For the versatile plotting library that enables beautiful data visualizations.
- Pandas & Numpy: For powerful data manipulation and analysis.

