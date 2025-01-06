# DriveX-Ritunjaya-Singh-Thakur
# Postman Quiz Tracker

## Overview
The **Postman Quiz Tracker** is a tool designed to track and manage quiz performance for multiple students across different batches. It allows for the collection of student details, quiz scores, feedback, and team information in a structured format, making it easier to analyze quiz data.

## Features
- **Batch Tracking**: Supports tracking of multiple quiz batches, each with detailed timestamps, student performance, and feedback.
- **Student Details**: Stores key student information such as email, name, registration number, and points.
- **Team-based Feedback**: Collects feedback and performance data for each student within a team.
- **Quiz Completion Times**: Tracks the start and completion time of each quiz attempt.
- **JSON Data Storage**: Data is stored in a structured JSON format for easy access and manipulation.

## Instructions for Running Locally

1. **Clone the repository**:
   First, clone this repository to your local machine using Git:
   ```bash
   git clone https://github.com/your-username/project-name.git
   cd project-name
##Challenges Faced During Development
Data Validation: Ensuring that the data input was consistent and valid across multiple quiz batches and students was a challenge. This required implementing validation logic for fields like student names, registration numbers, and timestamps.
Handling Large Data Sets: As more quiz data accumulated, the size of the JSON files grew. Optimizing the data structure to make it scalable for larger sets was important.
Formatting and Feedback Structure: Organizing and displaying feedback in a way that was easy to understand for each student and their team was a challenge. Feedback formatting had to be clear and concise while maintaining detailed insights.
Integration with Postman: Integrating this application with Postman to test the data handling and API responses added complexity to the development process. Ensuring that the application responded correctly to API calls was crucial.
