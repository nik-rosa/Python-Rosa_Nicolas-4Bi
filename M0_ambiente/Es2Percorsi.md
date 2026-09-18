# PERCORSI
### spostarsi e creare file:
mi sposto nella cartella Documents
C:\Users\nicolas.rosa>cd Documents

Creo una cartella all'interno di Documents
C:\Users\nicolas.rosa\Documents>mkdir esercizio-percorsi

Mi sposto dentro la cartella appena creata per creare 2 nuove sottocartelle
C:\Users\nicolas.rosa\Documents>cd esercizio-percorsi
C:\Users\nicolas.rosa\Documents\esercizio-percorsi>mkdir dati
C:\Users\nicolas.rosa\Documents\esercizio-percorsi>mkdir risultati

Mi sposto in dati
C:\Users\nicolas.rosa\Documents\esercizio-percorsi>cd dati

Mi sposto da dati a risultati
C:\Users\nicolas.rosa\Documents\esercizio-percorsi\dati>cd ..
C:\Users\nicolas.rosa\Documents\esercizio-percorsi>cd risultati

Per poter usare il comando Get-Location si deve essere in powershell e non cmd:
C:\Users\nicolas.rosa\Documents\esercizio-percorsi\risultati>powershell
Windows PowerShell
Copyright (C) Microsoft Corporation. Tutti i diritti riservati.

Installa la versione più recente di PowerShell per nuove funzionalità e miglioramenti. https://aka.ms/PSWindows

Ora posso usare il comando:
PS C:\Users\nicolas.rosa\Documents\esercizio-percorsi\risultati> Get-Location

Path
----
C:\Users\nicolas.rosa\Documents\esercizio-percorsi\risultati
