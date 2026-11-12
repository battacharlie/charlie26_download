# CHARLIE26 – Intercom Evoluto: download

Qui si scarica l'ultima versione di **CHARLIE26**, l'intercom di produzione per eventi: un canale Produzione e canali di reparto, con i tecnici che si collegano dallo **smartphone** inquadrando un QR code, senza installare nulla. Funziona in rete locale, senza internet.

| Per | File |
| --- | --- |
| Windows 10 e 11 (64 bit) | [charlie26-windows-amd64.exe](https://github.com/battacharlie/charlie26_download/releases/latest/download/charlie26-windows-amd64.exe) |
| Mac con chip Apple (M1, M2, M3…) | [charlie26-darwin-arm64](https://github.com/battacharlie/charlie26_download/releases/latest/download/charlie26-darwin-arm64) |
| Mac con processore Intel | [charlie26-darwin-amd64](https://github.com/battacharlie/charlie26_download/releases/latest/download/charlie26-darwin-amd64) |
| Android (app per tecnici e regia da smartphone) | [charlie26-android.apk](https://github.com/battacharlie/charlie26_download/releases/latest/download/charlie26-android.apk) |
| Verifica dei file | [SHA256SUMS.txt](https://github.com/battacharlie/charlie26_download/releases/latest/download/SHA256SUMS.txt) |

Le novità di ogni versione sono nella [release](https://github.com/battacharlie/charlie26_download/releases/latest).

## Come si avvia

**Windows**: doppio clic. Se compare "Windows ha protetto il PC": *Ulteriori informazioni → Esegui comunque*. Al primo avvio consenti l'accesso alle **Reti private**. Il programma resta come icona vicino all'orologio.

**Mac** (file non firmati da Apple), nel Terminale:
```
chmod +x charlie26-darwin-arm64
xattr -d com.apple.quarantine charlie26-darwin-arm64
./charlie26-darwin-arm64
```

**Android**: apri `charlie26-android.apk` dal telefono e consenti "Installa app sconosciute" per il browser o per File.

## NDI®

L'audio del programma può arrivare da una sorgente NDI®: serve il programma NDI Tools/Runtime sul computer di regia (da [ndi.video](https://ndi.video); non è incluso).

NDI® is a registered trademark of Vizrt NDI AB.

---

CHARLIE26 – Intercom Evoluto  
Ideato e sviluppato da [www.andreabattaglioli.it](https://www.andreabattaglioli.it) · [MyWebTvLive.com](https://www.mywebtvlive.com) · Made in Bolognina
