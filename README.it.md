<div align="center">
  <img src="public/icon.png" alt="Second Brain Logo" width="120" />
  <h1>Second Brain 🧠</h1>
  <p><strong>Il tuo assistente per colloqui invisibile basato sull'IA</strong></p>

  [English](README.md) | [Português](README.pt.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md)
</div>

<br/>

**Second Brain** è un assistente desktop 100% gratuito e invisibile creato per aiutare i professionisti di tutto il mondo a eccellere nei loro colloqui di lavoro. Viene eseguito silenziosamente in background, ascolta il colloquio e genera suggerimenti di risposta in prima persona basati sul tuo curriculum e sulla descrizione della posizione.

Alimentato dall'inferenza ultra-veloce Llama-3 di [Groq](https://groq.com) e dal modello Whisper-large-v3, l'intero processo — dall'acquisizione vocale al suggerimento intelligente — avviene in pochi millisecondi.

## ✨ Funzionalità

- **Trascrizione Vocale in Tempo Reale**: Utilizza Whisper-v3 tramite l'API Groq per trascrivere il discorso dell'intervistatore con estrema precisione e velocità.
- **Suggerimenti Contestuali**: Analizza la conversazione in corso, il tuo curriculum e la descrizione della posizione per suggerire le migliori risposte possibili.
- **Supporto Multilingue**: Interfaccia e motore IA localizzati al 100% per Inglese, Portoghese, Spagnolo, Francese e Italiano.
- **Modalità Invisibile**: Costruito con Electron, può essere ridotto a icona per non disturbare mentre ti concentri sulla tua videochiamata.
- **Privacy al Primo Posto**: Il tuo curriculum, l'offerta di lavoro e le tue chiavi API vengono salvati esclusivamente nella memoria locale (`localStorage`) del tuo computer.

## 🚀 Guida Rapida (Download)

1. **Scarica il Programma di Installazione:**
   Ottieni l'ultimo `Second Brain Setup .exe` dalla nostra pagina [Releases](../../releases).
   
2. **Crea una Chiave API Groq Gratuita:**
   Vai su [console.groq.com](https://console.groq.com/keys) e genera una chiave API gratuita. È essenziale per eseguire il motore IA ad alta velocità.

3. **Installa e Configura:**
   - Apri l'applicazione.
   - Incolla la tua Chiave API.
   - Incolla il tuo Curriculum e la Descrizione della Posizione.
   - Seleziona la tua lingua.
   - Clicca su **Inizia il Colloquio** e sei pronto!

## 🛠️ Sviluppo (Per Programmatori)

Se desideri compilare il codice sorgente o contribuire:

### Prerequisiti
- Node.js 18+
- npm o yarn

### Installazione

```bash
git clone https://github.com/2brain/second-brain.git
cd second-brain

# Installa le dipendenze
npm install

# Avvia il server di sviluppo
npm run dev
```

### Compilazione per la Produzione (Installatore)

```bash
# Compilare e generare l'installatore Electron
npm run dist
```
L'installatore `.exe` verrà generato all'interno della cartella `dist-installers`.

## 🤝 Sostieni il Progetto

Second Brain è open-source e gratuito per la comunità. Se questo strumento ti ha aiutato a ottenere un lavoro o a superare brillantemente un colloquio, offrici un caffè!

<a href="https://www.buymeacoffee.com/2brain" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 40px !important;width: 145px !important;" ></a>

## 📝 Licenza

Distribuito con una Licenza Non Commerciale. Sei libero di utilizzare e studiare il software, ma **la vendita o la distribuzione commerciale è severamente vietata**. Consulta il file `LICENSE` per ulteriori informazioni.
