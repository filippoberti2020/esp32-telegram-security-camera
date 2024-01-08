# Telegram Security Camera with ESP32 Lilygo T-Camera

Welcome to the Telegram Security Camera project, utilizing the ESP32 Lilygo T-Camera to create a DIY security camera solution with enhanced privacy and trust. This project employs the built-in motion sensor of the ESP32 T-Camera to detect motion and promptly sends a photo notification to your Telegram bot.

## Overview

This project aims to provide a secure alternative to commercial security cameras, offering users the ability to build their own surveillance system with increased privacy. By using the ESP32 Lilygo T-Camera and leveraging its motion sensor capabilities, you can receive instant alerts on your Telegram app whenever motion is detected.

## How it Works

1. **Motion Detection:** The ESP32 T-Camera's built-in motion sensor continuously monitors the surroundings.
2. **Capture Photo:** Upon detecting motion, the camera captures a photo of the area.
3. **Telegram Notification:** The captured photo is then sent as a notification to your configured Telegram bot.

## Features

- **Privacy-Focused:** Build your own security camera to mitigate concerns about privacy.
- **Telegram Integration:** Receive motion alerts directly on your Telegram app.
- **Open Source:** Access and modify the source code for transparency and customization.

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/Telegram-Security-Camera.git
    ```

2. Configure the necessary settings in the code, including your Telegram bot token.

3. Upload the code to your ESP32 Lilygo T-Camera.

4. Power on the camera and monitor motion detection through Telegram notifications.

## Configuration

- Update the relevant settings in the `config.h` file:

```cpp
#define WIFI_SSID "YourWiFiSSID"
#define WIFI_PASSWORD "YourWiFiPassword"
#define TELEGRAM_BOT_TOKEN "YourTelegramBotToken"
#define TELEGRAM_CHAT_ID "YourTelegramChatID"
// ... (other configuration options)
```

## Contributing

If you'd like to contribute or have suggestions, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
