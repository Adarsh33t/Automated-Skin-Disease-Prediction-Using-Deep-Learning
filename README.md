# Automated-Skin-Disease-Prediction-Using-Deep-Learning


This project is a web-based application that utilizes deep learning to predict skin diseases from images. It offers a user-friendly interface for users to upload images of skin conditions, receive predictions, and access additional features like disease information, chat support, and doctor recommendations.

## Table of Contents

- [Introduction](#introduction)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Skin diseases can often be difficult to diagnose accurately, and a misdiagnosis can lead to serious health issues. This project aims to provide a reliable tool for both users and healthcare professionals to identify and understand various skin conditions.

## Tech Stack

The project is built using the following technologies:

- HTML and CSS for the user interface.
- MySQL for the database to store user data.
- Django for the backend framework.
- Python for the core logic and machine learning.
- JavaScript for frontend interactivity.
- Deep Learning with TensorFlow for skin disease prediction.
- Numpy for data manipulation.

## Features

- **Accurate Disease Prediction:** The deep learning model achieves an impressive accuracy of 97.05% with a validation accuracy of 91.17%, ensuring reliable disease predictions.

- **User Authentication:** Users can create accounts, log in, and securely store their data.

- **Disease Information:** Users can access comprehensive information about various skin diseases to better understand their condition.

- **Chat Support:** Users can engage in real-time chat support with healthcare professionals or community members for guidance and support.

- **Doctor Recommendations:** Based on the prediction results, users can receive recommendations to consult a doctor or specialist.

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/skin-disease-prediction.git
   ```

2. Create a virtual environment:

   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

4. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

5. Configure the database settings in `settings.py` to connect to your MySQL database.

6. Run migrations:

   ```bash
   python manage.py migrate
   ```

7. Create a superuser for admin access:

   ```bash
   python manage.py createsuperuser
   ```

8. Start the development server:

   ```bash
   python manage.py runserver
   ```

9. Access the application in your web browser at `http://localhost:8000`.

## Usage

1. Register for an account or log in if you already have one.
2. Upload an image of the skin condition you want to diagnose.
3. Receive a prediction for the skin disease.
4. Explore disease information, chat with healthcare professionals or community members, and receive doctor recommendations as needed.

