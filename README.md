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
ε≤10−3

dla gradientu: <∇𝑓(𝑥),∇𝑓(𝑥)>≤ε1 

dla x: ||𝑥𝑛−𝑥𝑛−1||≤ε2 

dla f(x): |f(xn)−f(xn−1)|≤ε3 

liczba iteracji: 𝐿 

Zbieżność zastosowanego algorytmu: kwadratowa
