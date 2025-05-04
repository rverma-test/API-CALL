# AI Text Tool

A simple web application that uses AI to summarize and translate text.
![AI Text Tool Screenshot](./appimage.jpg)


This tool helps you:
- Summarize long text into shorter versions
- Translate text to different languages
- Or do both at once (summarize and then translate)

## Getting Started

### Requirements

- Node.js (v14 or newer)
- VS Code with Live Server extension
- Google Gemini API key

### Setup Instructions

#### Step 1: Clone or download this project

Download and unzip the project, or clone it from the repository.

#### Step 2: Set up the backend

1. Open a terminal in the project root folder
2. Create a `.env` file in the root folder with your Google Gemini API key:
GOOGLE_GENAI_API_KEY=your_api_key_here
3. Install dependencies:
npm install
4. Start the backend server:
npm run dev
This will start the server at http://localhost:4500

#### Step 3: Launch the frontend

1. Open the project in VS Code
2. Right-click on the `frontend/index.html` file
3. Select "Open with Live Server"
4. The application should open in your browser at http://localhost:5500/frontend/

## How to Use

1. Type or paste your text in the text box
2. Select what you want to do:
- Check "Summarize" to get a summary
- Check "Translate" to translate (and enter a language)
- Check both to summarize and then translate
3. Click "Process Text"
4. View the formatted results below

## Project Structure
project-root/
├── frontend/
│   ├── index.html      # Main HTML file
│   └── style.css       # CSS styling
├── server.js           # Backend server code
├── index.js            # Entry point for the server
├── package.json        # Node.js dependencies
└── .env                # Environment variables (create this yourself)

## Troubleshooting

- **No response from AI**: Check that your API key is correct in the `.env` file
- **CORS error**: Make sure you're using VS Code Live Server at port 5500
- **Server not starting**: Check if port 4500 is already in use by another application
