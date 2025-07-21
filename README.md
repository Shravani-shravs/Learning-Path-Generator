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

1️⃣ Gemini AI Studio API Key (Required)
Go to Google AI Studio
Log in with your Google Account
Click "Get API key"
Click "Create API key" (in new project or existing one)
Click Copy to copy your API key

2️⃣ YouTube Data MCP Server (Required)
Go to Pipedream
Log in with your Google Account
Search for YouTube Data MCP Server
Authorize and grant all permissions
Copy the MCP server URL

3️⃣ Google Drive or Notion MCP Server
Google Drive MCP Server
Log in via Pipedream
Search: Google Drive MCP Server
Grant permissions and copy the MCP URL
Notion MCP Server
Log in via Pipedream
Search: Notion MCP Server
Authorize access and copy the MCP URL

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
