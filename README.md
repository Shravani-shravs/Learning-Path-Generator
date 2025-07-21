# Learning Path Generator with Model Context Protocol (MCP)

This project is a Streamlit-based web application that generates personalized learning paths using the Model Context Protocol (MCP). It integrates with various services including YouTube, Google Drive, and Notion to create comprehensive learning experiences.

## Features

- 🎯 Generate personalized learning paths based on your goals
- 🎥 Integration with YouTube for video content
- 📁 Google Drive integration for document storage
- 📝 Notion integration for note-taking and organization
- 🚀 Real-time progress tracking
- 🎨 User-friendly Streamlit interface

## Prerequisites

- Python 3.10+
- Google ai Studio API Key
- Pipedream URLs for integrations (YouTube and either Drive or Notion)

## Installation

1. Clone the repository:

2. Create and activate a virtual environment:

3. Install the required packages:
```bash
pip install -r requirements.txt
```

## Configuration

Before running the application, you'll need to set up:

1. Google API Key
2. To get the Gemini AI Studio API key:

Go to Google AI Studio: Access the Google AI Studio page at Google AI Studio
Log in to your Google account.
Get API key: Click on the "Get API key" button, usually found in the left-side navigation panel.
Click on the "Create API Key" button, located at the top right.
Click on the "Create API Key in the New Project" button (if you have an existing project, you can use the key from that project). It will generate an API key. Click the "Copy" button to copy the key. Click on the "Create API Key in the New Project" button (if you have an existing project, you can use the key from that project). It will generate an API key. Click the "Copy" button to copy the key.

To get the Gemini AI Studio API key:
For Pipedream MCP servers:

Pipedream navigate and sign in with a Google account
YouTube Data MCP Server: YouTube Data MCP Server

In the Configuration:
Connect with your Google account and give all required permissions to access
Copy the MCP server URL
Do the same for the drive and notion MCP servers:

Google Drive MCP Server
Notion MCP Server
3. Pipedream URLs for:
   - YouTube (required)
   - Google Drive or Notion (based on your preference)

## Running the Application

To start the application, run:
```bash
streamlit run app.py
```

The application will be available at `http://localhost:8501` by default.

## Usage

1. Enter your Google ai studio API key and Pipedream URLs in the sidebar
2. Select your preferred secondary tool (Drive or Notion)
3. Enter your learning goal (e.g., "I want to learn python basics in 3 days")
4. Click "Generate Learning Path" to create your personalized learning plan

## Project Structure

- `app.py` - Main Streamlit application
- `utils.py` - Utility functions and helper methods
- `prompt.py` - Prompt template
- `requirements.txt` - Project dependencies
