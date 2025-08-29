
# Content-to-Text-AI-Converter 🎯

A modern, multilingual tool for converting audio, image, and video files to text with AI-powered transcription and translation capabilities, all in a single HTML file.

---

## 🚀 Getting Started

### Single File Structure
```
Content-to-Text-AI-Converter.html    # Complete standalone application (HTML+CSS+JS)
```

## Installation
### Running the Application:

#### Option 1: Direct File Access (Simplest)
1. Double-click the HTML file in your file explorer
2. Opens directly in browser (file:// protocol)

#### Option 2: With Local Server (Recommended)
Use any local server method:
- VS Code Live Server
- Python http.server
- Node.js http-server

```bash
# Example with Python:
python -m http.server 8000
```
Then open: `http://localhost:8000/Content-to-Text-AI-Converter.html`

---

## 🌟 Core Features

### File Processing
- 🎵 **Audio Transcription** - Convert speech to text from audio files
- 🖼️ **Image Text Extraction** - Extract text from images and screenshots
- 🎥 **Video Transcription** - Transcribe speech from video files
- 📁 **Multiple Format Support** - MP3, WAV, MP4, AVI, PNG, JPG, and more

### AI Integration
- 🤖 **Multiple API Providers** - Gemini, OpenAI, and Claude support
- 🎚️ **Intelligent Processing** - Automatic language detection
- 🔄 **Retry Mechanism** - Automatic retries for API overloads

### Translation & Formatting
- 🌐 **Multi-language Translation** - Persian, English, Arabic, Spanish, French
- 📝 **Text Formatting** - Structure and paragraph formatting options
- 📚 **Bilingual Interface** - Full English/Persian support with RTL/LTR switching

### User Experience
- 🌓 **Dark/Light Themes** - Theme customization
- 💫 **Modern UI** - Glassmorphism design with glow effects
- 📱 **Responsive Design** - Works on desktop and mobile devices
- 📊 **History Management** - Save and manage transcription/translation history

---

## 🛠️ Technical Implementation

### Architecture
- **Self-contained** single HTML file
- **Vanilla JavaScript** with modern ES6+ features
- **Tailwind CSS** for styling with custom dark/light themes
- **Multiple AI API integrations** with fallback handling

### Supported APIs
- **Google Gemini** - For image and text processing
- **OpenAI** - For audio transcription and text processing  
- **Anthropic Claude** - For image and text processing (images only)

### Default Configuration
- Gemini API provider
- Auto-detect language
- Dark theme
- English interface

---

## 🎮 How to Use

### 1. API Setup
1. Select your preferred API provider (Gemini, OpenAI, or Claude)
2. Enter your API key in the designated field
3. Click "Save & Activate" to enable the application

### 2. File Upload
4. Click the upload area or drag & drop your file
5. Supported formats: images (PNG, JPG), audio (MP3, WAV), video (MP4, AVI)

### 3. Conversion Settings
6. Select content language or use auto-detection
7. Click "Convert to Text" to process your file

### 4. Results & Translation
8. View transcribed text in the results section
9. Use translation tools to convert text to other languages
10. Enable formatting for structured output
11. Copy, clear, or restore results as needed

### 5. History Management
12. Access transcription and translation history
13. Restore previous sessions
14. Manage saved conversions

---

## ⚙️ Settings Overview

### API Providers
- **Gemini**: Best for image text extraction and general processing
- **OpenAI**: Best for audio transcription (Whisper) and comprehensive processing
- **Claude**: Best for image processing (does not support audio/video)

### Language Options
- **Auto-detect**: Automatically identifies content language
- **Manual selection**: Persian, English, Arabic, Spanish, French

### Theme Options
- **Dark theme** (default): Easy on eyes, reduced glare
- **Light theme**: Bright interface for well-lit environments

### Translation Features
- **Real-time translation** between supported languages
- **Text formatting** for improved readability
- **Bidirectional support** for RTL and LTR languages

---

## 📋 Supported File Formats

### Audio Files
- MP3, WAV, OGG, M4A, FLAC

### Video Files  
- MP4, AVI, MOV, WEBM, MKV

### Image Files
- PNG, JPG, JPEG, WEBP, BMP

---

## 🚦 Requirements

### Browser Compatibility
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

### Internet Connection
- Required for API communication
- Offline functionality limited to UI interactions

### API Keys
- Valid API key from selected provider required
- Free tiers available for all supported APIs

---

## 🔧 Troubleshooting

### Common Issues
1. **API Key Errors** - Ensure your API key is valid and has sufficient credits
2. **File Size Limits** - Large files may take longer to process
3. **Network Issues** - Check internet connection for API calls
4. **Browser Support** - Use updated browsers for best performance

### Performance Tips
- Use compressed audio/video formats for faster processing
- For long recordings, consider splitting into smaller segments
- Monitor API usage to avoid exceeding quota limits

---

## 📜 License [![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

This project is licensed under the MIT License.

---

## 🙏 Credits

Thanks to:
- **Tailwind CSS** for modern styling framework
- **Iconify** for comprehensive icon library
- **Vazirmatn** for beautiful Persian/Arabic typography

---

> A comprehensive, professional-grade content conversion tool packed into a single portable HTML file with enterprise-level features and beautiful design.
