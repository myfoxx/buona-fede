# Matrice delle decisioni — da chiudere prima della v0.3

2 novembre 2026 — recepisce la revisione esterna dello scheletro (2/11/2026). Cinque decisioni che i penalisti e il tavolo devono fissare prima di riscrivere l'articolato. Per ciascuna: opzione consigliata dalla revisione, stato rispetto ai principi già fissati dal progetto, e chi decide. Due regimi distinti: le decisioni 3 e 4 modificano principi fissati e sono **scelte politiche da ratificare al tavolo**; la decisione 2 è una **questione tecnico-giuridica da validare dai penalisti** — un'eventuale rettifica sulla natura giuridica non è una revisione politica del safe harbor.

| # | Decisione | Opzione consigliata | Stato rispetto ai principi | Nodo scheletro |
|---|---|---|---|---|
| 1 | Perimetro oggettivo | Qualsiasi vulnerabilità (def. art. 2, lett. ii, d.lgs. 138/2024); la Politica ACN resta la procedura, con obbligo di adeguamento entro 6 mesi | Coerente con la finalità; la Politica copre solo zero-day, la legge deve essere più ampia | Nodo 1 |
| 2 | Natura giuridica | Scriminante condizionata (il fatto è lecito), in alternativa alla causa di non punibilità del testo base v0.2. Opzione tecnica, non decisione acquisita | **Da validare dai penalisti** (regime tecnico, non ratifica politica): effetti su responsabilità civile, amministrativa e concorso richiedono il vaglio penalistico | Nodo 3 |
| 3 | Danno | Formula proposta, con limite di causalità ancorato alla condotta al momento dell'azione: *"Il ricercatore non cagiona intenzionalmente né con colpa un danno al sistema, ai dati o alla disponibilità dei servizi; in caso di effetto dannoso non prevedibile, la tutela resta ferma se interrompe immediatamente l'attività, segnala il fatto e collabora al ripristino"*. Le tre salvaguardie — **interruzione immediata**, **segnalazione immediata** al titolare e, se del caso, al CSIRT, **ripristino o collaborazione al ripristino** senza appropriarsi del ruolo di "sistematore" senza autorizzazione — trasformano un requisito astratto in condotte verificabili. Il limite di causalità evita che un malfunzionamento latente del sistema venga attribuito al ricercatore come "danno prevedibile". Protegge l'errore ragionevole, non la negligenza né la prosecuzione nonostante il danno | **Modifica un principio fissato** ("nessun danno" assoluto). Argomento: il danno assoluto rende la tutela illusoria — un log, una cache, un servizio temporaneamente degradato cancellerebbero la protezione di chi ha fatto tutto bene. Da ratificare al tavolo | Nodo 8 |
| 4 | Divulgazione | Il termine come regola, non il silenzio del CSIRT. Formula proposta: *"decorso un termine non superiore a 90 giorni dalla ricezione della segnalazione completa, il segnalante può divulgare, salvo che CSIRT Italia abbia motivatamente comunicato un'esigenza concreta di rinvio per tutelare la sicurezza nazionale, la salute pubblica o la disponibilità di servizi essenziali"*. La decorrenza dalla **segnalazione completa e utilizzabile**, non dalla prima comunicazione, evita che il termine si consumi su un avviso preliminare prima che il CSIRT abbia materiali per valutare (serve la definizione di "segnalazione completa", da rinviare alla Politica/atto ACN). Il rinvio è un'eccezione motivata e circoscritta, non un veto generico; configurata come condizione della tutela, non come divieto sanzionato. I 90 giorni fissi possono essere rigidi per supply chain, embedded e sistemi pubblici: è esattamente ciò che la clausola di rinvio motivato copre | **Modifica un principio fissato** (consenso discrezionale del CSIRT). Argomento: il veto indefinito è il punto più esposto su artt. 21 e 33 Cost. Da ratificare al tavolo | Nodo 12 |
| 5 | Attestazione CSIRT | Solo fatti oggettivi: ricezione, data, contenuto, canale, esito della procedura. Il giudizio su buona fede e proporzionalità resta al giudice | Coerente con la v0.2; esclude la variante "valutazione di conformità" | Nodo 22 |

## Decisioni collegate (non in matrice ma da chiudere)

- **Destinatari della segnalazione (Nodo 10):** regola semplice — al titolare quando identificabile, in ogni caso al CSIRT; CSIRT canale sostitutivo se il titolare è irraggiungibile o non risponde entro un termine. La v0.2 è già quasi lì: manca il termine di non risposta.
- **Esclusioni (art. 5 v0.2 / Nodo 15):** sostituire il segnaposto "fatti diversi" con una regola di proporzionalità — la tutela non copre i reati commessi al di fuori delle attività necessarie e proporzionate, non ogni reato formalmente connesso.
- **"Altra utilità" (Nodo 13):** esplicitare che non è solo denaro — vantaggi contrattuali, assunzioni, accesso privilegiato, pubblicità come condizione della segnalazione. I casi Magyar Telekom e FreeHour (quest'ultimo come allegazione) mostrano che è l'elemento decisivo nei casi reali.
- **Sistemi sensibili (Nodo 14):** via intermedia da discutere — tutela piena anche per i sistemi del terzo comma 615-ter, ma con contatto immediato con il CSIRT e divieto di qualsiasi test attivo oltre la verifica minima. Né esclusione, né parificazione pura. **Rischio residuo segnalato dalla revisione:** è il punto che più condiziona la fattibilità politica del testo, e "verifica minima" senza definizione operativa diventa una nuova clausola indeterminata. Proposta di partenza per i penalisti: la sola conferma dell'esistenza della vulnerabilità su scala ridotta, senza persistenza, senza movimento laterale, senza accesso a contenuti oltre la prova, con cessazione immediata al conseguimento della prova — da affinare con l'istruzione redazionale qui sotto.
- **Tabella normativa per l'art. 7 (esenzione CSIRT):** prima della v0.3, costruire la tabella reato / procedibilità / obbligo di denuncia / norma da derogare, sul testo Normattiva vigente. Senza, l'articolo è tecnicamente incompleto.

## Rischio di fondo e istruzione redazionale per i penalisti

Sovraccarico di condizioni cumulative: sette condizioni simultanee proteggono il ricercatore ideale, non quello reale.

**Istruzione redazionale** (vincolante per la riscrittura degli artt. 3-4): *ogni condizione deve essere formulata in modo che un ricercatore prudente, al momento della condotta, possa comprendere se la sta rispettando senza dover anticipare l'esito di un futuro giudizio penale.* Niente clausole come "strettamente necessario", "senza danno" o "buona fede" lasciate interamente all'interpretazione successiva: ciascuna va ancorata a indici verificabili ex ante.

**Test di realtà (ex post):** per ogni condizione chiedersi: il ricercatore di Modern Solution l'avrebbe rispettata sapendo quello che sapeva in quel momento? Se la risposta è no, la condizione è scritta male.

Formula guida per la relazione: la legge non premia l'abusivo, ma non lascia il ricercatore in buona fede alla mercé della querela, della perquisizione e del processo.

## Procedura di ratifica (un unico commit)

Quando il tavolo ratifica le decisioni 3 e 4, aggiornare insieme:
1. `proposta/matrice-decisioni.md`: stato da "da ratificare" a "ratificato", con data e motivazione.
2. `proposta/articolato-scheletro.md`: artt. 3, 4 e 8; nodi 8, 12 e 22.
3. `proposta/ddl-bozza-v0.2.md`: testo normativo, relazione illustrativa e nota di lavoro (nuova versione v0.3).
4. Registro modifiche: una voce unica "ratifica tavolo — principi su danno e divulgazione", distinta dalle correzioni di fonte.
Così la v0.3 ha una genealogia trasparente: le correzioni fattuali restano tracciate come revisione, le due scelte sostanziali come decisioni politico-giuridiche del proponente e dei penalisti.
