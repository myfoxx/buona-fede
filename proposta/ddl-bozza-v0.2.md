# Disegno di legge — bozza completa di lavoro

Versione 0.2 — 27 ottobre 2026

**Avvertenza.** Questo documento è una bozza di lavoro del progetto Buona Fede, destinata alla discussione con i penalisti e i giuristi, che scrivono e validano il testo definitivo (vedi GOVERNANCE.md). Non è un testo normativo. Per ogni articolo è proposto un testo base: dove il progetto ha già fissato un principio, il testo lo segue; dove la scelta è aperta, il testo base adotta l'alternativa indicata e rinvia al nodo corrispondente dello scheletro v0.1 (proposta/articolato-scheletro.md), che resta il documento di riferimento per le alternative. I riferimenti normativi, in particolare la numerazione del codice penale dopo la legge 28 giugno 2024, n. 90, sono da verificare dai penalisti sul testo vigente.

---

# DISEGNO DI LEGGE

## Disposizioni per la tutela penale della ricerca di sicurezza in buona fede e per la divulgazione coordinata delle vulnerabilità

d'iniziativa [del senatore / del deputato] [...]

---

# RELAZIONE ILLUSTRATIVA

## 1. Il quadro

Il 7 ottobre 2026 l'Agenzia per la cybersicurezza nazionale ha comunicato l'adozione della Politica nazionale di divulgazione coordinata delle vulnerabilità (CVD), adottata con determina del Direttore generale firmata il 6 ottobre 2026, d'intesa con il Ministero della giustizia espressa il 31 ottobre 2025, in attuazione dell'articolo 16 del decreto legislativo 4 settembre 2024, n. 138, di recepimento della direttiva (UE) 2022/2555 (NIS2).

La Politica chiede a chiunque scopra una vulnerabilità non nota di segnalarla al CSIRT Italia non appena ne abbia consapevolezza, vieta di condividerne i dettagli con terzi senza l'autorizzazione del CSIRT e, al tempo stesso, avverte che l'attività di ricerca non deve integrare alcuna fattispecie criminosa, richiamando espressamente gli articoli 615-ter, 617-quater e 635-bis del codice penale e l'articolo 167 del decreto legislativo 30 giugno 2003, n. 196. La stessa Politica ricorda che il personale del CSIRT Italia riveste la qualifica di pubblico ufficiale ed è quindi tenuto, ai sensi del codice di procedura penale, a informare l'autorità giudiziaria dei reati procedibili d'ufficio di cui abbia notizia nell'esercizio delle funzioni.

La Relazione annuale ACN per il 2025 (pag. 16) riconosce che la Politica «non reca una disciplina in materia di tutela dei segnalanti sotto i profili della responsabilità civile e penale», perché una simile disciplina richiede una norma di rango primario. Questo disegno di legge è quella norma.

## 2. Il problema

L'ordinamento chiede al ricercatore di sicurezza di segnalare e, nello stesso atto, lo espone a procedimento penale.

L'articolo 615-ter del codice penale punisce chiunque si introduce abusivamente in un sistema informatico o telematico protetto, o vi si mantiene contro la volontà di chi ha il diritto di escluderlo. Le Sezioni Unite della Corte di cassazione (sent. n. 4694 del 2012, Casani) hanno chiarito che ai fini della configurabilità del reato non rilevano gli scopi e le finalità che hanno motivato l'ingresso: conta la violazione oggettiva delle condizioni di accesso. La buona fede del ricercatore, da sola, non lo protegge.

La legge 28 giugno 2024, n. 90, ha inasprito il quadro: per i sistemi di interesse militare, di sicurezza pubblica, di sanità, di protezione civile o comunque di interesse pubblico la pena è della reclusione da tre a dieci anni, e da quattro a dodici anni nelle ipotesi aggravate del secondo comma. Sono proprio i sistemi dove la scoperta di una vulnerabilità ha il massimo valore per la collettività.

A questo si aggiunge l'obbligo di denuncia del CSIRT: chi segnala una vulnerabilità scoperta al di fuori di un incarico autorizzato consegna a un pubblico ufficiale, obbligato a riferire all'autorità giudiziaria, la prova documentale di una condotta astrattamente riconducibile all'articolo 615-ter. Il risultato prevedibile è che le vulnerabilità non vengano segnalate, o vengano segnalate in forma anonima e incompleta, o vengano vendute su mercati che nessuna Politica raggiunge. La sicurezza collettiva ne esce indebolita.

Il Parlamento ha già percepito il problema: il disegno di legge S. 1441 (aprile 2025) contiene una delega al Governo in materia, rimasta a oggi non esaminata. Il presente disegno di legge sceglie la via della norma diretta, immediatamente applicabile.

## 3. L'esperienza comparata

**Belgio.** Gli articoli 22 e 23 della legge del 26 aprile 2024 di recepimento della direttiva NIS2 introducono una tutela generale per il ricercatore che agisce senza intento fraudolento o di danno, si limita a quanto necessario e proporzionato, segnala senza ritardo al Centre for Cybersecurity Belgium (CCB) e al titolare e non divulga senza consenso del CCB. È il modello più completo oggi vigente in Europa e il riferimento principale di questa proposta per le condizioni cumulative.

**Paesi Bassi.** Non esiste una norma di legge dedicata: la tutela si fonda sulla guida CVD dell'NCSC (2013, aggiornata nel 2018) e sulla politica di esercizio dell'azione penale definita dalla Procura (lettera del 14 dicembre 2020), che orienta la discrezionalità del pubblico ministero verso l'archiviazione quando il ricercatore ha rispettato le regole di condotta. Il modello funziona nella pratica, ma dipende dalla discrezionalità dell'accusa: in Italia, dove vige l'obbligatorietà dell'azione penale (articolo 112 della Costituzione), non è replicabile senza una norma primaria. È la ragione per cui questa proposta è una legge e non una circolare.

**Germania.** Il Ministero federale della giustizia ha presentato nel novembre 2024 un Referentenentwurf che esclude la tipicità del fatto per la ricerca di sicurezza condotta a fini di segnalazione; il testo non è stato approvato nella scorsa legislatura, ma l'impegno è stato ripreso nel contratto di coalizione del 2025 e confermato in sede parlamentare nella risposta del Governo federale del 16 aprile 2026. La soluzione tecnica tedesca (ridefinire in negativo l'elemento dell'abusività) è una delle alternative sottoposte ai penalisti.

**Francia.** L'articolo L2321-4 del Code de la défense non incide sulla punibilità del ricercatore, ma esonera l'ANSSI dall'obbligo di denuncia per i fatti relativi alla vulnerabilità segnalata da una persona in buona fede e ne tutela la riservatezza, consentendo all'autorità le sole operazioni tecniche necessarie a caratterizzare il rischio e ad avvertire il titolare. È il modello dell'articolo 7 di questa proposta: senza di esso, qualunque safe harbor resterebbe teorico, perché il primo atto della segnalazione resterebbe una denuncia contro se stessi.

Nessuno dei quattro modelli, da solo, basta all'Italia. La proposta combina le condizioni sostanziali del modello belga con l'esenzione dall'obbligo di denuncia del modello francese.

## 4. Le scelte

**Natura giuridica della tutela.** Il testo base adotta la formula «non è punibile» (causa di non punibilità), perché è la soluzione a minore impatto sistematico e di più agevole scrittura. Restano sul tavolo, per i penalisti, la causa di giustificazione (che estenderebbe gli effetti alla responsabilità civile e amministrativa e coprirebbe il concorso di persone) e l'esclusione della tipicità sul modello tedesco. La scelta definitiva spetta a chi scrive il testo finale (Nodo 3 dello scheletro).

**Condizioni cumulative.** La tutela opera solo se ricorrono tutte le condizioni dell'articolo 4: buona fede e assenza di intento fraudolento o di fine di profitto; azioni strettamente necessarie e proporzionate; nessuna copia o conservazione di dati oltre lo stretto necessario; nessun danno; segnalazione tempestiva al CSIRT Italia e al titolare; nessuna divulgazione pubblica senza il consenso del CSIRT; nessuna richiesta di compenso come condizione della segnalazione. È una tutela stretta, costruita per il ricercatore che chiede aiuto, non per chi cerca una copertura.

**Collocazione.** La non punibilità entra nel codice penale (nuovo articolo 615-ter.1), dove il giudice e il ricercatore la cercano; le disposizioni procedurali e organizzative (segnalazione, esenzione dall'obbligo di denuncia, riservatezza, attestazioni) si collocano in raccordo con il decreto legislativo n. 138 del 2024, sede naturale della CVD.

**Esenzione dall'obbligo di denuncia.** Senza la deroga agli obblighi del pubblico ufficiale, la Politica CVD chiede al ricercatore di autodenunciarsi. L'articolo 7 introduce l'esenzione sul modello francese, limitata ai fatti relativi alla vulnerabilità segnalata e priva di effetti sulle indagini fondate su altre notizie di reato.

**Riservatezza.** L'identità del segnalante è riservata, con le sole eccezioni necessarie al diritto di difesa e agli accertamenti dell'autorità giudiziaria.

**Ciò che la proposta non fa.** Non autorizza preventivamente alcuna attività; non sostituisce i test autorizzati (penetration test su incarico, programmi di bug bounty, autorizzazioni scritte), che restano la via maestra; non tocca la punibilità di chi danneggia, esfiltra, estorce o monetizza; non limita i poteri dell'autorità giudiziaria che proceda sulla base di notizie diverse dalla segnalazione.

## 5. Commento articolo per articolo

**Articolo 1 (Finalità).** Dichiara lo scopo della legge e la aggancia all'articolo 16 del decreto legislativo n. 138 del 2024 e alla Politica nazionale CVD. La tutela penale del segnalante è il tassello che la Relazione annuale ACN 2025 indica come mancante.

**Articolo 2 (Definizioni).** Definisce vulnerabilità, segnalante, CSIRT Italia, titolare del sistema e scoperta. Il perimetro oggettivo adottato è ampio (qualsiasi vulnerabilità di un prodotto, servizio o sistema, con rinvio alla Politica per la procedura): limitare la tutela alle sole vulnerabilità non note lascerebbe fuori la maggior parte dei casi reali, come le esposizioni e le errate configurazioni di sistemi specifici (Nodo 1).

**Articolo 3 (Non punibilità).** Introduce l'articolo 615-ter.1 del codice penale. La non punibilità copre i fatti previsti dagli articoli 615-ter, 617-quater e 635-bis del codice penale e dall'articolo 167 del Codice privacy, cioè i reati che la stessa Politica ACN indica come rischio tipico della ricerca, quando ricorrono tutte le condizioni dell'articolo 4. L'estensione ad altri reati strumentali è rimessa alla valutazione dei penalisti (Nodo 15).

**Articolo 4 (Condizioni).** Elenca le condizioni cumulative. Per la segnalazione il testo base adotta la formula «senza ritardo e comunque entro settantadue ore dalla scoperta», che unisce l'immediatezza chiesta dalla Politica a un termine verificabile, sul modello della notifica completa belga (Nodo 9). Se il titolare non è identificabile o raggiungibile con la diligenza ordinaria, basta la segnalazione al CSIRT Italia, che provvede a informarlo. La proporzionalità è una clausola generale accompagnata da un elenco esemplificativo di condotte comunque escluse, ricavato dal modello belga (Nodo 5).

**Articolo 5 (Esclusioni).** La tutela non si applica a chi subordina la segnalazione a un compenso, ferma la liceità dei programmi di ricompensa istituiti dal titolare e degli accordi conclusi prima dell'inizio della ricerca. Resta aperto, come nodo per i penalisti e per il dibattito parlamentare, il trattamento dei sistemi di cui al terzo comma dell'articolo 615-ter (Nodo 14): il testo base non li esclude, perché sono i sistemi dove la segnalazione vale di più, ma il punto va discusso.

**Articolo 6 (Altre responsabilità).** Chiarisce che restano ferme le responsabilità per i fatti estranei alle condizioni, e rinvia alla scelta sulla natura giuridica per gli effetti civili e amministrativi (Nodo 16). Prevede il coordinamento con il Garante per la protezione dei dati personali per i profili sanzionatori amministrativi.

**Articolo 7 (Esenzione dall'obbligo di denuncia).** Trasposizione del modello francese: gli obblighi di denuncia e di referto non si applicano al personale del CSIRT Italia per i fatti relativi alla vulnerabilità segnalata da una persona in buona fede. Il CSIRT può compiere le operazioni tecniche strettamente necessarie a caratterizzare il rischio. L'esenzione non opera per i reati diversi che emergano dalla segnalazione né impedisce i procedimenti fondati su altre notizie (Nodi 17-20).

**Articolo 8 (Riservatezza del segnalante).** Il CSIRT Italia preserva l'identità del segnalante e le condizioni della segnalazione, salvo consenso dell'interessato, esigenze del diritto di difesa o provvedimento motivato dell'autorità giudiziaria. Sono ammesse le segnalazioni anonime, come prevede la Politica.

**Articolo 9 (Ricevuta e attestazioni).** Il CSIRT Italia rilascia una ricevuta con data e contenuto della segnalazione, anche con identificativo per le segnalazioni anonime, e su richiesta dell'autorità giudiziaria attesta i dati oggettivi della procedura. La valutazione del rispetto delle condizioni resta al giudice (Nodo 22).

**Articolo 10 (Protezione dei dati personali).** Impone al segnalante minimizzazione, custodia sicura e cancellazione dei dati; rinvia a un provvedimento del Garante, sentita l'ACN, per le modalità attuative. L'articolo presuppone la consultazione del Garante ai sensi dell'articolo 36, paragrafo 4, del regolamento (UE) 2016/679.

**Articolo 11 (Monitoraggio).** L'ACN riferisce annualmente al Parlamento su segnalazioni, tempi e procedimenti avviati nei confronti di segnalanti; clausola di valutazione a ventiquattro mesi.

**Articolo 12 (Invarianza finanziaria e entrata in vigore).**

## 6. Coordinamento con la normativa vigente

Il testo richiede il coordinamento con: il codice penale, come modificato dalla legge n. 90 del 2024 (numerazione e procedibilità delle fattispecie, da verificare sul testo vigente); il codice di procedura penale (articoli 331 e seguenti); il decreto legislativo n. 138 del 2024 e la Politica nazionale CVD; il Codice in materia di protezione dei dati personali e il regolamento (UE) 2016/679; il regolamento (UE) 2024/2847 (Cyber Resilience Act), i cui obblighi di segnalazione per i fabbricanti si applicano dal settembre 2026; il decreto legislativo 10 marzo 2023, n. 24, in materia di whistleblowing, dal quale il canale CVD resta distinto.

## 7. Analisi di impatto

La proposta non istituisce organi né procedure nuove: utilizza il CSIRT Italia e la procedura CVD già operativi. La clausola di invarianza finanziaria è ritenuta sostenibile, salvo verifica con l'ACN sugli oneri delle ricevute e delle attestazioni. Il monitoraggio dell'articolo 11 consente la valutazione dell'efficacia.

---

# TESTO ARTICOLATO

## Capo I — Finalità e definizioni

### Art. 1 — Finalità

1. La presente legge tutela chi ricerca e segnala vulnerabilità informatiche in buona fede, al fine di rafforzare la sicurezza dei sistemi informativi e di rete, in coerenza con la politica nazionale di divulgazione coordinata delle vulnerabilità di cui all'articolo 16 del decreto legislativo 4 settembre 2024, n. 138.

### Art. 2 — Definizioni

1. Ai fini della presente legge si intende per:
a) «vulnerabilità»: una debolezza, una suscettibilità o un difetto di un prodotto, di un servizio o di un sistema informatico o telematico che può essere sfruttato per comprometterne la sicurezza [coordinare con la definizione del decreto legislativo n. 138 del 2024 — Nodo 1];
b) «segnalante»: la persona fisica o giuridica che segnala una vulnerabilità al CSIRT Italia, anche in forma anonima;
c) «CSIRT Italia»: il gruppo nazionale di risposta agli incidenti di sicurezza informatica di cui al decreto legislativo 4 settembre 2024, n. 138;
d) «titolare del sistema»: il soggetto che ha il diritto di escludere terzi dal sistema informatico o telematico, ovvero il fabbricante o il fornitore del prodotto o del servizio cui la vulnerabilità si riferisce;
e) «scoperta»: il momento in cui il segnalante acquisisce consapevolezza dell'esistenza della vulnerabilità [Nodo 2].

## Capo II — Non punibilità della ricerca di sicurezza in buona fede

### Art. 3 — Non punibilità

1. Dopo l'articolo 615-ter del codice penale è inserito il seguente:

> «Art. 615-ter.1 (Ricerca di sicurezza in buona fede). — Non è punibile chi, al fine di verificare l'esistenza di una vulnerabilità di un prodotto, di un servizio o di un sistema informatico o telematico e di segnalarla, commette taluno dei fatti previsti dagli articoli 615-ter, 617-quater e 635-bis del presente codice o dall'articolo 167 del decreto legislativo 30 giugno 2003, n. 196, quando ricorrono tutte le condizioni previste dalla legge.»

[Formula «non è punibile» adottata come testo base; alternative (scriminante, esclusione della tipicità) al Nodo 3. Estensione ad altri reati strumentali al Nodo 15. Collocazione alternativa nel d.lgs. 138/2024 al Nodo relativo alla riserva di codice.]

### Art. 4 — Condizioni

1. La non punibilità di cui all'articolo 615-ter.1 del codice penale opera quando il segnalante:
a) agisce in buona fede, senza intento fraudolento e senza fine di profitto per sé o per altri;
b) compie le sole azioni strettamente necessarie e proporzionate alla verifica dell'esistenza della vulnerabilità e alla sua segnalazione;
c) non copia, non estrae e non conserva dati oltre quanto strettamente necessario a dimostrare l'esistenza della vulnerabilità, e cancella i dati acquisiti al termine della procedura di segnalazione, salvo quanto previsto dall'articolo 10;
d) non cagiona danno ai sistemi, ai dati o alla disponibilità dei servizi [alternativa «danno prevedibile» al Nodo 8];
e) segnala la vulnerabilità, senza ritardo e comunque entro settantadue ore dalla scoperta, al CSIRT Italia e al titolare del sistema; quando il titolare non è identificabile o non è raggiungibile con l'ordinaria diligenza, la segnalazione al solo CSIRT Italia, che provvede a informare il titolare, soddisfa la condizione [termine e destinatari: Nodi 9-11];
f) non divulga né comunica a terzi informazioni sulla vulnerabilità senza il consenso del CSIRT Italia [Nodo 12];
g) non subordina la segnalazione alla corresponsione di un compenso o di altra utilità.
2. Non sono in ogni caso necessarie né proporzionate, ai sensi del comma 1, lettera b): l'installazione di programmi malevoli; le condotte dirette a rendere indisponibili i sistemi o i servizi; l'ingegneria sociale, il phishing e l'invio massivo di comunicazioni; l'acquisizione di credenziali mediante tentativi sistematici; la cancellazione o l'alterazione di dati; la prosecuzione delle operazioni oltre quanto occorre a dimostrare l'esistenza della vulnerabilità su scala ridotta. [Elenco esemplificativo sul modello belga; tassatività al Nodo 5.]

### Art. 5 — Esclusioni

1. La non punibilità non si applica a chi subordina la segnalazione alla corresponsione di un compenso o di altra utilità, anche quando ricorrono le altre condizioni.
2. Il comma 1 non si applica ai compensi previsti da programmi di ricompensa istituiti dal titolare del sistema né a quelli concordati con il titolare prima dell'inizio della ricerca.
3. [Eventuale disciplina speciale per i sistemi di cui all'articolo 615-ter, terzo comma, del codice penale — Nodo 14: il testo base non prevede esclusioni; alternativa dell'accordo preventivo per un elenco di soggetti.]

### Art. 6 — Altre responsabilità

1. Restano ferme le responsabilità previste dalla legge per i fatti diversi da quelli indicati nell'articolo 615-ter.1 del codice penale e per le condotte non conformi alle condizioni di cui all'articolo 4.
2. [Effetti sulla responsabilità civile e sulle sanzioni amministrative: dipendono dalla natura giuridica scelta — Nodo 16. In caso di causa di non punibilità, valutare una disposizione espressa di esonero per i soli atti conformi alle condizioni, previa consultazione del Garante per la protezione dei dati personali per i profili di cui al regolamento (UE) 2016/679.]

## Capo III — Segnalazione e garanzie

### Art. 7 — Esenzione dall'obbligo di denuncia

1. Gli obblighi di cui agli articoli 331 del codice di procedura penale e 361 e 362 del codice penale non si applicano al personale del CSIRT Italia e dell'Agenzia per la cybersicurezza nazionale che, nell'ambito della procedura di divulgazione coordinata di cui all'articolo 16 del decreto legislativo 4 settembre 2024, n. 138, riceve da una persona in buona fede la segnalazione dell'esistenza di una vulnerabilità, limitatamente ai fatti relativi alla vulnerabilità segnalata. [Individuazione esatta degli obblighi da derogare: Nodo 17.]
2. Il CSIRT Italia può compiere le operazioni tecniche strettamente necessarie a caratterizzare il rischio connesso alla vulnerabilità, allo scopo di avvertire il titolare del sistema o il fabbricante del prodotto.
3. L'esenzione di cui al comma 1 non si applica ai fatti costituenti reato diversi da quelli relativi alla vulnerabilità segnalata e non preclude all'autorità giudiziaria di procedere sulla base di notizie di reato acquisite aliunde. [Nodi 18-20.]

### Art. 8 — Riservatezza del segnalante

1. Il CSIRT Italia preserva la riservatezza dell'identità del segnalante e delle condizioni in cui la segnalazione è stata effettuata.
2. L'identità del segnalante può essere rivelata soltanto con il suo consenso, ovvero quando la rivelazione è indispensabile per l'esercizio del diritto di difesa o è disposta con provvedimento motivato dell'autorità giudiziaria. [Anonimato e prova: Nodo 21.]
3. Sono ammesse le segnalazioni in forma anonima.

### Art. 9 — Ricevuta e attestazioni

1. Il CSIRT Italia rilascia al segnalante una ricevuta che attesta la data e il contenuto della segnalazione. Per le segnalazioni anonime la ricevuta reca un identificativo univoco che consente al segnalante di ricollegarsi alla segnalazione.
2. Su richiesta dell'autorità giudiziaria, il CSIRT Italia attesta la data e il contenuto della segnalazione e l'esito della procedura di divulgazione coordinata. [La valutazione del rispetto delle condizioni dell'articolo 4 spetta al giudice: Nodo 22.]

### Art. 10 — Protezione dei dati personali

1. Il segnalante tratta i soli dati personali strettamente necessari alla dimostrazione e alla segnalazione della vulnerabilità, li custodisce con misure adeguate di sicurezza e li cancella alla conclusione della procedura di segnalazione, salvo che la conservazione sia necessaria in un procedimento in corso.
2. Con provvedimento del Garante per la protezione dei dati personali, sentita l'Agenzia per la cybersicurezza nazionale, sono definite le modalità di attuazione del comma 1 e il trattamento dei dati personali contenuti nelle segnalazioni da parte del CSIRT Italia. [Punti per il Garante nello scheletro v0.1; consultazione ex articolo 36, paragrafo 4, del regolamento (UE) 2016/679.]

## Capo IV — Disposizioni finali

### Art. 11 — Monitoraggio e valutazione

1. L'Agenzia per la cybersicurezza nazionale riferisce annualmente al Parlamento, nell'ambito della relazione di cui alla normativa vigente, sul numero delle segnalazioni ricevute ai sensi della presente legge, sui tempi di trattamento e sui procedimenti penali avviati nei confronti di segnalanti dei quali abbia avuto conoscenza.
2. Decorsi ventiquattro mesi dalla data di entrata in vigore della presente legge, il Governo trasmette alle Camere una relazione sulla sua attuazione e sui suoi effetti.

### Art. 12 — Invarianza finanziaria ed entrata in vigore

1. Dall'attuazione della presente legge non derivano nuovi o maggiori oneri a carico della finanza pubblica. Le amministrazioni interessate provvedono con le risorse umane, strumentali e finanziarie disponibili a legislazione vigente. [Nodo 23.]
2. La presente legge entra in vigore il giorno successivo a quello della sua pubblicazione nella Gazzetta Ufficiale. [Disciplina intertemporale: Nodo 24, dipende dalla natura giuridica scelta.]

---

## Nota di lavoro

Scelte di testo base operate in questa versione, tutte reversibili in sede di revisione dei penalisti:
formula «non è punibile» (Nodo 3); perimetro ampio delle vulnerabilità, non limitato alle zero day (Nodo 1); termine di segnalazione «senza ritardo e comunque entro settantadue ore» (Nodo 9); doppio destinatario con fallback sul solo CSIRT (Nodo 10); elenco esemplificativo delle condotte sproporzionate (Nodo 5); nessun danno in assoluto, come da principi fissati (Nodo 8); consenso del CSIRT per la divulgazione, come da principi fissati (Nodo 12); nessuna esclusione dei sistemi di interesse pubblico (Nodo 14, da discutere); deroga agli articoli 331 c.p.p. e 361-362 c.p. (Nodo 17, da verificare).

I numeri dei Nodi rinviano a proposta/articolato-scheletro.md.
