# ChrAi
ChrAi is a local AI assistant for Lumina Shaders/GPTShaders, powered by Gemma 3 through Ollama. No API key required.

ChrAi v0.1 Prototype Installation Guide
Requirements
Windows 10 or Windows 11
Python 3.10 or newer
Ollama
Gemma 3 (gemma3:latest)
Step 1: Install Python
Download and install Python from:
https://www.python.org/downloads/
During installation, make sure Add Python to PATH is checked.
Step 2: Install Ollama
Download Ollama from:
https://ollama.com/download
Complete the installation.
Step 3: Download the AI Model
Open PowerShell or Command Prompt and run:
ollama pull gemma3:latest
Wait for the download to finish.
Step 4: Install the Python Packages
Navigate to the ChrAi folder.
Example:
cd "D:\Dev Stuff\other projects\ChrAi"
Install the required packages:
python -m pip install ollama
Step 5: Launch ChrAi
Run:
python app.py
ChrAi will start and display:
Hello! I'm ChrAi.
ChrAi v0.1
Features
Local AI powered by Gemma 3
Conversation memory
No API key required
Runs completely offline after the model is installed
/image and /im commands (prototype)
Exit ChrAi
Type:
exit
and press Enter.
Troubleshooting
'python' is not recognized
Reinstall Python and ensure Add Python to PATH is enabled.
'ollama' is not recognized
Restart your computer after installing Ollama or reinstall it.
Model not found
Run:
ollama pull gemma3:latest
ChrAi cannot connect to Gemma 3
Verify the model is installed:
ollama list
You should see:
gemma3:latest
Version Information
ChrAi Prototype v0.3
Created by Chris
Powered locally by Gemma 3 through Ollama
No cloud AI or API key is required.
