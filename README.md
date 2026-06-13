# Bank Term Deposit Prediction

Ky projekt përdor algoritme të machine learning për të parashikuar nëse një klient bankar do të regjistrohet në një depozitë me afat.

## Përmbajtja e projektit

- `bank.csv` - dataset-i i përdorur
- `bank_term_deposit_analysis.ipynb` - kodi dhe analiza e projektit
- `requirements.txt` - bibliotekat e nevojshme
- `README.md` - udhëzimet për konfigurim dhe ekzekutim

## Kërkesat

Për ekzekutimin e projektit nevojiten:

- Python 3
- pip
- Jupyter Notebook

## Konfigurimi

Shkarkoni ose klononi repository-n:

```bash
git clone https://github.com/erze-haziri/bank-term-deposit-prediction.git
cd bank-term-deposit-prediction
```

Krijoni një virtual environment:

```bash
python -m venv venv
```

Aktivizojeni virtual environment në Windows:

```bash
venv\Scripts\activate
```

Instaloni bibliotekat e nevojshme:

```bash
pip install -r requirements.txt
```

## Ekzekutimi

Nisni Jupyter Notebook:

```bash
jupyter notebook
```

Pastaj hapni skedarin:

```text
bank_term_deposit_analysis.ipynb
```

Në Jupyter zgjidhni:

```text
Kernel → Restart Kernel and Run All Cells
```

Skedari `bank.csv` duhet të jetë në të njëjtin folder me notebook-un.

## Modelet e implementuara

- Logistic Regression
- K-Nearest Neighbors
- Decision Tree
- Random Forest
- Neural Network
- K-Means Clustering

## Autorët

- Erina Ukzeka  232470136
- Erzë Haziri   232470094
- Agnesa Halimi 232469951