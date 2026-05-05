---
title: Privacy Policy — Buddy
layout: default
---

🇮🇹 **Italiano** · [🇬🇧 English](./en.html)

# Privacy Policy — Buddy

_Ultimo aggiornamento: 2026-05-05_

## Chi siamo

Buddy è un'app mobile pensata per studenti con DSA, ADHD o difficoltà di apprendimento, ma utilizzabile da chiunque voglia organizzare lo studio. Buddy è sviluppata e gestita da **Alessandro Dianna**, che agisce come **Titolare del trattamento** ai sensi del Regolamento UE 2016/679 (GDPR).

**Contatto privacy**: buddy.coach.ai@gmail.com

## Dati che raccogliamo

Quando crei un account o usi l'app, raccogliamo i seguenti dati:

### Dati forniti direttamente da te
- **Email** — per autenticazione e recupero password
- **Nome utente** (`displayName`) — per personalizzare l'esperienza e identificare l'utente per il Coach
- **Avatar** — emoji preset oppure foto che scegli di caricare
- **Family ID** — codice condiviso tra Coach e Studente per collegare gli account
- **Lingua preferita** (italiano/inglese)
- **Ruolo** — Coach o Studente
- **Consenso GDPR** — registriamo data e ora del consenso fornito durante la registrazione del Coach

### Dati generati dall'utilizzo dell'app
- **Task** che crei (titolo, descrizione, scadenza, priorità, ricompensa)
- **Materiali scolastici** che carichi (foto degli appunti o PDF)
- **Riassunti, mappe concettuali e quiz** generati automaticamente dai tuoi materiali
- **Risultati dei quiz** (punteggi, risposte, data) — inclusi quiz, mini-quiz di ripasso e interrogazioni orali simulate
- **Sessioni Pomodoro** completate (durata, data)
- **Routine** create (titolo, passi, orari)
- **Solleciti** scambiati tra Coach e Studente
- **Statistiche di gamification** (XP, livello, badge, streak)
- **Token push** per ricevere notifiche

### Dati tecnici
- **Identificativo del dispositivo** (token Expo Push Notifications)
- **Statistiche di utilizzo aggregate** (numero di elaborazioni AI mensili, costi stimati) — usate solo dall'amministratore per controllo costi

**Non raccogliamo né tracciamo**: posizione GPS, contatti, dati di pagamento, identificatori pubblicitari, dati biometrici.

## Come usiamo i tuoi dati

I tuoi dati vengono usati esclusivamente per:
- Fornire il servizio (autenticazione, sincronizzazione tra Coach e Studente, generazione contenuti AI)
- Inviare notifiche push relative all'utilizzo dell'app (nuove task, solleciti, promemoria routine, ripassi programmati)
- Migliorare l'esperienza (statistiche di apprendimento mostrate solo all'utente e al suo Coach)
- Controllare i costi operativi (solo l'amministratore può vedere statistiche aggregate di utilizzo)

**Non vendiamo, affittiamo o cediamo i tuoi dati a terze parti** per scopi commerciali o di marketing.

## Servizi di terze parti

Per fornire il servizio Buddy si appoggia ai seguenti fornitori, i quali agiscono come **Responsabili del trattamento** ai sensi del GDPR:

| Servizio | Scopo | Dati condivisi | Sede |
|----------|-------|----------------|------|
| **Google Firebase** (Auth, Firestore, Cloud Messaging) | Autenticazione, database utenti e contenuti, notifiche push | Email, nome, dati app | EU/USA |
| **Cloudflare R2** | Archiviazione file (foto materiali, PDF, avatar) | Immagini e PDF caricati | UE |
| **Anthropic (Claude)** | Estrazione testo da immagini/PDF, generazione mappa concettuale, valutazione risposte aperte | Contenuto dei materiali caricati (testo, immagini), risposte ai quiz | USA |
| **OpenAI** | Generazione riassunti, quiz e voce di lettura ad alta voce (TTS) | Testo estratto dai materiali | USA |
| **Expo (Notifications)** | Inoltro notifiche push | Token dispositivo, contenuto notifica | USA |
| **Sentry** | Diagnostica errori e crash dell'app | Stack trace, contesto tecnico (no contenuti utente) | USA |

Tutti i fornitori USA aderiscono al **Data Privacy Framework UE-USA** o utilizzano **Standard Contractual Clauses (SCC)** per il trasferimento dati.

## Conservazione dei dati

I tuoi dati vengono conservati finché l'account è attivo. Se richiedi la cancellazione (vedi sezione "I tuoi diritti"), tutti i tuoi dati vengono eliminati entro 30 giorni dalla nostra richiesta, fatta eccezione per:
- Dati che dobbiamo conservare per obblighi di legge
- Dati anonimi/aggregati non più riconducibili a te

## Sicurezza

- Le password sono cifrate da Firebase Auth (mai visibili a noi)
- I file materiali sono serviti via URL pubbliche con identificatori non indovinabili
- Le credenziali "ricordami" sul dispositivo sono salvate nel **Keychain iOS / Keystore Android**, non in chiaro
- Gli accessi amministrativi sono protetti da flag server-side `isAdmin` non modificabile dal client

## I tuoi diritti (GDPR)

In qualunque momento puoi:
- **Accedere** ai tuoi dati personali
- **Rettificare** dati inesatti
- **Cancellare** il tuo account e tutti i dati associati (anche direttamente dall'app, profilo → "Cancella account")
- **Portare** i tuoi dati (esporto in formato JSON)
- **Limitare** il trattamento
- **Opporti** al trattamento
- **Revocare** il consenso

Per esercitare i tuoi diritti scrivi a **buddy.coach.ai@gmail.com** specificando la richiesta. Risponderemo entro 30 giorni.

Hai inoltre diritto di **proporre reclamo all'autorità di controllo** competente (in Italia: Garante per la Protezione dei Dati Personali, [www.gpdp.it](https://www.gpdp.it)).

## Minori

Buddy è progettata anche per minori. Per gli **utenti con ruolo Studente** è richiesto il consenso del **Coach** (genitore o insegnante), che si registra per primo e fornisce il proprio consenso GDPR durante la registrazione. Il Coach è responsabile dell'utilizzo dell'app da parte del minore di cui ha cura.

In conformità con l'art. 8 GDPR e la normativa italiana, **non raccogliamo direttamente dati di minori di 14 anni senza il consenso di chi esercita la responsabilità genitoriale**. Se sei un genitore o tutore e vuoi che eliminiamo i dati di un minore registrato senza il tuo consenso, contattaci.

## Modifiche alla privacy policy

Possiamo aggiornare questa policy. La data in alto indica l'ultimo aggiornamento. Ti notificheremo via email o nell'app le modifiche sostanziali.

## Contatti

**Titolare del trattamento**: Alessandro Dianna
**Email**: buddy.coach.ai@gmail.com
