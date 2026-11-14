# CHARLIE26 – Intercom Evoluto: download

Qui si scarica l'ultima versione di **CHARLIE26**, l'intercom di produzione per eventi: un canale Produzione e canali di reparto, con i tecnici che si collegano dallo **smartphone** inquadrando un QR code, senza installare nulla. Funziona in rete locale, senza internet. Ci sono anche le [brochure in 6 lingue](brochure/).

| Per | File |
| --- | --- |
| Windows 10 e 11 (64 bit), installer con la libreria NDI® | [charlie26-setup.exe](https://github.com/battacharlie/charlie26_download/releases/latest/download/charlie26-setup.exe) |
| Mac con chip Apple (M1, M2, M3…) | [charlie26-darwin-arm64](https://github.com/battacharlie/charlie26_download/releases/latest/download/charlie26-darwin-arm64) |
| Mac con processore Intel | [charlie26-darwin-amd64](https://github.com/battacharlie/charlie26_download/releases/latest/download/charlie26-darwin-amd64) |
| Android (app per tecnici e regia da smartphone) | [charlie26-android.apk](https://github.com/battacharlie/charlie26_download/releases/latest/download/charlie26-android.apk) |
| Verifica dei file | [SHA256SUMS.txt](https://github.com/battacharlie/charlie26_download/releases/latest/download/SHA256SUMS.txt) |

Le novità di ogni versione sono nella [release](https://github.com/battacharlie/charlie26_download/releases/latest).

## Versione gratuita e licenza

Il programma si può provare gratis, senza registrazione: la versione gratuita funziona **4 ore a ogni avvio** (poi va chiusa e riaperta), con **al massimo 2 canali** (Produzione compresa), **regia + 3 telefoni** insieme e **solo nella rete locale**, senza accesso da internet. Tutte le funzioni sono sempre disponibili.

La **licenza annuale** (50 € l'anno) toglie i limiti (tempo, canali, telefoni): si richiede dal modulo su [charlie26inter.com](https://www.charlie26inter.com/#licenza), si riceve fattura e file di licenza via email e si attiva incollandola nella scheda *Licenza* della console, senza riavviare. Non è legata a un computer. Alla scadenza si torna alla versione gratuita.

L'edizione con accesso da remoto (server su internet) ha una licenza a parte, su appuntamento.

## Come si avvia

**Windows**: doppio clic sull'installer e segui la procedura (serve l'amministratore: aggiunge anche la regola del firewall). Si disinstalla da *App installate*. Se compare "Windows ha protetto il PC": *Ulteriori informazioni → Esegui comunque*. Al primo avvio consenti l'accesso alle **Reti private**. Il programma resta come icona vicino all'orologio.

**Mac** (file non firmati da Apple), nel Terminale:
```
chmod +x charlie26-darwin-arm64
xattr -d com.apple.quarantine charlie26-darwin-arm64
./charlie26-darwin-arm64
```

**Android**: apri `charlie26-android.apk` dal telefono e consenti "Installa app sconosciute" per il browser o per File.

## NDI®

L'installer per Windows **include la libreria NDI®**, quindi l'audio del programma da sorgenti NDI funziona subito. Su Mac la libreria NDI non è inclusa.

NDI® is a registered trademark of Vizrt NDI AB.

---

CHARLIE26 – Intercom Evoluto  
Ideato e sviluppato da [www.andreabattaglioli.it](https://www.andreabattaglioli.it) · [MyWebTvLive.com](https://www.mywebtvlive.com) · Made in Bolognina
