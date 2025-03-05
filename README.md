# Conversational AI Interface  

This repository contains a **Conversational AI Interface** built using **Google Gemini API**, **Speech Recognition**, and **Text-to-Speech (TTS)**. The project enables real-time voice-based interaction with an AI assistant by leveraging **Natural Language Processing (NLP)** and **Generative AI**.  

## 🚀 Features  
- **Speech Recognition**: Converts spoken words into text using **Google Speech-to-Text API**.  
- **Conversational AI**: Utilizes **Google Gemini API** to generate context-aware responses based on user queries.  
- **Text-to-Speech (TTS)**: Converts AI-generated text into human-like speech using `pyttsx3`.  
- **Prompt Engineering**: Implements tailored system prompts to define the chatbot’s behavior, tone, and response structure.  
- **Interactive Voice Assistant**: Allows seamless hands-free communication with the AI.  

## 📌 How It Works  
1. The user speaks into the microphone.  
2. The speech is transcribed into text using the **Speech-to-Text API**.  
3. The transcribed text is processed and sent to **Google Gemini API**, with a structured system prompt to guide the chatbot’s responses.  
4. The AI generates a response considering **context, user intent, and predefined constraints**.  
5. The response is converted to speech and played back to the user using **TTS**.  

## 🛠 Setup Instructions  
### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/conversational-ai-interface.git
cd conversational-ai-interface
