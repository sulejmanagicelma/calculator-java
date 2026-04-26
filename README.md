# Izvještaj

## LOC

Calculator.java 134 

Start.java 19

Ukupno LOC: 153

## ANALIZA

Calculator.java : glavni file u kojem je logika kalkulatora. Program podrzava osnovenmracunske operacije. Dobro je sto su simboli tih operacija jasno definisani. Sam file ima dosta linija i sve je u jednoj klasi, pa ga to cini malo nepreglednim. Ima ponavljanja slicnog koda za razlicite operacije. Koristena je stsaticka varijabla za rezultat, sto nije bas najoptimalnije rjesenje jer smanjuje fleksibilnost za dalje koristenje i prosirenje koda

Start.java : jednostavan file za pokretanje programa. Omogucava korisniku unos preko tastature, a sam unos bi se mogao bolje organziuriati tako da se scanner kreira jednom prije petlje, umjesto da se pravi ponovo pri svakom novom unosu. Kratko, jasno i razumljivo je.  
