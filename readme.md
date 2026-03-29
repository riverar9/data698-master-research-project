# data698-master-research-project

## Setup and Installation

Follow these steps to get your local development environment running.

### 1. Create a Virtual Environment
Initialize a new environment named `.venv` in the root directory:
```bash
python3 -m venv .venv
```
*Note: If you are on a Debian-based system (like Linux Mint) and this fails, run sudo apt install python3-venv first.*
## 2. Activate the Environment
You must activate the environment so your terminal uses the local Python instance.
* Linux / macOS:
    ```bash
    source .venv/bin/activate
    ```
* Windows (PowerShell):
    ```PowerShell
    .\.venv\Scripts\Activate.ps1
    ```
* Windows (Command Prompt):
    ```DOS
    .venv\Scripts\activate
    ```
## 3. Install Dependencies
Once the environment is active (you should see `(.venv)` in your prompt), install the required packages:
```bash
pip install -r py-requirements.txt
```

*Tip: To exit the virtual environment when you are done, simply run the command deactivate.*

A document for notes sharing and collaboraiton can be found here:
https://docs.google.com/document/d/1-1Bte1qaL4INa-D7judeCcjxUVgT_y6mYSkXMHHOw-c/edit?tab=t.0