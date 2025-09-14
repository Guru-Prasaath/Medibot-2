Synapse Health AI - Medical Chatbot
Synapse Health AI is a modern, responsive, and intelligent medical chatbot designed to provide preliminary health information and guidance. It leverages a powerful Large Language Model (LLM) to offer dynamic, context-aware conversations in a clean, user-friendly interface inspired by ChatGPT.

This project is built as a single, self-contained HTML file, making it incredibly portable and easy to run without any complex setup or server-side dependencies.

✨ Features
Intelligent Conversations: Powered by Google's Gemini LLM for natural and informative responses to a wide range of health queries.

Safety First: A carefully crafted system prompt instructs the AI to prioritize user safety, provide medical disclaimers, and recognize emergency symptoms.

Modern UI/UX: A clean, minimalist interface that is both beautiful and intuitive.

Light & Dark Mode: A theme toggle allows users to switch between light and dark modes for comfortable viewing. The user's preference is saved in their browser.

Markdown Support: AI responses are rendered with proper formatting (bold, lists, etc.) for enhanced readability, powered by marked.js.

Conversation Management: Easily start a new chat session with the "New Chat" button, clearing the current conversation.

Copy to Clipboard: Conveniently copy the AI's response with a single click.

Responsive Design: The layout is fully responsive and works seamlessly on desktops, tablets, and mobile devices.

Welcome Screen: A friendly welcome screen greets the user and provides quick-start suggestion prompts.

Zero Dependencies: The entire application runs directly in the browser. No installation or build steps are required.

🛠️ Technology Stack
Frontend: HTML5, Vanilla JavaScript

Styling: Tailwind CSS for a utility-first styling workflow.

AI Engine: Google Gemini API (gemini-2.5-flash-preview-05-20 model).

Markdown Parsing: marked.js library to render AI responses with rich formatting.

🚀 How to Run
This project is designed for simplicity.

Download the File: Save the medical_chatbot.html file to your local machine.

Open in Browser: Open the file with any modern web browser (e.g., Google Chrome, Mozilla Firefox, Microsoft Edge).

That's it! The chatbot will be fully functional.

Note on API Key: The apiKey variable in the JavaScript code is intentionally left as an empty string (""). In many online development environments (like the one this was built in), the API key is automatically provided at runtime. If you are running this file in a local environment where this is not the case, you will need to obtain your own Google Gemini API key and place it within the quotes.

📜 Ethical Considerations & Disclaimer
This application is for informational purposes only and is not a substitute for professional medical advice, diagnosis, or treatment.

The AI is explicitly instructed via a system prompt to attach a disclaimer to all medical-related advice.

It is programmed to recognize keywords indicating a medical emergency and will advise the user to contact emergency services immediately.

Users are reminded in the UI that the AI can make mistakes and important information should be verified.

