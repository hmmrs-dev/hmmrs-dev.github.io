---
lang: it
title: Informativa sulla privacy – Turno
description: Come l'app Turno gestisce i tuoi dati.
home_url: /turno/it/
alt_lang: en
alt_url: /turno/privacy/
alt_label: English
privacy_url: /turno/it/privacy/
privacy_label: Informativa sulla privacy
---

# Informativa sulla privacy

<p class="updated">Ultimo aggiornamento: 8 ottobre 2026</p>

Turno è un'app Android per tenere il punteggio nei giochi da tavolo, sviluppata da
{{ site.developer }}. Questa informativa spiega quali dati gestisce l'app e in che modo.

**In breve:** Turno non ha account, pubblicità né strumenti di analisi, e non uso alcun server.
Le tue partite restano sul tuo dispositivo, a meno che tu non scelga di sincronizzarle tramite una
cartella, e io non posso accedervi.

## Dati salvati sul dispositivo

L'app salva le tue partite (nomi, punteggi, cronologia dei punti e timer), i giocatori, i gruppi di
giocatori, i preset di regole, le impostazioni (come tema e lingua) e se Turno Pro è sbloccato.
Tutto viene conservato nello spazio privato dell'app sul tuo dispositivo.

Se il backup è attivo sul tuo dispositivo, Android include questi dati nel backup sul tuo account
Google e nei trasferimenti da un dispositivo all'altro, così da poterli ripristinare su un nuovo
telefono. Questi backup sono gestiti da Google nel tuo account Google e io non posso accedervi. Puoi
disattivare il backup dalle impostazioni del dispositivo.

## Microfono e punteggio vocale

Il punteggio vocale (incluso in Turno Pro) usa il microfono solo dopo che hai concesso
l'autorizzazione, e solo mentre lo stai usando. L'app passa l'audio al servizio di riconoscimento
vocale del dispositivo (di solito fornito da Google), che lo trasforma in testo. A seconda del
dispositivo e delle sue impostazioni, questo servizio può elaborare l'audio sui server di Google,
secondo le [norme sulla privacy di Google](https://policies.google.com/privacy?hl=it). L'app non
registra, non salva e non invia l'audio da nessuna parte.

Il testo riconosciuto viene interpretato sul dispositivo, con Gemini Nano sui dispositivi che lo
supportano o altrimenti con regole integrate. Vengono salvate solo le variazioni di punteggio che ne
risultano.

## Modalità bussola

La modalità bussola usa i sensori di orientamento del dispositivo per selezionare il giocatore verso
cui punti il telefono. Tutto avviene sul dispositivo: l'app non chiede né usa la tua posizione.

## Acquisti

Turno Pro si acquista tramite Google Play, che gestisce interamente il pagamento: l'app non vede
mai i tuoi dati di pagamento. L'app chiede a Google Play solo se hai acquistato Pro, per sbloccarlo,
anche dopo una reinstallazione o su un nuovo dispositivo. Gli acquisti sono regolati dalle
[norme sulla privacy di Google](https://policies.google.com/privacy?hl=it).

## Condivisione e importazione delle partite

Quando condividi una partita, l'app crea un file con il suo nome, i nomi dei giocatori, i punteggi e
la cronologia, e lo passa all'app che scegli. Viene inviato solo dove decidi tu. Quando apri il file
di una partita condivisa, l'app lo legge solo per importare la partita.

## Cartelle sincronizzate

Le cartelle sincronizzate (incluse in Turno Pro) permettono ai giocatori di ricevere le partite
degli altri tramite una cartella condivisa. Ogni cartella sincronizzata è una che scegli tu: sul
dispositivo o nel tuo Google Drive. Ogni volta che apri o lasci l'app, esci da una partita finita o
sincronizzi a mano, Turno:

- salva nella cartella le tue partite finite, quelle delle regole e dei gruppi che hai scelto per
  la cartella, ognuna in un file con il suo nome, la data, le regole, il nome del gruppo, i nomi dei
  giocatori, i punteggi e la cronologia;
- aggiunge all'app le partite che trova nella cartella, salvate lì dagli altri giocatori.

Chiunque possa aprire la cartella può leggere le partite che contiene, come i giocatori con cui la
condividi. Se un'app di cloud storage o di sincronizzazione tiene sincronizzata una cartella del
dispositivo, è quell'app a caricarne i file, secondo la sua informativa sulla privacy.

Turno non modifica né elimina mai i file di una cartella sincronizzata: una partita che elimini
dall'app resta nella cartella, e una cartella sincronizzata che rimuovi dall'app resta com'è, con i
suoi file. L'elenco delle cartelle sincronizzate è conservato sul dispositivo, insieme all'account
Google di ogni cartella su Google Drive.

## Google Drive

Se scegli una cartella sincronizzata su Google Drive, l'app chiede l'accesso al tuo Drive tramite
la schermata di consenso di Google, poi comunica con Google Drive direttamente dal dispositivo.
Niente passa da me, e io non posso accedere al tuo Drive né ai tuoi file.

Google permette a un'app di leggere i file scritti da altre copie della stessa app, come le partite
che gli altri giocatori salvano in una cartella condivisa con te, solo con l'accesso a tutto il tuo
Drive: per questo la schermata di consenso lo richiede. L'app lo usa solo per le cartelle
sincronizzate:

- elenca le cartelle del tuo Drive e quelle condivise con te, per sceglierne una, e crea una
  cartella quando glielo chiedi;
- legge e scrive file di partite solo nelle cartelle che hai scelto;
- legge l'indirizzo email del tuo account Google, per usare l'account giusto per ogni cartella, e lo
  conserva solo sul dispositivo.

Non apre, non modifica e non elimina nessun altro file del tuo Drive. L'accesso che concedi è
conservato da Google Play Services sul dispositivo, non dall'app. Puoi interromperlo in qualsiasi
momento: rimuovi la cartella dall'app, e rimuovi l'accesso di Turno dal tuo
[Account Google](https://myaccount.google.com/connections).

L'uso e il trasferimento ad altre app delle informazioni ricevute dalle API di Google da parte di
Turno rispetteranno le
[Norme relative ai dati utente dei servizi API di Google](https://developers.google.com/terms/api-services-user-data-policy?hl=it),
inclusi i requisiti di utilizzo limitato.

## Servizi Google usati dall'app

- **ML Kit**, che esegue Gemini Nano sul dispositivo. Secondo la
  [dichiarazione sui dati di ML Kit](https://developers.google.com/ml-kit/android-data-disclosure),
  invia a Google informazioni diagnostiche e di utilizzo: dettagli del dispositivo (come produttore,
  modello e versione di Android), nome e versione dell'app, identificativi di installazione, metriche
  di prestazioni, codici di errore e le lingue configurate. Queste informazioni sono cifrate durante
  la trasmissione e non vengono condivise con terze parti. Non includono la tua voce, il testo
  riconosciuto né le tue partite.
- **Google Drive** e **Google Play Services**, solo se scegli una cartella sincronizzata su Google
  Drive, per ottenere il tuo consenso e raggiungere la cartella, come descritto sopra.
- **Google Play Billing** e **aggiornamenti in-app di Google Play**, che comunicano con l'app Google
  Play Store sul dispositivo per gestire acquisti e aggiornamenti.

## Cosa non faccio

Turno non richiede un account, non mostra pubblicità e non usa strumenti di analisi o
tracciamento. Non raccolgo, non vendo e non condivido i tuoi dati personali.

## Minori

L'app non è rivolta ai minori di 13 anni, e non raccolgo consapevolmente dati personali di
nessuno, minori inclusi.

## Le tue scelte

- Puoi revocare l'autorizzazione al microfono in qualsiasi momento dalle impostazioni del
  dispositivo.
- Puoi eliminare partite, giocatori e preset dall'app.
- Puoi rimuovere una cartella sincronizzata dall'app, e rimuovere l'accesso di Turno al tuo Google
  Drive dal tuo account Google.
- Disinstallando l'app, o cancellandone i dati dalle impostazioni del dispositivo, tutti i suoi dati
  vengono eliminati dal dispositivo. Le copie di backup si possono eliminare dalle impostazioni di
  backup del tuo account Google.

## I tuoi diritti

Risiedo nell'Unione europea e sono titolare del trattamento per gli unici dati personali che potrei
trattare: quelli che mi invii quando mi contatti, che uso solo per risponderti. Ai sensi del GDPR hai
diritto di accedere ai tuoi dati personali, di rettificarli e di cancellarli, e di proporre reclamo a
un'autorità di controllo, come il
[Garante per la protezione dei dati personali](https://www.garanteprivacy.it).

## Modifiche a questa informativa

Se questa informativa cambia, la nuova versione sarà pubblicata su questa pagina e la data in alto
verrà aggiornata.

## Contatti

Per qualsiasi domanda su questa informativa o sui tuoi dati, scrivi a
[{{ site.contact_email }}](mailto:{{ site.contact_email }}).
