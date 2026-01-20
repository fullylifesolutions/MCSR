# M.C.S.R. - Monitoraggio Clima di Sicurezza Responsabile

## 📊 App Responsabile

Progressive Web App per responsabili sicurezza: raccolta, analisi e reporting dei questionari aziendali sul clima di sicurezza.

---

## 🚀 Caratteristiche

- ✅ **Gestione multi-azienda e multi-divisione**
- ✅ **Import massivo** file JSON collaboratori
- ✅ **Filtraggio automatico** per azienda/divisione/periodo
- ✅ **Dashboard analitica** con statistiche e grafici
- ✅ **Visualizzazione dettagliata** 36 domande per questionario
- ✅ **Report PDF Divisione** con grafico radar
- ✅ **Report PDF Aziendale** con analisi comparative
- ✅ **Storico multi-periodo** navigabile
- ✅ **Backup completo** dati e configurazioni
- ✅ **Funzionamento offline** (PWA)

---

## 📦 Installazione

### Desktop (Consigliato)
1. Apri l'app nel browser (Chrome/Edge)
2. Clicca sull'icona "Installa" nella barra degli indirizzi
3. Conferma installazione
4. L'app apparirà come programma standalone

### Mobile
1. Apri in browser
2. Menu → "Aggiungi a Home"
3. Icona M.C.S.R. sulla schermata home

---

## 🎯 Setup Iniziale (IMPORTANTE!)

### Prima di caricare file:

1. **Inserisci Nome Responsabile**
2. **Click "⚙️ Gestisci Aziende e Divisioni"**
3. **Opzione 1** → Inserisci aziende (una per riga):
   ```
   Acme S.p.A.
   Beta Industries
   ```
4. **Opzione 2** → Seleziona azienda → Inserisci divisioni:
   ```
   Produzione
   Magazzino
   Amministrazione
   ```
5. **Ripeti** per ogni azienda
6. **Seleziona** azienda, divisione, mese, anno
7. **Click "🔍 Applica Filtri"**

**Ora puoi caricare i file!**

---

## 📥 Caricamento Questionari

### Procedura Mensile:

1. **Raccogli** file JSON dai collaboratori (via email)
2. **Seleziona** filtri (azienda, divisione, periodo)
3. **Click "Applica Filtri"**
4. **Click sezione "📤 Carica Questionari"**
5. **Seleziona** tutti i JSON (Ctrl+Click multiplo)
6. **Attendi** caricamento
7. **Leggi feedback**: 
   - ✅ X caricati (corrispondono ai filtri)
   - ⚠️ Y saltati (diversa azienda/divisione/periodo)
8. **Dashboard** si aggiorna automaticamente

---

## 📊 Analisi Dati

### Dashboard
- **Statistiche**: Totale questionari, media, aree critiche
- **Grafico Radar**: Visualizzazione 6 dimensioni aggregate
- **Lista Questionari**: Click per dettagli completi

### Visualizzazione Dettaglio
- Click su questionario → Modal con:
  - Info collaboratore
  - Punteggio complessivo
  - **Tutte le 36 risposte** con barre colorate
  - Note aggiuntive

### Identificazione Problemi
- **Barre rosse**: Domande critiche (punteggio < 2.5)
- **Pattern**: Stessa domanda bassa per più persone = problema sistematico

---

## 📄 Report PDF

### Report PDF Divisione
**Quando**: Analisi specifica divisione
**Contenuto**:
- Azienda, divisione, periodo, responsabile
- N. questionari e media
- **Grafico radar immagine**
- Punteggi per dimensione (colorati)
- Note collaboratori

**File**: `Report_Acme_Produzione_2025_01.pdf`

### Report PDF Aziendale
**Quando**: Confronto tutte le divisioni
**Contenuto**:
- Panoramica aziendale
- Totale questionari
- **Grafico radar aggregato aziendale**
- Analisi per divisione (medie colorate)
- Punteggi dimensioni aggregati

**File**: `Report_Aziendale_Acme_2025_01.pdf`

---

## 🔄 Navigazione Multi-Periodo

### Cambiare Periodo:
1. Cambia Mese/Anno nei dropdown
2. Click "Applica Filtri"
3. Dashboard carica dati del nuovo periodo

**Tutti i dati restano salvati!** Puoi tornare ai periodi precedenti.

---

## 💾 Backup

### Quando fare backup:
- Dopo ogni caricamento mensile
- Prima di cancellare dati browser
- Per archiviazione sicurezza

### File Backup contiene:
- Tutti i questionari di tutti i periodi
- Configurazioni aziende/divisioni
- Storico completo

### Ripristino:
- Click "💾 Backup" → Salva JSON
- Per ripristinare: carica il file backup

---

## 📱 Compatibilità

- ✅ **Desktop** (Chrome, Edge) - **CONSIGLIATO**
- ✅ Tablet (tutti i browser)
- ✅ Mobile (per visualizzazione, meno comodo per caricamenti)

---

## 🎨 Colori Brand

- Primario: `#05BFDB` (Azzurro)
- Secondario: `#00FFCA` (Verde acqua)
- Sfondo: `#1A1A2E` (Dark)

---

## ⚡ Best Practices

1. **Backup mensile** dopo caricamento
2. **Genera PDF** subito per archiviare
3. **Usa Desktop** per analisi e report
4. **Non cancellare** dati browser senza backup
5. **Auto-popolamento**: Lascia che le liste si riempiano dai JSON

---

## 🆘 Troubleshooting

### File non si caricano
→ Hai applicato i filtri?
→ I file corrispondono ad azienda/divisione/periodo selezionati?

### PDF non genera grafico
→ Aspetta caricamento completo dashboard prima di esportare

### Dati scomparsi
→ Hai cancellato i dati del browser?
→ Ripristina da backup

---

## 📄 Licenza

Copyright © 2025 - Tutti i diritti riservati

---

## 📚 Documentazione

Manuale completo disponibile nell'app:
**Click "❓ Istruzioni"** in alto a destra

---

## 🔐 Privacy e Sicurezza

- **Dati locali**: Salvati solo nel browser del responsabile
- **No cloud**: Nessun invio automatico a server esterni
- **Controllo totale**: Tu gestisci quando e dove esportare i report
- **GDPR compliant**: I dati rimangono sotto il tuo controllo
