# 🎵 Audio Converter (Standalone .exe)

Un'applicazione desktop sviluppata in **Python** con **CustomTkinter**, convertita in **file eseguibile (.exe)** con inclusi **ffmpeg.exe, ffplay.exe e ffprobe.exe**.

👉 Funziona **standalone su Windows 10/11** senza necessità di installare Python o altre librerie.

<img width="847" height="671" alt="Immagine 2025-08-16 175741" src="https://github.com/user-attachments/assets/9643fce3-eed3-46a5-8783-92860c04c4d2" />


## ✨ Funzionalità

* 🎼 Conversione di file audio in diversi formati:

  * MP3, FLAC, AAC, OGG, WAV
* 🖼️ Estrazione automatica della copertina (se presente nei tag ID3/FLAC)
* 📂 Possibilità di selezionare una copertina manualmente
* 🎨 Interfaccia moderna e scura con **CustomTkinter**
* 📁 Selezione della cartella di destinazione + apertura diretta
* 📜 Log in tempo reale durante la conversione
* ✅ Nessuna dipendenza esterna: FFmpeg integrato

---

## 🛠️ Requisiti

* **Windows 10 o Windows 11**
* Basta fare doppio clic sul file `AudioConverter.exe` per avviare l’applicazione

> ⚠️ Su sistemi Linux potrebbe essere eseguito tramite **Wine**, ma non è ancora stato testato.

---

## ▶️ Utilizzo

1. Scarica il file `AudioConverter.exe`
2. Fai doppio clic per avviarlo
3. Seleziona un **file audio** da convertire
4. Scegli la **cartella di destinazione**
5. Seleziona il **formato di uscita**
6. (Opzionale) Aggiungi una copertina manualmente
7. Premi **Converti Audio**

Il programma creerà il nuovo file e mostrerà i log della conversione.

---

## ⚙️ Tecnologie utilizzate

* Python
* Tkinter + CustomTkinter
* FFmpeg (integrato nell’eseguibile)
* Pillow (PIL)
* Mutagen

---

## 🚀 Roadmap (idee future)

* [ ] Supporto per conversioni batch (più file alla volta)
* [ ] Scelta del bitrate personalizzato
* [ ] Supporto a ulteriori formati audio
* [ ] Versione portabile per Linux/macOS

---

## 📺 Autore

Sviluppato da **Alex Lignola**
📌 Release 1.0.2 (2025)
YouTube: [@AngoloInformatico](https://www.youtube.com/@AngoloInformatico)

---

## ⚖️ Licenza

- Il codice di questo progetto è rilasciato con licenza **BSD-3-Clause license**.
- Una copia della licenza è disponibile nel file [LICENSE](LICENSE).

## Terze parti
Questo pacchetto include:
- **FFmpeg (ffmpeg.exe, ffplay.exe, ffprobe.exe)**  
  Rilasciato con licenza **GPL v2 o successiva**.  
  Vedi il file NOTICE-FFmpeg.txt per dettagli.  
 

