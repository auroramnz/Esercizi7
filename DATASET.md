
==================================================
 1. DATASET AMAZON 
==================================================
Dimensione del dataset originale: (20000, 2)
Nomi di colonna: ['reviewText', 'Positive']

Dieci righe estratte a caso (Esempio):
1. 'this is a really cool game. super fun.', 1
2. 'worst app ever made, freezes every two minutes', 0
3. 'highly addictive and super entertaining game', 1
4. 'very bad experience, do not download', 0
5. 'this is awesome and you don't need wi fi', 1
6. 'I hate it! all you do is tap stuff.', 0
7. 'love it! this game is awesome.', 1
8. 'this app is fricken stupid.it froze', 0
9. 'This is a silly game but lots of fun', 1
10. 'This game is a rip off. No real animals', 0

[RISPOSTA BILANCIAMENTO]:
Il dataset contiene esattamente 10.000 recensioni positive (1) e 10.000 negative (0).
-> Il dataset è perfettamente BILANCIATO.

==================================================
 2. DATASET DIABETES 
==================================================
Dimensioni del dataset reale: (768, 9)
Nomi di colonna: ['Pregnancies', 'Glucose', 'BloodPressure', 'SkinThickness', 'Insulin', 'BMI', 'DiabetesPedigree', 'Age', 'Outcome']

--- Media della pressione diastolica calcolata per fascia d'età ---
Fascia d'età 20-29 anni: 65.62 mm Hg
Fascia d'età 30-39 anni: 69.83 mm Hg
Fascia d'età 40-50 anni: 74.92 mm Hg
-> Nota: La pressione media cresce costantemente all'aumentare dell'età.

==================================================
 3. DATASET INSURANCE 
==================================================
Dimensioni del dataset reale: (1338, 7)
Colonne: ['age', 'sex', 'bmi', 'children', 'smoker', 'region', 'charges']

[ANALISI DEI COSTI MEDI (CHARGES)]:

1. Rispetto alla REGIONE (Differenze minime):
   - southwest: 12346.94$ | southeast: 14735.41$ | northwest: 12417.58$ | northeast: 13406.38$

2. Rispetto al FUMO (Differenza ENORME):
   - NON Fumatori (no):   8434.27$
   - Fumatori (yes):     32050.23$  <-- Costa quasi 4 volte di più!

3. Rispetto al SESSO (Differenza minima):
   - Donne (female): 12569.58$ | Uomini (male): 13956.75$

4. Costi divisi per quartili di BMI (Indice Massa Corporea):
   - Q1 (BMI basso <= 26.3):  Media costi -> 10352.28$
   - Q2 (BMI medio <= 30.4):  Media costi -> 11299.38$
   - Q3 (BMI alto <= 34.7):   Media costi -> 13993.30$
   - Q4 (BMI molto alto > 34.7): Media costi -> 16983.47$

==================================================
 4. DATASET POKEMON 
==================================================
[RISPOSTA DOMANDA 1] L'indice automatico combacia con la colonna '#'? NO.
Perché per le forme Mega (es. Mega Venusaur) il numero ID '#' si ripete identico.

[RISPOSTA DOMANDA 2] Filtri applicati sui dati reali:
- Numero totale di Pokémon Leggendari presenti: 65
- Leggendari con Tipo 1 'Grass': Celebi, Shaymin (Land), Shaymin (Sky), Virizion.
- Leggendari con Tipo 1 'Ice' o 'Fire': Articuno, Moltres, Entei, Ho-oh, Regice, Heatran.
- Esempi di Pokémon di 1° Gen con Attack > 50 e HP < 60:
  Mankey, Growlithe, Diglett, Dugtrio, Shellder, Gastly, Haunter, Krabby.

==================================================
 5. DATASET PUB E LOCALI IN ITALIA 
==================================================
Numero totale di righe (locali censiti): 2497
Metadati delle colonne: ['Comune', 'Provincia', 'Regione', 'Nome', 'Anno inserimento', 'Data e ora inserimento', 'Identificatore', 'Longitudine', 'Latitudine']

[RISPOSTE DOMANDE]:
- Primo elemento del file: Comune 'ALTRO', Regione 'ALTRO' (Riga senza nome specifico inserita nel 2011).
- Ultimo elemento del file: 'Pizzeria da Nino' situata a Barletta.
- Un elemento estratto a caso (Esempio reale): 'Lenny's Pub' a Torino.
- Anni di inserimento presenti nel file: [2007, 2008, 2009, 2010, 2011, 2012, 2013, 2014, 2015, 2016]
- Quante enoteche ci sono e come si chiamano? Ci sono 6 enoteche registrate:
  1. Enoteca di Andrea e Gianluca
  2. Enoteca Regionale del Barolo
  3. Enoteca della Valpolicella
  4. La Vecchia Enoteca
  5. Enoteca Le Volte
  6. Enoteca Pinchiorri

==================================================
 TUTTI I DATASET SONO STATI ELABORATI CON SUCCESSO! 
==================================================


** Process exited - Return Code: 0 **
