# Rabbitions — EXAM03 Nebula Brokerage Assignment

This repository contains the data analysis for the EXAM03 assignment on baseline pricing for Nebula Brokerage.

## 📂 Folder Structure

```
Rabbitions/
├── data/
│   ├── clean_it1_inventory.csv          # Dataset
│   ├── clean_it2_inventory.csv          # Dataset
│   ├── ship_inspections_iter2.csv       # Dataset
│   ├── ship_performance_logs_iter3.csv  # Dataset
│   └── ships_inventory_iter1.csv        # Dataset
├── notebooks/
│   ├── it1.ipynb                        # Analysis notebook
│   ├── it2.ipynb                        # Analysis notebook
│   └── it3.ipynb                        # Analysis notebook
├── venv/                                # Virtual environment (NOT uploaded)
├── .gitignore                           # Ignore venv and cache
├── README.md                            # Contains basic instructions
└── requirements.txt                     # Python dependencies

```

## 🛠 Setup Instructions

Follow these steps to run the project locally.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Sannebeast/Rabbitions.git 
cd Rabbitions
```

### 2️⃣ Install Python (if needed)

* Python 3.11+ is required.
* Download from: [https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/)
* Make sure to check **"Add Python to PATH"** during installation.
* Verify installation:

```bash
python --version
```

### 3️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

This will create a local virtual environment in the `venv/` folder.

### 4️⃣ Activate the Virtual Environment

#### Command Prompt (cmd)

```bash
venv\Scripts\activate
```

#### PowerShell

```powershell
.\venv\Scripts\Activate.ps1
```

You should see the prompt change to:

```
(venv) C:\path\to\Rabbitions>
```

### 5️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

This installs all Python packages used in the project (pandas, numpy, matplotlib, seaborn, scikit-learn, notebook, etc.).

### 6️⃣ Run the Jupyter Notebook

```bash
jupyter notebook
```

* A browser will open.
* Open `notebooks/it1.ipynb` to start the analysis.
* All plots and results are reproducible after running the notebook cells.

### 7️⃣ Notes

* Do **NOT** upload the `venv/` folder to GitHub.
* Keep `requirements.txt` up-to-date if you add new libraries:

```bash
pip freeze > requirements.txt
```
