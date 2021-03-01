# NewtonAlgorithm



## Spis treści
* [Informacje ogólne](#general-info)
* [Szczegółowe omówienie algorytmu optymalizacji](#features)
* [Technologie](#technology)
* [Instalacja](#setup)
* [Bibliografia](#bibliography)

## Informacje ogólne
Projekt powstał w ramach zajęć "Teoria i Metody Optymalizacji" na studiach magisterskich na kierunku Automatyka i Robotyka.
Współautorem jest Dorian Janiak ([Yep97](https://github.com/Yep97))

Temat projektu to:

Zastosowanie zmodyfikowanej metody Newtona do znajdowania minimum funkcji nieliniowej.

## Szczegółowe omówienie algorytmu optymalizacji

Zmodyfikowana metoda Newtona jest iteracyjnym algorytmem służącym do znajdywania minimum zadanej funkcji celu f(x). 
Metodę Newtona z modyfikacją nazywa się metodą Newtona-Raphsona, a sama modyfikacja polega na dodaniu do algorytmu metody znajdującej minimum kierunkowe.

### Typ algorytmu
Iteracyjny algorytm optymalizacji lokalnej.

### Zastosowane kryteria stopu

![1](./Screenshots/1.png)

Zbieżność zastosowanego algorytmu: kwadratowa

### Schemat działania algorytmu

![2](./Screenshots/2.png)

### Ograniczenia algorytmu

![3](./Screenshots/3.png)

## Technologie

Do napisania programu implementującego algorytm Newton’a został wykorzystany język **C#** wraz z zintegrowanym środowiskiem programistycznym **Visual Studio**. Projekt opiera się na platformie **WPF** służącej do tworzenia aplikacji okienkowych. Do implementacji parsera funkcji użyto biblioteki **„Mxparser”**. Wizualizacje wykresów wykonano za pomocą biblioteki **„GnuplotCSharp”**. Jako pomocniczą bibliotekę do zaawansowanych działań matematycznych oraz operacji na zbiorach liczb wykorzystano **„Accord”**. Reszta użytych bibliotek to wbudowane biblioteki systemowe.

## Działanie programu

Program działa w trybie graficznym i wygląda tak jak zdjęciu poniżej. 

![4](./Screenshots/4.png)

Wyniki działania algorytmu są prezentowane na kilka sposobów. Pierwszy z nich to postać wynikowa, w której pokazana jest kolejno: wartość funkcji w punktach optymalnych, wartości punktów optymalnych oraz kryterium stopu, które zatrzymało algorytm. Drugi to postać wpisów kolejnych iteracji działania algorytmu w tabeli w dolej części okna. Wykreślone wyniki posiadają dokładność 10^-3. Dodatkowo użytkownik może zlecić wykreślenie wykresu 3D badanej funkcji oraz wykresu warstwic wraz ze ścieżką z wyszczególnionymi punktami reprezentującymi kolejne iteracje algorytmu. Przykładowe wykresy zostały umieszczone na poniższych zdjęciach.

![5](./Screenshots/5.png)

![6](./Screenshots/6.png)
