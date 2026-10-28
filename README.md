# APBD — Ćwiczenia 1: Git i GitHub

Mała aplikacja konsolowa w C# (.NET) tworzona na potrzeby ćwiczenia pracy z Gitem:
commity, gałęzie, scalanie (fast-forward i three-way merge) oraz ręczne rozwiązywanie
konfliktu.

## Opis programu

Program operuje na tablicy liczb całkowitych i wypisuje:

- powitanie,
- sumę elementów,
- średnią arytmetyczną,
- liczbę elementów,
- wartość maksymalną.

Logika obliczeń znajduje się w klasie `StatisticsHelper`, a powitanie w klasie `Greeting`.

## Wymagania

- .NET SDK
- Git

## Uruchomienie

```bash
dotnet run
```

Dla domyślnej tablicy `{ 2, 4, 6 }` końcowy program wypisuje:

```
Witaj w kalkulatorze APBD!
Suma: 12
Średnia: 4
Liczba elementów: 3
Maksimum: 6
```
