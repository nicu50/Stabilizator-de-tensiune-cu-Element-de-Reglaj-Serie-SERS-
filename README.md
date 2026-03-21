# Stabilizator-de-tensiune-cu-Element-de-Reglaj-Serie-SERS-

## Descriere
Acest proiect prezintă proiectarea, simularea și analiza unui stabilizator liniar cu element de reglaj serie.  
Proiectul a fost realizat în cadrul **Universitatea Politehnica din București, Facultatea de Electronică, Telecomunicații și Tehnologia Informației**.

## Principiu de funcționare
Stabilizatorul menține constantă tensiunea pe sarcină printr-un proces de reglare automată:
- O fracțiune din tensiunea de ieșire este comparată cu o tensiune de referință stabilă (diodă Zener + sursă de curent constant).
- Semnalul de eroare este amplificat și comandă elementul regulator serie (tranzistoare Darlington).
- Include protecție la supracurent pentru a limita curentul maxim la 0,4 A.

## Schema bloc
![Schema bloc](imagini/schema_bloc.png)

## Schema electrică
![Schema electrica](imagini/schema_electrica.png)

## Simulare și rezultate
![Simulare](imagini/simulare.png)
![Grafice](imagini/grafice.png)

## Documentație completă
Toate detaliile tehnice, calculele și analiza sunt în `proiect.pdf`.

## Autor
Tănăselea Neculai
