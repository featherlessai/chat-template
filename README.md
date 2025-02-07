# Featherless Chat Template

A starter template for a chat interface for the Featherless AI platform. Get started with AI-powered chat in minutes.

## 🚀 Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/featherless/chat-template
   cd chat-template
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Copy the environment file:
   ```bash
   cp .env.example .env
   ```

4. Add your Featherless API key to `.env`

5. Start the development server:
   ```bash
   npm run dev
   ```

## 🔑 Features

- 🎨 Dark/Light theme
- 💬 Conversation management
- 🤖 Model selection
- ⚡ Streaming responses
- 📱 Mobile-responsive
- 🔒 Secure API key handling

## 🛠️ Customization

### Styling
The template uses Tailwind CSS. Customize colors and styling in `tailwind.config.js`.

### Models
Edit `POPULAR_MODELS` in `src/components/ModelSelector.jsx` to change default models.

### API
Modify API calls in `src/services/api.js` to add custom endpoints or parameters.

## 📦 Deployment

1. Build the project:
   ```bash
   npm run dev
   ```

2. Deploy to your preferred platform (Vercel, Netlify, etc.)

## 📝 License

MIT