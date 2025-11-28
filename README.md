
<img width="1535" height="546" alt="image" src="https://github.com/user-attachments/assets/9eed665f-8d79-4948-996e-b8acd5768107" />

# Telegram AI Bot

This project is an interactive Telegram bot powered by AI. Users can send messages to the bot, and the AI will respond intelligently.

## Workflow Overview

1. **Telegram Trigger:** Receives messages from the Telegram bot.
2. **AI Agent:** Connected to the Gemini AI model to generate intelligent responses.
3. **Text Cleaning:** Removes extra characters that Telegram bot cannot handle.
4. **Send Response:** Sends the AI-generated text back to the Telegram bot.

## Usage

1. Send a message to the Telegram bot.
2. The AI will process your message and reply with a smart response.

## Running in n8n

1. Import the workflow JSON file into your n8n instance.
2. Configure your credentials:

   * Telegram Bot API token
   * Google Gemini (PaLM) API key
3. Activate the workflow.
4. Send a message to your Telegram bot to start interacting with the AI.

## Notes

* The workflow handles character escaping to prevent Telegram parsing errors.
* Make sure your Telegram Bot API token and Google API credentials are correct.

## Contact

For any questions or further information, you can:

* Send me an email at: [s.ghanavati94@gmail.com](mailto:s.ghanavati94@gmail.com)
* Connect with me on LinkedIn: [Somayeh Ghanavati Nasab](https://www.linkedin.com/in/somayeh-ghanavati-nasab/)

---

Optional: Include screenshots or GIFs showing the bot in action to make the README more engaging.
 action to make the README more engaging.

