# Project Setup Guide

## Create Project Folder and Environment Setup

```bash
# Create a new project folder
mkdir <project_folder_name>

# Move into the project folder
cd <project_folder_name>

# Open the folder in VS Code
code .

# Conda -----------------------------
# Create a new Conda environment with Python 3.10
conda create -p <env_name> python=3.10 -y

# Activate the environment (use full path to the environment)
conda activate <path_of_the_env>

# OR Venv ..........
# Create venv 
python -m venv myenv

# Activate ENV
.\env\Scripts\activate

# Install dependencies from requirements.txt
pip install -r requirements.txt

# Initialize Git
git init

# Stage all files
git add .

# Commit changes
git commit -m "<write your commit message>"

# Push to remote (after adding remote origin)
git push

# Cloning the repository
git clone https://github.com/sunnysavita10/document_portal.git
```



## Minimum Requirements for the Project

### LLM Models
- **Groq** (Free)
- **OpenAI** (Paid)
- **Gemini** (15 Days Free Access)
- **Claude** (Paid)
- **Hugging Face** (Free)
- **Ollama** (Local Setup)

### Embedding Models
- **OpenAI**
- **Hugging Face**
- **Gemini**

### Vector Databases
- **In-Memory**
- **On-Disk**
- **Cloud-Based**

## API Keys

### GROQ API Key
- [Get your API Key](https://console.groq.com/keys)  
- [Groq Documentation](https://console.groq.com/docs/overview)

### Gemini API Key
- [Get your API Key](https://aistudio.google.com/apikey)  
- [Gemini Documentation](https://ai.google.dev/gemini-api/docs/models)


# These are all the commands which you need to run on your command prompt if you want to work with UV

Write python on your terminal
If you have python then no need to install it
 uv --version
If you are not able to get the version
Pip install uv
import shutil
print(shutil.which("uv"))
 
6. Uv init <my-project-name>
7. uv pip list
 
8. uv python list
uv venv myenv --python cpython-3.10.18-windows-x86_64-none
uv venv <your-env-namne> --python <your-python-version>
Note: please use either 3.10 or 3.11 or 3.12
Command Prompt (CMD)  .\<your-env-nanme>\Scripts\activate.bat
Git Bash ya WSL terminal  or MAC Terminal:
source <your-env-nanme>/Scripts/activate
uv pip install -r .\requirements.txt

18. If your git is asking for login to publish the repo execute this below command
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
git config commit.gpgsign false
19. Uv add <package_name>
20. Uv add -r requirements.txt

 local to folder: 
  git config user.name "Rakesh Kumar"
  git config user.email "rakeshonrediff@gmail.com"
git config commit.gpgsign false
