# AI-Powered Learning Companion (AILC) Setup Guide

## Overview

This documentation provides an overview of the initial setup for the AI-Powered Learning Companion (AILC), an intelligent platform leveraging large language models to enhance educational experiences. The document guides you through creating a minimal Python-based application using the Flask framework to interact with OpenAI's language models.

## Project Structure

The project is structured as follows:

- **`AI_Learning_Companion/`**: Main project directory
  - **`app.py`**: The main Python application file, establishing a web interface using Flask.
  - **`requirements.txt`**: List of required Python packages needed to run the application.
  - **`templates/`**: Directory containing HTML templates for the web interface.
    - **`index.html`**: Main HTML page for user interaction.
  - **`static/`**: Directory for static files like CSS.
    - **`style.css`**: Stylesheet to add basic styling to the HTML interface.

## Key Components

1. **Flask Application (`app.py`)**:
   - Sets up a basic web application to handle user requests and interface with the OpenAI language model.
   - Uses the Flask framework to create routes and render HTML templates.
   - Interacts with OpenAI's API to generate responses based on user input.

2. **HTML Template (`index.html`)**:
   - Provides a simple user interface where students can input questions and receive AI-generated responses.
   - Integrated with JavaScript for asynchronous form submission and response display.

3. **Stylesheet (`style.css`)**:
   - Adds basic styling to make the web interface more user-friendly and visually appealing.

## Getting Started

### Prerequisites

- Ensure that Python is installed on your system. The application is developed in Python, so a compatible Python environment is necessary.
- Set up an OpenAI account and acquire an API key to interact with their language model services.

### Installation

1. **Clone the Repository**:
   Place the project files in a directory named `AI_Learning_Companion` or create it manually and populate it with the provided structure.

2. **Install Required Packages**:
   Navigate to the project directory and install the necessary Python packages using:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set OpenAI API Key**:
   Export your OpenAI API key as an environment variable:
   ```bash
   export OPENAI_API_KEY='your-api-key-here'
   ```

4. **Run the Flask Application**:
   Start the Flask application by executing:
   ```bash
   python app.py
   ```

5. **Access the Web Interface**:
   Visit `http://127.0.0.1:5000/` in your web browser to interact with the AI-powered learning companion.

## Future Enhancements

The initial setup can be expanded with additional features and functionality, including:

- User authentication for personalized experiences.
- Comprehensive analytics to track student progress.
- Support for multimedia and advanced content delivery.
- Integration with educational platforms and tools.

## Summary

This guide outlines a basic web-based application for the AI-Powered Learning Companion, using Flask and large language models as a backend service. Feel free to enhance and build upon this foundation to add sophisticated educational features.
