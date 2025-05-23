# Vector-Art-Studio
Vector Art Studio is a Python-based desktop GUI application that transforms images into stunning vector-style artwork using OpenCV and k-means clustering. It features a modern UI built with customtkinter, and supports voice commands using speech recognition and NLP!

# Features
Upload and view any image.
Apply vector art style filters using image processing.
Save the processed image to your computer.
# Use voice commands like:
"open image"
"save image"
"reset"
"exit"
"stop listening"
Animated splash screen and user-friendly interface.

# Requirements
Make sure you have Python 3.8+ installed. Then install the following dependencies:

# Install these pips on your terminal 
pip install opencv-python numpy Pillow customtkinter SpeechRecognition pyttsx3 fuzzywuzzy python-Levenshtein
Note: python-Levenshtein speeds up fuzzywuzzy, and may be required to avoid warnings.

 # How to Run
1.Clone or download the project files.
2.Open the terminal (or command prompt) in the project folder.
3.Run the main Python file:
python filename.py
Replace filename.py with your actual script name if it's different.

# Supported Voice Commands
Command Phrase	Action
"load", "open image"	Load an image for processing
"save", "save image"	Save the processed vector art
"reset", "start over"	Clear current images
"exit", "quit"	Close the application
"stop listening"	Disable voice control

# Example Output
The application takes an input image and converts it into a vector-styled output with stylized edges and color clustering.
Technologies Used
OpenCV for image processing
Tkinter / CustomTkinter for GUI
SpeechRecognition + Pyttsx3 for voice input/output
FuzzyWuzzy for NLP-based intent matching
Pillow for image format handling

# Tips
Use a clear microphone for voice commands.
Speak in short, clear phrases for best recognition.
Make sure your image file is in .jpg, .jpeg, .png, or .bmp format.

# Folder Structure
VectorArtStudio/
├── main.py                # Main application code
├── README.md              # This file
└── requirements.txt       # Optional: Add dependencies here

# To-Do (Optional Ideas)
Add undo/redo functionality
Support batch processing of multiple images
Add more stylized filters (e.g., sketch, cartoon)
Export vector art as SVG
