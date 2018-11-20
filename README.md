# UniPocket
Secondo Assignment di Processo e Sviluppo del Software.

Version 1.0 – 15.11.2018

Adorni Giorgia 806787  
Basso Matteo 807628

# Requirements Elicitation (RE)

## <!--Istruzioni del documento-->

<!--inserire le istruzioni eventuali-->

## Obiettivi del documento

Vengono descritte nel seguente documento le procedure di estrazione dei requisiti dell'applicazione **UniPocket** e i conseguenti risultati<!--, incluse attività di analisi-->. Vengono inoltre riportate le funzionalità del sistema e ciò che intende risolvere, fungendo da base contrattuale tra il cliente e lo sviluppatore.
Il documento viene redatto nella lingua del dominio del business e di competenza del cliente (nel nostro caso l'italiano).

## Sistem as-is

L'applicazione **UniPocket** si propone come un'alternativa che unisce al suo interno diversi sistemi preesistenti. Al momento per visualizzare la carriera universitaria e gli orari delle aule è infatti necessario l'utilizzo di due applicazioni mobile differenti. Alcune informazioni invece non risultano disponibili da alcuna di esse ma sono consultabili solamente mediante siti web.
Appare dunque chiaro che vi è una frammentazione dell'informazione che fa si che gli utenti possano trovarsi confusi o poco soddisfatti dei sistemi in uso. Avere un singolo applicativo mediante il quale è possibile svolgere ogni tipo di attività porterebbe alla semplificazione della vita universitaria e magari ad una maggiore inclusione da parte degli studenti.

### <!--Domain understanding-->

<!-- Descrizione dell'ambiente universitario, organizzazioni etc
Definire chi è il **committente** e chi sono gi **sviluppatori**-->

Il sistema UniPocket e i suoi servizi<!--elencare enventuali nomi per il servizio voti, statistiche etc.--> sono progettati per essere una singola applicazione destinata a dispositivi smartphone (iOS e Android). 

## System to-be
UniPocket è un applicazione mobile universitaria indirizzata a due principali gruppi di utenti: studenti e docenti (dell'Università degli Studi di Milano-Bicocca). 

Essa prevede numerosi gruppi di funzionalità, differenziati anche sulla base dell'utente. In particolare, effettuando l'accesso (tramite il sistema delle segreterie online) e acconsentendo l'accesso ai dati, sono disponibili le seguenti funzionalità: 

- Consultazione degli orari delle lezioni e degli esami
- News dall’università tramite la newsletter Unimib Informa
- Consultazione del menù giornaliero delle mense universitarie
- Consultazione degli orari della navetta
- Analisi dei dati a scopo statistico da parte dell'amministrazione universitaria

#### Studenti

- Visibilità del piano di studi e libretto voti 
- Statistiche relative l'andamento della carriera, come media dei voti degli esami e base di laurea
- Statistiche relative ai corsi difficoltà (es. valutazione dei docenti, valutazione sull'organizzazione e  difficolta di un corso etc.)
- Iscrizione agli esami
- Vendita e acquisto di libri usati e non

#### Professori

- Statistiche relative al gradimento dei propri corsi e della proprio metodo di insegnamento 
- Statistiche riguardo l'andamento dei propri studenti nei diversi corsi
- Creazione di appelli d'esame 
- Prenotazione di aule e laboratori

## Stakeholders

Esistono cinque tipi principali "attori" nell'applicazione UniPocket:

- Gli **studenti** hanno la possibilità di accedere all'applicazione e monitorare la loro carriera universitaria. Risultano rilevanti per il processo di elicitazione per identificare e risolvere le problematiche circa il reperimento di alcune informazioni che possono risultare utili quotidianamente. Inoltre sono in grado di fornire opinioni riguardo i sistemi correnti, ovvero le motivazioni del loro scarso utilizzo.
- I **professori** hanno la possibilità di accedere all'applicazione ed effettuare svariate attività, tra cui la prenotazione delle aule e dei laboratori, l'inserimento di prove d'esame e la visualizzazione delle statistiche relative i propri corsi. Essi risultano coloro che utilizzano l'applicazione per gestire le attività universitarie ed è dunque necessario che il sistema risulti comodo e veloce da utilizzare secondo i loro bisogni. Sono in grado di identificare quali processi possono rendere la comunicazione con gli studenti difficoltosa e una possibile soluzione.
- Le segreterie online possono causare difficoltà nel processo di richiesta dei dati dello studente/professore se alcuni aspetti interferiscono con i loro diritti, ma non sono considerate come stakeholder in quanto il loro impatto principale, se presente, sarà come una fonte di vincoli. 
- L'**amministrazione universitaria** deve essere in grado di accedere a statistiche e informazioni relative l'attività svolta da studenti e professori. Essa risulta rilevante per comprendere quali sono i dati di fondamentale interesse e quali schermate possono essere sviluppate per la loro visualizzazione e analisi. È necessario determinare come l'università può essere in grado di valutare la soddisfazione complessiva e come alcuni cambiamenti si riflettano sugli utenti. L'amministrazione fornisce quindi dei vincoli esterni al progetto, per esempio quali sono i dati che è interessati a raccogliere e in che modo l'applicazione può aiutare a farlo, diventando di conseguenza uno stakeholder con diritti limitati.
- Enti della privacy (garante della protezione dei dati personali), che impongono dei regolamenti sulla gestione dei dati degli utenti, impongono dei vincoli "normativi" ma non sono parti interessate. Il loro principale impatto sarà come una fonte di vincoli. 

Esaminando questi cinque candidati abbiamo definito che solo tre sono stakeholders, ovvero gli studenti, i professori e l'amministrazione universitaria. 

<!-- MANCA QUESTO Inoltre, prima di poter procedere alla fase di sottomissione dei questionari e delle interviste, abbiamo definito le priorità e i diritti di ciascuna categoria (parte interessata), in modo da poter scegliere tra due requisiti contrastanti e risolvere situazioni in cui abbiano uguale priorità e non possano essere scambiati in modo efficace. 
In seguito, dopo aver compreso il ruolo, le responsabilità e le interazioni tra gli stakeholders, abbiamo  identificato i rappresentanti appropriati che possono parlare a nome di un determinato gruppo di stakeholders, in modo da ricevere un contributo per il  processo di sollecitazione dei requisiti del sistema.-->

<!-- QUESTO é SOLO UN APPUNTO PER LA PROSSIMA SUBMIT Idealmente, un rappresentante adeguato per gli stakeholder deve:  
• comprendere il dominio aziendale;  
• comprendere questa particolare area applicativa all'interno del dominio aziendale;  
• capire il problema specifico;   
• rappresentare fedelmente le esigenze della propria comunità di stakeholder;  
• essere di supporto al sistema e al processo di definizione dei requisiti;  
• avere tempo sufficiente per essere in grado di contribuire quando richiesto. 
Poiché non tutti gli stakeholders possiedono gli attributi di cui sopra (per esempio la comprensione del dominio etc.), è necessario un periodo di formazione e istruzione per garantire che le parti interessate siano a conoscenza dei requisiti (da implementare).-->

### <!--System models-->

<!-- PROSSIMA SUBMIT Eventuali scenari, storyboard e mockup dell'applicazione: modelli illustrativi, l'interfaccia utente del sistema e i percorsi di navigazione che rappresentano la sequenza di schermate-->

## Questionnaires

I questionari sono molteplici e differenti in base allo stakeholder. Essi sono costituiti principalmente da domande chiuse e a scelta multipla così da poter ottenere in modo rapido e da svariate persone informazioni soggettive circa il sistema attuale e il suo utilizzo. Vengono utilizzati inoltre per mostrare il grado di interessamento alla soluzione proposta da UniPocket. Essi non mirano alla sostituzione delle interview ma solamente all'acquisizione di informazioni per migliorarle e dar maggior risalto a ciò che risulta veramente importante.

I questionari sono stati sviluppati e svolti secondo la scala sotto riportata:

1. decisione del pubblico del questionario (vari questionari per i diversi stakeholder).
2. determinazione delle informazioni che si desidera ottenere.
3. decisione del metodo di raccolta dei dati (elettronico, telefonico, postale).
4. decisione dei tipi di domande.
5. utilizzo del questionario su un campione di potenziali rispondenti e, se necessario, revisione delle domande.
6. distribuzione del questionario.
7. analisi delle risposte.
8. presentazione e utilizzo dei risultati.

### Questionario studente

La prima sezione del questionario dedicato agli studenti pone domande volte alla comprensione dei sistemi correnti e del loro utilizzo da parte degli studenti.
In particolare richiediamo quali sono le applicazioni esistenti, quanti di essi le utilizzano, di quali funzionalità sono dotate e il grado di soddisfazione del loro utilizzo, così da poter meglio delineare la situazione corrente e poter successivamente agire di conseguenza offrendo un servizio di più alto livello.
Sempre nella prima sezione, a seguito di tali domande, ne vengono poste alcune riguardo il livello di interesse verso UniPocket e il suo grado di utilità. In questo modo è possibile ottenere informazioni circa l'interessamento da parte degli utilizzatori verso la nostra proposta.
Nelle due sezioni successive viene richiesto di valutare il grado di interessamento alle singole funzionalità, così da identificare al meglio gli interessi degli utenti e potergli dare priorità e rilievo.
Vengono infine poste alcune domanda aperte per comprendere al meglio ulteriori idee dell'utente, commenti ed interessamente complessivo.

<!--MANCA QUESTO: spiegazione della ridondanza di alcune domande, e la spiegazione della scala di gratimento usata -->

## Interviews

Anche per quanto riguarda le interview sono stati redatti documenti differenti in base allo stakeholder. Dal punto di vista pratico è stato selezionato un set limitato di domande da porre al fine di ottenere informazioni specifiche e mirate. Esse risultano volutamente non eccessivamente numerose, così da poter lasciare spazio a un libero dialogo, al fine di esplorare e comprendere meglio il sistema corrente, le problematiche e le eventuali soluzioni possibili dal suo punto di vista.  
Le interview inizieranno dunque con la parte strutturata, costituita dalle domande definite nei documenti e proseguiranno con una parte non strutturata e libera.

Di seguito vengono riportate le informazioni che è necessario ottenere da ciascuno stakeholder:
- Gli studenti hanno la possibilità di esporre la soddisfazione generale riguardo la ricezione di informazioni, l'utilizzo di applicativi offerti dall'università e da terze parti per la gestione della loro carriera universitaria, con conseguente identificazione di una soluzione.
- I professori possono esprimere la loro soddisfazione riguardo le procedure e l'utilizzo di applicativi offerti dall'università. Sono in grado di identificare le problematiche esistenti, poichè consuenti utilizzatori dei sistemi e dunque potenzialmente capaci di identificare migliorie dal punto di vista procedurale e comunicativo all'interno dell'ambiente universitario.
- L'università ha la capacità di identificare quali dati sono rilevanti per effettuare analisi e come possono essere visualizzati e utilizzati per migliorare i servizi offerti al personale e agli studenti.

Successivamente ad ogni interview viene trascritto un report per riassumere ed evidenziare le criticità e i punti di maggior interesse che sono emersi dal processo. Tale report viene sottoposto quindi allo stakeholder che deve confermare o rifinire ciò che è stato riportato. Risulta possibile a questo punto effettuare un'analisi su quanto trascritto e valutare come viene ritenuto adeguato procedere.

## <!-- Analisi dei risultati analizzati-->

## <!-- Segnalazione dei requisiti emergenti-->
