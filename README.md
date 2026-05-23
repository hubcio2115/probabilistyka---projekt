# Zastosowania probabilistyki w informatyce - Zadania projektowe

## Raport powinien zawierać:

1. opis problemu i zastosowanego modelu,

2. obliczenia analityczne (wykonane ręcznie lub za pomocą języka R),

3. kod w języku R wykorzystany do symulacji,

4. wyniki liczbowe wraz z wnioskami.

## Zadanie 1. Warsztat

W warsztacie samochodowym pracuje dwóch mechaników zajmujących się wymianą
filtrów oleju. Obsługa każdego klienta składa się z trzech kolejnych etapów:
diagnozy, wymiany filtra oraz kontroli końcowej. Czas trwania każdego etapu ma
rozkład wykładniczy: dla pierwszego mechanika z parametrem $λ_1 = 5 h^{−1}$,
natomiast dla drugiego z parametrem $λ_2 = 20 h^{−1}$. Prawdopodobieństwo, że
klient trafi do pierwszego mechanika, wynosi 0,2, a do drugiego 0,8. Niech $X$
oznacza całkowity czas obsługi jednego klienta.

1. Oblicz prawdopodobieństwoP(X > 35min). Zwróć uwagę na dobór właściwego
   rozkładu.

2. Oszacuj to prawdopodobieństwo metodą Monte Carlo w taki sposób, aby błąd
   oszacowania nie przekraczał 0,01 z prawdopodobieństwem co najmniej 0,9.

3. Zbadaj wpływ liczby przeprowadzonych symulacji na dokładność otrzymanej
   estymacji.
