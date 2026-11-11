# AmpliEvent — Download

Programma per Windows che distribuisce la **traduzione simultanea** agli smartphone del pubblico, in rete locale, **senza app da installare**: il pubblico inquadra un QR code, sceglie la lingua e ascolta con le proprie cuffie.

## Scarica

1. Apri la pagina [**Releases**](../../releases/latest).
2. Scarica l'installatore (Windows 10/11, 64 bit):
   - `AmpliEvent-Admin-…-Setup.exe`: modalità **Admin**, scegli da un menu quali moduli installare;
   - oppure un installatore per ogni modulo: `AmpliEvent-Traduzione-…`, `AmpliEvent-Domande-…`, `AmpliEvent-Video-…`. Se più tardi ne installi un altro, si aggiunge a quello già presente.
   (In alternativa lo zip `AmpliEvent-…-windows.zip`: estrai la cartella e fai doppio clic su `amplievent.exe`.)
3. Durante l'installazione incolla il testo della **licenza** ricevuta (si può anche fare dopo, dalla scheda **Licenza** della regia). Ogni modulo funziona solo con la sua licenza; una prova di 24 ore si richiede dal sito www.amplievent.com.

Se compare "Windows ha protetto il PC": *Ulteriori informazioni → Esegui comunque*. Al primo avvio consenti l'accesso alle **Reti private** (serve al pubblico per collegarsi).

Il file `SHA256SUMS.txt` permette di controllare che il download sia integro.

## Come si usa

1. Si apre la **finestra di regia**: nella scheda **Evento** scegli il nome, la WiFi (nome e password) e, per ogni lingua, la scheda audio da cui arriva l'interprete. Premi **Salva e applica**.
2. Nella scheda **Pagina** scegli titolo, benvenuto, colori e logo che vedrà il pubblico.
3. Nella scheda **QR** trovi i codici da mostrare, proiettare a tutto schermo o stampare in PDF:
   - **due QR** (predefinito, funziona con qualsiasi router): il primo collega il telefono alla WiFi, il secondo apre la pagina;
   - **QR unico**: richiede di impostare nel router, come DNS, l'IP del PC di regia.
4. Il pubblico inquadra, sceglie la lingua e ascolta. Chi vuole può anche scrivere una **domanda ai relatori**; il moderatore la vede dal telefono con un QR riservato.

**Esporta / Importa** (scheda Evento) salva e ricarica schede audio, lingue, pagina del pubblico, WiFi e video: comodo per riusare un evento.

## Video (facoltativo)

Dalla scheda **Video** si può mandare ai telefoni l'anteprima del programma in onda e permettere di **salvare il fotogramma in Full HD**. Sorgenti: scheda di acquisizione o OBS Virtual Camera, flusso di rete (SRT, RTMP, RTSP, UDP) e **NDI®**.

Per NDI la libreria `Processing.NDI.Lib.x64.dll` è inclusa nel pacchetto, accanto a `amplievent.exe`: non spostarla (informazioni: https://ndi.video/).

## Requisiti

- Windows 10/11 a 64 bit, collegato in rete (meglio via cavo) alla stessa rete della WiFi dell'evento.
- Una scheda audio (o più) da cui prendere il segnale di ogni interprete.
- Tutto funziona **senza internet**.

---

**Crediti** · [Andrea Battaglioli](https://www.andreabattaglioli.it/)

Powered by [mywebtvlive.com](https://www.mywebtvlive.com/) · © 2026 AmpliEvent · Made in Bolognina

NDI® is a registered trademark of Vizrt NDI AB.
