# Samsung Prism AI Companion

A web-based interactive AI assistant with computer vision capabilities. This project integrates real-time object detection using TensorFlow.js (MobileNet) and conversational AI powered by Google's Gemini API. 

## Features
- **Real-Time Object Detection**: Uses the device's webcam to analyze and identify objects in real-time.
- **Conversational AI**: Integrates with the Gemini 1.5 Flash API to answer questions and understand context based on what the camera sees.
- **Screen Sharing**: Switch between webcam and screen sharing to allow the AI to see your screen.
- **Image Analysis**: Take screenshots of the video feed and prompt the AI to analyze them.
- **Voice Commands**: Built-in speech recognition allows you to speak to the bot.
- **Dark UI**: A sleek, custom dark mode interface using Tailwind CSS.

## Usage
1. Open the `index.html` file in your preferred web browser.
2. Grant camera and microphone permissions when prompted.
3. Click the **Settings** gear icon in the top right.
4. Enter your **Google Gemini API Key** (obtainable from Google AI Studio).
5. Start chatting! You can ask "What is this?" while holding an object to the camera, or take a screenshot and ask specific questions about the image.

## Technologies Used
- HTML5 / CSS3 / JavaScript
- Tailwind CSS
- TensorFlow.js & MobileNet (Object Detection)
- Google Gemini API (Generative AI)
- WebRTC (Webcam & Screen Capture)
- Web Speech API (Speech Recognition & Synthesis)
