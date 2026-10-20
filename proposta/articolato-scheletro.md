# Scheletro del testo articolato

Versione 0.1 - 20 ottobre 2026 - bozza di lavoro

**Avvertenza.** Questo documento non è un testo normativo. È uno scheletro con alternative e nodi da sottoporre ai penalisti, che scrivono e validano il testo definitivo (vedi GOVERNANCE.md). Le parti tra parentesi quadre sono alternative o segnaposto. I riferimenti a norme sono da verificare dai penalisti sul testo vigente: in particolare la numerazione degli articoli del codice penale dopo la L. 90/2024.

Titolo provvisorio: *Disposizioni per la tutela penale della ricerca di sicurezza in buona fede e per la divulgazione coordinata delle vulnerabilità.*

## Impianto

| Articolo | Oggetto |
|---|---|
| 1 | Finalità e definizioni |
| 2 | Non punibilità della ricerca di sicurezza in buona fede (nuovo art. 615-ter.1 c.p. o comma del 615-ter) |
| 3 | Condizioni cumulative |
| 4 | Esclusioni |
| 5 | Reati ai quali si applica la disposizione e altre responsabilità |
| 6 | Esenzione dall'obbligo di denuncia per il CSIRT Italia |
| 7 | Riservatezza del segnalante |
| 8 | Accertamento delle condizioni |
| 9 | Dati personali |
| 10 | Monitoraggio e valutazione |
| 11 | Invarianza finanziaria |
| 12 | Entrata in vigore e disciplina transitoria |

## Art. 1 - Finalità e definizioni

1. La presente legge assicura la tutela penale di chi ricerca e segnala vulnerabilità in buona fede, in coerenza con la politica nazionale di divulgazione coordinata delle vulnerabilità di cui all'articolo 16 del decreto legislativo 4 settembre 2024, n. 138.
2. Ai fini della presente legge si intende per:
   a) «vulnerabilità»: [rinvio alla definizione del d.lgs. 138/2024, da individuare] / [definizione autonoma];
   b) «segnalante»: la persona fisica o giuridica che segnala una vulnerabilità, anche in forma anonima [verificare coerenza con la Politica];
   c) «CSIRT Italia»: il gruppo nazionale di risposta agli incidenti di sicurezza informatica di cui al d.lgs. 138/2024;
   d) «titolare del sistema»: il soggetto che ha il diritto di escludere terzi dal sistema informatico o telematico;
   e) «scoperta»: [il momento in cui il segnalante acquisisce consapevolezza della vulnerabilità].

**Nodo 1 - Perimetro oggettivo.** La Politica ACN riguarda le vulnerabilità "zero day" e dichiara fuori ambito le altre (pagina ACN dedicata alla CVD). Molte situazioni reali (esposizioni, errate configurazioni, difetti noti in uno specifico sistema) potrebbero restare fuori. Alternative: A) solo zero day, come la Politica; B) qualsiasi vulnerabilità di un prodotto, servizio o sistema; C) B, con rinvio alla Politica per la procedura. Il progetto ritiene da discutere B o C: se la tutela coprisse solo i casi della Politica lascerebbe fuori la maggior parte dei ricercatori.

**Nodo 2 - Definizione di "scoperta".** Serve per fissare il termine di segnalazione e la sua prova.

## Art. 2 - Non punibilità

**Collocazione, alternative.**

- **A) Nuovo comma all'art. 615-ter c.p.** Pro: la norma sta dove il ricercatore la cerca. Contro: aggiunge un comma a un articolo già lungo, e lega la tutela al solo 615-ter.
- **B) Nuovo art. 615-ter.1 c.p.** (come previsto dal progetto). Pro: norma autonoma, estendibile ad altri reati. Contro: numerazione e coordinamento da verificare con gli uffici legislativi.
- **C) Disposizione autonoma nel d.lgs. 138/2024 (nuovo comma dell'art. 16 o articolo 16-bis).** Pro: vicina alla Politica e a CSIRT Italia. Contro: meno visibile per il giudice penale; da valutare rispetto al principio della riserva di codice (art. 3-bis c.p.) *[da verificare dai penalisti]*.

**Testo base (variante B).**

> Art. 615-ter.1 (Ricerca di sicurezza in buona fede). - [ALT. 1: Non è punibile] [ALT. 2: Non sussiste il reato] [ALT. 3: Il fatto non costituisce reato] chi, al fine di verificare l'esistenza di una vulnerabilità e di segnalarla, commette i fatti previsti dagli articoli 615-ter, 617-quater e 635-bis [e ...] del presente codice e dall'articolo 167 del decreto legislativo 30 giugno 2003, n. 196, quando ricorrono tutte le condizioni previste dall'articolo 3 della legge [...].

**Nodo 3 - Natura giuridica.** È la scelta chiave e spetta ai penalisti.

| Alternativa | Come funziona | Pro | Contro |
|---|---|---|---|
| Causa di non punibilità in senso stretto | Il fatto resta reato, ma non si punisce | Più semplice da scrivere, non entra nella teoria dell'antigiuridicità | Il fatto resta tipico: possibili conseguenze extra-penali, limiti sul concorso di persone, valutazione residua |
| Causa di giustificazione (scriminante) | Il fatto è lecito | Effetti anche civili e amministrativi, copre il concorso | Va delimitata con attenzione, rischio di conflitto con le scriminanti generali |
| Esclusione della tipicità (modello tedesco) | Si definisce in negativo l'"abusivamente" del 615-ter | Il fatto non è nemmeno tipico | Il 615-ter punisce anche chi si mantiene contro la volontà del titolare, con conseguenze da studiare dopo la sentenza Casani |

Il Belgio usa, secondo il CCB, una causa di giustificazione; la Germania ha proposto l'esclusione della tipicità; la Francia non tocca la punibilità del ricercatore.

## Art. 3 - Condizioni cumulative

Le condizioni devono ricorrere **tutte**. Per ciascuna sono indicati alternative e nodi.

**a) Buona fede e assenza di profitto.** *Agisce in buona fede, senza intento fraudolento e senza fine di profitto per sé o per altri.*
- Nodo 4: come si prova. Alternative: A) solo clausola generale; B) clausola generale e indici oggettivi (rapida segnalazione, assenza di condotte successive incoerenti, eventuale identificazione verso il titolare durante la ricerca, come suggerisce il CCB belga); C) presunzione relativa di buona fede se rispettate le altre condizioni. Da decidere chi ha l'onere.

**b) Azioni necessarie e proporzionate.** *Compie azioni strettamente necessarie e proporzionate alla verifica della vulnerabilità e alla sua segnalazione.*
- Nodo 5: clausola generale oppure clausola generale con elenco di condotte considerate non proporzionate (modello belga: installazione di malware, DoS, social engineering, phishing, spam, furto di password o brute force, cancellazione di dati, danno prevedibile). Alternative: elenco tassativo / esemplificativo / affidato alla Politica.
- Nodo 6: dimostrazione su scala ridotta; divieto di proseguire oltre.

**c) Nessuna copia o esfiltrazione oltre lo stretto necessario.** *Non copia, non estrae e non conserva dati oltre quanto strettamente necessario a dimostrare e segnalare la vulnerabilità e li cancella al termine della procedura [entro ...].*
- Nodo 7: cosa vuol dire "stretto necessario" per un ricercatore che deve mostrare la prova; termini di conservazione; rapporto con l'art. 167 e con il Garante (vedi sezione dedicata).

**d) Nessun danno.** *Non cagiona danno al sistema, ai dati o alla disponibilità dei servizi.*
- Nodo 8: alternative: A) assenza di qualsiasi danno; B) assenza di danno "prevedibile" (modello belga: "danno prevedibile" tra le condotte sproporzionate); C) assenza di danno non lieve. A), scelta nei principi, rischia di rendere la tutela illusoria se un effetto collaterale imprevedibile fa venire meno la protezione.

**e) Segnalazione tempestiva a CSIRT Italia e al titolare.** *Segnala la vulnerabilità [senza ritardo] [entro ... ore dalla scoperta] a CSIRT Italia e al titolare del sistema.*
- Nodo 9: termine. Alternative: A) "senza ritardo" (la Politica dice "non appena"); B) termini fissi in due tempi (Belgio: 24 ore la notifica semplificata, 72 ore la completa); C) termine unico (per esempio entro [x] giorni). Il progetto privilegia che il termine sia ragionevole e verificabile.
- Nodo 10: destinatari. Alternative: A) CSIRT Italia e titolare, entrambi; B) CSIRT Italia, che informa il titolare (modello francese); C) il titolare e, se non risponde, CSIRT Italia. Se il titolare non è identificabile o raggiungibile: segnalazione al solo CSIRT Italia. I principi fissati prevedono entrambi: da riesaminare per i sistemi dove il titolare è un soggetto di interesse pubblico.
- Nodo 11: forma (ricevuta, canale ufficiale), prova della data.

**f) Nessuna divulgazione pubblica senza il consenso del CSIRT.** *Non diffonde informazioni sulla vulnerabilità senza il consenso di CSIRT Italia.*
- Nodo 12: tutela della libertà di espressione (art. 21 Cost.) e rischio di veto indefinito. Alternative: A) consenso discrezionale del CSIRT, come nei principi; B) consenso che non può essere irragionevolmente negato; C) decorso di un termine dopo il quale il segnalante può divulgare se la vulnerabilità non è risolta e il CSIRT non ha motivato un ulteriore rinvio. Il principio fissato dal progetto è A: B e C sono alternative da discutere, non una proposta.

**g) Nessuna richiesta di compenso come condizione della segnalazione.** *Non subordina la segnalazione alla corresponsione di un compenso o di altra utilità.*
- Nodo 13: confine fra segnalazione disinteressata e richiesta di compenso; eventuali programmi di bug bounty o accordi preventivi (il Belgio esclude la monetizzazione "salvo compenso concordato in precedenza"); rapporto con l'art. 629 c.p. (estorsione). Distinguere il ringraziamento o il premio spontaneo successivo dalla richiesta come condizione.

## Art. 4 - Esclusioni

1. La disposizione non si applica a chi subordina la segnalazione alla corresponsione di un compenso o di altra utilità, anche se le altre condizioni ricorrono.
2. [Non si applica a chi, nel corso della ricerca, commette fatti diversi da quelli previsti all'articolo 5.]
3. [Sistemi per i quali è richiesto un accordo preventivo.]

**Nodo 14 - Sistemi di interesse pubblico e sicurezza nazionale.** Le pene più alte (da 3 a 10 e da 4 a 12 anni) colpiscono i sistemi di interesse militare, pubblico, sanitario, ecc. Il Belgio richiede un accordo scritto preventivo per alcuni soggetti sensibili. Alternative: A) tutela uguale per tutti; B) accordo preventivo per un elenco di soggetti; C) esclusione di alcune categorie. Va deciso con i penalisti, perché è il punto di maggior rischio per il ricercatore e di maggior preoccupazione per l'ordinamento.

## Art. 5 - Reati ai quali si applica e altre responsabilità

1. La disposizione si applica ai fatti previsti dagli artt. 615-ter, 617-quater, 635-bis del codice penale e dall'art. 167 del decreto legislativo 30 giugno 2003, n. 196.
2. Restano ferme le altre responsabilità per atti non necessari alla segnalazione o non conformi alle condizioni (modello belga).

**Nodo 15 - Altri reati strumentali.** La Politica ACN richiama 615-ter, 617-quater, 635-bis e 167 Codice privacy. Restano da valutare i reati strumentali (per esempio la detenzione o diffusione di strumenti e codici di accesso, il danneggiamento di sistemi, la rivelazione di segreti): elenco e numerazione dopo la L. 90/2024 a cura dei penalisti.

**Nodo 16 - Responsabilità civile e amministrativa.** La Relazione ACN parla di tutela "sotto i profili della responsabilità civile e penale". Un articolo sulla sola non punibilità non esclude il risarcimento né le sanzioni amministrative. Alternative: A) solo penale; B) penale e civile; C) penale, civile e amministrativa, per i soli atti coperti dalle condizioni. Con il Garante per le sanzioni privacy (vedi sotto).

## Art. 6 - Esenzione dall'obbligo di denuncia per CSIRT Italia

**Testo base (modello francese, art. L2321-4 Code de la défense).**

> 1. Per le esigenze di sicurezza dei sistemi informativi e di rete, gli obblighi di cui all'articolo 331 del codice di procedura penale e all'articolo 361 del codice penale non si applicano al personale del CSIRT Italia [e dell'ACN] che, in qualità di coordinatore ai sensi dell'articolo 16 del decreto legislativo 4 settembre 2024, n. 138, riceve da una persona di buona fede la segnalazione dell'esistenza di una vulnerabilità, per i fatti relativi alla vulnerabilità segnalata.
> 2. CSIRT Italia può compiere le operazioni tecniche strettamente necessarie a caratterizzare il rischio, allo scopo di avvertire il titolare o il fabbricante.

**Nodo 17 - Quali norme neutralizzare.** Il personale CSIRT è pubblico ufficiale (così la Politica ACN) e ha obbligo di informare l'autorità giudiziaria dei reati procedibili d'ufficio. I penalisti verificano quali obblighi vanno derogati (331 c.p.p.? 361 c.p.? altri) e dove inserire la deroga (codice di procedura penale o d.lgs. 138/2024). Da verificare anche la procedibilità dell'art. 615-ter dopo la L. 90/2024: se il primo comma resta a querela, l'obbligo di denuncia opera soprattutto per le ipotesi aggravate, cioè quelle sui sistemi di interesse pubblico, che sono proprio le più gravi.

**Nodo 18 - Limiti.** Alternative per i casi in cui dalla segnalazione emergano fatti gravi (esfiltrazione massiva, estorsione, danneggiamento): A) esenzione piena come in Francia; B) esenzione con eccezione per i reati gravi; C) esenzione condizionata al rispetto da parte del segnalante delle condizioni dell'articolo 3 (verificate dal CSIRT).

**Nodo 19 - Altri canali.** Se la segnalazione arriva a un'autorità diversa dal CSIRT (forze di polizia), l'esenzione non opera. Alternative: estenderla o prevedere l'inoltro al CSIRT.

**Nodo 20 - Indagini già in corso.** Chiarire che l'esenzione non impedisce all'autorità giudiziaria di procedere sulla base di altre notizie.

## Art. 7 - Riservatezza del segnalante

1. CSIRT Italia preserva la riservatezza dell'identità del segnalante e delle condizioni in cui la segnalazione è stata effettuata [a richiesta] [sempre].

**Nodo 21 - Anonimato e prova.** La Politica ammette segnalazioni anonime. Chi segnala in forma anonima può avere difficoltà a dimostrare in futuro di aver rispettato le condizioni. Alternative: ricevuta con identificativo che il segnalante conserva, custodia da parte del CSIRT di una corrispondenza sigillata, divulgazione dell'identità al solo giudice. Limiti di riservatezza rispetto al diritto di difesa, da definire con i penalisti.

## Art. 8 - Accertamento delle condizioni

1. CSIRT Italia rilascia al segnalante una ricevuta che attesta data e contenuto della segnalazione.
2. [Su richiesta dell'autorità giudiziaria, CSIRT Italia attesta: a) data e contenuto della segnalazione; b) esito della procedura; c) [il rispetto delle condizioni dell'articolo 3.]]

**Nodo 22 - Ruolo del CSIRT.** In Belgio il CCB, con la procura, esamina il rispetto delle condizioni. Alternative: A) solo attestazioni oggettive (date, contenuti, esito); B) anche valutazione di conformità. B affida a un organo amministrativo un giudizio che compete al giudice penale e che pesa sulla libertà personale: i penalisti devono dire se è accettabile come mero elemento di prova.

## Art. 9 - Dati personali

1. Il segnalante tratta i dati personali strettamente necessari, li conserva in modo sicuro e li cancella al termine della procedura.
2. [Disposizioni sul trattamento da parte di CSIRT Italia e sulla trasmissione al titolare.]

Questo articolo richiede il confronto con il Garante: vedi sezione "Punti per il Garante".

## Art. 10 - Monitoraggio e valutazione

1. ACN riferisce al Parlamento, con la relazione annuale, il numero di segnalazioni ricevute, i tempi di trattamento, i casi in cui l'autorità giudiziaria ha avviato un procedimento nei confronti di segnalanti.
2. Clausola di valutazione a [24] mesi dall'entrata in vigore.

## Art. 11 - Invarianza finanziaria

Dall'attuazione non derivano nuovi o maggiori oneri per la finanza pubblica. **Nodo 23:** da verificare con ACN e con gli uffici parlamentari se la ricevuta e il trattamento dell'attestazione comportino costi.

## Art. 12 - Entrata in vigore e disciplina transitoria

Entrata in vigore il [giorno successivo alla pubblicazione]. **Nodo 24 - Disciplina intertemporale.** Applicazione ai fatti anteriori e ai procedimenti in corso: art. 2 c.p. e natura giuridica scelta all'art. 2 della proposta (vedi Nodo 3).

## Altri nodi per i penalisti

- **Nodo 25 - Territorialità.** La tutela vale per il diritto italiano: sistemi o titolari fuori dall'Italia (il Belgio lo dichiara espressamente). Ricadute sull'art. 6 c.p. e sulla giurisdizione.
- **Nodo 26 - Rapporto con attività autorizzate.** Distinguere con chiarezza i test autorizzati (contratto di penetration test, bug bounty, autorizzazione scritta) dal safe harbor: il safe harbor non li sostituisce.
- **Nodo 27 - Rapporto con altre scriminanti e con il whistleblowing.** Interazione con le cause di giustificazione generali del codice e con la disciplina sulle segnalazioni di illeciti (*da verificare*: d.lgs. 24/2023). Il CCB belga tiene separato il canale di segnalazione di vulnerabilità dal regime dei whistleblower.
- **Nodo 28 - Coordinamento con il Regolamento (UE) 2024/2847 (Cyber Resilience Act)**, in vigore dal 2024, con obblighi di segnalazione dei fabbricanti applicabili dal settembre 2026 e il ruolo dei CSIRT: da verificare se la nuova architettura di segnalazione incida sul perimetro dell'articolo 1.

## Punti per il Garante per la protezione dei dati personali

Il confronto con il Garante serve perché la proposta tocca l'art. 167 del Codice privacy e perché il segnalante, nel corso della ricerca, può venire a contatto con dati personali. L'art. 36, par. 4, del GDPR prevede la consultazione dell'autorità di controllo durante l'elaborazione di misure legislative che riguardano il trattamento di dati personali *[da verificare dai giuristi]*.

1. **Art. 167 e sanzioni amministrative.** La non punibilità non cancella le sanzioni amministrative del GDPR (art. 83) né il risarcimento (art. 82). Serve decidere se e come coordinare: senza coordinamento, il ricercatore potrebbe essere protetto in sede penale ed esposto in sede amministrativa e civile.
2. **Ruolo del ricercatore.** Il CCB belga considera il segnalante titolare del trattamento che compie, tenuto al GDPR. Occorre valutare se questa qualificazione sia corretta per l'Italia e quale base giuridica sostenga il trattamento minimo.
3. **Violazione di dati.** In Belgio il segnalante deve informare entro 72 ore l'organizzazione e l'autorità per la protezione dei dati in caso di perdita di dati con rischio per gli interessati. Serve decidere se replicare l'obbligo o attribuirlo al titolare del sistema.
4. **Trattamento da parte di CSIRT Italia.** Ricezione di dati personali nelle segnalazioni, conservazione, trasmissione al fabbricante o al titolare: finalità, base giuridica, tempi, misure.
5. **Minimizzazione e cancellazione.** Termini concreti di conservazione e cancellazione dei dati raccolti dal segnalante; casi di procedimenti in corso.
6. **Categorie particolari e dati giudiziari.** Cosa fa il segnalante che incontra dati sanitari o giudiziari durante la verifica.
7. **Altre norme del Codice.** Se estendere la non punibilità anche ad altre fattispecie del capo sulle sanzioni penali (per esempio la comunicazione e diffusione illecita su larga scala e l'acquisizione fraudolenta): *da verificare numerazione e contenuto*.
8. **Tempi e forma della consultazione.** Prima della presentazione in Parlamento oppure durante l'esame; richiesta di parere scritto.

## Struttura della relazione illustrativa (da scrivere dopo la fase 2)

1. Il quadro: Politica ACN, Relazione annuale 2025, delega non esercitata (L. 15/2024, art. 3, comma 1, lett. i), art. 615-ter e L. 90/2024.
2. Il problema: il ricercatore si espone ai reati informatici anche quando agisce in buona fede, e il CSIRT ha un obbligo di denuncia.
3. L'esperienza comparata: Belgio, Paesi Bassi, Germania, Francia.
4. Le scelte: natura giuridica, condizioni cumulative, esclusioni, esenzione del CSIRT, riservatezza.
5. Commento articolo per articolo.
6. Coordinamento con la normativa vigente (codice penale, c.p.p., d.lgs. 138/2024, Codice privacy, normativa UE).
7. Analisi di impatto (clausola di invarianza, monitoraggio).
8. Elenco dei firmatari.
