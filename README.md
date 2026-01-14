# Tech Repair – Update Repository

Questa repository **non contiene codice sorgente**.

Serve esclusivamente a distribuire:
- i file di aggiornamento (release) dell’app **Tech Repair**
- il file `latest.json` necessario al sistema di **auto-update** (Tauri)

## 🧰 Cos’è Tech Repair
**Tech Repair** è una desktop app per la gestione operativa di un laboratorio di riparazioni.
Permette di organizzare in modo semplice:
- anagrafica clienti
- ticket/riparazioni e stati di lavorazione
- magazzino componenti
- preventivi e pagamenti
- stampa/generazione documenti (PDF)

L’app è pensata per essere installabile e utilizzabile come un normale programma su Windows.

## 🔒 Privacy e sicurezza
Il codice sorgente dell’app è mantenuto in una repository privata.
Qui vengono pubblicati **solo** gli artefatti necessari all’installazione e agli aggiornamenti.

---

## 📦 Contenuto della repo
In ogni release vengono caricati (almeno) i seguenti file:

- `latest.json`  
  Manifest usato dall’updater per capire versione, url e firma.

- Installer Windows (esempio):
  - `tech-repair_0.1.3_x64-setup.exe`
  - `tech-repair_0.1.3_x64-setup.exe.sig`

- Installer Windows (msi) 
  - `tech-repair_0.1.3_x64_en-US.msi`  
  - `tech-repair_0.1.3_x64_en-US.msi.sig`
