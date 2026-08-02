# 🤖 Project-3-My-First-LLM-Powered-Telegram-Chatbot-using-n8n
Welcome to my first AI-powered Telegram chatbot, built entirely with an n8n workflow! <br>
The bot supports both text and voice messages. Simply send it a question, and it will use a large language model (LLM) to generate a response directly within Telegram. <br>

## ✨ Features
<ul>
  <li>💬 Chat with an LLM through Telegram</li>
  <li>🎤 Voice message support</li>
  <li>📝 Text message support</li>
  <li>⚡ Automated with n8n</li>
  <li>🤖 AI-generated responses in real time</li>
</ul>
<br>

## ⚙ How it works
<ol>
  <li>First a Telegram trigger node receives the user message.</li>
  <li>A switch node sends text messages directly to the AI agent, and voice messages to Whisper, a speech-to-text model, 
      which transcribes the recording and sends the result to the AI agent.</li>
  <li>Finally, The agent generates a response to the query, and sends it back to the user.</li>
</ol>
 
<br>

<img width="1241" height="419" alt="Workflow" src="https://github.com/user-attachments/assets/68d036a5-d9a1-4c6d-a96a-89c53dca1729" />



## 🚀 Try it yourself
You can chat with the bot here:<br>
[@hamouns_first_telegram_chat_bot](https://t.me/hamouns_first_telegram_chat_bot)
<br>
Whether you type a message or send a voice note, the bot will understand your request and reply just like a modern AI assistant.
