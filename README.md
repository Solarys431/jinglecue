# JingleCue Pro

> Broadcast Cue Studio per iPad. Multi-playback, registro cue sheet automatico, export in formati standard di settore.

## Stato del progetto

**JingleCue Pro è attualmente in fase di test interno (TestFlight).**
L'app **non è ancora distribuita su App Store** e non è disponibile per il download pubblico. La submission per la pubblicazione è in preparazione. Questa repository ospita le pagine pubbliche di supporto e privacy.

—

## Pagine pubbliche

- **Home** · https://solarys431.github.io/jinglecue/
- **Privacy Policy** · https://solarys431.github.io/jinglecue/privacy.html
- **Supporto / FAQ** · https://solarys431.github.io/jinglecue/support.html

—

## Cosa fa l'app

**Audio engine nativo.** Basato su AVAudioEngine di iOS. Supporta multi-playback simultaneo, fade in/out per pad, IN/OUT point al centesimo di secondo, loop seamless.

**Modalità Automix.** Toggle nell'header dell'app: quando attivo, premere un pad fermo mentre un altro suona avvia un crossfade automatico tra i due. Durata configurabile da 0,5 a 10 secondi.

**Forma d'onda live con seek.** Durante la riproduzione la forma d'onda viene disegnata nel pad in tempo reale. Trascinando con un dito si salta a qualsiasi punto del brano.

**Registro cue sheet.** Ogni pad mandato in onda viene registrato con: data, ora, titolo, artista, compositore, autore del testo, editore, album, etichetta discografica, anno, ISRC, ISWC, tipo di utilizzo, durata effettiva.

**Export.**
- **CSV** in UTF-8 conforme a RFC 4180, apribile in Excel, Numbers e LibreOffice
- **XML strutturato per SIAE** con i campi del bordereau (data, titolo, autori, editore, codici, durata) e header con identità emittente
- **XML conforme allo standard MOS Protocol 2.8.5** (Media Object Server) per integrazione potenziale con newsroom system di settore
- **JSON** per integrazioni custom

> **Nota importante:** la conformità formale degli export al template adottato dalla propria emittente (per SIAE) o al newsroom system in uso (per MOS) va verificata caso per caso prima dell'invio o dell'integrazione ufficiale. JingleCue Pro produce file conformi agli standard tecnici di riferimento, ma non garantisce l'accettazione automatica da parte di sistemi specifici di terze parti.

**Lettura tag automatica.** Tag ID3 v2.3/v2.4, iTunes M4A e WAV INFO chunks letti automaticamente al momento dell'import. Popolamento di titolo, artista, compositore, autore testo, editore, album, etichetta, anno, ISRC.

**Banchi memoria e colori.** Categorie default: Jingle, Stinger, SFX, Bank 4, Bank 5, Bank 6. Aggiungibili e rinominabili in qualsiasi momento. Eliminazione protetta da conferma quando il banco contiene pad. Categoria Playlist separata con funzione di sequenza automatica e loop opzionale. Palette di 10 colori per i pad.

**Background audio nativo.** L'audio continua se l'utente passa ad un'altra app o blocca lo schermo. Usa l'iOS Background Audio Mode.

**Privacy.** L'app funziona interamente sul dispositivo. Non vengono raccolti dati personali. Non sono integrati SDK di analytics, crash reporting di terze parti, tracker o pubblicità. Vedi la [privacy policy](https://solarys431.github.io/jinglecue/privacy.html) per i dettagli completi.

—

## Pensato per

- Radio comunitarie, web radio, FM locali
- DJ, animatori, MC per eventi e matrimoni
- Studio televisivo (sigle, stinger, tappetini)
- Teatro e live show
- Sport e arena (inni, sirene, fanfare modulari)
- Scuole di radio e accademie audio

—

## Compatibilità

- iPad con **iPadOS 17.0** o superiore
- Orientamento **landscape**
- Ottimizzata per iPad Pro 11", 12.9" e 13"
- Solo iPad (non disponibile per iPhone)

—

## Supporto

- **FAQ** · https://solarys431.github.io/jinglecue/support.html
- **E-mail** · info@danielecappello.com

—

## Licenza e marchi

JingleCue Pro © 2026 Daniele Cappello. Tutti i diritti riservati.

Apple, iPad, iPadOS e App Store sono marchi registrati di Apple Inc. SIAE è marchio della Società Italiana degli Autori ed Editori. Avid iNews è un marchio di Avid Technology, Inc. Mosart è un marchio di Vizrt. **JingleCue Pro non è affiliato a, sponsorizzato da o associato a Apple Inc., SIAE, Avid Technology o Vizrt.** I nomi dei prodotti di terze parti sono citati esclusivamente a scopo descrittivo per indicare lo standard tecnico (MOS Protocol) supportato dagli export dell'app.
