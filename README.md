# UniPocket
Secondo Assignment di Processo e Sviluppo del Software.

Version 1.0 – 20.11.2018

Adorni Giorgia 806787  
Basso Matteo 807628

# Requirements Elicitation (RE)

## <!--Istruzioni del documento-->

<!--inserire le istruzioni eventuali-->

## Obiettivi del documento

Vengono descritte nel seguente documento le procedure di estrazione dei requisiti dell'applicazione **UniPocket** e i conseguenti risultati, incluse attività di analisi. Vengono inoltre riportate le funzionalità del sistema e ciò che intende risolvere, fungendo da base contrattuale tra il cliente e lo sviluppatore.
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

Esistono sei tipi principali "attori" nell'applicazione UniPocket:

- Gli **studenti** hanno la possibilità di accedere all'applicazione e monitorare la loro carriera universitaria. Risultano rilevanti per il processo di elicitazione per identificare e risolvere le problematiche circa il reperimento di alcune informazioni che possono risultare utili quotidianamente. Inoltre sono in grado di fornire opinioni riguardo i sistemi correnti, ovvero le motivazioni del loro scarso utilizzo.
- I **professori** hanno la possibilità di accedere all'applicazione ed effettuare svariate attività, tra cui la prenotazione delle aule e dei laboratori, l'inserimento di prove d'esame e la visualizzazione delle statistiche relative i propri corsi. Essi risultano coloro che utilizzano l'applicazione per gestire le attività universitarie ed è dunque necessario che il sistema risulti comodo e veloce da utilizzare secondo i loro bisogni. Sono in grado di identificare quali processi possono rendere la comunicazione con gli studenti difficoltosa e una possibile soluzione.
- Le segreterie online possono causare difficoltà nel processo di richiesta dei dati dello studente/professore se alcuni aspetti interferiscono con i loro diritti, ma non sono considerate come stakeholder in quanto il loro impatto principale, se presente, sarà come una fonte di vincoli. 
- L'**amministrazione universitaria** deve essere in grado di accedere a statistiche e informazioni relative l'attività svolta da studenti e professori. Essa risulta rilevante per comprendere quali sono i dati di fondamentale interesse e quali schermate possono essere sviluppate per la loro visualizzazione e analisi. È necessario determinare come l'università può essere in grado di valutare la soddisfazione complessiva e come alcuni cambiamenti si riflettano sugli utenti. L'amministrazione fornisce quindi dei vincoli esterni al progetto, per esempio quali sono i dati che è interessati a raccogliere e in che modo l'applicazione può aiutare a farlo, diventando di conseguenza uno stakeholder con diritti limitati.
- Enti della privacy (garante della protezione dei dati personali), che impongono dei regolamenti sulla gestione dei dati degli utenti, impongono dei vincoli "normativi" ma non sono parti interessate. Il loro principale impatto sarà come una fonte di vincoli. 
- Il team di sviluppo è colui che realizza effettivamente l'applicazione una volta ottenuti tutti i requisiti ed effettuata l'analisi. Appare dunque chiara la motivazione per la quale risulta interessato al prodotto.

Esaminando questi cinque candidati abbiamo definto che solo tre di essi sono dei veri e propri stakeholders, ovvero agli studenti, ai professori e all'amministrazione universitaria. Ad essi verranno sottoposti questionari ed interviste, .

Prima di poter procedere alla fase di sottomissione dei questionari e delle interviste, abbiamo definito le priorità e i diritti di ciascuna categoria, in modo da poter scegliere tra due requisiti contrastanti e risolvere situazioni in cui abbiano uguale priorità e non possano essere scambiati in modo efficace. In particolare è stato scelto di attribuire maggior importanza agli studenti, poichè risultano coloro che utilizzeranno maggiormente i sistemi mobile durante la vita quotidiana e che hanno la necessità di accedere a una grande quantità di informazioni di diversa natura. Successivamente vi sono i professori che utilizzano i sistemi informativi per svolgere il loro lavoro, probabilmente per la maggior parte del tempo mediante l'utilizzo di un computer laptop, e solo infine l'amministrazione dell'università.  
Nonostante ciò i requisiti di studenti, professori e amministrazione non dovrebbero risultare in contrasto tra di loro, poichè ognuno di essi visualizza una versione differente dell'applicazione con le sole funzionalità disponibili coerenti con il ruolo ricoperto.  
Sono stati inoltre selezionati alcuni rappresentati appropriati degli stakeholder che possono parlare a nome del gruppo. Nel caso degli studenti, come nel caso dei professori, essi risultano coloro che ricoprono cariche amministrative, ovvero i rappresentanti degli studenti e i coordinatori dei vari dipartimenti. Nel caso dell'amministrazione invece è necessario individuare gli addetti all'analisi dei dati e questionari per la soddisfazione generale.

### <!--System models-->

<!-- PROSSIMA SUBMIT Eventuali scenari, storyboard e mockup dell'applicazione: modelli illustrativi, l'interfaccia utente del sistema e i percorsi di navigazione che rappresentano la sequenza di schermate-->

## Strategia di elicitazione

Secondo le specifiche sugli stakeholder del capitolo precedente la strategia di elicitazione risulta la seguente: <!-- manca la motivazione della strtegia: perchè abbiamo eseguito certe azioni e perchè in questo ordine-->

1. Background study: viene studiato e valutato il sistema esistente, il dominio e altre informazioni utili. <!-- Non lo abbiamo fatto però... -->
2. Brainstorming: vengono effettuate una o più sessioni di brainstorming per determinare idee, problemi e soluzioni per l'applicazione. <!-- nemmeno questo lo abbiamo fatto. il brainstorming è un'attività che coinvolge gli stakeholders e non gli sviluppatori.-->
3. Questionari: vengono svolti questionari da un set di stakeholder selezionato secondo i criteri riportati nei sottocapitoli successivi.
3. Interview: vengono svolte interviste ad alcuni stakeholder sempre secondo i criteri riportati nei sottocapitoli successivi. In alcuni casi saranno utili i questionari per sviluppare interviste migliori (come nel caso degli studenti e i professori), in altri tale operazione non sarà necessaria.
4. Nel caso in cui ci dovessero emergere dei requisiti contrastanti tra i vari stakoholder sarà necessario riprendere il processo di elicitazione del punto 2. Tenendo in considerazione le regole definite nel capitolo precedente per la risoluzione dei conflitti.
5. Al termine dei punti precedenti sarà possibile sviluppare un mock-up da sottoporre agli stakeholder, nel caso in cui tutto sia corretto sarà possibile procedere con gli sviluppi. In caso contrario risulta necessario riprendere l'attività di elicitazione fino alla produzione di mock-up validi e approvati da essi. <!-- non so se ha senso parlare di mock-up se poi non lo facciamo-->

### Questionnaires

I questionari sono molteplici e differenti in base allo stakeholder. In particolare è stato scelto di sottoporre questionari diversi a studenti e professori, che rappresentano gli stakeholder più numerosi.
Essi sono costituiti principalmente da domande chiuse e a scelta multipla così da poter ottenere in modo rapido e da svariate persone informazioni soggettive circa il sistema attuale e il suo utilizzo. Vengono utilizzati inoltre per mostrare il grado di interessamento alla soluzione proposta da UniPocket. Essi non mirano alla sostituzione delle interview ma solamente all'acquisizione di informazioni per migliorarle e dar maggior risalto a ciò che risulta veramente importante.

I questionari sono stati sviluppati e svolti secondo la scala sotto riportata:

1. decisione del pubblico del questionario (vari questionari per i diversi stakeholder).
2. determinazione delle informazioni che si desidera ottenere.
3. decisione del metodo di raccolta dei dati (elettronico, telefonico, postale).
4. decisione dei tipi di domande.
5. utilizzo del questionario su un campione di potenziali rispondenti e, se necessario, revisione delle domande.
6. distribuzione del questionario.
7. analisi delle risposte.
8. presentazione e utilizzo dei risultati.

#### Questionario studente

La prima sezione del questionario dedicato agli studenti pone domande volte alla comprensione dei sistemi correnti e del loro utilizzo da parte degli studenti.
In particolare richiediamo quali sono le applicazioni esistenti, quanti di essi le utilizzano, di quali funzionalità sono dotate e il grado di soddisfazione del loro utilizzo, così da poter meglio delineare la situazione corrente e poter successivamente agire di conseguenza offrendo un servizio di più alto livello.
Sempre nella prima sezione, a seguito di tali domande, ne vengono poste alcune riguardo il livello di interesse verso UniPocket e il suo grado di utilità. In questo modo è possibile ottenere informazioni circa l'interessamento da parte degli utilizzatori verso la nostra proposta.
Nelle due sezioni successive viene richiesto di valutare il grado di interessamento alle singole funzionalità, così da identificare al meglio gli interessi degli utenti e potergli dare priorità e rilievo.  
Oltre alle domande a scelta multipla vengono infine poste alcune brevi domande aperte, di cui alcune opzionali, per comprendere al meglio ulteriori idee dell'utente, commenti ed interessamente complessivo.   

Si noti inoltre che alcune domande vengono ripetute più volte all'interno del questionario, così da comprendere se l'utente stia effettivamente svolgendo una compilazione attenta e poter dare alle sue risposte il giusto peso. 

Molte domande sono costituite da una scala di gradimento numerica pari, ovvero da 0 a 5, in modo che l'utente non dia una risposta neutrale e possa attribuire un'importanza maggiormente espressiva ad ogni punto.

#### Questionario professore

Analogamente al questionario degli studenti, il questionario dei professori è composto da una prima sezione per comprendere i sistemi correnti e il loro utilizzo, successivamente vengono richieste informazioni circa l'interesse in UniPocket e i servizi a cui si è maggiormente interessati.   
Come appare evidente le domande risultano differenti poichè differenti sono le funzionalità di cui si tratta e gli applicativi utilizzati per usufruirne. Mentre per gli studenti sono disponibili svariate applicazioni infatti, nel caso dei professori queste risultano particolarmente limitate, è necessario quindi comprendere ancor di più i requisiti necessari per il sistema.
Sono sempre presenti domande ridondanti e scale numeriche di gradimento.

### Interviews

Anche per quanto riguarda le interview sono stati redatti documenti differenti in base allo stakeholder. Esse verranno poste sia a studenti, che a professori e amministrazione. Nei primi due casi le interviste saranno svolte a partire dal questionario precedentemente sottoposto a tali stakeholder, nel caso dell'amministrazione invece verrà svolta senza una precedente interazione.
Dal punto di vista pratico è stato selezionato un set limitato di domande da porre al fine di ottenere informazioni specifiche e mirate. Esse risultano volutamente non eccessivamente numerose, così da poter lasciare spazio a un libero dialogo, al fine di esplorare e comprendere meglio il sistema corrente, le problematiche e le eventuali soluzioni possibili dal suo punto di vista.  
Le interview inizieranno dunque con la parte strutturata, costituita dalle domande definite nei documenti e proseguiranno con una parte non strutturata e libera.

Di seguito vengono riportate le informazioni che è necessario ottenere da ciascuno stakeholder:
- Gli studenti hanno la possibilità di esporre la soddisfazione generale riguardo la ricezione di informazioni, l'utilizzo di applicativi offerti dall'università e da terze parti per la gestione della loro carriera universitaria, con conseguente identificazione di una soluzione.
- I professori possono esprimere la loro soddisfazione riguardo le procedure e l'utilizzo di applicativi offerti dall'università. Sono in grado di identificare le problematiche esistenti, poichè consuenti utilizzatori dei sistemi e dunque potenzialmente capaci di identificare migliorie dal punto di vista procedurale e comunicativo all'interno dell'ambiente universitario.
- L'università ha la capacità di identificare quali dati sono rilevanti per effettuare analisi e come possono essere visualizzati e utilizzati per migliorare i servizi offerti al personale e agli studenti.

Successivamente ad ogni interview viene trascritto un report per riassumere ed evidenziare le criticità e i punti di maggior interesse che sono emersi dal processo. Tale report viene sottoposto quindi allo stakeholder che deve confermare o rifinire ciò che è stato riportato. Risulta possibile a questo punto effettuare un'analisi su quanto trascritto e valutare come viene ritenuto adeguato procedere.

#### Interview amministrazione

All'amministrazione vengono dapprima poste domande circa l'utilizzo degli applicativi correnti per l'analisi e la consultazione di dati raccolti durante l'anno accademico. Non avendo svolto preventivamene un questionario infatti è ancora necessario comprendere questo tipo di informazioni. Nello specifico viene domandato quali processi vengono monitorati e come avviene la raccolta e l'utilizzo dei dati, i formati nei quali vengono resi disponibili e la loro effettiva utilità.

Successivamente si cerca di identificare e valutare ulteriori dati potenzilamente utili al miglioramente dell'attività universitaria ma al momento non disponibili per svariati motivi. In particolare si cerca di stabilire se l'utilizzo di UniPocket posso fornire tali dati e come possa visualizzarli per agevolare la loro consultazione da parte dell'utente. Viene dunque domandato come UniPocket possa migliorare l'esperienza corrente e si cerca di identificare le statistiche che possono essere condivise anche con professori e studenti al fine di mantenere una gestione trasparente.

## Analisi dei risultati ottenuti

### Questionario studenti

Il questionario è stato sottoposto agli studenti mediante google form ed è disponibile al seguente indirizzo: [https://docs.google.com/forms/d/e/1FAIpQLSd7e5LX8WeAVVtyQL24afb8JZkmHL7s5nHrhenUhMRVNFwtUQ/viewform](https://docs.google.com/forms/d/e/1FAIpQLSd7e5LX8WeAVVtyQL24afb8JZkmHL7s5nHrhenUhMRVNFwtUQ/viewform).

A seguito della sua compilazione sono emersi diversi aspetti che vengono riportati di seguito.

#### Utenti coinvolti

Il questionario è stato svolto quasi per il 50% da studenti maschili e 50% ad studenti femminili. Essi provengono da diversi corsi di studio, nonostante la grande maggioranza, circa il 70%, proviene da quello di informatica, il 10% da quello di economia e il restante da corsi differenti.

#### Sistemi utilizzati correntemente

Circa il 50% del totale non sembra utilizzare alcuna applicazione per monitorare la propria carriera universitaria, piano di studi, media etc. Tra gli utilizzatori vi è una forte prevalenza dell'applicativo "UniWhere". Invece per controllare gli orari delle lezioni risulta che la maggior parte degli studenti utilizza l'applicazione "UnimibCourse". <!-- definire cosa offrono queste applicazioni (?) => penso sia sufficiente così, rende l'idea generale -->  
Per quanto riguarda la vendita di libri quasi la totalità degli studenti non utilizza applicazioni, solo il 20% sfrutta canali alternativi quali social network (Facebook e Telegram in particolare) oppure negozi come il "libraccio". Inoltre gli utilizzatori non sembrano essere interessati all'aggiunta di questo tipo di funzionalità all'interno di UniPocket.  
Il sistema di prenotazione degli esami non sembra soddisfare a sufficienza gli studenti, infatti molti esprimono l'esigenza di poterlo fare in modo più pratico tramite un app mobile.  
La mensa universitaria non sembra essere frequentata spesso, se non da pochi studenti, nonostante ciò notiamo un certo  interesse verso i servizi che vorremmo integrare.   
Infine, lo spostamento tra gli edifici per le lezioni non appare difficoltoso, nonostante ciò molti sono interessati ad avere a disposizione l'orario della navetta e addirittura altri mezzi di trasporto che collegano i vari edifici .

#### Interesse nelle funzionalità

![alt text](RE%20questionnaires/TableQuestion.jpg)

![alt text](RE%20questionnaires/Functions.jpg)

#### La soluzione proposta

Le applicazioni esistenti vengono al momento utilizzate con una media frequenza, tuttavia è emerso che un'unico applicativo contenente tutte le funzionalità farebbe risparmiare molto tempo agli studenti e semplificherebbe la vita universitaria.  
Tutte le funzionalità proposte risultano quasi di uguale importanza, mentre di particolare rilevanza risulta essere la possibilità di sapere dove poter trovare posto nelle aule studio e in biblioteca per potersi fermare a studiare.  
Per quanto riguarda l'interesse generale allo sviluppo di UniPocket è emerso che circa il 20% degli intervistati è veramente entuasiasta dell'idea, tanto da lasciare commenti esaustivi.
Alcuni utenti appaiono visibilmente spaventati dal fatto di produrre un'applicazione unica con molte funzionalità, pensando che essa diventi particolarmente difficile da utilizzare o confusionaria. Come sottolineato da alcuni di essi è necessario sviluppare un sistema semplice, fluido e intuitivo per raggiungere il giusto obiettivo. Tramite l'utilizzo di mock-up sarà possibile verificare se questa condizione verrà correttamente rispettata.

## Segnalazione dei requisiti emergenti

Dopo lo svolgimento di questionari e interviste sono emersi requisiti aggiuntivi di vario genere, provenienti da studenti differenti. Non vengono dunque riportati nella loro totalità ma viene segnalato l'unico requisito richiesto più volte e che costituisce dunque un elemento di discreta importanza:

- visualizzazione della capienza delle aule e la disponibilità dei posti a sedere

| **Altri requisiti**                                          | **Percentuale** |
| ------------------------------------------------------------ | --------------- |
| Laboratori e aule libere                                     | 6%              |
| Capienza aule                                                | 12%             |
| Calendario accademico                                        | 6%              |
| Materiali forniti dai docenti                                | 6%              |
| Sezione appunti                                              | 6%              |
| Orari segreterie e tempo di attesa                           | 6%              |
| Mail universitaria integrata                                 | 6%              |
| Sostituzione delle segreterie online                         | 6%              |
| Orientamento matricole                                       | 6%              |
| Orari apertura e chiusure edificio e aule                    | 6%              |
| Sezione bibliotecaria                                        | 6%              |
| Importazione eventi e lezioni sul calendario personale       | 6%              |
| Previsione voto sulla base di statistiche generali e andamento | 6%              |
| Statistiche tempo di studio richiesto per l’esame            | 6%              |
| Elenco dei capitoli da studiare                              | 6%              |
| Controllo tasse                                              | 6%              |
