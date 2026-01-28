# Gomoku 9×9 Reinforcement Learning – Command Line Guide

This README provides all command-line instructions required to set up, run, and train the Gomoku 9×9 Reinforcement Learning project.

Repository:
https://github.com/Drackyay/Gomoku-9x9-RL

---

## Environment Setup

Ensure Python 3 is installed. It is recommended to use a virtual environment.

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

cd api
python app.py

http://localhost:5000

cd frontend
npm install
npm start

http://localhost:3000

python alphazero_train.py

deactivate

pip install --upgrade -r requirements.txt
