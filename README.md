# RE2017_6
Binarizacija slike iterativnim određivanjem praga binarizacije


Napisati program koji učitava sliku u PGMA formatu, zatim primenom iterativnog metoda
određuje prag binarizacije T i zatim vrši binarizaciju slike tako što se svi pikseli sa vrednošću
većom od T postavljaju na 255, a svi manji od T na 0.

. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 

Iterativno određivanje praga zasniva se na formiranju histograma slike (više informacija o
histogramu može se pročitati u tekstu projekta 3) i definisanju početnog praga binarizacije T.
Zatim se računaju srednje vrednosti osvetljaja piksela intenziteta manjeg od T (T1) i piksela
intenziteta većeg od T (T2). Novi prag binarizacije dobija se kao srednja vrednost pragova T1
i T2. Ovaj postupak ponavlja se dok god je razlika između pragova dobijenih u dva susedna
koraka ve¢a od neke predefinisane konstante.
Rezultat izvršavanja programa je slika u PGMA formatu binarizovana primenom dobijenog
praga.

Više na: http://tnt.etf.bg.ac.rs/~oe3re/Projekti/Projekti_2017.pdf
