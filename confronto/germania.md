# Germania - Referentenentwurf del novembre 2024, non approvato

Scheda v0.1 - 20 ottobre 2026

## In sintesi

In Germania la tutela della ricerca di sicurezza non esiste. Un progetto del Ministero federale della Giustizia è stato pubblicato nel novembre 2024 ma non è stato approvato dal Bundestag prima della fine della legislatura. Il contratto di coalizione del 2025 prevede una soluzione e il governo, il 16 aprile 2026, ha risposto che il ministero sta valutando come attuarla, senza indicare una scadenza.

## Il progetto del 2024

- **Documento**: Referentenentwurf (bozza ministeriale) del Ministero federale della Giustizia "Entwurf eines Gesetzes zur Änderung des Strafgesetzbuches - Modernisierung des Computerstrafrechts", pubblicato il 4 novembre 2024 e inviato in consultazione tra i ministeri.
- **Tecnica**: esclusione della tipicità, non causa di giustificazione. Si aggiunge un comma 3 al § 202a StGB (accesso abusivo ai dati) che definisce in negativo il requisito "unbefugt" (senza autorizzazione): non è non autorizzato l'atto compiuto nell'ambito della ricerca di sicurezza informatica, quando ricorrono le condizioni. L'esclusione si estende, per rinvio, al § 202b (intercettazione di dati) e al § 303a (alterazione di dati) e si collega al § 202c (atti preparatori).
- **Condizioni**: secondo le analisi di dottrina che ho consultato, l'atto deve essere compiuto con l'intenzione di individuare una vulnerabilità e di segnalarla o eliminarla, e deve essere obiettivamente necessario. La dottrina ritiene che ne derivi un onere di documentazione per il ricercatore. **Testo esatto del § 202a Abs. 3 StGB-E da leggere nel PDF originale** (non sono riuscito a scaricarlo con il mio strumento di lettura).
- **Il prezzo politico**: lo stesso progetto introduceva casi particolarmente gravi (§ 202a Abs. 4, § 202b Abs. 2) con pene più alte per gli accessi veramente dannosi. La riforma "di tutela" era accoppiata a un aggravamento.
- **Critiche**: la protezione sarebbe limitata ad accessi "chiaramente innocui" e non coprirebbe le attività tipiche di un penetration test che esamina un sistema nel suo insieme senza mirare a una vulnerabilità specifica; ricercatori, hacker e industria hanno criticato il testo da lati opposti (troppo ampio per alcuni, insufficiente per altri).

## Dopo il 2024

- Il progetto non è stato adottato dal Bundestag prima della fine della legislatura. La risposta del governo del 16 aprile 2026 (Bundestag, Drucksache 21/5456, domanda 16) lo conferma: il progetto è stato "pubblicato ma non approvato" nella scorsa legislatura.
- **Contratto di coalizione 2025 (CDU/CSU-SPD)**: prevede di creare certezza del diritto per la ricerca di sicurezza informatica nel diritto penale informatico, evitando gli abusi. La fonte che ho consultato indica la pagina 92 (Gesellschaft für Informatik); **da verificare sul testo del contratto**.
- **Risposta del governo del 16 aprile 2026 (Drs. 21/5456, domanda 16)**: il Ministero della Giustizia e della Tutela dei consumatori sta valutando "come attuare al meglio" l'impegno, tenendo conto anche delle osservazioni ricevute sulla bozza della legislatura precedente. **Nessuna data indicata**, nessun progetto nuovo annunciato.
- Segnalazioni nel dibattito pubblico: la presidente del BSI, Claudia Plattner, nel novembre 2025 avrebbe chiesto di non perseguire chi segnala (fonte secondaria, **da verificare**).

## Il caso Modern Solution

Un professionista IT, che aveva individuato e segnalato una falla nel software di una società di e-commerce, risulta condannato a 3.000 euro (OLG Köln, luglio 2025) con ricorso costituzionale annunciato o depositato. Le fonti secondarie non concordano su alcuni dettagli (anno della condanna, articolo applicato, esito di un precedente ricorso al Tribunale costituzionale). **Non usare il caso se non dopo aver letto i provvedimenti.**

## Cosa insegna all'Italia

1. Una tutela basata sull'intenzione ("Absicht") sposta sul ricercatore l'onere di provare il proprio fine: va confrontata con il requisito di buona fede dei principi del progetto.
2. Una norma troppo stretta (solo accessi "chiaramente innocui") lascia il ricercatore nel grigio.
3. Accoppiare la tutela a un aggravamento delle pene può far passare la riforma ma ne cambia il senso: è un nodo politico da decidere in fase 2.
4. Il caso tedesco mostra che l'inerzia ha un costo: il tema è nel programma di governo e ancora senza data.

## Fonti

- BMJ, Referentenentwurf, pagina e PDF: https://www.bmjv.de/SharedDocs/Downloads/DE/Gesetzgebung/RefE/RefE_ComputerStrafR.html?v=3 (pagina verificata con data 4 novembre 2024; **PDF non letto integralmente**)
- netzpolitik.org, Hacker-Paragrafen: https://netzpolitik.org/2024/hacker-paragrafen-wir-veroeffentlichen-den-gesetzentwurf-zum-computerstrafrecht/ (fonte secondaria, verificata)
- Der Betrieb, Gesetzentwurf zum Computerstrafrecht (5 novembre 2024): https://der-betrieb.de/meldungen/gesetzentwurf-zum-computerstrafrecht/ (fonte secondaria, verificata)
- KriPoZ, analisi dell'entwurf (31 marzo 2025): https://kripoz.de/2025/03/31/erlaubtes-gray-hat-hacking-und-neue-strafrahmen-im-computerstrafrecht-ueberlegungen-zum-entwurf-eines-gesetzes-zur-aenderung-des-strafgesetzbuches-zur-modernisierung-des-computerstrafrechts (dottrina, verificata)
- Bundestag, Drucksache 21/5456 (16 aprile 2026): https://dserver.bundestag.de/btd/21/054/2105456.pdf (verificata, risposta alla domanda 16 letta integralmente)
- Gesellschaft für Informatik, Dringend reformbedürftig: das Computerstrafrecht: https://gi.de/themen/beitrag/dringend-reformbeduerftig-das-computerstrafrecht (fonte secondaria, per il riferimento al contratto di coalizione)
- Contratto di coalizione 2025, p. 92: **non consultato direttamente**

## Da verificare

1. Testo del § 202a Abs. 3 StGB-E e dei richiami in §§ 202b, 202c, 303a.
2. Testo del contratto di coalizione, pagina e formulazione.
3. Caso Modern Solution sui provvedimenti giudiziari.
4. Dichiarazione del BSI del novembre 2025.
