# Sito personale

Sito statico in HTML e CSS, senza build. GitHub Pages lo pubblica così com'è.

## File

- `index.html` – tutta la pagina
- `style.css` – lo stile (colori in cima, nel blocco `:root`)
- `favicon.svg` – icona della scheda
- `.nojekyll` – dice a GitHub Pages di non passare i file da Jekyll

## Anteprima sul server

```bash
python3 -m http.server 8080 --bind 0.0.0.0
```

Poi apri `http://IP-DEL-SERVER:8080` (la porta 8000 è già di HomeHub).

## Da completare

I segnaposto sono evidenziati con un bordo tratteggiato ocra (classe `da-completare`).
Quando li sostituisci, togli anche la classe.

- [ ] Cognome nella testata
- [ ] Email (due punti: pulsante "Scrivimi" e sezione Contatti)
- [ ] Indirizzo del profilo LinkedIn (due punti)
- [ ] Quattro schermate di HomeHub con dati di esempio: salvale in `img/`
      e sostituisci ogni `<div class="schermata ...">` con
      `<div class="schermata"><img src="img/nome.png" alt="descrizione"></div>`
- [ ] CV in PDF: salvalo come `cv.pdf` e togli il commento al link nella hero
