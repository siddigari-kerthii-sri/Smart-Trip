# Smart Trip – AI-Powered Travel Planner

**Live Demo:** https://smart-trip-q7gc.onrender.com

## Application Preview

![Smart Trip Application Preview](smart-trip.PNG)

Smart Trip is a full-stack travel planning application that helps users plan and manage trips based on their destinations, travel preferences, and budgets. It integrates Groq's Llama 3.1 model to generate AI-powered travel recommendations and provides tools to organize trip details in one place.

## Features

- **User Authentication:** Register and log in to manage trips.
- **Trip Management:** Create, view, and manage travel plans.
- **AI-Powered Recommendations:** Generate travel suggestions using the Groq API and Llama 3.1.
- **Budget Planning:** Calculate and manage trip budgets using application logic.
- **Shareable Trips:** Generate token-based links to share trip details.
- **Reliable AI Responses:** Validate AI-generated JSON responses and use fallback handling when needed.

## Tech Stack

| Category | Technologies |
|---|---|
| Backend | Python, Flask |
| Frontend | JavaScript, HTML, CSS, Tailwind CSS |
| Database | MySQL |
| Database Hosting | Aiven |
| AI Integration | Groq API, Llama 3.1 (8B Instant) |
| Deployment | Render |

## Project Structure

```text
Smart-Trip/
├── app.py
├── auth.py
├── trips.py
├── recommendations.py
├── smarttrip.sql
├── templates/
├── static/
└── requirements.txt
```

## How It Works

1. Users sign up or log in to access the application.
2. Users create and manage their travel plans.
3. The application processes trip details and budget information.
4. The AI recommendation module uses Groq's Llama 3.1 model to generate travel suggestions.
5. Generated responses are validated, with fallback handling for unexpected responses.
6. Users can share their trips through token-based links.

## Key Highlights

- Integrated a Large Language Model into a full-stack web application.
- Implemented structured AI response validation and fallback handling.
- Used MySQL for persistent trip data storage.
- Separated AI-based recommendations from rule-based budget calculations.
- Deployed the application using Render.

## Future Improvements

- Add more detailed destination recommendations.
- Improve trip customization and itinerary management.
- Enhance the user experience with additional planning features.

---

**Built with Python, Flask, MySQL, JavaScript, and Groq AI.**
