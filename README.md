# Pagliolo Studio

Web app statica per il predimensionamento trasparente di paglioli in acciaio, con modello 3D interattivo.

## Avvio locale

Apri `dist/index.html` con un server statico. È necessario un server HTTP perché la vista 3D usa moduli JavaScript.

## Pubblicazione su GitHub Pages

Il workflow incluso in `.github/workflows/pages.yml` pubblica automaticamente la cartella `dist` su GitHub Pages a ogni push sul branch `main`.

Nel repository GitHub apri **Settings → Pages** e seleziona **GitHub Actions** come sorgente.

## Funzioni

- modello 3D di lamiera, grigliato e doghe;
- geometria parametrica e profili RHS;
- percorso dei carichi piano → traversi → longheroni → gambe;
- verifiche locali di momento, taglio, freccia e instabilità assiale;
- reazioni agli appoggi ed equilibrio numerico;
- salvataggio e apertura dei progetti JSON;
- relazione stampabile in PDF.

## Campo di applicazione

È uno strumento di predimensionamento. Non costituisce una portata autorizzata né una verifica completa secondo RINA, DNV o altro registro navale. Nodi, saldature, fissaggi, ancoraggi, carichi puntuali e mobili, fatica, vibrazioni, urti, accelerazioni navali, instabilità globale e proprietà certificate dei prodotti richiedono verifiche separate.

## Licenza

Il codice è pubblicato per uso tecnico e personale. Prima di riutilizzarlo in un progetto reale, verificare formule, ipotesi, materiali e regolamento applicabile con un tecnico qualificato.
