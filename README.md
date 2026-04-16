# 📊 Repository Gantt Progetti

## Scopo del repository

Questo repository contiene i diagrammi di Gantt relativi alle attività progettuali, realizzati in formato HTML interattivo e pubblicati tramite GitHub Pages.

L'obiettivo è fornire una rappresentazione chiara e condivisibile delle pianificazioni di progetto, consentendo la consultazione sia tramite browser web sia tramite integrazione nelle pagine di documentazione (es. Confluence).

I diagrammi qui contenuti sono utilizzati come riferimento ufficiale per:

* pianificazione delle attività
* monitoraggio delle dipendenze
* verifica delle milestone
* comunicazione dello stato avanzamento lavori
* supporto alle attività di coordinamento tra team

---

## 📁 Struttura del repository

La struttura del repository è organizzata per progetto.

```plaintext
/
├── index.html                → Pagina principale (facoltativa)
├── progetto-a/
│   ├── index.html            → Gantt principale del progetto
│   ├── gantt-v1.html         → Versioni precedenti (opzionale)
│   └── assets/               → CSS, JS o immagini di supporto
│
├── progetto-b/
│   ├── index.html
│   └── assets/
│
└── README.md
```

Ogni progetto deve essere contenuto in una directory dedicata.

---

## 🌐 Pubblicazione tramite GitHub Pages

I diagrammi vengono pubblicati tramite GitHub Pages.

URL di pubblicazione:

```plaintext
https://<username>.github.io/<repository-name>/
```

Esempi:

```plaintext
https://username.github.io/gantt-progetti/progetto-a/
https://username.github.io/gantt-progetti/progetto-b/
```

---

## 🔗 Integrazione con Confluence

I Gantt pubblicati possono essere incorporati nelle pagine Confluence tramite la macro:

```plaintext
/embed
```

Utilizzando l'URL GitHub Pages del progetto.

Esempio:

```plaintext
https://username.github.io/gantt-progetti/progetto-a/
```

Questo consente la visualizzazione interattiva del Gantt direttamente nella documentazione di progetto.

---

## 🛠️ Modalità di aggiornamento

Per aggiornare un Gantt esistente:

1. Modificare il file HTML relativo al progetto.
2. Effettuare il commit delle modifiche.
3. Attendere la pubblicazione automatica tramite GitHub Pages.
4. Verificare la corretta visualizzazione tramite URL pubblico.
5. Aggiornare eventuali riferimenti documentali se necessario.

---

## ➕ Aggiunta di un nuovo progetto

Per aggiungere un nuovo Gantt:

1. Creare una nuova directory con il nome del progetto.

Esempio:

```plaintext
progetto-nuovo/
```

2. Inserire il file:

```plaintext
index.html
```

contenente il Gantt.

3. Inserire eventuali file di supporto:

```plaintext
assets/
```

4. Effettuare commit e push.

Il nuovo Gantt sarà automaticamente pubblicato.

---

## 📌 Convenzioni di naming

Per garantire uniformità, utilizzare le seguenti convenzioni:

Directory progetto:

```plaintext
nome-progetto
```

File principale:

```plaintext
index.html
```

Versioni alternative:

```plaintext
gantt-v1.html
gantt-v2.html
gantt-baseline.html
```

---

## 🔄 Versioning dei Gantt

Quando viene effettuata una modifica significativa alla pianificazione:

* mantenere una copia della versione precedente
* incrementare la versione del file
* aggiornare la documentazione correlata

Esempio:

```plaintext
gantt-v1.html
gantt-v2.html
gantt-baseline.html
```

---

## ⚠️ Note operative

* I file HTML devono essere compatibili con browser moderni.
* Evitare riferimenti a risorse locali non presenti nel repository.
* Tutti gli asset devono essere inclusi nella directory del progetto.
* Verificare sempre il funzionamento del Gantt dopo la pubblicazione.

---

## 👥 Responsabilità

Il mantenimento e l'aggiornamento dei Gantt è responsabilità del team di progetto.

Ogni modifica deve essere:

* tracciata tramite commit
* documentata se rilevante
* verificata prima della condivisione

---

## 📚 Riferimenti

* Documentazione tecnica di progetto
* Pianificazione delle attività
* Milestone approvate
* Dipendenze funzionali e tecniche
