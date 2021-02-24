# NewtonAlgorithm



## Spis treści
* [Informacje ogólne](#general-info)
* [Szczegółowe omówienie algorytmu optymalizacji](#features)
* [Instalacja](#setup)
* [Bibliografia](#bibliography)

## Informacje ogólne
Projekt powstał w ramach zajęć "Teoria i Metody Optymalizacji" na studiach magisterskich na kierunku Automatyka i Robotyka.
Współautorem jest Dorian Janiak

Temat projektu to:

Zastosowanie zmodyfikowanej metody Newtona do znajdowania minimum funkcji nieliniowej.

## Szczegółowe omówienie algorytmu optymalizacji

Zmodyfikowana metoda Newtona jest iteracyjnym algorytmem służącym do znajdywania minimum zadanej funkcji celu f(x). 
Metodę Newtona z modyfikacją nazywa się metodą Newtona-Raphsona, a sama modyfikacja polega na dodaniu do algorytmu metody znajdującej minimum kierunkowe.

### Typ algorytmu
Iteracyjny algorytm optymalizacji lokalnej.

### Zastosowane kryteria stopu


### Schemat działania algorytmu
1. Wybierz punkt startowy 𝑥0=𝑥𝑘. Oblicz wartość funkcji f(𝑥𝑘) oraz jej gradient ∇ f(xk). (2) Zbadaj kryterium zbieżności (stopu). (3) Jeśli spełnione to koniec, w przeciwnym razie przejdź do (4). (4) Wyznacz kierunek poszukiwań: dk=−H−1∇ f(xk) (5) Wykonaj minimalizację kierunkową wybraną metodą: 𝑥𝑘−1∈𝑇(𝑥𝑘,𝑑𝑘) (6) Podstaw 𝑥𝑘⟸𝑥𝑘−1 oraz 𝑘⇐𝑘+1 i powtórz krok (1).
