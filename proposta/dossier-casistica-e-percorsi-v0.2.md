# Dossier: casistica 2016-2026 e percorsi normativi

Versione 0.2 — 2 novembre 2026 — recepisce la revisione esterna del 2/11/2026 (correzioni su Modern Solution, FreeHour, Belgio; nota metodologica rafforzata). Materiale di lavoro per la relazione illustrativa e per il percorso parlamentare della proposta.

**Metodo.** Ogni affermazione è classificata per livello di verifica: **[A]** atto o fonte primaria (sentenza, comunicato ufficiale, legge, risposta parlamentare) consultata; **[B]** fonte qualificata (stampa specializzata o agenzia con ricostruzione verificabile, concordante su più testate); **[C]** fonte secondaria o ricostruzione (blog, dossier, analisi di studio legale, fonte singola), da riscontrare prima dell'uso in relazione. La colonna "coperto" valuta se la causa di non punibilità condizionata della bozza v0.2 (buona fede, proporzionalità, nessuna esfiltrazione oltre il necessario, nessun danno, segnalazione tempestiva, nessuna divulgazione senza consenso, nessuna richiesta di compenso) avrebbe coperto il fatto. Dove un fatto è solo una tesi dell'accusa, è detto espressamente: le allegazioni processuali non sono fatti accertati.

---

## 1. Italia

### Luigi Gubello ("Evariste Gal0is") — piattaforma Rousseau, 2017-2019 [B]

Studente universitario, nell'agosto 2017 verifica la sicurezza della piattaforma Rousseau (M5S/Casaleggio), segnala le falle via email ai gestori, riceve ringraziamenti, poi viene denunciato dall'Associazione Rousseau e identificato dalla polizia postale (febbraio 2018). Indagato per accesso abusivo a sistema informatico (art. 615-ter c.p.). Dichiarò agli inquirenti di aver agito "per testare la vulnerabilità del sistema, nessuna finalità politica". Il processo si apre a Milano e si chiude alla prima udienza, il 19 aprile 2019: secondo la cronaca, sentenza di non doversi procedere per remissione di querela (giudice Elena Bernante, XI sezione penale). Rousseau aveva annunciato il ritiro della querela il 9 marzo 2019, dopo quasi due anni di esposizione mediatica e giudiziaria del ricercatore.

- Esito: nessuna condanna, ma solo perché il denunciante ha rimesso la querela. L'esito è dipeso interamente dalla volontà della parte offesa, non da una valutazione della buona fede.
- Nota per la relazione: prima della citazione in sede parlamentare, acquisire la sentenza o l'estratto dell'udienza; la formula sopra deriva dalla stampa, non dall'atto.
- Coperto dal safe harbor: **in larga parte sì.** Segnalazione al titolare, nessun profitto, nessun danno documentato. Punto critico: la pubblicazione dell'analisi prima della correzione, che oggi richiederebbe il consenso del CSIRT (il CSIRT come coordinatore CVD non esisteva). Con la legge proposta la sua posizione non sarebbe dipesa dalla benevolenza del denunciante.
- Stefano Zanero (PoliMi) all'epoca: vedere che anche con le migliori intenzioni si finisce nei guai "è un disincentivo" per gli altri ricercatori.
- Fonti: ANSA 6/2/2018; AGI 7-8/2/2018; Open 9/3/2019; Il Giorno 19/4/2019; Vice Italia 2018.

### Dopo la L. 90/2024 [A per le pene, C per l'assenza di casi]

Il rischio è cresciuto: per i sistemi di interesse pubblico (sanità, ordine pubblico, militare, protezione civile) reclusione da 3 a 10 anni, da 4 a 12 col concorso delle aggravanti del secondo comma, procedibilità d'ufficio. Pene che rendono astrattamente possibili misure cautelari. **Nota metodologica:** nelle fonti consultate per questo dossier non risultano condanne definitive italiane 2024-2026 a carico di segnalatori in buona fede; è un'assenza rilevata nelle fonti consultate, non un'assenza accertata — i procedimenti per 615-ter di norma non fanno notizia se l'indagato non è pubblico. Il dato più visibile resta il silenzio dei ricercatori, non i processi: è il chilling effect (§4), e la call for paper serve anche a far emergere i casi sommersi.

---

## 2. Estero

| Caso | Paese, anni | Contestazione | Esito | Coperto dal safe harbor proposto |
|---|---|---|---|---|
| Sviluppatore vs **Modern Solution** [B, concordante su heise e borncity] | Germania, 2021-2025 | § 202a StGB (Ausspähen von Daten) e § 205, per aver verificato, con phpMyAdmin e una password contenuta nel software, che il DB del fornitore esponeva i dati di circa 700.000 clienti; segnalò al titolare, che lo denunciò | Perquisizione e sequestro dei dispositivi (2021); condanna a 3.000 € di ammenda (AG Jülich, gen. 2024, Az. 17 Cs 55/23, riportato per esteso anche come 17 Cs-230 Js 99/21-55/23); confermata da LG Aachen (4/11/2024) e da OLG Köln (fine luglio 2025): **condanna definitiva**. Il ricorso costituzionale al BVerfG, presentato dopo la definitività, è stato **respinto**, secondo heise e borncity nell'autunno 2025. *Nota di verifica:* la prima copertura heise dell'agosto 2025 riportava la sola presentazione del ricorso; fonti successive dello stesso heise e di borncity riportano il rigetto. Il dato è mantenuto con doppia fonte e distinzione tra fase di presentazione ed esito; il provvedimento del BVerfG resta non consultato direttamente [B] | **Sì.** Si disconnesse appena capì la portata, segnalò al titolare il giorno dopo, nessun profitto, nessun danno. Unico nodo: divulgazione pubblica dopo la correzione, gestibile nel canale CVD. È il caso-manifesto: ha fatto tutto "giusto" ed è stato condannato in via definitiva |
| "András", ricercatore vs **Magyar Telekom** [B] | Ungheria, 2017-2019 | Violazione di sistema informatico; riqualificata come reato contro impianto di pubblica utilità (2-8 anni) dopo il rifiuto del patteggiamento | Trovò una falla grave (aprile 2017), la segnalò, la società discusse un'assunzione mai concretizzata, lui proseguì i test e fu arrestato su denuncia. La procura chiese **8 anni di reclusione effettiva**; offrì 2 anni sospesi in cambio della confessione; rifiutò. Trib. di Szolnok 10/7/2019: colpevole nell'ipotesi base, **multa 600.000 HUF (~1.800 €)**, confermata in appello il 6/12/2019 | **In parte / no.** Secondo la sentenza riportata dalla stampa, proseguì i test contro la volontà del titolare e chiese un impiego retribuito collegato alla segnalazione: le condizioni b) ed eventualmente g) non reggono. Caso utile in relazione per mostrare che le condizioni filtrano gli abusi, e insieme la sproporzione (8 anni chiesti per un fatto chiuso con una multa) |
| 18enne vs **BKK/T-Systems** (biglietti Budapest) [B] | Ungheria, 2017 | Denunciato da T-Systems per aver mostrato che il prezzo del biglietto online era modificabile lato client | Arrestato, caso chiuso **in fase di polizia** dopo la sollevazione pubblica | **Sì** (sulla base delle cronache) |
| Studenti e docente **FreeHour** [B] | Malta, 2022-2025 | Accesso non autorizzato: segnalarono una falla nell'app al fondatore, che informò la polizia | Arresti (nov. 2022), perquisizioni, incriminazione formale (mar. 2025), **grazia presidenziale** il 1/7/2025 su raccomandazione del premier Abela, che ha riconosciuto la responsabilità dello Stato di aggiornare le leggi (parafrasi della stampa) | **In parte, con riserva.** Secondo l'accusa sarebbe stata richiesta una ricompensa (contestata come tentata estorsione) e un'app temporaneamente modificata: sono **allegazioni processuali mai accertate**, perché la grazia ha chiuso il caso senza giudizio. Il punto fermo è un altro: quasi tre anni di procedimento per un fatto che un canale CVD con regole chiare avrebbe gestito in settimane |
| **Coalfire** (DeMercurio e Wynn) [B] | USA, 2019-2020 | Burglary (poi trespass) per un penetration test fisico **autorizzato per contratto** dalla Iowa Judicial Branch sul tribunale di Dallas County | Arresto in flagranza (11/9/2019), cauzione a 100.000 $, tuta arancione, accuse cadute il 30/1/2020 dopo pressione pubblica e un'audizione legislativa statale; fedina con arrest record permanente | Fuori perimetro (attività autorizzata, non CVD) ma utile in relazione: anche il lavoro contrattualizzato finisce in cella quando manca una cornice legale chiara |

### Sintesi onesta per la relazione

Nei casi europei verificati nessuno ha scontato carcere: multe, archiviazioni, remissioni, una grazia. Ma il carcere è stato chiesto (8 anni in Ungheria), minacciato come leva di patteggiamento (2 anni sospesi contro 5-8 effettivi), e gli arresti, le custodie, le perquisizioni con sequestro dei ferri del mestiere e i procedimenti pluriennali ci sono stati tutti. In Italia, dopo la L. 90/2024, le cornici edittali sui sistemi di interesse pubblico (3-10, 4-12) rendono il rischio di misura cautelare e di pena detentiva concreto, non teorico. L'argomento forte non è "la legge evita la condanna": è **"la legge evita il processo"** — e con esso la perquisizione all'alba, il sequestro dei dispositivi di lavoro di un professionista, due anni di udienze e il casellario. Formula per la relazione: la legge non premia l'abusivo, ma non lascia il ricercatore in buona fede alla mercé della querela, della perquisizione e del processo.

---

## 3. Tassonomia dei percorsi (cosa hanno fatto gli altri)

1. **Legge penale sostanziale — Belgio** (artt. 22-23 legge NIS2, 26/4/2024, in vigore dal 18/10/2024): **tutela condizionata dalla responsabilità penale** per la divulgazione coordinata di vulnerabilità, subordinata a requisiti cumulativi e riferita a un elenco determinato di reati; **non un'immunità generale** — il CCB stesso precisa che la legge non impedisce l'applicazione della responsabilità penale al di fuori delle condizioni. È il modello più completo oggi vigente e il più vicino a quello proposto.
2. **Norma sull'autorità, non sul ricercatore — Francia** (art. L2321-4 Code de la défense, 2016): l'ANSSI non è tenuta a denunciare il segnalante in buona fede e ne protegge l'identità. Il valore pratico è la riduzione del **rischio di denuncia dal canale di segnalazione** e la riservatezza: non dà al ricercatore alcuna certezza penale se la notizia arriva alla procura per altre vie.
3. **Prassi della procura — Paesi Bassi** (guida NCSC 2013/2018 + lettera di policy dell'OM, 14/12/2020): la discrezionalità dell'azione penale assorbe i casi in buona fede. **Non replicabile in Italia**: art. 112 Cost., obbligatorietà dell'azione penale.
4. **Policy di enforcement federale — USA** (DOJ, 19/5/2022): direttiva ai prosecutor di non incriminare sotto CFAA la "good-faith security research" (accesso al solo scopo di testare/segnalare, senza danno, con uso delle informazioni a beneficio della sicurezza). Stessa logica olandese, stesso limite: in Italia una circolare così non può esistere.
5. **Grazia ex post — Malta** (1/7/2025): il fallimento istituzionale ammesso. Tre anni di procedimento e poi il perdono presidenziale: il contrario della certezza del diritto.
6. **Riforma pendente — Germania e Regno Unito**: Referentenentwurf BMJ nov. 2024 (decaduto), impegno nel Koalitionsvertrag 2025, risposta parlamentare 16/4/2026 (Drucksache 21/5456); nel Regno Unito la campagna CyberUp preme per una statutory defence nel Computer Misuse Act 1990, da ultimo con la submission al Cyber Security and Resilience Bill (gennaio 2026). In entrambi i Paesi i casi (Modern Solution; i numeri UK sotto) spingono la riforma.

Per l'Italia restano in piedi due sole vie reali: la **1** (eventualmente combinata con la 2 per il CSIRT) per via parlamentare diretta, oppure l'attuazione della **delega** già scritta (S. 1441, art. 1, lett. q — safe harbor per chi segnala; e il precedente criterio L. 15/2024, art. 3, co. 1, lett. i, rimasto inattuato sul versante penale). Le vie 3 e 4 sono precluse dalla Costituzione; la 5 non è una politica.

---

## 4. Il chilling effect in numeri (per relazione e manifesto)

- Regno Unito, survey CyberUp/techUK 2020: **80%** dei professionisti teme di violare la legge nel difendere da attacchi; **93%** giudica il Computer Misuse Act inadatto al secolo; 58% dei ricercatori dice che il CMA ha ostacolato ricerca di sicurezza o threat intelligence propria o di colleghi.
- CyberUp 2023: 60% dei ricercatori vede il CMA come barriera al proprio lavoro; stima di **16.850 professionisti** persi verso Paesi con leggi più permissive e fino a **3 miliardi di sterline** di ricavi a rischio sul settore.
- Italia: la Politica CVD è operativa dal 7/10/2026; i volumi di segnalazione andranno letti nelle prossime relazioni annuali ACN — primo indicatore misurabile dell'effetto (o del non effetto) di un canale senza tutela. Numeri italiani di survey equivalenti non risultano: è esattamente il buco che la call for paper può riempire con le testimonianze.

(Nota: i numeri UK riguardano il CMA, non il 615-ter; si citano come evidenza del meccanismo, non come dato italiano.)

---

## 5. La via "strumento ad ACN" e la lista di professionisti

Domanda ricorrente nel dibattito: invece di una legge, dare ad ACN uno strumento rapido, per esempio una lista pubblica di professionisti che, se fanno divulgazioni coordinate, non sono perseguibili.

**Risposta secca: da sola non può funzionare, e la lista come condizione è l'opzione peggiore. Dentro una legge, uno strumento ad ACN è invece la parte giusta del disegno.**

1. **Riserva di legge (art. 25, co. 2, Cost.).** Nessuna determina, regolamento o lista ACN può creare una causa di non punibilità: solo la legge decide cosa è punibile e cosa no. Lo ammette ACN stessa: la Relazione 2025 dichiara che la Politica, elaborata a legislazione vigente, non reca tutele penali o civili per i segnalanti. Una "lista dei non perseguibili" per atto amministrativo sarebbe carta: il PM dovrebbe ignorarla.
2. **Obbligatorietà dell'azione penale (art. 112 Cost.).** Le vie che altrove hanno sostituito la legge — linee guida della procura olandese, policy DOJ americana — in Italia sono costituzionalmente precluse: il PM non può ricevere direttive di non perseguire. Per lo stesso motivo il personale CSIRT, pubblico ufficiale, resta oggi obbligato a denunciare: anche questo si deroga solo per legge (il modello esiste: L. 124/2007 per i servizi; la Francia l'ha fatto con L2321-4).
3. **La lista come condizione contraddice il sistema.** L'art. 16, co. 3, d.lgs. 138/2024 e l'art. 12 NIS2 garantiscono la segnalazione anonima; nessuno dei quattro modelli esteri richiede iscrizioni; lo scopritore occasionale, lo studente, il ricercatore straniero non sono iscritti a nulla; e trasformerebbe un diritto in una concessione amministrativa, con il non iscritto presuntivamente in malafede.
4. **L'architettura che tiene insieme le due esigenze:** una **legge breve** (o un emendamento alla lett. q del DDL S. 1441, veicolo già incardinato: via più rapida di un DDL autonomo) che fissa le sole tre cose che richiedono rango primario: la causa di non punibilità condizionata, l'esenzione del CSIRT dall'obbligo di denuncia, la riservatezza del segnalante. Tutto il resto — procedura, termini operativi, codice di condotta interpretativo di necessità e proporzionalità, **registro volontario non condizionante** (identità pseudonima persistente, canale rapido, valore solo probatorio), attestazioni con data certa, riconoscimento dei programmi VDP/bug bounty dei titolari — la legge lo **delega ad ACN** come fonte secondaria. Così ACN ha davvero lo strumento veloce e aggiornabile che chi propone la via amministrativa chiede, i penalisti hanno una norma primaria minima e difendibile, e la lista diventa ciò che può legittimamente essere: un acceleratore facoltativo, mai la porta d'ingresso della tutela.

---

## Registro delle modifiche v0.1 → v0.2 (revisione esterna 2/11/2026)

1. Modern Solution: fascicolo corretto in AG Jülich, Az. 17 Cs 55/23 (forma estesa 17 Cs-230 Js 99/21-55/23); esito del ricorso al BVerfG riformulato con doppia fonte e cautela, da riscontrare sul provvedimento. Accolta/in parte.
2. FreeHour: richiesta di ricompensa e modifica dell'app riqualificate come allegazioni dell'accusa, non fatti accertati. Accolta.
3. Belgio: "esenzione dalla responsabilità penale" sostituita con "tutela condizionata, non immunità generale", con la precisazione del CCB. Accolta.
4. Francia: aggiunto che il valore è la riduzione del rischio di denuncia e la riservatezza, non la certezza penale. Accolta.
5. Assenza di casi italiani post-L. 90/2024: nota metodologica esplicita ("assenza rilevata nelle fonti consultate"). Accolta.
6. Gubello: aggiunta l'avvertenza di acquisire la sentenza prima della citazione in relazione. Accolta.
7. Aggiunta la classificazione [A]/[B]/[C] del livello di verifica. Accolta.

## Fonti principali

Italia: ANSA (6/2/2018), AGI (7-8/2/2018), Open (9/3/2019), Il Giorno (19/4/2019), Vice Italia; Guerre di Rete, "L'Italia non protegge gli hacker etici" (14/10/2026, agg. 20/10/2026); Relazione annuale ACN 2025. Germania: heise.de (conferma OLG Köln, presentazione ed esito Verfassungsbeschwerde), borncity.com (dossier Modern Solution 2021-2025). Ungheria: Infostart/MTI (11/7/2019), 444.hu (26-28/1/2019, 11/7/2019, 6/12/2019), adozona.hu, hvg.hu, PortSwigger Daily Swig. Malta: MaltaToday (1/7/2025), Malta Independent, Wikipedia "2022 FreeHour ethical hacking case" (per la qualificazione delle allegazioni). USA: KrebsOnSecurity (31/1/2020), comunicato Coalfire (30/1/2020), The Register, Dark Reading; DOJ press release e policy CFAA (19/5/2022), analisi Morrison Foerster, Arnold & Porter. Regno Unito: CyberUp/techUK survey 2020 e 2023, submission al Cyber Security and Resilience Bill (gen. 2026), committees.parliament.uk. Paesi Bassi: om.nl (policy CVD). Belgio/Francia: CCB (FAQ NIS2 v2.0.1), Légifrance (verifiche nel report del 27/10).
