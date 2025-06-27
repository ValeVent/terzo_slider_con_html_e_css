Slider 3D

Questo progetto implementa uno slider di immagini 3D innovativo, realizzato interamente con HTML e CSS. Le immagini ruotano in uno spazio tridimensionale, accompagnate da un cambio di colore dello sfondo sincronizzato per un'esperienza visiva dinamica e coinvolgente.


Descrizione Approfondita del Progetto

Lo slider crea l'illusione di una galleria fotografica tridimensionale in continua rotazione. A differenza dei caroselli tradizionali, l'animazione e la trasformazione delle immagini sono gestite esclusivamente tramite le proprietà CSS transform-style: preserve-3d, transform, e le @keyframes, senza l'uso di JavaScript per il movimento principale. Il colore di sfondo del corpo della pagina cambia in perfetta armonia con la rotazione delle immagini, arricchendo l'esperienza visiva.


Tecnologie Utilizzate

. HTML5: Struttura di base della galleria e contenitore delle immagini.

. CSS3: La tecnologia chiave per le animazioni. Utilizza:

 . Trasformazioni 3D (transform, perspective, rotateX, rotateY, translateZ) per posizionare le immagini nello spazio tridimensionale.

 . Animazioni (@keyframes) per controllare la sequenza di rotazione delle immagini e il cambiamento dei colori di sfondo.

 . Proprietà CSS Custom (--s, --_p, --_t) per rendere il codice più leggibile e modulare.


Funzionalità Principali

. Galleria Immagini 3D: Le immagini si dispongono e ruotano in uno spazio tridimensionale.

. Animazione Continua: Lo slider anima automaticamente e ininterrottamente.

. Pure CSS: Tutta l'animazione e la logica 3D sono gestite esclusivamente tramite CSS, senza l'ausilio di JavaScript per il movimento.

. Sfondo Dinamico: Il colore di sfondo della pagina cambia in modo sincronizzato con l'animazione delle immagini, creando un'esperienza visiva coerente.


Come Avviare il Progetto

Segui questi semplici passaggi per visualizzare il progetto localmente:


Prerequisiti

Non sono richiesti particolari prerequisiti oltre a un browser web moderno che supporti le trasformazioni CSS3 (tutti i browser moderni lo fanno).


Installazione

1. Clona il repository (o scarica la cartella del progetto):

git clone https://github.com/ValeVent/slider-3d.git

Assicurati di sostituire 'slider-3d.git' con il nome esatto del tuo repository.

2. Naviga nella directory del progetto:

cd slider-3d


Avvio dell'Applicazione

- Assicurati che i file immagine (es. media/pexels-jamaal-hutchinson-675024091-18696933 1.png, ecc.) siano presenti nella cartella media all'interno della directory del progetto.

- Apri il file index.html (o il nome del tuo file HTML principale) direttamente nel tuo browser web.

Se hai installato http-server globalmente (opzionale, per un server locale):

npm install -g http-server
http-server .

L'applicazione sarà accessibile all'indirizzo mostrato dal server (es. http://localhost:8080).


Stato del Progetto

Questo progetto è un esempio funzionale di animazione 3D puramente CSS, che dimostra capacità avanzate di styling e trasformazioni web.


Contatti

GitHub: https://github.com/ValeVent

LinkedIn: https://www.linkedin.com/in/valentina-venturo

Sito Web: http://www.valentinaventuro.it
