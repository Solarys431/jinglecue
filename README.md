# JingleCue Pro

> Broadcast Cue Studio per iPad. Multi-playback, cue sheet SIAE automatico, export MOS Protocol.

JingleCue Pro è un cue studio professionale per iPad, pensato per chi va davvero in onda: speaker radio, animatori di eventi, registi televisivi, tecnici di sala. L'audio engine nativo permette il multi-playback simultaneo con fade, IN/OUT point e loop indipendenti per ogni pad. Ogni jingle mandato in onda viene registrato automaticamente nel cue sheet con tutti i metadati editoriali richiesti per la rendicontazione SIAE.

Questa repo contiene le pagine di supporto pubbliche del prodotto: **landing**, **privacy policy** e **centro assistenza**.

—

## Pagine pubbliche

- **Home** · https://solarys431.github.io/jinglecue/
- **Privacy Policy** · https://solarys431.github.io/jinglecue/privacy.html
- **Supporto / FAQ** · https://solarys431.github.io/jinglecue/support.html

—

## Cosa fa l'app

**Audio engine nativo.** Basato su AVAudioEngine: latenza minima, multi-pad simultaneo, fade in/out per pad, IN/OUT point al centesimo di secondo, loop seamless.

**Modalità Automix.** Toggle nell'header: quando attivo, premere un pad fermo mentre un altro suona avvia un crossfade automatico tra i due. Durata configurabile da 0,5 a 10 secondi.

**Forma d'onda live con seek.** Durante la riproduzione la forma d'onda viene disegnata nel pad in tempo reale. Trascinando con un dito si salta a qualsiasi punto del brano, anche durante il playback.

**Cue Sheet SIAE.** Ogni jingle in onda viene loggato automaticamente con: data, ora, titolo, artista, compositore, autore del testo, editore, album, etichetta discografica, anno, ISRC, ISWC, tipo di utilizzo, durata effettiva on-air.

**Export multipli.**
- CSV (UTF-8, RFC 4180) per Excel e Numbers
- SIAE XML 1.1 con header bordereau completo (P.IVA, codice SIAE, responsabile, periodo)
- MOS XML 2.8.5 compatibile con Avid iNews e Vizrt Mosart
- JSON per integrazioni custom

**Lettura ID3 automatica.** Tag ID3 v2.3/v2.4, iTunes M4A e WAV INFO chunks. Popolamento automatico di titolo, artista, compositore, autore testo, editore, album, etichetta, anno, ISRC.

**Categorie e colori.** Categorie personalizzabili, palette di 10 colori curati per identificare i pad a colpo d'occhio. Playlist dedicata con sequenza automatica e loop opzionale.

**Background audio nativo.** L'audio non si interrompe se passi ad un'altra app o blocchi lo schermo. iOS Background Audio Mode.

**Privacy reale.** L'app funziona interamente sul dispositivo. Nessun account, nessun cloud, nessun SDK di analytics, nessun annuncio pubblicitario, nessun tracker.

—

## Pensato per

- Radio comunitarie, web radio, FM locali
- DJ, animatori, MC per eventi e matrimoni
- Studio televisivo (sigle, stinger, tappetini, integrazione iNews/Mosart)
- Teatro e live show
- Sport e arena (inni, sirene, fanfare modulari)
- Scuole di radio e accademie audio

—

## Compatibilità

- iPad con **iPadOS 17.0** o superiore
- Orientamento **landscape**
- Ottimizzata per iPad Pro 11", 12.9" e 13"

—

## Privacy

JingleCue Pro non raccoglie alcun dato personale dell'utente. Tutti i file audio, la configurazione e il cue sheet restano sul dispositivo, nel sandbox dell'app. Vedi la [privacy policy completa](https://solarys431.github.io/jinglecue/privacy.html).

—

## Supporto

Per domande, segnalazioni o richieste:

- **FAQ** · https://solarys431.github.io/jinglecue/support.html
- **E-mail** · info@danielecappello.com

—

## Licenza

JingleCue Pro © 2026 Daniele Cappello. Tutti i diritti riservati. L'applicazione è distribuita esclusivamente tramite Apple App Store. Apple, iPad, iPadOS e App Store sono marchi registrati di Apple Inc. SIAE è marchio della Società Italiana degli Autori ed Editori. JingleCue Pro non è affiliato a Apple Inc. né alla SIAE.
