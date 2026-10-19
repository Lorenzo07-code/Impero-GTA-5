# Il tuo impero — GTA Online

Web app installabile su Android come PWA (non è un APK).

## Funzioni
- Valore totale aggiornato automaticamente
- Categorie verticali: Attività, Immobili, Veicoli, Armi
- Corona e tutti i simboli del dollaro in oro
- Aggiunta, modifica ed eliminazione degli acquisti
- Apertura/chiusura categorie
- Backup JSON esportabile e importabile
- Salvataggio locale nel browser e cache offline dopo la prima apertura

## Patrimonio iniziale
- Attività: Ufficio CEO — $2.250.000
- Attività: Laboratorio di cocaina — $1.462.500
- Immobili: Clubhouse — 1778 Hawick Avenue — $495.000
- Armi: Carabina speciale — $14.750
- Totale iniziale: $4.222.250

## Installazione sul telefono
1. Pubblica i file su un hosting statico HTTPS (ad esempio GitHub Pages o Netlify).
2. Apri l'indirizzo HTTPS in Chrome su Android.
3. Dal menu ⋮ scegli “Installa app” o “Aggiungi a schermata Home”.

Aprire il solo file HTML localmente consente di provarlo, ma le funzioni PWA/offline richiedono HTTPS o localhost.

## Dati
Gli acquisti sono salvati nel local storage del browser sul dispositivo. Esporta periodicamente un backup JSON, soprattutto prima di cancellare i dati del browser o cambiare telefono. L'importazione sostituisce gli acquisti correnti.
