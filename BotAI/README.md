# BotAI: Building a Chatbot with NLTK

BotAI is a chatbot implemented in Python using the NLTK library for natural language processing. It can respond to user queries, schedule appointments, cancel appointments, and show scheduled appointments.

## Features

- **Greeting:** BotAI responds to greetings such as "hi", "hello", "hey", and "greetings".
- **About:** Users can ask about the chatbot, such as "What is your name?" or "Tell me about yourself".
- **Time:** BotAI can tell the current time when asked, e.g., "What time is it?" or "Can you tell me the time?".
- **Appointment Scheduling:** Users can schedule appointments by providing subject, time, and date.
- **Appointment Cancellation:** Users can cancel scheduled appointments.
- **Show Appointments:** BotAI can show all scheduled appointments.

## Usage

1. **Installation:**
   - Clone this repository.
   - Install the required dependencies using `pip install -r requirements.txt`.

2. **Running the Chatbot:**
   - Run `python botai.py` to start the chatbot.
   - Follow the on-screen prompts to interact with BotAI.

## Example Interactions

- **User:** hi
  - **BotAI:** Hello!
  - **BotAI:** How can I assist you today?

- **User:** What is your name?
  - **BotAI:** I'm BotAI, your personal assistant.

- **User:** Can you tell me the time?
  - **BotAI:** It's [current time].

- **User:** Schedule an appointment for a meeting at 3:00 PM tomorrow.
  - **BotAI:** What is the subject of the appointment?
  - **User:** Meeting
  - **BotAI:** When is the appointment? (e.g., 9:00 AM)
  - **User:** 3:00 PM
  - **BotAI:** What is the date of the appointment? (e.g., May 5th)
  - **User:** Tomorrow
  - **BotAI:** Your appointment for Meeting is scheduled for 3:00 PM on [Tomorrow's date].

- **User:** Cancel appointment for Meeting.
  - **BotAI:** Appointment for Meeting cancelled.

- **User:** Show my appointments.
  - **BotAI:** Your scheduled appointments are:
    - Meeting: 3:00 PM on [Tomorrow's date]

## Contribution

Contributions are welcome! Feel free to submit bug reports, feature requests, or pull requests to improve BotAI.
