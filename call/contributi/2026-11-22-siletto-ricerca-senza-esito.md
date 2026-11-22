# La tutela deve coprire la ricerca, non solo la scoperta

**Autore:** Alessandro Siletto, software architect. Testo redatto con l'assistenza di Claude Fable 5.2 (Anthropic).

**Tipo di contributo:** position paper.

**Punti della call:** 1 (buona fede), 2 (azioni necessarie e proporzionate), 3 (dati), 4 (danno), 5 (segnalazione).

**Data:** 22 novembre 2026.

## In sintesi

La bozza tutela chi trova una vulnerabilità, non chi la cerca. Nella mia esperienza, su cento prove condotte sulle API di un servizio, se va bene una individua un difetto. Le altre novantanove restano senza copertura esplicita.

Chiedo che la tutela riguardi l'attività di ricerca nel suo complesso, e non il solo fatto che ha prodotto la scoperta.

## Come si cerca una vulnerabilità

La scoperta e il fatto punito coincidono. Un esempio tipico: un ricercatore si registra a un servizio e, con il proprio account, modifica le richieste alle API per vedere se restituiscono dati di altri clienti. Non esiste un modo di sapere se il difetto c'è senza provare.

Tre caratteristiche di questa attività contano per la norma:

- **È intenzionale.** Il ricercatore non inciampa nel difetto: lo cerca. Una buona fede intesa come scoperta casuale escluderebbe quasi tutta la ricerca reale.
- **È fatta di tentativi falliti.** Una prova è una singola richiesta modificata, questione di secondi. Su cento, se va bene, una rivela una vulnerabilità. È una stima personale, non una statistica.
- **Spesso non trova nulla.** Molte ricerche su un sistema si chiudono senza alcun difetto da segnalare.

Ogni segnalazione arriva quindi insieme a decine di prove andate a vuoto. Il test senza esito non è un caso limite: è la parte prevalente del lavoro.

## Il vuoto nella bozza

La bozza v0.2 copre la verifica, ma fa dipendere la tutela dall'esistenza di una scoperta. L'art. 3 esclude la punibilità dei fatti commessi per verificare l'esistenza di una vulnerabilità. L'art. 4, lett. e), richiede però di segnalarla entro settantadue ore dalla scoperta, che l'art. 2, lett. e), definisce come il momento in cui si acquisisce consapevolezza dell'esistenza della vulnerabilità. Chi non trova nulla non ha nulla da segnalare e non può soddisfare la condizione.

La bozza non menziona il tentativo, e la matrice delle decisioni non contiene una voce sul test senza esito.

Ne derivano tre effetti:

1. **Un paradosso.** La stessa condotta è tutelata se il sistema è vulnerabile e non lo è se il sistema è sicuro. L'esito dipende dal titolare, non dal ricercatore.
2. **Un incentivo sbagliato.** Chi ha provato senza trovare nulla ha interesse a insistere finché trova qualcosa da segnalare. È il contrario della proporzionalità che la norma chiede.
3. **Un'incertezza sul caso tipico.** Quando una prova su cento riesce, non è chiaro se la segnalazione copra anche le altre novantanove.

L'istruzione redazionale della matrice chiede che il ricercatore possa capire, al momento della condotta, se sta rispettando ogni condizione. Una condizione che dipende dall'esito del test non può esserlo.

## Proposta

**1. Riformulare la condizione di segnalazione.** L'obbligo dell'art. 4, lett. e), va riferito alle vulnerabilità eventualmente scoperte. Il testo dovrebbe precisare che la tutela si estende alle attività di verifica rimaste senza esito, quando rispettano tutte le altre condizioni.

**2. Riconoscere un registro volontario del ricercatore.** Un registro con data, sistema esaminato e prove eseguite mostra che le prove formavano un'attività unica, con uno scopo e un limite. Deve valere come mezzo di prova, non come condizione: è un documento di parte e non può diventare un adempimento formale.

**3. Non introdurre una notifica al CSIRT per i test senza esito.** Una notifica preventiva, o una comunicazione di esito negativo, ha tre difetti:

- con un rapporto di cento a uno sommergerebbe il CSIRT di comunicazioni inutili;
- esporrebbe il ricercatore prima di sapere se c'è qualcosa da segnalare;
- scoraggerebbe la ricerca spontanea, che è quella che la norma vuole tutelare.

## Ricadute sugli altri punti

La stessa logica dà criteri pratici per le altre condizioni.

- **1. Buona fede.** È compatibile con la ricerca intenzionale. Si desume da comportamenti oggettivi: prove limitate, registro, segnalazione completa.
- **2. Proporzionalità.** Il confine passa fra provare e raccogliere: cambiare un parametro è verifica, scorrere migliaia di identificativi non lo è. L'elenco dell'art. 4, comma 2, va già in questa direzione. Va chiarito che la «scala ridotta» riguarda i dati raggiunti, non il numero di prove.
- **3. Dati.** Dove possibile, la prova si fa su due account propri. Dove non è possibile, ci si ferma alla prima conferma: un solo record. Quanti clienti sono esposti lo accerta il titolare.
- **4. Danno.** Gli allarmi generati e i costi di accertamento del titolare non sono danno. Sostengo la formula con limite di causalità proposta al Nodo 8 della matrice.

## Questioni per i penalisti

Questo contributo descrive la pratica. La traduzione giuridica spetta ai penalisti, a cui pongo tre domande:

- Le prove senza esito integrano un tentativo ai sensi dell'art. 56 c.p., e la formula dell'art. 3 lo copre?
- Le prove condotte nella stessa sessione sullo stesso sistema possono essere trattate come un'unica condotta?
- La scelta fra causa di non punibilità e scriminante condizionata (Nodo 3) cambia la risposta per il test senza esito?

## Fonti

- [Call sui principi, Fase 1](../CALL.md)
- [Manifesto](https://buonafede.org/)
- [Bozza del disegno di legge v0.2](../../proposta/ddl-bozza-v0.2.md): art. 2, lett. e); art. 3; art. 4, comma 1, lett. e), e comma 2
- [Matrice delle decisioni aperte](../../proposta/matrice-decisioni.md): decisioni 2 (Nodo 3) e 3 (Nodo 8), istruzione redazionale
- Esperienza diretta dell'autore, senza riferimento a sistemi o soggetti reali
