# Voice Assistant

This is a simple voice assistant program written in Python that recognizes voice commands and performs various tasks.

## Features

- Plays music from a predefined directory.
- Opens YouTube, Google, TikTok, and other websites.
- Provides current time.
- Performs web search.

## Prerequisites

Before running the program, make sure you have the following libraries installed:
- `pyaudio`
- `speech_recognition`
- `psutil`
- `pygame`

You can install these libraries via pip:

## Usage

To use the voice assistant, run the script. It will listen for voice commands and perform the associated actions.

### Voice Commands

- **"бот"** or **"помоги"**: Activates the assistant.
- **"стоп"** or **"выключись"**: Stops the assistant.
- **"время"**: Provides the current time.
- **"YouTube"**, **"Ютуб"**, **"ютубчик"**: Opens YouTube.
- **"Google"**, **"Гугл"**: Opens Google.
- **"TikTok"**, **"тикток"**, **"тики таки"**: Opens TikTok.
- **"закрой браузер"** or **"закрой browser"**: Closes the browser.
- **"Telegram"**, **"телеграм"**: Opens Telegram.
- **"Steam"**, **"стим"**: Opens Steam.
- **"task manager"** or **"диспечер задач"**: Opens Task Manager.
- **"проводник"**: Opens File Explorer.
- **"загугли мне"**, **"поиск в интернете"**, **"найти"**: Performs a web search.
- **"музыка"**, **"музыку"**, **"включи музыку"**: Plays music.
- **"выключи музыку"**: Stops playing music.

## Customization

You can customize the voice commands and their associated actions by modifying the `commands_list` dictionary in the code.

## Note

This README assumes you're using the Russian language ("ru-RU") for speech recognition.

