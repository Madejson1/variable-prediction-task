# Model predykcyjny – analiza danych

Projekt przedstawia proces budowy modelu predykcyjnego na podstawie dostarczonego zbioru danych.

## Cel projektu

Celem projektu było przeprowadzenie analizy danych oraz zbudowanie modelu predykcyjnego przewidującego wartość zmiennej zależnej `Zmienna_Y` na podstawie zmiennych objaśniających.

## Etapy analizy

Projekt obejmuje następujące etapy:

1. Wczytanie i wstępna eksploracja danych (EDA)
2. Analiza statystyczna zmiennych
3. Wizualizacja korelacji pomiędzy zmiennymi
4. Podział danych na zbiór treningowy i testowy
5. Budowa modeli predykcyjnych
6. Ocena jakości modeli

## Zastosowane modele

W projekcie porównano trzy podejścia:

- Dummy Regressor (model bazowy)
- Linear Regression
- Random Forest Regressor

## Metryki oceny modeli

Do oceny jakości predykcji wykorzystano:

- RMSE (Root Mean Squared Error)
- R² (współczynnik determinacji)

Najlepsze wyniki uzyskał model **Random Forest**, który osiągnął najniższy błąd predykcji oraz najwyższą wartość współczynnika R².

## Technologie

Projekt został wykonany w Pythonie z wykorzystaniem bibliotek:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Pliki w repozytorium

- `PredictionModel.ipynb` – notebook zawierający pełną analizę danych oraz budowę modeli predykcyjnych
