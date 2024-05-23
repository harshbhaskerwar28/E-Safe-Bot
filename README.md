# 🚨 Emergency_Chat_Bot

Welcome to **Emergency_Chat_Bot**! This intelligent Telegram bot is designed to assist users during emergencies by quickly gathering crucial information and notifying relevant authorities. Whether it's a medical emergency, a crime, or a fire, Emergence_Chat_Bot is here to help!

## 🌟 Features

- **Intelligent Emergency Detection**: Automatically understands and categorizes emergencies using NLP.
- **Location Tracking**: Captures and processes user location data to provide precise assistance.
- **Image Upload**: Allows users to upload images related to the emergency.
- **Prompt and Accurate Responses**: Uses AI to provide friendly, detailed, and engaging responses.
- **Admin Notification**: Sends detailed emergency information to administrators.

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- Telegram Bot Token
- Gemini API Token
- Admin Chat ID

### Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/harshbhaskerwar28/Emergency_Chat_Bot.git
    cd Emergence_Chat_Bot
    ```

2. **Install the required dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Set up environment variables**:
    Create a `.env` file in the project directory with the following content:
    ```env
    TELEGRAM_BOT_TOKEN=your_telegram_bot_token
    GEMINI_API_TOKEN=your_gemini_api_token
    ADMIN_CHAT_ID=your_admin_chat_id
    ```

### Running the Bot

Start the bot by executing : python app.py


## 🛠️ Usage

1. **Start the Bot**: Send `/start` to initiate the bot.
2. **Select Emergency Type**: Choose the type of emergency or describe your situation.
3. **Share Location**: Allow the bot to access your location for precise assistance.
4. **Upload Images**: Provide images related to the emergency if available.
5. **Additional Information**: Add any extra details if necessary.

## 📦 Project Structure

- `app.py`: Main script containing the bot logic.
- `requirements.txt`: List of dependencies.
- `.env`: File to store environment variables (not included in the repository).

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## 💡 Inspiration

Emergence_Chat_Bot is inspired by the need for quick and efficient emergency response systems that leverage modern AI and NLP technologies to save lives.

## 🙌 Contributions

We welcome contributions! Feel free to submit issues or pull requests.
