# Wordpress-Ai-Chatbot
# 💪 WordPress AI Chatbot (lightweight Ai chatbot)

A modern, fully customizable AI chatbot widget for WordPress, built as a single HTML file. This chatbot supports LLMs via [OpenRouter.ai](https://openrouter.ai), and is designed to be easy to use, embed, and configure within any WordPress site using the Code Snippets plugin or theme editor.


# 📷 UI Previews

| Theme  | Preview |
|--------|---------|
|  Orange  | Orange Chatbot UI <img width="3840" height="2160" alt="orange ui" src="https://github.com/user-attachments/assets/9968fd7e-97d2-4f07-a8aa-54f1626ee109" />|
|Navy Blue   | Navy Blue Chatbot UI <img width="2560" height="1440" alt="blue ui" src="https://github.com/user-attachments/assets/e1483142-0c45-4cd2-b34b-6fc8fc5f5013" />|
|Green (Dark Mode)   | Green (night mode) Chatbot UI <img width="2560" height="1440" alt="green black" src="https://github.com/user-attachments/assets/363da8b7-ef21-4801-8c9d-4dc78785aad2" />|

Lightweight HTML-based AI assistant widget for WordPress. Compatible with OpenRouter API, customizable prompts, and visual themes included.

--------
## ✨ Features

- 🧠 Powered by any OpenRouter-compatible LLM
- 🪄 Built-in system prompt customization
- 🎨 Three color themes: **Orange** ,**Navy Blue** and **green(Dark Mode).
- 📄 Supports text and image uploads
- 💡 Zero JavaScript conflicts (WordPress-safe)
- 🧩 Easily embeddable with a single HTML snippet



---

## 🚀 How to Use in WordPress

1. **Install the [Code Snippets](https://wordpress.org/plugins/code-snippets/) plugin** (or use your theme's custom HTML block).
2. **Open the chatbot `.html` file** (either green or blue version) in VS Code or any editor.
3. Copy the entire code and **paste it into a new HTML snippet** in WordPress.
4. Save and activate the snippet.

---

## 🔧 Configuration

In the HTML file, locate the `WP_CHATBOT_CONFIG` section inside the JavaScript code:

```js
const WP_CHATBOT_CONFIG = {
  OPENROUTER_API_KEY: "YOUR_OPENROUTER_KEY_HERE", // 🔑 Replace this
  MODEL_NAME: "mistralai/mistral-small-3.2-24b-instruct:free",        // ✅ Use any supported OpenRouter model
  SYSTEM_PROMPT: `Customize your assistant's tone, knowledge, and personality here.`,
  ```


------------------------------------------

# 📜 License

- This project is open-source under the MIT License.

--------------------------------------------------------------

# 🤝 Contributions

- Feel free to open issues, suggest features, or submit pull requests. Let’s build smarter web experiences together!


