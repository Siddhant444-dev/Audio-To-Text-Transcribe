# Audio Transcription System

## Overview
This is an **AI-powered Audio-to-Text Transcription System** built with:
- **Backend:** Spring Boot (Handles API requests, file processing, and OpenAI integration)
- **AI Model:** OpenAI Whisper API (Used for speech-to-text conversion)
- **Frontend:** React + Vite (For a fast and interactive user interface)

## Features
- **Upload Audio Files:** Users can upload MP3, WAV, and other formats.
- **Real-time Transcription:** The system processes the file and converts it to text.
- **Multi-language Support:** Works with multiple languages supported by OpenAI Whisper.
- **User-friendly Interface:** Built with React and Vite for a smooth experience.
- **Download & Copy Transcriptions:** Users can download or copy the generated text.
- **History & Search:** Stores previous transcriptions for easy access.

## Prerequisites
Before running the project, ensure you have:
- **Java 17+** (For Spring Boot Backend)
- **Node.js 18+** (For React Frontend)
- **PostgreSQL or MongoDB** (For storing transcription records)
- **OpenAI API Key** (Required for using Whisper API)

## How to Get an OpenAI API Key
1. Go to [OpenAI's website](https://platform.openai.com/signup/)
2. Sign up or log in.
3. Navigate to [API Keys](https://platform.openai.com/account/api-keys)
4. Click **Create API Key** and copy it.
5. Store it in your backend application as an environment variable.

## Installation

### **Backend (Spring Boot)**
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/audio-transcribe.git
   cd audio-transcribe/backend
   ```
2. Set up your OpenAI API Key in `application.properties`:
   ```properties
   openai.api.key=your_api_key_here
   ```
3. Run the Spring Boot application:
   ```sh
   mvn spring-boot:run
   ```

### **Frontend (React + Vite)**
1. Navigate to the frontend folder:
   ```sh
   cd ../frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React app:
   ```sh
   npm run dev
   ```

## Usage
- Open the frontend in your browser (default: `http://localhost:5173`).
- Upload an audio file and wait for transcription.
- Copy or download the text output.

## Contribution
Feel free to fork this repository and submit pull requests for improvements!

## License
This project is licensed under the MIT License.

