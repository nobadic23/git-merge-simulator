# Modeliranje Git povijesti usmjerenim acikličkim grafom i pronalazak najbližeg zajedničkog pretka

Projekt iz kolegija *Diskretne strukture s teorijom grafova*, FOI, ak. god. 2026./2027.

Povijest commitova u Gitu modeliramo kao **usmjereni aciklički graf (DAG)**, a spajanje grana (merge) kao problem pronalaska **najbližeg zajedničkog pretka** (*merge base*). Izrađujemo interaktivni simulator naredbi `commit`, `branch` i `merge` te analiziramo povijest stvarnih Git repozitorija.

## Problem

Kad dvije osobe razvijaju projekt na odvojenim granama i žele spojiti svoj rad, Git mora odrediti od kojeg su se stanja razišle. U grafu povijesti to je **merge base**: zajednički predak oba commita koji nije predak nijednog drugog zajedničkog pretka.

**Pitanja koja istražujemo:**

1. Kako matematički opisati povijest Git repozitorija?
2. Kojim algoritmom pouzdano pronaći merge base, uključujući slučajeve kad ih ima više?
3. Kako izgleda povijest stvarnih projekata: koliko spajanja, koliko fast-forwarda, koliko slučajeva s više baza?

## Članice tima

| Ime i prezime | JMBAG | GitHub |
| --- | --- | --- |
| Nina Obadić | 0016164299  | [@nobadic23](https://github.com/korisnicko-ime) |
| Ana Maria Levanić | 0000000000 | [@alevanic23](https://github.com/korisnicko-ime) |
| Ema Mučić | 0000000000 | [@emucic23](https://github.com/korisnicko-ime) |
