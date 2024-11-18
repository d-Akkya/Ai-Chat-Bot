# Ai-AutoReply-ChatBot

This project is a Python-based AI-powered Autoreply Chatbot integrated with OpenAI's API. It is designed to provide automated responses on behalf of users across multiple social media platforms like WhatsApp, Instagram & Facebook. The chatbot uses Natural Language Processing (NLP) to understand and respond in multiple languages, making it ideal for handling customer inquiries, personal interactions & automated messaging.

## 🛠️ Features
- **Platform Integration**: Works seamlessly on WhatsApp, Instagram & Facebook using platform-specific APIs.
- **Multi-Language Support**: Utilizes OpenAI's capabilities to auto-reply in various languages based on user input.
- **Customizable Responses**: Tailor responses according to user needs using OpenAI's prompt engineering.
- **24/7 Availability**: Automates social media interactions, providing quick responses to keep users engaged.
- **Scalable & Secure**: Easy to scale and deploy on cloud services like AWS, ensuring data privacy.

## ⚙️ Technologies Used
- Python
- OpenAI GPT API
- Facebook Graph API
- WhatsApp Business API
- Instagram Graph API
- Flask (for web integration)
- JSON (for storing configurations)

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- OpenAI API Key
- Social media platform API keys (Facebook, WhatsApp, Instagram)

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/d-Akkya/Ai-Chat-Bot.git
   cd Ai-Chat-Bot
   ```
2. **Install the required Python packages**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Set up environment variables**: Create a .env file in the project root with the following:
   ```plaintext
   OPENAI_API_KEY=your_openai_api_key
   FACEBOOK_ACCESS_TOKEN=your_facebook_token
   WHATSAPP_ACCESS_TOKEN=your_whatsapp_token
   INSTAGRAM_ACCESS_TOKEN=your_instagram_token
   ```
### Running the Chatbot
To start the chatbot server, run:
```bash
python 03_bot.py
```
The chatbot will now automatically reply on your connected social media platforms.

## 🔧 Configuration
- **OpenAI API**: Modify the chatbot.py file to adjust prompt settings and response behavior.
- **Platform APIs**: Update access tokens in the .env file to connect with your social media accounts.
- **Language Support**: The chatbot automatically detects the language of incoming messages and replies in the same language.

## 📋 Example Usage
Send a message on WhatsApp or Instagram, and the chatbot will respond based on the context:
- **User**: "Hey, can you help me with my order?"
- **Chatbot**: "Sure! Please provide your order number & I'll check the details for you."

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository, create a branch & submit a pull request.

## 📞 Contact
For any queries or suggestions, please reach out :

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:akhileshbamane26@gmail.com)
   [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/d-akkya/)
         [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://www.instagram.com/d_akkya_007/)
