
# Lucarelli podcast contest

l’idea del progetto è creare una piattaforma che permetta agli utenti di guadagnare punti attraverso la visione dei video del lucarelli podcast





## pagine

- ## login/signup
- solamente username e password
- no 2FA o OAuth
- ## premi
- visualizzazione premi
- ## dashboard utente
- video disponibili da vedere
- ## video
- pagine per vedere i video e guadagnare punti
- ## profilo utente
- mostra i punti accumulati
- le informazioni generali
- possibilità cambio impostazioni(password, email)
- ## pagine riservate (necessitano autenticazione con password)
- upload nuovi video con punteggio assegnato

# video
i video saranno fruibili nella pagina tramite l'API di youtube. I video selezionati per il contest saranno inseriti manualmente attribuendo un punteggio ad essi.


## sistema punteggio
ogni visualizzazione completa del video darà x punti(assegnati alla pubblicazione del video sulla piattaforma). I video già visti non saranno replicabili.
Saranno implementati meccanismi di validazione. 

## stack
* PHP
* MYSQL
* Redis (da discutere)
* Youtube Api
* apache
