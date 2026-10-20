# Call for paper

**Buona Fede. Per chi fa sicurezza in Italia: scrivi la norma che ti manca**

Versione 0.1 - 20 ottobre 2026

## Prima di tutto

Questo non è un tavolo già fatto. È una call per formarlo. Abbiamo messo insieme un manifesto, quattro schede sui Paesi che hanno già affrontato il problema e uno scheletro con le domande aperte, perché a una proposta di legge si arriva con del materiale in mano, non con un sondaggio. Ma le risposte non le abbiamo, i principi sono tutti in discussione e chi decide cosa entra nel testo lo sceglie chi risponde a questa call, non chi l'ha scritta. Chi risponde entra; chi entra firma, se vuole, con nome e ruolo.

## Il punto

Il 7 ottobre 2026 ACN ha invitato la comunità a segnalare le vulnerabilità zero day al CSIRT Italia. L'invito arriva senza una tutela scritta per chi segnala: l'ACN stessa lo ha riconosciuto nella Relazione annuale 2025. Il 615-ter non distingue le intenzioni e, sui sistemi di interesse pubblico, arriva a 10 anni, 12 con l'aggravante.

Vogliamo scrivere, in pubblico, una proposta di legge per una causa di non punibilità condizionata, con l'esenzione dall'obbligo di denuncia per il CSIRT, e portarla in Parlamento. Il testo penale lo scrivono i penalisti, ma i casi, i confini e gli errori li conosci tu. Questa call serve a raccogliere la tua esperienza prima che il testo prenda forma.

Si parte dal [manifesto](../manifesto/MANIFESTO.md) e dalle [schede comparative](../confronto/README.md). Lo [scheletro dell'articolato](../proposta/articolato-scheletro.md) è un elenco di domande che ci siamo fatti, non di risposte.

## A chi è rivolta

Hacker etici, ricercatori di sicurezza, professionisti (pentester, red team, incident response, DPO, CISO), giuristi e penalisti, ricercatori universitari, chi lavora in un CSIRT o in un SOC. Non servono titoli, né essere noti.

## Le due fasi

### Fase 1 - Principi (quattro settimane dal [DATA APERTURA])

Ci servono contributi sui principi, non sui commi. In discussione: buona fede e assenza di profitto; azioni necessarie e proporzionate; nessuna copia o esfiltrazione oltre lo stretto necessario; nessun danno; segnalazione tempestiva a CSIRT Italia e al titolare; nessuna divulgazione senza il consenso del CSIRT; nessuna richiesta di compenso come condizione; esenzione dall'obbligo di denuncia per il CSIRT; estensione ai reati citati dalla Politica.

Domande guida (rispondi a quelle dove hai esperienza, non a tutte):

1. **Buona fede.** Come si riconosce da fuori? Quali comportamenti la rendono credibile? A chi spetta dimostrarla?
2. **Necessario e proporzionato.** Per categorie di azioni, senza parlare di sistemi reali: dove passa il confine tra verificare e andare oltre? Un elenco di condotte escluse aiuta o irrigidisce?
3. **Dati.** Cosa significa "stretto necessario" quando la prova richiede di mostrare un dato? Come si documenta senza conservare?
4. **Danno.** Quali effetti collaterali sono ragionevolmente imprevedibili? Una condizione di "nessun danno" assoluta regge?
5. **Tempestività.** Il Belgio chiede 24 ore per la notifica semplificata e 72 per la completa. È realistico? Come si fissa il momento della scoperta? E se il titolare non si trova?
6. **Divulgazione.** Tempi di correzione che hai visto; cosa dovrebbe succedere se il CSIRT non risponde o non autorizza; esperienze con altri CSIRT o programmi (anonimizzate).
7. **Compenso.** Dove passa il confine tra ringraziamento, bug bounty e richiesta come condizione?
8. **CSIRT.** Cosa serve perché ti fidi: ricevuta, tempi di risposta, riservatezza, anonimato? Come si prova di aver segnalato?
9. **Perimetro.** La Politica riguarda gli zero day. La tutela deve coprire anche esposizioni, errate configurazioni, vulnerabilità note su un sistema specifico?
10. **Sistemi di interesse pubblico.** Dove le pene sono più alte: tutela uguale, accordo preventivo, esclusioni?
11. **Casi.** Casi già pubblici (sentenze, provvedimenti, atti, pubblicazioni ufficiali), anonimizzati, in cui l'assenza di tutela ha avuto effetti concreti.

Formati: nota breve (una pagina), position paper (massimo 3.000 parole), scheda su altri Paesi, nota tecnica. Italiano, Markdown. Per i giuristi: osservazioni su natura giuridica, collocazione e formulazione sono benvenute già in fase 1. Basta anche una pagina.

### Fase 2 - Testo articolato (dopo la sintesi della fase 1)

Chi ha risposto alla fase 1 sceglie il comitato (vedi [GOVERNANCE.md](../GOVERNANCE.md), che è una proposta). Il comitato pubblica una sintesi dei contributi e una versione dell'articolato (v0.2) costruita su quelle risposte. Segue un periodo di commento sul testo, con attenzione a formulazione delle condizioni, esenzione del CSIRT, confronto con il Garante privacy, disciplina transitoria. I penalisti validano il testo prima della chiusura.

## Come inviare

Pull request con il tuo file in `call/contributi/`, oppure issue con il modello "osservazione sui principi". Se non usi Git, scrivi alla segreteria: segreteria@buonafede.org. Lo pubblichiamo noi.

## Regole

a. **Niente vulnerabilità reali.** Non indicare vulnerabilità non risolte, nomi di sistemi o aziende, exploit, accessi non autorizzati non ancora definiti in sede giudiziaria. I casi sono ammessi solo se già pubblici e anonimizzati, con la fonte. Leggi il [Codice di condotta](../CODE_OF_CONDUCT.md): il contributo che lo viola viene rimosso.

b. **Se hai una vulnerabilità da segnalare**, non farlo qui: usa i canali di CSIRT Italia.

c. **Nome o pseudonimo.** Puoi inviare con uno pseudonimo e lo pubblichiamo così. Per comparire tra i firmatari serve il nome reale e il ruolo.

d. **Nessuna consulenza.** Non rispondiamo a domande sulla tua posizione personale: per quello serve un avvocato.

e. **Licenza.** Inviando accetti che il contributo sia rilasciato con la licenza del repository.

f. **Fonti.** Se affermi qualcosa su una norma o un documento, indica la fonte.

## Cosa succede dopo

Ogni contributo che rispetta il Codice di condotta è pubblicato. La segreteria risponde a ciascuno nel registro delle osservazioni, con esito e motivazione. I contributi che hanno cambiato il testo sono citati nella relazione illustrativa con il nome o lo pseudonimo dell'autore, se lo consente.

## Chi promuove

Maurizio Siracusa, ricercatore di sicurezza indipendente, a titolo personale. Nessuna azienda, nessun marchio. Chi decide, da qui in avanti, è scritto in [GOVERNANCE.md](../GOVERNANCE.md).

## Calendario

| | |
|---|---|
| Apertura fase 1 | [DATA APERTURA] |
| Chiusura fase 1 | [DATA APERTURA + 28 giorni] |
| Assemblea dei contributori e scelta del comitato | [DATA] |
| Sintesi e articolato v0.2 | [DATA] |
| Fase 2 | [DATA] - [DATA] |
| Chiusura v1.0 e firme | [DATA] |
