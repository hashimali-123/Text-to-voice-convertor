# Text-to-Voice Converter  

## Overview  
This is a simple text-to-voice converter using the Web Speech API. It allows users to input text and convert it into speech using available system voices.  

## Features  
- Converts text to speech using the browser's SpeechSynthesis API  
- Allows users to select different voices  
- Simple UI with a text input and a play button  

## How to Use  
1. Enter text into the provided textarea.  
2. Select a voice from the dropdown menu (if multiple voices are available).  
3. Click the "Speak" button to hear the text read aloud.  

## Prerequisites  
- A modern web browser that supports the SpeechSynthesis API (e.g., Chrome, Edge, Firefox).  

## Code Explanation  
- `SpeechSynthesisUtterance` is used to create a speech object.  
- Available voices are retrieved using `window.speechSynthesis.getVoices()`.  
- A dropdown allows users to select different voices.  
- When the button is clicked, the entered text is spoken aloud.  

## Future Enhancements  
- Add pitch and speed control for speech.  
- Improve UI for a better user experience.  
- Support multiple languages.  

## License  
This project is open-source. Feel free to modify and use it for learning purposes. 
