# Model XGBoost

To repozytorium zawiera kompletną implementację pipeline’u XGBoost w Jupyter Notebooku.
Dostępne są dwie części:

* `Lista2-Część I.ipynb` — wstępna eksploracja danych i przygotowanie zestawu
* `Lista2-Część II.ipynb` — finalne strojenie modelu XGBoost, ewaluacja i interpretacja wyników

---

## Struktura repozytorium

```
xgboost-model/
├── Lista2-Część I.ipynb     # wstępna wersja analizy i przygotowania danych
├── Lista2-Część II.ipynb    # główny notebook z ostatecznym modelem i oceną
├── requirements.txt         # lista bibliotek Python wymaganych do uruchomienia
└── dane_list2.csv           # dane      
```

---

## Wymagania wstępne

* Python 3.7+
* Jupyter Notebook
* Zależności:

  ```bash
  pip install -r requirements.txt
  ```

`requirements.txt` zawiera:

```
numpy
pandas
scikit-learn
xgboost
matplotlib
seaborn
shap
```

---

## Instrukcja uruchomienia

1. Sklonuj repozytorium:

   ```bash
   git clone https://github.com/YourUser/xgboost-model.git
   cd xgboost-model
   ```
2. Zainstaluj zależności:

   ```bash
   pip install -r requirements.txt
   ```
3. Uruchom Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
4. W przeglądarce otwórz `Lista2-Część I.ipynb` lub `Lista2-Część II.ipynb` i wykonaj komórki kolejno.

---

## Pipeline krok po kroku

1. **Wczytanie danych i analiza wstępna** (EDA)
2. **Inżynieria cech**
3. **Podział na zbiory treningowy/testowy**
4. **Trening modelu i strojenie hiperparametrów**
5. **Ewaluacja i metryki** 
6. **Analiza ważności cech** 
7. **Wnioski**



