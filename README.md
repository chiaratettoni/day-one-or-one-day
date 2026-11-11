# Love Quest — Andre Edition

Pacchetto statico HTML/CSS/JavaScript, apribile con Safari, Chrome o Firefox su Mac e Windows. Non richiede installazione né server per la prova locale.

## Stato dei contenuti

La conversazione di riferimento non conteneva allegati né il sorgente completo. È stato fornito solo il metodo Python `final_message()` / `restart_game()`: testi, sequenza del finale e riavvio sono stati riportati fedelmente e la pioggia di cuori pixelati è stata ricreata.

Per non inventare o sostituire contenuti personali, il pacchetto segnala i contenuti mancanti. Per completare il gioco servono:

- il file Python/Tkinter completo (con domande, risposte, flusso delle schermate, lettera, password segreta e indizio);
- tutte le fotografie e gli altri asset originali.

Non sono presenti foto in questo pacchetto. La galleria e gli altri testi personali non sono stati simulati.

## Prova locale

1. Estrai lo ZIP.
2. Apri `index.html` nel browser.
3. Seleziona **ENTRA NELLA MISSIONE** per vedere l'avviso sui contenuti mancanti, oppure **VEDI IL FINALE** per visualizzare il finale fornito e l'animazione.

## Pubblicazione gratuita con GitHub Pages

1. Crea un repository GitHub nuovo e vuoto (per esempio `love-quest-andre`).
2. Carica nel repository tutti i file e le cartelle di questa cartella, mantenendo `index.html` nella radice.
3. Nel repository vai su **Settings → Pages**.
4. In **Build and deployment**, scegli **Deploy from a branch**, seleziona `main` e `/ (root)`, quindi salva.
5. Attendi la pubblicazione: GitHub mostrerà l'indirizzo del sito nella stessa pagina **Pages**.
6. Apri il link per controllarlo e condividilo con Andre.

Per ora il sito online mostrerà chiaramente che il gioco personalizzato è incompleto. Prima di condividerlo come regalo finito, aggiungi il sorgente e le foto mancanti, poi crea di nuovo lo ZIP e pubblica i file aggiornati.

## Struttura

```text
index.html
styles.css
game.js
README.md
assets/        (riservata alle foto originali, non ancora disponibili)
```
