# Kolokwium I - Makarony
_Czas pracy: 90 minut_

## Zadanie 1
Napisz klasę `Tagliatelle`, która posiada:
- Prywatne pole `double L`, reprezentujące długość kawałka makaronu
- Prywatne pole `double W`, reprezentujące szerokość kawałka makaronu
- Prywatne pole `double R`, reprezentujące proporcję jajek do mąki
- Prywatne statyczne pole `const double C`, reprezentujące pewną stałą. Nie definiuj jego wartości, a jedynie je zadeklaruj (definicja znajdzie się w kodzie z testami).
- Publiczny konstruktor parametryczny `Tagliatelle(double, double, double)`, nadający polom odpowiednie wartości przy pomocy listy inicjalizacyjnej
- Publiczną metodę `double ileMaki(unsigned P)` zwracającą masę mąki, potrzebną do przygotowania liczby porcji równej argumentowi metody, zgodnie ze wzrorem `P * L * W * (1. - R) * C`

## Zadanie 2
Napisz klasę `Makaron`, która posiada publiczną, czysto wirtualną (abstrakcyjną) metodę `double ileMaki(unsigned)`. Zmodyfikuj `Tagliatelle` tak, aby klasa ta dziedziczyła publicznie po `Makaron` i nadpisywała odpowiednią metodę. Następnie napisz klasę `Penne`, która 
