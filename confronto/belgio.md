# Belgio - legge NIS2 del 26 aprile 2024, artt. 22-23

Scheda v0.1 - 20 ottobre 2026

## In sintesi

Il Belgio è l'unico dei quattro Paesi con una protezione scritta in una legge per chi cerca e segnala vulnerabilità senza autorizzazione preventiva. La protezione è condizionata, limitata e si applica solo al diritto belga. Il testo è nella legge di recepimento NIS2 e vale per chiunque, anche se l'organizzazione non ha una propria politica CVD.

## Strumento giuridico e stato

- Legge del 26 aprile 2024 che istituisce un quadro per la cibersicurezza delle reti e dei sistemi informativi di interesse generale per la sicurezza pubblica ("legge NIS2"). Artt. 22 e 23 sulla segnalazione delle vulnerabilità al CSIRT nazionale (Centre for Cybersecurity Belgium, CCB).
- Pubblicata nel Moniteur belge il 17 maggio 2024 (fonte: CCB). In vigore dal 18 ottobre 2024.
- Si applica a vulnerabilità di prodotti e servizi ICT soggetti al diritto belga (sistemi e reti situati in Belgio).

## Chi è protetto

Qualsiasi persona fisica o giuridica che agisca senza intento fraudolento o di nuocere, indipendentemente dal fatto che l'organizzazione colpita sia soggetta a NIS2 o abbia una politica CVD.

## Condizioni (come le elenca la pagina del CCB)

Numerazione della pagina CCB, sezione B. La numerazione dell'art. 23 nel testo di legge potrebbe differire: **da verificare sul testo pubblicato nel Moniteur belge** (una fonte secondaria, Timelex, numera diversamente: quarta condizione la proporzionalità, quinta il divieto di divulgazione).

1. Non si agisce oltre quanto necessario e proporzionato per verificare l'esistenza della vulnerabilità e segnalarla.
2. Nessun intento fraudolento o di nuocere. Non si può monetizzare l'informazione verso l'organizzazione o terzi, salvo che un compenso sia stato concordato in precedenza (pentest, bug bounty, accordo). Non si usa la vulnerabilità a vantaggio proprio o di terzi senza accordo.
3. Notifica semplificata entro 24 ore dalla scoperta, all'organizzazione responsabile e al CCB.
4. Notifica completa entro 72 ore dalla scoperta, con descrizione dettagliata e passi per riprodurre.
5. Nessuna divulgazione pubblica senza l'accordo del CCB (che tiene conto della posizione dell'organizzazione).
6. Per alcuni soggetti sensibili (servizi di intelligence, difesa, polizia, rappresentanze diplomatiche fuori dall'UE, stabilimenti nucleari di classe I, enti giudiziari, CCB stesso, ecc.) serve un accordo scritto preventivo.

La pagina del CCB indica anche come proporzionalità: sono considerate sproporzionate l'installazione di malware, il DDoS, il social engineering, il phishing, lo spam, il furto di password o il brute force, la cancellazione di dati, il danno prevedibile al sistema. Se la dimostrazione è possibile su scala ridotta non si va oltre; i dati raccolti vanno cancellati entro un tempo ragionevole dopo la segnalazione.

## Effetto giuridico

Se tutte le condizioni sono rispettate, secondo il CCB può essere riconosciuta, in misura limitata, una **causa di giustificazione** per i reati degli artt. 314bis (intercettazione), 458 (segreto professionale), 550bis (accesso abusivo) e 550ter (danneggiamento di dati) del codice penale belga, e dell'art. 145 della legge del 13 giugno 2005 sulle comunicazioni elettroniche. Chi segnala informazioni apprese nel contesto professionale non viola il segreto professionale per la trasmissione necessaria alla segnalazione. Ogni altra responsabilità per atti non necessari alla segnalazione o non conformi alle condizioni resta intatta. La tutela vale solo per il diritto belga.

Il CCB, su richiesta e se le condizioni sono rispettate, si impegna a mantenere riservata l'identità del segnalante. Il CCB, con la competente procura, esamina il rispetto delle condizioni.

Dati personali: il segnalante resta tenuto a rispettare il GDPR come titolare per il trattamento che compie, nel minimo necessario, con cancellazione appena finito il procedimento; in caso di perdita di dati con rischio per gli interessati deve informare l'organizzazione e l'autorità per la protezione dei dati entro 72 ore.

## Limiti e critiche (da approfondire)

- La protezione è espressa come causa di giustificazione "in misura limitata": il segnalante non ha una certezza assoluta, perché è la procura (con il CCB) a verificare le condizioni.
- Termini di 24 e 72 ore dalla scoperta: rigidi. La prova del momento della scoperta resta a carico del segnalante (il CCB raccomanda di conservare i log).
- La protezione non copre fatti in sistemi situati fuori dal Belgio.
- Fonti secondarie segnalano che, con la nuova legge, non sono più protette scoperte basate su manipolazione fisica dell'hardware: **da verificare sul testo di legge** prima di usare questo punto.

## Cosa insegna all'Italia

La struttura delle condizioni coincide quasi del tutto con quella dei principi fissati dal progetto (buona fede, proporzionalità, segnalazione, nessuna divulgazione senza consenso del CSIRT, nessuna monetizzazione). Differenze da discutere: i termini di 24/72 ore contro "tempestività"; l'elenco di condotte sproporzionate; l'accordo scritto per i sistemi sensibili (in Italia i sistemi di interesse pubblico sono proprio quelli con le pene più alte); la scelta tecnica fra causa di giustificazione, causa di non punibilità o esclusione della tipicità.

## Fonti

- CCB, Vulnerability reporting to the CCB: https://ccb.belgium.be/en/node/1871 (verificata)
- CCB, pagina introduttiva: https://ccb.belgium.be/node/299 (verificata)
- CCB, pubblicazione della legge NIS2 nel Moniteur belge: https://ccb.belgium.be/nl/node/412 (verificata)
- Timelex (via Mondaq), Protecting Ethical Hackers Under Belgian Law, 1 dicembre 2025: https://www.mondaq.com/security/1711834/protecting-ethical-hackers-under-belgian-law-and-how-organisations-should-respond-to-vulnerabilities-disclosed-to-them (fonte secondaria)
- Testo della legge nel Moniteur belge (artt. 22-23): **non ancora consultato**

## Da verificare

1. Testo ufficiale degli artt. 22-23 e numerazione delle condizioni.
2. Se la causa di giustificazione sia testuale nella legge o formulazione del CCB.
3. Eventuali casi applicativi o prime decisioni dopo il 18 ottobre 2024.
4. Il punto sull'hardware fisico.
