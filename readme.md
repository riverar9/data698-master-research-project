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

Powerpoint presentation here:
https://docs.google.com/presentation/d/1zLCfP-Y5SwLP5Qj38TW9WikB-J_3pHrjlQlBf5xUYE4/edit?slide=id.g34c462e2c2a_1_0#slide=id.g34c462e2c2a_1_0
