# ECO 726: Policy and Program Evaluation

This is a collaborative repository for ECO 726.

Fall 2025 Hunter College

## Minimum Wage DiD Replication

**Prerequisites:**
- Python 3.8+
- Git
- IDE with Jupyter support (VS Code, PyCharm, etc.)

**Setup:**
```bash
git clone https://github.com/lrud/726_Sullivan.git
python3 -m venv minwage_env
source minwage_env/bin/activate  # On Windows: minwage_env\Scripts\activate
cd 726_Sullivan/DiD && pip install -r requirements.txt
# Then open and run 726_Sullivan/DiD/load_min_wage_data.ipynb in your IDE
```

**Data:** Already included at `data/min_wage_CS.csv`