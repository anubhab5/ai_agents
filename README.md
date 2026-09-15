# ai_agents

## Commands

@echo off
REM Create a virtual environment named 'venv'
python -m venv venv

REM Activate the virtual environment
call venv\Scripts\activate

REM Verify activation
python --version

echo Virtual environment created and activated!
pip install -r requirements.txt