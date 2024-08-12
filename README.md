# Architecture Design Session with Gen AI

This repo includes a few jupyter notebooks for design software architecture using Generative AI

### Prerequisites:
- Python
- LLM (GPT-4) deployed on Azure or SML running locally on Ollama  (TODO)


### Start:

To create a Python virtual environment for running a Jupyter notebook, follow these instructions based on your operating system:

**Linux:**
1. Open a terminal.
2. Navigate to the directory where you want to create the virtual environment.
3. Run the command `python3 -m venv venv` to create a virtual environment named "venv".
4. Activate the virtual environment by running `source venv/bin/activate`.

**Windows:**
1. Open a command prompt.
2. Navigate to the directory where you want to create the virtual environment.
3. Run the command `python -m venv venv` to create a virtual environment named "venv".
4. Activate the virtual environment by running `venv\Scripts\activate.bat`.

**macOS:**
1. Open a terminal.
2. Navigate to the directory where you want to create the virtual environment.
3. Run the command `python3 -m venv venv` to create a virtual environment named "venv".
4. Activate the virtual environment by running `source venv/bin/activate`.

### Dependencies and infrastructure

Install python dependencies, run:
> pip install -r requirements.txt

#### Gen AI

Option 1: Azure Open AI
Option 2: Ollama (not recommended)

#### Run PlantUML Local server

To run a local PlantUML server using Docker, follow these steps:

1. Make sure you have Docker installed on your machine.
1. In a terminal, navigate to `plantuml` folder.
1. Run `docker-compose up -d`.
1. To stop the Docker Compose when you're done: `docker-compose down`

### Start Jupyter Lab

Start the Jupyter lab server by running `jupyter lab`.




