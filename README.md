ExaMind 🤖  

Synthetic Wisdom Engine with Adaptive Response Modes 

A smart chat interface that dynamically switches between **concise answers** and **detailed explanations** based on user preference. Built with vanilla JavaScript and powered by OpenRouter's AI API.  


🌟 Features  
  
Adaptive Responses - Toggle between "Concise" (1-2 sentences) or "Detailed" (in-depth explanations) modes  
Persistent Memory - Saves chat history and preferences using `localStorage` 
Markdown Support - Rendered responses with lists, code blocks, and formatting via `marked.js` 
Dark/Light Theme - Eye-friendly theme toggle 
API Flexibility - Easily switch AI models (default: DeepSeek-R1)   


🛠️ Technologies  

- Frontend: HTML5, CSS3, JavaScript (ES6+)  
- UI Framework: Bootstrap 4  
- Markdown: [marked.js](https://marked.js.org/)  
- AI API: [OpenRouter](https://openrouter.ai/)  
- Deployment: GitHub Pages (optional)


⚙️ Configuration

🔄 Response Modes

Mode	Trigger	Behavior

Concise	Default	Short, direct answers (optimized for quick info)

Detailed	Manual toggle	Explanations with examples and reasoning


🌗 Theme Settings

Automatically saves user’s light/dark preference.


🤖 API Integration

ExaMind uses OpenRouter’s unified AI API. Supported models:

deepseek/deepseek-r1:free (default)

anthropic/claude-3-sonnet

openai/gpt-4





