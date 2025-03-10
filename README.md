# Inżynieria Oprogramowania

To jest repozytorium testowe, stworzone do nauki Git.


Ulubiony serial:
    Breaking Bad
### Zadanie 1 - Breaking Bad

Twoim zadaniem jest obliczenie średniej długości odcinka w 3 sezonie. (Zaokrąglij długości odcinka do całości)

Dane wejściowe:
    sezon; numer odcinka/ liczba odcinków w sezonie; czas trwania odcinka

Przykład:
    3; 1/ 3; 43
    3; 2/ 3; 51
    3; 3/ 3; 46

Dane wyjściowe:
    średnia długość odcinka w 3 sezonie

Przykład:
```python
# Dane wejściowe (czasy w minutach)
czasy = [43, 51, 46]

# Inicjalizowanie sumy
suma = 0

# Sumowanie czasów
for czas in czasy:
    suma += czas

# Obliczanie średniej
srednia = suma / len(czasy)

# Wyświetlanie wyniku
print(f"Średnia długość odcinka: {srednia:.2f} minut")
```