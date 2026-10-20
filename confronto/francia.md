# Francia - art. L2321-4 del Code de la défense

Scheda v0.1 - 20 ottobre 2026

## In sintesi

La Francia non protegge il ricercatore: protegge il rapporto fra il ricercatore e l'autorità che riceve la segnalazione. Dal 2016 il personale dell'ANSSI non è obbligato a denunciare alla procura una vulnerabilità segnalata in buona fede e deve mantenere riservata l'identità del segnalante. L'immunità penale per chi segnala fu voluta dai deputati ma non è entrata nel testo.

## Strumento giuridico

- Art. L2321-4 del Code de la défense, creato dall'art. 47 della legge n. 2016-1321 del 7 ottobre 2016 (loi pour une République numérique).
- Contenuto, in sintesi:
  1. Per esigenze di sicurezza dei sistemi d'informazione, l'obbligo di denuncia previsto dall'art. 40 del codice di procedura penale non si applica nei confronti di una persona di buona fede che trasmetta alla sola autorità nazionale di sicurezza dei sistemi d'informazione (ANSSI) l'informazione sull'esistenza di una vulnerabilità di un sistema di trattamento automatizzato di dati.
  2. L'autorità preserva la riservatezza dell'identità della persona che ha trasmesso e delle condizioni in cui la trasmissione è avvenuta.
  3. L'autorità può compiere le operazioni tecniche strettamente necessarie a caratterizzare il rischio o la minaccia, allo scopo di avvertire l'host, l'operatore o il responsabile del sistema d'informazione.

Il testo che ho letto è la copia pubblicata dal Consiglio d'Europa. **Da confrontare con la versione vigente su Légifrance** (potrebbero esserci state modifiche).

## Cosa fa e cosa non fa

- L'obbligo che viene neutralizzato è quello dell'art. 40 CPP, che impone ai pubblici ufficiali di avvisare il procuratore quando apprendono un reato nell'esercizio delle funzioni. Il segnalante di buona fede che si rivolge all'ANSSI non innesca quella denuncia d'ufficio.
- **Non** c'è esenzione penale per il ricercatore. Secondo la stampa specializzata dell'epoca (fonte secondaria), il Senato eliminò l'esenzione penale che l'Assemblea nazionale voleva. La vittima può quindi sempre sporgere denuncia: l'ANSSI semplicemente non denuncerà.
- Secondo la stessa fonte, prima della legge l'ANSSI non aveva mai attivato l'art. 40 in questi casi: la norma ha formalizzato una prassi. **Da verificare con fonti primarie.**
- Il sito dell'ANSSI raccomanda di segnalare direttamente all'ente interessato quando questo ha una politica di trattamento delle vulnerabilità, e conferma la riservatezza dell'identità e degli elementi della dichiarazione.

## Cosa insegna all'Italia

1. È il modello della parte "CSIRT" del progetto: l'esenzione dall'obbligo di denuncia e la riservatezza del segnalante. In Italia l'equivalente dell'art. 40 CPP francese è l'obbligo di denuncia dei pubblici ufficiali (art. 331 c.p.p.) con la sanzione dell'art. 361 c.p. per l'omessa denuncia: **i penalisti devono verificare quali norme vanno neutralizzate**.
2. La sola esenzione dell'autorità, senza protezione del ricercatore, lascia aperto il rischio principale: la denuncia della vittima. Per questo il progetto combina il modello francese (esenzione e riservatezza per il CSIRT) con il modello belga (condizioni cumulative e protezione del ricercatore).
3. Il testo francese condiziona l'esenzione a una segnalazione "alla sola autorità" e alla buona fede; la versione dell'Assemblea chiedeva anche "assenza di pubblicità" dell'informazione (fonte secondaria): è un criterio che il progetto già tratta con il divieto di divulgazione senza consenso del CSIRT.

## Fonti

- Code de la défense, art. L2321-4 (copia Consiglio d'Europa): https://rm.coe.int/code-de-la-defense-art-l-2321-4/16808e92d0 (verificata)
- ANSSI, Déclaration de vulnérabilités: https://cyber.gouv.fr/reglementation/cybersecurite-systemes-dinformation/declaration-de-vulnerabilites/ (verificata)
- ANSSI, Signalement par un lanceur d'alerte: https://cyber.gouv.fr/reglementation/cybersecurite-systemes-dinformation/signalement-lanceur-dalerte/ (verificata; precisa che il regime dei lanceurs d'alerte non prevede deroga all'art. 40 CPP)
- Next (ex Next INpact), articoli del 2016 sulla loi République numérique e sull'ANSSI: https://next.ink/14190/99629-loi-numerique-l-anssi-future-plateforme-pour-signaler-failles-informatiques/ ; https://next.ink/10949/103055-signalements-failles-a-l-anssi-pas-raz-de-maree-apres-loi-lemaire/ (stampa, fonti secondarie)
- Légifrance, versione vigente dell'art. L2321-4: **non consultata**
- Lavori parlamentari della legge 2016-1321 (emendamenti sull'immunità penale): **non consultati**

## Da verificare

1. Versione vigente dell'art. L2321-4 su Légifrance, e se sia stato modificato dopo il 2016.
2. Storia dell'emendamento sull'immunità penale (Assemblea e Senato).
3. Dati sull'uso effettivo della procedura da parte dell'ANSSI.
4. Rapporto fra L2321-4 e il regime dei lanceurs d'alerte.
