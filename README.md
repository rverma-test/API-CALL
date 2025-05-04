AI Text Tool
A simple web application that uses AI to summarize and translate text.
What This Tool Does
This tool helps you:

Summarize long text into shorter versions
Translate text to different languages
Or do both at once (summarize and then translate)

Getting Started
Requirements

Node.js (v14 or newer)
VS Code with Live Server extension
Google Gemini API key

Setup Instructions
Step 1: Clone or download this project
Download and unzip the project, or clone it from the repository.
Step 2: Set up the backend

Open a terminal in the project root folder
Create a .env file in the root folder with your Google Gemini API key:
GOOGLE_GENAI_API_KEY=your_api_key_here

Install dependencies:
npm install

Start the backend server:
npm run dev
This will start the server at http://localhost:4500

Step 3: Launch the frontend

Open the project in VS Code
Right-click on the frontend/index.html file
Select "Open with Live Server"
The application should open in your browser at http://localhost:5500/frontend/

How to Use

Type or paste your text in the text box
Select what you want to do:

Check "Summarize" to get a summary
Check "Translate" to translate (and enter a language)
Check both to summarize and then translate


Click "Process Text"
View the formatted results below

Project Structure
project-root/
├── frontend/
│   ├── index.html      # Main HTML file
│   └── style.css       # CSS styling         
├── index.js            # Entry point for the server
├── package.json        # Node.js dependencies
├── package-lock.json   # Locked js dependencies
└── .env                # Environment variables (create this yourself)
