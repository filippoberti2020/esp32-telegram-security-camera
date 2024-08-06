# Telegram Security Camera with ESP32 Lilygo T-Camera

Welcome to the Telegram Security Camera project, utilizing the ESP32 Lilygo T-Camera to create a DIY security camera solution with enhanced privacy and trust. This project employs the built-in motion sensor of the ESP32 T-Camera to detect motion and promptly sends a photo notification to your Telegram bot.

![Alt text](https://img.addel.hu/termekfotok/348/fhdfotok/lilygo_t-camera_esp32-wrover-b_camera_modul_v1.7_1jhc9j.jpg)


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
    git clone https://github.com/filippoberti2020/esp32-telegram-security-camera.git
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

## Obtain your Telegram User ID and Bot Token:

### Telegram User ID:

In your Telegram account, search for "IDBot" or open [this link](https://t.me/myidbot) on your smartphone. Start a conversation with the bot and type `/getid`. You will receive a reply back with your user ID. Save that user ID, as you'll need it later in this tutorial.

### Telegram Bot Token:

Open Telegram and follow these steps to create a Telegram Bot. First, search for "botfather" and click on BotFather. Or open [this link](https://t.me/botfather) on your smartphone. Type `/newbot` and follow the instructions to create your bot, giving it a name and username. Once created, you'll receive a message with a link to access the bot and the bot token. Save the bot token, as it will be used for ESP32 interaction with the bot.


## Contributing

If you'd like to contribute or have suggestions, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
