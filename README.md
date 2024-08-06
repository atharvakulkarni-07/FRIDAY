# Project: Personal Assistant F.R.I.D.A.Y

## Description
F.R.I.D.A.Y is a personal assistant designed to help users manage their tasks, open and close applications, and perform various commands using speech recognition. This project leverages OpenAI's API, speech recognition, and various system commands to create a seamless and interactive user experience.

## Functions

### Command Interpretation
- The `command()` function listens for voice input from the user, processes it using Google's speech recognition service, and returns the interpreted query.
- Handles errors such as unknown values, request errors, and other exceptions gracefully, providing appropriate feedback to the user.

### Voice Response
- The `say(text)` function enables the assistant to respond verbally to the user by converting text to speech.

### Task Management
- The `add_task(task)` function allows users to add tasks to a to-do list, which is then stored in a JSON file.
- The `list_tasks()` function reads tasks from the JSON file and displays them.

### Time and Weather Information
- Provides the current time.
- Retrieves and announces the weather based on the user's location using the OpenWeatherMap API.

### Application Control
- Opens and closes various applications such as Notion, FaceTime, Firefox, App Store, Spotify, WhatsApp, Terminal, and Safari based on voice commands.

## Capabilities
- **Voice Command Execution:** The assistant can execute a wide range of commands through voice recognition, making it highly interactive and user-friendly.
- **Task Management:** Users can manage their daily tasks efficiently by adding and listing tasks via voice commands.
- **Time and Weather Updates:** Users can get real-time updates on the current time and weather conditions.
- **Application Control:** Opens and closes frequently used applications, enhancing productivity and convenience.
