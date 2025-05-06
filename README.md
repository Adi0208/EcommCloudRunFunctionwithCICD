Project: Travel Booking via Google Cloud Function & Cloud Run
Description:

This project demonstrates a serverless travel booking system using Google Cloud Functions and Cloud Run. The deployed web service listens for POST requests containing customer travel details (name, origin, destination, date, passengers, trip type). Once a request is received, the backend processes the input and returns a Booking ID along with the submitted data for confirmation.

Key Features:

🌐 Deployed on Google Cloud Run for scalability

⚙️ Triggered using Google Cloud Functions

📩 Accepts and validates JSON-based booking requests

🔐 Secured with Identity Tokens (Bearer Authentication)

📬 Returns Booking ID and travel details as response

Tech Stack:

Google Cloud Platform (Cloud Run, Cloud Functions)

Python/Node.js backend (customizable)

REST API design

JSON data handling
