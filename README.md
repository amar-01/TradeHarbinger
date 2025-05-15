# 🚀 Local Translation & Copywriting Tool

![App Screenshot](/assets/screenshot.png) *(Add a screenshot later)*

A **lightweight, offline-first** translation tool designed for Windows 10 (optimized for i5 laptops) that helps you translate and manage copywriting tasks locally with **zero costs** and **no internet dependency**.

## ✨ Features
- 🔒 **100% Offline** - No API keys, no subscriptions
- ⚡ **Fast Performance** - Optimized for i5 processors
- 🌍 **Multi-Language Support** - EN↔FR, EN↔DE, FR↔DE (extendable)
- 📚 **Translation History** - SQLite database stores all your work
- 📁 **Portable** - Single executable version available
- 🛡️ **Privacy Focused** - All data stays on your machine

## 📦 Installation

### Prerequisites
- Windows 10/11 (64-bit)
- Python 3.9+ ([Download Python](https://www.python.org/downloads/))
- 4GB RAM (8GB recommended for smoother performance)

### Method 1: From Source
```bash
# Clone the repository
git clone https://github.com/amar-01/TranslationTool.git
cd TranslationTool

# Create and activate virtual environment
python -m venv venv
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the application
python main.py
