# Virtual Assistants: Jules & Zade

Welcome to the **Jules** and **Zade** virtual assistant repositories! These Python-based virtual assistants provide voice-activated services, including performing web searches, sending emails, playing music, and more.

## Features

Both assistants share a variety of functionalities, such as:

- **Voice Recognition**: Utilize Google’s speech-to-text for command recognition.
- **Web Searching**: Query Wikipedia and open websites like YouTube, Google, and StackOverflow.
- **Email Sending**: Send emails using a Gmail account.
- **System Control**: Execute system-level commands like locking the device, restarting, or shutting down.
- **Entertainment**: Tell jokes, play music, and take photos using the device's camera.
- **Weather Updates**: Fetch weather details for any city (API key setup required).
- **Notes Management**: Write, save, and read notes.

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- Python 3.8 or later
- Required Python libraries (install with `pip`):
  - `pyttsx3`
  - `speechrecognition`
  - `wolframalpha`
  - `wikipedia`
  - `pyjokes`
  - `twilio`
  - `ecapture`
  - `bs4`
  - Other standard libraries (e.g., `os`, `shutil`, `webbrowser`, etc.)

### Installation

1. Clone the repository or download the script files (`Jules.py` and `Zade.py`).
2. Install the required dependencies by running:
   ```bash
   pip install -r requirements.txt
   ```
   *(Note: Create a `requirements.txt` file containing the necessary libraries.)*
3. Set up the required API keys for WolframAlpha, OpenWeather, and Twilio in the respective sections of the code.
4. Update email credentials in the `sendEmail` function securely (e.g., using environment variables).

### Usage

1. Run the desired assistant script:
   ```bash
   python Jules.py
   ```
   or
   ```bash
   python Zade.py
   ```
2. Follow the voice prompts to interact with the assistant.

## File Descriptions

### Jules.py

This script implements the **Jules** assistant, which has:

- A customizable greeting message.
- Integration with multiple APIs for advanced features.
- User-specific commands for controlling music playback, taking notes, and checking the weather.

### Zade.py

This script implements the **Zade** assistant, featuring:

- Similar capabilities to Jules with minor customization differences (e.g., voice settings).
- Flexible responses tailored to the user’s input.

## Customization

Both assistants can be customized to:

- Add more commands and features.
- Integrate with additional APIs.
- Modify the assistant’s voice and responses.

## Contribution

Contributions are welcome! Feel free to fork the repository and submit pull requests for new features or improvements.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

Enjoy using Jules and Zade to simplify your daily tasks!

