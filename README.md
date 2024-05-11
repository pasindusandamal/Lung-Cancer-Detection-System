# Lung Cancer Detection System

This repository contains the code for a lung cancer detection system, which uses machine learning to analyze CT scans to detect signs of lung cancer. The system also assists users in finding top doctors and the nearest medical centers for treatment.

## Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## Features

- **Cancer Detection:** Analyzes CT scans to detect lung cancer.
- **Doctor and Medical Center Database:** Provides details on top doctors and nearest medical centers.
- **Appointment Scheduling:** Enables users to book appointments with specialists.
- **User Interface:** Allows users to upload CT scans and fill out medical details through a user-friendly web interface.

## Installation

Follow these detailed steps to set up the project locally:

### 1. Install Python
   - Ensure Python 3.8 is installed on your system.

### 2. Download and Set Up the Project
   - Clone the project repository from GitHub or download the zip file and extract it to your preferred directory:
     ```bash
     git clone https://github.com/yourusername/lung-cancer-detection-system.git
     cd lung-cancer-detection-system
     ```

### 3. Set Up a Virtual Environment (Optional but Recommended)
   - Open your terminal and execute the following commands:
     ```bash
     python -m venv lung-cancer-env  # Create a virtual environment
     lung-cancer-env\Scripts\activate  # Activate the virtual environment on Windows
     python -m pip install --upgrade pip  # Upgrade pip
     python -m pip install tensorflow  # Install TensorFlow
     pip install Flask Werkzeug Pillow numpy tensorflow flask-mail flask-pymongo  # Install required libraries
     ```

### 4. Start the Flask Application
   - Run the following command from within the project directory to start the Flask server:
     ```bash
     python app.py
     ```

### 5. Access the Web Application
   - Open a web browser and visit `http://localhost:5000` or the port specified in the Flask application.
   - The lung cancer detection system's homepage should load, allowing you to interact with the application.

## Contributing

Contributions to the project are welcome! Please open an issue first to discuss what you would like to change.

Please ensure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
