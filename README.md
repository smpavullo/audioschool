# Audioschool

Programma di registrazione e montaggio audio che funziona nel browser, pensato per gli alunni della
**Scuola Secondaria di I grado R. Montecuccoli, Pavullo nel Frignano**.

Sito: <https://smpavullo.github.io/audioschool/>

> **Versione modificata di SoundCraft.** SoundCraft è software libero (licenza MIT oppure Apache-2.0)
> del gruppo ArtCraft e dei suoi collaboratori: <https://github.com/storytold/soundcraft>.
> Questa versione è stata adattata per la scuola dai docenti e **non è un prodotto del gruppo
> ArtCraft né di Avid Technology, Inc.**; non è da loro approvata. I loghi ArtCraft sono stati tolti.

## Cosa cambia rispetto a SoundCraft

- **Accesso con l'account Google della scuola**: entrano solo gli indirizzi `@smpavullo.com`.
- **Salvataggio su Google Drive**: sessioni ed esportazioni vanno nella cartella *Audio* del Drive
  dell'alunno (se il Drive non risponde, il file viene scaricato sul computer). *Apri da Drive* elenca i file.
- **Interfaccia in italiano**, con un pulsante per tornare all'inglese (la lingua originale).
- **Finestra Informazioni** con chi ha adattato il programma e da dove viene.
- **Tablet**: sugli schermi touch l'interfaccia si ingrandisce e ci sono i pulsanti A− / A+.
- Tolti il collegamento a Discord e i marchi ArtCraft.

## Come funziona e cosa si salva

Il programma gira tutto nel browser: **non c'è nessun server della scuola né del programma**, nessun
database e nessuna statistica di utilizzo. I file vanno solo nel Drive dell'utente, con il permesso
minimo di Google (`drive.file`: l'app vede soltanto i file che crea lei). Nel browser restano solo le
preferenze (lingua, zoom). Il file del programma pesa circa 6,5 MB al primo caricamento.

Il sito è ospitato da GitHub Pages: GitHub vede l'indirizzo IP di chi apre la pagina. All'apertura
viene caricato lo script di accesso di Google.

## Pubblicazione

Il sito si pubblica da solo a ogni modifica (`.github/workflows/pages.yml`).

## Licenza e provenienza

Le modifiche dei docenti sono sotto la stessa licenza di SoundCraft (MIT oppure Apache-2.0). I testi
originali sono nei file `LICENSE-MIT`, `LICENSE-APACHE` e `NOTICE`. Il resto della documentazione
tecnica di SoundCraft è nelle cartelle `docs/` e nei file `AGENTS.md` e `ROADMAP.md` (in inglese).
