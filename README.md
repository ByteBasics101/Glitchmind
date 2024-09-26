# Glitchmind

AI Desktop Assistant is a voice- and text-enabled assistant that offers internet search, system monitoring, coding assistance, and machine learning model training features. It acts as a system security monitor and helps automate tasks, all through a clean and responsive desktop interface.

## Features

- **Internet Search & Data Scraping**: Perform intelligent web searches, scrape content, and create datasets.
- **Voice & Text Interaction**: Interact using voice (Mozilla DeepSpeech) or text, with responses via Coqui TTS.
- **System Monitoring & Security**: Real-time monitoring of CPU, RAM, network usage, and malware detection.
- **Coding Assistant**: Generate, review, and debug code, plus Git integration for version control.
- **Machine Learning Model Training**: Support for dataset creation and fine-tuning with Hugging Face Transformers.
- **Task Automation**: Automate repetitive tasks with custom macros and voice-activated commands.
- **User-Friendly Interface**: Built with React and Electron.js for seamless desktop interaction.

## Technologies Used

- **Frontend**: React, Tailwind CSS, Electron.js
- **Backend**: FastAPI (Python)
- **Voice Processing**: Mozilla DeepSpeech (voice recognition), Coqui TTS (text-to-speech)
- **Machine Learning**: Hugging Face Transformers, PyTorch, TensorFlow
- **System Monitoring**: psutil, Antivirus APIs

## Getting Started

### Prerequisites

- **Node.js** and **npm** (for frontend and Electron setup)
- **Python 3.12.6** (for backend and FastAPI)
- **DeepSpeech** and **Coqui TTS** for voice processing

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-desktop-assistant.git
   cd ai-desktop-assistant
