# Allez Collective — Website

## File structure

```
allezcollective/
├── index.html      # Homepage
├── trail.html      # Trail Weekend detail
├── bike.html       # Bike Weekend detail
├── about.html      # Chi siamo
├── style.css       # CSS condiviso
└── README.md
```

## Setup su GitHub Pages

1. Crea un account su github.com (se non ce l'hai)
2. Crea un nuovo repository pubblico, es. `allezcollective`
3. Carica tutti i file (index.html, trail.html, bike.html, about.html, style.css)
4. Vai su **Settings → Pages**
5. Source: seleziona `main` branch, root `/`
6. Salva → il sito sarà live su `https://tuonome.github.io/allezcollective`

## Collegare il dominio allezcollective.it

1. Vai su Settings → Pages → Custom domain
2. Inserisci `allezcollective.it`
3. Vai sul pannello del tuo registrar (dove hai comprato il dominio)
4. Aggiungi questi record DNS:

```
A     @     185.199.108.153
A     @     185.199.109.153
A     @     185.199.110.153
A     @     185.199.111.153
CNAME www   tuonome.github.io
```

5. Attendi 10–30 minuti per la propagazione

## Collegare Tally (waiting list)

1. Crea un account su tally.so
2. Crea un nuovo form con i campi: Nome, Email, Sport (Trail / Cycling), Data preferita
3. Copia il link del form (es. `https://tally.so/r/XXXXXXX`)
4. Cerca e sostituisci `https://tally.so/YOUR_FORM_ID` in tutti i file HTML con il tuo link

## Cose da aggiornare prima del lancio

- [ ] Link Tally form (4 occorrenze: index, trail, bike, about)
- [ ] Link Instagram reale
- [ ] Link Strava club reale
- [ ] Testo about page (storia/fondatore se vuoi aggiungerla)
- [ ] Programma giornaliero (verifica km e orari con la guida locale)
- [ ] Aggiungere favicon (favicon.ico nella root)
