# UniPocket
Secondo Assignment di Processo e Sviluppo del Software.

Version 1.0 – 15.11.2018

Adorni Giorgia 806787  
Basso Matteo 807628

# Requirements Elicitation (RE)

## Istruzioni del documento

<!--inserire le istruzioni eventuali-->

## Obiettivi del documento

Vengono descritte nel seguente documento le procedure di estrazione dei requisiti e i conseguenti risultati, incluse attività di analisi. Vengono inoltre riportate le funzionalità del sistema e ciò che intende risolvere, fungendo da base contrattuale tra il cliente e lo sviluppatore.
Il documento viene redatto nella lingua del dominio del business / competenza del cliente (nel nostro caso l'italiano).

In questo documento viene descritta l'applicazione **UniPocket** e viene definita una strategia per acquisire conoscenze, compresa la proposta di una soluzione.

## Introduzione

La prima sezione è un'introduzione con lo scopo di fornire una breve panoramica della funzione del sistema e le ragioni della sua realizzazione, portata e riferimenti al contesto di sviluppo (ad es. riferimento alla dichiarazione del problema scritta dal cliente, riferimenti a sistemi esistenti, studi di fattibilità).
L'introduzione include anche gli obiettivi e i criteri di successo del progetto.

### Domain understanding

Studiare l'ambiente e il sistema così com'è
- Organizzazione aziendale
- Dominio dell'applicazione
- Punti di forza e punti deboli del sistema così com'è

Il sistema UniPocket e i suoi servizi<!--elencare enventuali nomi per il servizio voti, statistiche etc.--> sono progettati per essere una singola applicazione destinata a dispositivi smartphone (iOS e Android). <!--valutare se è la sezione giusta in cui inserire questo-->

### Scope of the system/Objectives and success criteria of the project

UniPocket è un applicazione universitaria, utilizzata per lo più da studenti ma anche docenti. <!--aggiungere i servizi offerti-->


- opportunità tecnologiche, condizioni di mercato
- obiettivi di miglioramento
- vincoli organizzativi / tecnici sul futuro sistema
- opzioni alternative per la soddisfazione degli obiettivi, per l'assegnazione delle responsabilità
- scenari di ipotetica interazione software-ambiente
- requisiti sul software, ipotesi sull'ambiente
  Risultato: ulteriori sezioni per la bozza di proposta preliminare

Il sistema UniPocket ha due diversi tipi di utenti: studenti e docenti<!--valutare se aggiungerne altri-->. L'utilizzo dell'intero sistema è diverso sulla base del tipo di utente che ha effettuato l'accesso. <!--accettazione dei termini delle condizioni per il consenso per l'acquisizione dei dati-->

- Modulo di registrazione e accesso per i diversi utenti
- Consentire all'amministrazione universitaria e alle segreterie di accedere ai dati degli studenti
- Permettere agli studenti di visualizzare <!--qualcosa-->
- ....
- <!--L'identità di ogni utente è protetta-->

###  Definitions, acronyms, and abbreviations

<!--valutare se tenere-->

### References  

<!--contenuto-->

### Overview	 

<!--contenuto-->

## Sistema corrente

L'applicazione si propone come un'alternativa che unisce al suo interno diversi sistemi preesistenti. Al momento per visualizzare la carriera universitaria e gli orari delle aule è infatti necessario l'utilizzo di due applicazioni differenti. Alcune informazioni invece non risultano disponibili da alcuna di esse ma sono consultabili solamente mediante siti web.
Appare dunque chiaro che vi è una frammentazione dell'informazione che fa si che gli utenti possano trovarsi confusi o poco soddisfatti dei sistemi in uso. Avere un singolo applicativo mediante il quale è possibile svolgere ogni tipo di attività porterebbe alla semplificazione della vita universitaria e magari ad una maggiore inclusione da parte degli studenti.

In questa sezione viene descritto lo stato attuale delle cose. Se il nuovo sistema sostituirà un sistema esistente, questa sezione descrive la funzionalità e i problemi del sistema attuale, altrimenti, quali sono le attività supportate dal nuovo sistema.

<!--Descrizione dettagliata dell'ambiente corrente per identificare e supportare bisogni e obiettivi descritti nella sezione precedente: 
Quali sono i problemi attuali (supponendo l'assenza di questo il sistema)?
Quali problemi dovrebbe risolvere questo sistema?
Devi fare le cose manualmente, cosa ti piacerebbe automatizzare?
Hai problemi di prestazioni che devono essere modificati?
Avete limitazioni funzionali che vorreste cambiare?-->

### Product functions

L'applicazione universitaria UniPocket (per ora dedicata alla Bicocca ma possibile ampliarla) prevede <n> importanti gruppi di funzionalità. 

- Accesso tramite account universitario
- Visibilità piano di studi, libretto voti
- Statistiche per studenti (relative alla difficoltà esami, media voti, base di laurea, andamento della carriera, valutazioni ai professori)
- Statistiche per docenti (andamento studenti nei vari corsi)
- Analisi dei dati a scopo statistico da parte dell'amministrazione dell'università
- Possibilità di gestire le aule da parte delle segreterie (prenotazioni)
- Prenotazione aule e laboratori per lezioni da parte degli insegnati
- Creazione di appelli d'esame dai docenti
- Iscrizione degli studenti agli esami
- Orari lezioni ed esami (con reminder)
- News dall’università (stessa newsletter della mail)
- Menu mensa
- Controllo orari navetta
- Vendita libri

## Proposed system
La terza sezione documenta l'elicitazione dei requisiti e il modello di analisi del nuovo sistema.

### Panoramica/Overview
Viene presentata una panoramica funzionale del sistema, con un riepilogo descrittivo dell'approccio, dei metodi e della documentazione dei requisiti aziendali, tra cui: driver di progetto, parti interessate del progetto (stakeholders), funzioni principali che verranno eseguite dal sistema e una tempistica della documentazione dei requisiti generali.

<!--per la parte stakeholder: Sono compresi in questa categoria ... analisti di sistema (ad esempio, gli sviluppatori che partecipano ai requisiti). -->

<!--un piano che mostra e spiega in quale ordine sono le attività di elicitazione eseguite. Il piano deve indicare chiaramente qualsiasi dipendenza tra le attività.-->

## Stakeholders

Esistono quattro tipi principali "attori" nell'applicazione UniPocket:

<!--(elencarli e spiegare perché ciascun stakeholder è rilevante per il processo di elicitazione;)
Chiunque possa avere o essere percepito come una partecipazione nel progetto: interessato al sistema, o influenzato dal risultato del sistema, o che è in grado di influenzarlo in in qualche modo. 
Identificare i candidati per tipo e raggrupparli in base al comune interesse / effetto e ai requisiti comuni. -->

Abbiamo valutato ciascun candidato per determinare se sono veri stakeholder, o se sono semplicemente attori all'interno del sistema. <!--Dobbiamo capire il loro interesse per il sistema. Le parti interessate hanno il diritto di influenzare i requisiti di sistema, quindi è da loro che autorizziamo pareri su cosa il sistema dovrebbe fare e su come dovrebbe apparire ed esibirsi.-->

Una volta definiti gli stakeholder e i gruppi di stakeholder, abbiamo compreso i ruoli e le responsabilità di ogni singolo gruppo e il modo in cui interagiscono.

Poichè non è possibile coinvolgere tutti gli stakeholder di un certo tipo, abbiamo identificato i rappresentanti appropriati che possono parlare a nome di un determinato gruppo di stakeholder. 
A questi rappresentati vengono richiesti i requisiti e il loro contributo al ciclo di vita del sistema è cruciale, un'attenta selezione di rappresentanti appropriati è molto importante. 

Oltre a essere in grado di contribuire al processo di sollecitazione dei requisiti, è molto importante che ogni rappresentante sia di supporto e deve essere accettato dal gruppo come loro portavoce. 

Idealmente, un rappresentante adeguato per gli stakeholder deve:  
• comprendere il dominio aziendale;  
• comprendere questa particolare area applicativa all'interno del dominio aziendale;  
• capire il problema specifico;   
• rappresentare fedelmente le esigenze della propria comunità di stakeholder;  
• essere di supporto al sistema e al processo di definizione dei requisiti;  
• avere tempo sufficiente per essere in grado di contribuire quando richiesto. 

Chiaramente, il successo del processo dipenderà in larga misura dall'attenta selezione dei rappresentanti delle parti interessate. 
Poiché non tutti gli stakeholders possiedono gli attributi di cui sopra (per esempio la comprensione del dominio etc.), è necessario un periodo di formazione e istruzione per garantire che le parti interessate siano a conoscenza dei requisiti (da implementare).

Inoltre sono state definite la priorità e i diritti di ciascuna categoria (parte interessata), in modo da poter scegliere tra due requisiti conttrastanti e risolvere situazioni in cui abbiano uguale priorità e non possano essere scambiati in modo efficace. 

Esaminiamo ciascuno dei candidati in modo più dettagliato: 

- Committente
- L'università è interessata a ricevere i dati riguardo statistiche ed altro, non ha il diritto di decidere come sarà il strutturata l'applicazione ma è in grado di fornire dei vincoli esterni al progetto, per esempio quali sono i dati che è interessati a raccogliere e in che modo l'applicazione può aiutare a farlo. Di conseguenza può diventare uno stakeholder con diritti limitati.
- Gli studenti hanno la possibilità di accedere all'applicazione e monitorare la loro carriera universitaria. Risultano rilevanti per il processo di elicitazione per identificare e risolvere le problematiche circa il reperimento di alcune informazioni che possono risultare utili quotidianamente. Inoltre sono in grado di fornire opinioni riguardo i sistemi correnti, ovvero le motivazioni del loro scarso utilizzo.
- I professori hanno la possibilità di accedere all'applicazione ed effettuare svariate attività, tra cui la prenotazione delle aule e dei laboratori, l'inserimento di prove d'esame e la visualizzazione delle statistiche relative i propri corsi. Essi risultano coloro che utilizzano l'applicazione per gestire le attività universitarie ed è dunque necessario che il sistema risulti comodo e veloce da utilizzare secondo i loro bisogni. Sono in grado di identificare quali processi possono rendere la comunicazione con gli studenti difficoltosa e una possibile soluzione.
- Le segreterie online possono causare difficoltà nel processo di richiesta dei dati dello studente/professore se alcuni aspetti interferiscono con i loro diritti, ma non sono considerate come stakeholder in quanto il loro impatto principale, se presente, sarà come una fonte di vincoli. 
- L'amministrazione universitaria deve essere in grado di accedere a statistiche e informazioni relative l'attività svolta da studenti e professori. Essa risulta rilevante per comprendere quali sono i dati di fondamentale interesse e quali schermate possono essere sviluppate per la loro visualizzazione e analisi. È necessario determinare come l'università può essere in grado di valutare la soddisfazione complessiva e come alcuni cambiamenti si riflettano sugli utenti.
- Enti della privacy (garante della protezione dei dati personali), che impongono dei regolamenti sulla gestione dei dati degli utenti, impongono dei vincoli "normativi" ma non sono parti interessate. Il loro principale impatto sarà come una fonte di vincoli. 

<!--una o più strategie di elicitazione associate a ciascun stakeholder: motivare le strategie e descrivere il tipo di informazioni che saranno acquisite sfruttando le strategie indicate.-->

Un requisito è una dichiarazione che identifica un attributo, una capacità, una caratteristica o una qualità necessari di un sistema affinché possa avere valore e utilità per uno stakeholder.

Priorità delle parti interessate. (es. categoria 1 con diritti, cateoria 2 con diritti limitati)

### System models

<!--I modelli di sistema descrivono gli scenari, i casi d'uso, il modello a oggetti e i modelli dinamici per il sistema. Questa sezione contiene le specifiche funzionali complete.-->

<!--  3.4.1 Scenarios  
​      3.4.2 Use case model  
​      3.4.3 Analysis object model  
​      3.4.4 Dynamic model  
​      3.4.5 User interface--navigational paths and screen mock-ups	  -->

<In questa sezione vengono presentati dei mock-up dell'applicazione: modelli illustrativi, l'interfaccia utente del sistema e i percorsi di navigazione che rappresentano la sequenza di schermate>

###  References/Inputs  
<!--Identify the sources of information/reference materials that were used to develop the Requirements Plan, such as: Author name, title, and publication date.  Glossary: A glossary of important terms, to ensure consistency in the specification and to ensure that we use the client’s terms. A precurser to the Data Dictionary-->

## Interviews

<!--- quale tipo di informazioni che dovrebbero essere scoperte
- perché alcune domande sono state scelte
- come l'intervista / questionario è organizzato logicamente (gruppi di domande)
- perché un ordine specifico per le domande-->

Per quanto riguarda le interview, sono stati redatti documenti differenti in base allo stakeholder interessato. Dal punto di vista pratico è stato selezionato un set limitato di domande da porre al fine di ottenere informazioni specifiche e mirate. Esse risultano volutamente non eccessivamente numerose, così da poter lasciare spazio a un libero dialogo, al fine di esplorare e comprendere meglio il sistema corrente, le problematiche e le eventuali soluzioni possibili dal suo punto di vista. Le interview inizieranno dunque con la parte strutturata, costituita dalle domande definite nei documenti e proseguiranno con una parte non strutturata e libera.

Di seguito vengono riportate le informazioni che è necessario ottenere da ciascuno stakeholder:
- Gli studenti hanno la possibilità di esporre la soddisfazione generale riguardo la ricezione di informazioni, l'utilizzo di applicativi offerti dall'università e da terze parti per la gestione della loro carriera universitaria, con conseguente identificazione di una soluzione.
- I professori possono esprimere la loro soddisfazione riguardo le procedure e l'utilizzo di applicativi offerti dall'università. Sono in grado di identificare le problematiche esistenti, poichè consuenti utilizzatori dei sistemi e dunque potenzialmente capaci di identificare migliorie dal punto di vista procedurale e comunicativo all'interno dell'ambiente universitario.
- L'università ha la capacità di identificare quali dati sono rilevanti per effettuare analisi e come possono essere visualizzati e utilizzati per migliorare i servizi offerti al personale e agli studenti.

Successivamente ad ogni interview viene trascritto un report per riassumere ed evidenziare le criticità e i punti di maggior interesse che sono emersi dal processo. Tale report viene sottoposto quindi allo stakeholder che deve confermare o rifinire ciò che è stato riportato. Risulta possibile a questo punto effettuare un'analisi su quanto trascritto e valutare come viene ritenuto adeguato procedere.

## Questionnaires

- quale tipo di informazioni che dovrebbero essere scoperte
- perché alcune domande sono state scelte
- come l'intervista / questionario è organizzato logicamente (gruppi di domande)
- perché un ordine specifico per le domande

## <!-- Analisi dei risultati analizzati-->

## <!-- Segnalazione dei requisiti emergenti-->
