# 🎯 FocusTask

Una **web app gamificata** per gestire richieste di supporto con focus, streak e livelli! 

Perfetta per help desk, supporto tecnico, e gestione ticket con un tocco di divertimento.

---

## ✨ Features Principali

- 📊 **Kanban Board** - TODO → IN WORK → WAITING → DONE con drag & drop
- 📧 **Parsing PDF Automatico** - Google Gemini AI estrae dati dalle email
- 🎮 **Gamification Completa** - XP, livelli, streak, achievements
- 📅 **Appuntamenti Videocall** - Fissa assistenze, rinvia, completa
- 📞 **Solleciti Visivi** - Traccia quante volte hai sollecitato (barrette "carcere")
- 🎯 **Planning Intelligente** - Auto-schedule ticket negli slot orari
- 🖨️ **Planning Stampabile** - Stampa il tuo giorno su 1 foglio A4 fronte-retro
- 📋 **Personalizzazione Totale** - Routine e categorie custom
- 📊 **Dashboard Giornaliero** - Statistiche completati, streak, livello
- 💾 **Offline-First** - Funziona senza internet, localStorage
- 📤 **Backup JSON** - Esporta/importa i tuoi dati
- 🌙 **Dark Mode Ready** - Comoda anche la sera
- 🎓 **Tutorial Interattivo** - 24 step con spotlight per imparare tutto

---

## 🚀 Come Usare

### Installazione

1. **Scarica** il file `focustask.html`
2. **Doppio click** per aprire nel browser (niente server necessario!)
3. **Fine!** L'app è pronta all'uso

### Prima Volta?

Clicca **❓ Tutorial** in alto a destra per una guida completa di 24 step interattivi!

---

## 🎮 Workflow Consigliato

### Mattina - Setup
1. Clicca **➕ Aggiungi Task** o **📧 PDF Email** per carica le richieste
2. Gemini AI analizza automaticamente i PDF (se configurato)
3. Stima i task che farai oggi

### Durante il Giorno
1. **Kanban** - Trascina i task: TODO → IN WORK → WAITING → DONE
2. **⚡ Focus Mode** - Clicca su un task IN WORK per modalità fullscreen
3. **📞 Sollecita** - Clicca [+] nel modale per tracciare solleciti
4. **✓ Completa** - Clicca il bottone verde per gain XP!

### Sera - Recap
1. Guarda **📊 Dashboard** per statistiche del giorno
2. Mantieni lo **streak** 🔥 completando almeno un task
3. Ogni **sabato** → Auto-clear DONE per fresh start

---

## 🔑 Configurazione Opzionale: Gemini AI

Per usare il **parsing PDF automatico**, configura Google Gemini (GRATIS!):

### Passi

1. Vai su **https://aistudio.google.com/app/apikey**
2. Accedi con il tuo account Google
3. Clicca **"Create API Key"** (no carta di credito!)
4. **Copia** la chiave
5. Apri FocusTask → ⚙️ **Impostazioni**
6. Incolla in **"Gemini API Key"**
7. **Salva** - Pronto!

### Caratteristiche

- ✅ Completamente **GRATIS** - Niente piano a pagamento
- ✅ Niente carte di credito
- ✅ Limiti: **15 richieste/min** (più che sufficiente!)
- 📖 [Guida Ufficiale Google](https://ai.google.dev/gemini-api/docs/api-key)

---

## ⚙️ Personalizzazione

### Routine Giornaliere

In **⚙️ Impostazioni → Routine Personalizzate**:

- **Aggiungi** routine nuove (es: "Contatta CEO", "Analizza bug")
- **Modifica** nome e XP di ogni routine
- **Elimina** quando non servono più
- **Spunta** ogni giorno per bonus XP

Default: Sollecita fornitori + Follow-up clienti

### Categorie Ticket

In **⚙️ Impostazioni → Categorie Tipo**:

- **Aggiungi** categorie custom (es: "Manutenzione", "Consulenza")
- **Modifica** i nomi (es: "Ricambio" → "Parts Supply")
- **Elimina** quando non servono
- I dropdown si aggiornano automaticamente!

Default: Ricambio, Assistenza, Info/Reclami

### Orari di Lavoro

In **⚙️ Impostazioni → Orari di Lavoro**:

Configura il tuo orario per il Planning:
- Inizio mattina (default: 08:30)
- Fine mattina (default: 12:30)
- Inizio pomeriggio (default: 14:00)
- Fine pomeriggio (default: 18:00)

---

## 🖨️ Planning Stampabile

### Come Stampare il Tuo Giorno

1. Vai nel tab **📅 PLANNING**
2. Clicca **[🤖 Auto]** per pianificare i task
3. Clicca **[🖨️ Stampa]** per anteprima
4. Clicca **[🖨️ Stampa Pagina]** o Ctrl+P
5. **Stampa su 1 foglio A4 fronte-retro**

### Cosa Vedrai

**FRONTE (Mattina)**:
```
Ora | Titolo Task | Cliente | Tipo | Priorità
08:30 | Ricambio pompa | ACME | Ricambio | Alta
09:00 | Assistenza | PIERO | Assistenza | Media
...
```

**RETRO (Pomeriggio)**:
```
14:00 | Setup server | CAR SERVICE | Assistenza | Alta
14:45 | Consulenza | PIERO | Ricambio | Media
...
```

### Info Salienti per ogni Task

| Campo | Utilità |
|-------|---------|
| **ORA** | Quando fare il task |
| **TITOLO** | Cosa devi fare |
| **CLIENTE** | Chi è interessato ✅ |
| **TIPO** | Categoria (Ricambio/Assistenza/Info) |
| **PRIORITÀ** | Urgenza (Alta/Media/Bassa) |

### Vantaggi

- ✅ Uno **foglio A4 per il giorno completo**
- ✅ **Fronte-retro** (mattina + pomeriggio)
- ✅ Consultabile **senza app** durante il lavoro
- ✅ Tutto quello che serve **a colpo d'occhio**
- ✅ Perfetto per **avere sempre con te**

---

## 📱 Browser Support

| Browser | Desktop | Mobile |
|---------|---------|--------|
| Chrome/Edge | ✅ | ✅ |
| Firefox | ✅ | ✅ |
| Safari | ✅ | ✅ |
| Opera | ✅ | ✅ |

**Consigliato**: Chrome/Edge per migliore compatibilità

---

## 💡 Tips & Tricks

### Kanban
- **Drag & drop** le card tra le colonne
- **Clicca card** per aprire dettagli completi
- **⚡ Solo RAPIDI** - Filtra solo quick wins

### Quick Wins
- Un ticket è "rapido" se ha **ricambio + codice** oppure **risposta a offerta**
- Guadagnano **⚡ badge** sulla card
- Puoi marcare manualmente in dettagli ticket

### Focus Mode
- Per ticket **IN WORK** → **[🎯 Focus Mode]** per fullscreen
- Perfetto per concentrarsi senza distrazioni
- Uscire con **[✓ Completa]** o **[Continua a guardare]**

### Appuntamenti
- Fissa nel modale ticket con **[📅 Fissa]**
- Vedi nel sidebar **📅 Appuntamenti** per il giorno
- Clicca per dettagli → **[✓ Completa]** o **[📅 Rinvia]**
- Il ticket va in DONE quando completi l'appuntamento

### Planning
- **📅 PLANNING** → Pianifica il tuo giorno con slot orari
- **[🤖 Auto]** → Distribuisce automaticamente i task
- **[🖨️ Stampa]** → Stampa su 1 foglio A4 fronte-retro (Mattina + Pomeriggio)
- **[🔄 Reset]** → Svuota la pianificazione
- **Sabato auto-clear** → Fresh start per la nuova settimana

### Backup
- **💾 Backup** → Scarica un JSON con tutti i tuoi dati
- **📥 Ripristina** → Carica un backup precedente
- Utile se cambi PC o browser!

---

## 🎮 Gamification

### XP
- **Alta priorità**: 50 XP
- **Media priorità**: 25 XP
- **Bassa priorità**: 10 XP
- **Routine**: dipende da come la configuri

### Livelli

Salisci di livello guadagnando XP:
- Livello 1: 0 XP
- Livello 2: 100 XP
- Livello 3: 250 XP
- Livello 4: 450 XP
- Livello 5: 700 XP
- (e così via...)

### Streak

Mantieni una striscia **completando almeno 1 task al giorno**:
- 🔥 Streak 3 giorni = Piccolo traguardo
- 🔥 Streak 7 giorni = Settimana perfetta
- 🔥 Streak 30 giorni = Leggenda!

---

## 📊 Statistiche Giornaliere

Nel **📊 DASHBOARD** vedi:

- ✓ **Completati Oggi** - Quanti task finiti
- 🔄 **Ricambi** - Quanti ricambi risolti
- 🎧 **Assistenze** - Quanti supporto tecnico
- ℹ️ **Info/Reclami** - Quanti info gestite
- ⏳ **In Attesa** - Quanti ticket sono in WAITING
- 📊 **Totali Oggi** - Tutti i task del giorno
- 📈 **Livello** - Il tuo livello attuale
- 🔥 **Streak** - La tua striscia attuale

Azzera ogni sabato per un fresh start!

---

## 🔐 Privacy & Dati

- **Offline-first** - I tuoi dati rimangono nel browser locale
- **localStorage** - Niente cloud, niente server esterno
- **Backup locale** - Esporta JSON quando vuoi
- **Gemini API key** - Salvata solo nel tuo browser
- **Zero tracking** - Niente analitiche, niente cookie

---

## ⚡ Shortcut Utili

| Azione | Come |
|--------|------|
| Aggiungi task | ➕ Aggiungi Task |
| Carica PDF | 📧 PDF Email |
| Dettagli ticket | Click sulla card |
| Modifica ticket | Click nella sezione modale |
| Fissa appuntamento | [📅 Fissa] nel modale |
| Focus mode | [🎯 Focus Mode] nel modale |
| Pianifica giorno | 📅 PLANNING → [🤖 Auto] |
| Stampa planning | 📅 PLANNING → [🖨️ Stampa] |
| Vedi statistiche | 📊 DASHBOARD |
| Personalizza | ⚙️ Impostazioni |
| Impara | ❓ Tutorial |

---

## 🐛 Problemi Comuni

### "I miei dati sono spariti!"
- Controlla se hai **cambiato browser** (localStorage è per browser)
- Usa **💾 Backup** per esportare i dati regolarmente
- Se avevi un backup, usa **📥 Ripristina**

### "Il PDF non si analizza"
- Hai **configurato la Gemini API key**? (⚙️ Impostazioni)
- Il PDF è **leggibile** (non scansionato/immagine)?
- Controlla che la **key sia valida** su https://aistudio.google.com/app/apikey

### "Il tutorial non funziona"
- Clicca **❓ Tutorial** di nuovo
- Hard refresh: **Ctrl+F5** (Windows) o **Cmd+Shift+R** (Mac)

### "Voglio cancellare tutto"
- **Svuota localStorage**: DevTools → Application → Clear all
- Oppure semplicemente crea un nuovo profilo nel browser

### "La stampa non funziona"
- Assicurati di avere **[🤖 Auto] già schedulato** i task
- Prova **Ctrl+P** se [🖨️ Stampa Pagina] non funziona
- Nelle opzioni stampa: attiva **stampa fronte-retro**

---

## 📚 File Inclusi

```
focustask/
├── focustask.html    ← L'app (unico file necessario!)
├── README.md         ← Questa guida
└── LICENSE           ← MIT License
```

---

## 🤝 Contributi

Hai idee per migliorare? Suggerimenti? Bug?

Senti libero di:
- **Fare un fork** del repo
- **Aprire issue** per bug/feature request
- **Condividere** con colleghi/amici

Tutte le contribuzioni sono benvenute! 🚀

---

## 📄 License

Questo progetto è sotto **MIT License**.

Sei libero di:
- ✅ Usare l'app
- ✅ Modificarla
- ✅ Distribuirla
- ✅ Usarla commercialmente

Guarda il file `LICENSE` per dettagli.

---

## 💬 Feedback

Ti piace FocusTask? Hai suggerimenti?

⭐ **Stella il repo** per supportare il progetto!

---

## 🙌 Credits

Creato con ❤️ per help desk, supporto tecnico, e chiunque voglia **gestire il caos con stile e gamification**.

---

**Versione**: 1.1  
**Ultimo aggiornamento**: Maggio 2026  
**Status**: Stabile e Production-Ready

Buon lavoro! 🚀✨
