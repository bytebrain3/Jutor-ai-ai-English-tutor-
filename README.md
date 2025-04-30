# Jutor AI - English Language Tutor

Jutor AI is an interactive English language learning application that helps users improve their English grammar and writing skills. It uses Google's Gemini AI model to analyze and correct English sentences, providing detailed explanations for grammar rules and corrections.

## Features

- **Grammar Checking**: Analyzes English sentences for grammatical errors
- **Interactive Learning**: Provides detailed explanations for grammar corrections
- **User Authentication**: Secure login and signup system using Firebase
- **Chat Interface**: Clean and intuitive chat-based interface
- **Theme Support**: Light and dark theme options
- **Message History**: Saves conversation history using Firebase database
- **Email Verification**: Secure email verification system

## How It Works

1. **AI Integration**: The application uses Google's Gemini AI model to analyze English sentences
2. **Grammar Analysis**: When a user submits a sentence, the AI:
   - Checks for grammatical errors
   - Provides corrections if needed
   - Explains the grammar rules involved
3. **User Interface**: Built with KivyMD framework, providing a modern and responsive UI
4. **Data Storage**: Uses Firebase for:
   - User authentication
   - Storing conversation history
   - User profile management

## Use Cases

1. **Language Learning**: Students can practice English grammar and get instant feedback
2. **Writing Improvement**: Writers can check their sentences for grammatical accuracy
3. **ESL Education**: English as a Second Language learners can improve their skills
4. **Professional Development**: Professionals can refine their business communication
5. **Academic Writing**: Students can improve their academic writing skills

## Technical Requirements

- Python 3
- KivyMD framework
- Firebase Admin SDK
- Google Gemini AI API
- Required Python packages:
  - kivy
  - kivymd
  - firebase-admin
  - google-generativeai
  - requests
  - pickle

## Setup Instructions

1. Clone the repository
2. Install required dependencies:
   ```bash
   pip install kivy kivymd firebase-admin google-generativeai requests
   ```
3. Set up Firebase:
   - Create a Firebase project
   - Download the service account key (chatapp1.json)
   - Update the Firebase database URL in the code
4. Configure Gemini AI:
   - Get your Gemini API key
   - Update the API key in the code
5. Run the application:
   ```bash
   python main.py
   ```

## Security Features

- Secure user authentication
- Email verification system
- Encrypted password storage
- Secure API key management

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Google Gemini AI
- Firebase
- KivyMD framework
