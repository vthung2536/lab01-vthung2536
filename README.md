# Study Assistant — starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Setup

Follow these steps on a fresh Windows machine.

### 1. Clone the repository

Clone the repository from GitHub:

```bash
git clone https://github.com/vthung2536/lab01-vthung2536.git
cd lab01-vthung2536

### 2. Create a Python virtual environment then run 
python -m venv .venv

###3. Activate the virtual environment 
.venv\Scripts\activate

### 4. Install dependencies
pip install -r requirements.txt
pip install -e .

##Run
Run the Study Assistant with:
python -m assistant "where is the IT helpdesk?"

##Test
Run the test suite with:
pytest -q

##Progress structure
lab01-vthung2536/
├── src/
│   └── assistant/
├── tests/
├── scripts/
├── data/
├── README.md
├── requirements.txt
├── pyproject.toml
└── .gitignore