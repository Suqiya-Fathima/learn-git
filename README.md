# 🤖 SAK AI Assistant - Smart AI Knowledge Assistant

<p align="center">
  <img src="screenshots/04_full_interface.png" alt="SAK AI Assistant" width="600"/>
</p>

<p align="center">
  <strong>A modern, feature-rich AI chat application with image generation, translation, voice input, and more!</strong>
</p>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-usage">Usage</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-documentation">Documentation</a> •
  <a href="#-contributing">Contributing</a>
</p>

---

## ✨ Features

### 🎯 Core Features
- **AI-Powered Chat** - Intelligent conversations with multiple AI models (GPT-4, Gemini, Llama, Mistral)
- **🎨 Image Generation** - Create stunning images from text descriptions using Stable Diffusion
- **🌍 Multi-Language Support** - Chat in 12+ languages with real-time translation
- **🔊 Text-to-Speech** - Listen to AI responses with voice synthesis
- **🎤 Voice Input** - Speak your messages instead of typing
- **📎 File Upload** - Share and analyze files (images, documents, code)
- **📊 Content Analysis** - Get detailed statistics and sentiment analysis
- **👤 User Authentication** - Secure login with profile management

### 💬 Chat Features
- **Copy Messages** - One-click copy to clipboard
- **Edit Messages** - Edit and regenerate responses
- **Regenerate Responses** - Get alternative AI answers
- **Translation** - Translate messages to 12+ languages
- **Content Analysis** - Word count, reading time, sentiment analysis
- **File Attachment** - Upload and share files
- **Voice Input** - Speak instead of typing
- **Suggested Prompts** - Quick-start conversation templates
- **Chat History** - Persistent conversation history
- **Export Chat** - Download conversations as text or PDF

### 🎨 AI Image Generation
- **Text-to-Image** - Generate images from text descriptions
- **Multiple Styles** - Photorealistic, artistic, abstract, anime, and more
- **High Resolution** - 1024x1024 pixel images
- **Download** - Save generated images as PNG
- **Easy Commands** - Just type "generate image of..."

### 🔒 Security
- **Password Hashing** - SHA-256 encryption with salt
- **Rate Limiting** - Brute-force protection
- **XSS Protection** - Input sanitization
- **Session Management** - Secure token-based authentication
- **Secure Storage** - Encrypted local storage

---

## 🚀 Quick Start

### Prerequisites
- **Node.js** 14+ and npm
- **OpenRouter API Key** (Get free key from https://openrouter.ai/)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/SAK_Project.git
cd SAK_Project/frontend
```

2. **Install dependencies**
```bash
npm install
```

3. **Set up environment variables**
```bash
# Copy the example file
cp .env.example .env

# Edit .env and add your API key
REACT_APP_GEMINI_API_KEY=your_openrouter_api_key_here
```

4. **Start the development server**
```bash
npm start
```

5. **Open your browser**
Navigate to `http://localhost:3000`

---

## 📖 Usage

### 💬 Basic Chat
Simply type your message and press Enter!

### 🎨 Generate Images
```
generate image of a futuristic city at night
create image of a beautiful sunset over mountains
draw a cute robot assistant
```

### 🌍 Translation
- Click the 🌐 icon on any message
- Or type: `translate to Spanish`

### 🔊 Text-to-Speech
- Click the 🔊 icon on any message
- Or type: `read aloud`

### 🎤 Voice Input
Click the 🎤 microphone icon and speak

### 📎 File Upload
- Click the 📎 paperclip icon
- Or type: `attach file`

### 📊 Content Analysis
- Click the 📊 icon on any message
- Or type: `analyze`

### 💡 More Commands
- `speak in French` - Change assistant language
- `generate image of...` - Create AI images
- `translate to [language]` - Translate messages
- `read aloud` - Listen to responses
- `analyze` - View content statistics

---

## 🛠️ Tech Stack

- **Frontend**: React 19
- **Styling**: CSS3 with Glassmorphism design
- **Icons**: Lucide React
- **AI API**: OpenRouter (Multiple AI models)
- **Image Generation**: Stable Diffusion 3.5 Large
- **Translation**: MyMemory API
- **Security**: Web Crypto API
- **Storage**: LocalStorage with encryption

---

## 📁 Project Structure

```
SAK_Project/
├── frontend/                 # React application
│   ├── public/              # Static files
│   ├── src/
│   │   ├── components/      # React components
│   │   │   ├── Chat.js      # Main chat interface
│   │   │   ├── Login.js     # Authentication page
│   │   │   └── SakLogo.js   # Custom logo component
│   │   ├── utils/
│   │   │   └── security.js  # Security utilities
│   │   ├── App.js           # Main app component
│   │   └── index.js         # Entry point
│   ├── package.json
│   └── .env.example
├── screenshots/             # Project screenshots
├── README.md               # This file
├── TESTING_GUIDE.md        # Complete testing guide
└── IMAGE_GENERATION_FEATURE.md  # Image gen documentation
```

---

## 🎨 Image Generation Examples

### 🌆 Landscapes
```
generate image of a cyberpunk city with neon lights at night
create image of a majestic mountain range covered in snow
make image of a tropical beach with crystal clear water
```

### 🎭 Art & Characters
```
draw a watercolor painting of cherry blossoms
generate a portrait of a steampunk inventor
create image of a magical unicorn in an enchanted forest
```

### 🚀 Sci-Fi
```
generate image of a spaceship landing on Mars
create image of a futuristic space station
draw a robot assistant in a modern office
```

### 🏰 Architecture
```
generate image of a medieval castle on a cliff
create image of a modern glass skyscraper at night
make image of a cozy cottage in the countryside
```

---

## 🌍 Supported Languages

English, Spanish, French, German, Italian, Portuguese, Russian, Japanese, Korean, Chinese, Arabic, Hindi

---

## 🔐 Environment Variables

Create a `.env` file in the `frontend` directory:

```env
# OpenRouter API Key (Get from https://openrouter.ai/)
REACT_APP_GEMINI_API_KEY=your_api_key_here

# Optional: Google OAuth Client ID
# REACT_APP_GOOGLE_CLIENT_ID=your_google_client_id
```

---

## 📱 Mobile Support

The application is fully responsive and optimized for:
- 📱 Mobile phones (480px+)
- 📱 Tablets (768px+)
- 💻 Desktops (1024px+)

---

## 🎯 Available AI Models

- **SAK Smart** - OpenAI GPT-4o Mini (Fast, Good quality)
- **SAK Pro** - OpenAI GPT-4o (Medium speed, Best quality)
- **SAK Flash** - Google Gemini 2.0 (Fastest, Good quality)
- **SAK Advanced** - Meta Llama 3.1 70B (Medium speed, Good quality)
- **SAK Ultra** - Mistral Large (Medium speed, Good quality)

---

## 📸 Screenshots

| Login | Chat Interface | Image Generation |
|-------|---------------|------------------|
| ![Login](screenshots/login_page_fullpage.png) | ![Chat](screenshots/chat_interface_full.png) | ![Image Gen](screenshots/04_full_interface.png) |

| Translation | Content Analysis | Copy Feature |
|-------------|------------------|--------------|
| ![Translation](screenshots/08_translated_spanish.png) | ![Analysis](screenshots/06_analyze_content.png) | ![Copy](screenshots/05_copy_button_works.png) |

---

## 🧪 Testing

Run the complete test suite:

```bash
npm test
```

See [TESTING_GUIDE.md](TESTING_GUIDE.md) for manual testing instructions.

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** your feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Development Guidelines
- Follow existing code style
- Add comments for complex logic
- Test your changes thoroughly
- Update documentation if needed

---

## 📝 License

This project is licensed under the MIT License - see below for details.

```
MIT License

Copyright (c) 2026 Suqiya

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 👨‍💻 Created By

**Suqiya** - A talented student developer passionate about AI and web development.

---

## 🙏 Acknowledgments

- **OpenRouter** for AI API access and image generation
- **Stability AI** for Stable Diffusion image generation
- **Lucide React** for beautiful icons
- **React team** for the amazing framework
- **MyMemory** for free translation API

---

## 📊 Project Stats

- **Lines of Code**: ~3,000+
- **Features**: 20+
- **Supported Languages**: 12+
- **AI Models**: 5
- **Response Time**: <5 seconds (average)

---

## 📞 Support

If you have any questions or need help:

1. 📖 Check the [Documentation](SAK_DOCUMENTATION.md)
2. 🧪 Review the [Testing Guide](TESTING_GUIDE.md)
3. 🎨 Read [Image Generation Guide](IMAGE_GENERATION_FEATURE.md)
4. 🐛 Open an issue on GitHub
5. 📧 Contact the developer

---

## 🌟 Show Your Support

If you find this project helpful, please give it a ⭐ star on GitHub!

---

<p align="center">
  Made with ❤️ and AI by Suqiya
</p>
