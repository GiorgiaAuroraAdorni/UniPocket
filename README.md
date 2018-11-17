# UniPocket
Secondo Assignment di Processo e Sviluppo del Software.

Version 1.0 – 15.11.2018

Adorni Giorgia 806787
Basso Matteo 807628

# Requirements Analysis Document (RAD)

## Document Instructions

<!--inserire le istruzioni eventuali-->


## Purpose

Vengono documentati nel RAD i risultati dell'estrazione dei requisiti e le attività di analisi, inoltre viene descritto il sistema in termini di requisiti funzionali e non funzionali, fungendo da base contrattuale tra il cliente e lo sviluppatore. 
Il RAD viene scritto nella lingua del dominio del business / competenza del cliente (nel nostro caso l'italiano). 

In questo documento viene descritta l'applicazione **UniPocket** <!--da sviluppare, un applicazione/sistema completamente nuovo--> e viene definita una strategia per acquisire conoscenze, compresa la proposta di una soluzione<!--obiettivi e requisiti?-->.

UniPocket è un applicazione universitaria, utilizzata per lo più da studenti ma anche docenti. <!--aggiungere i servizi offerti-->

## Introduction

La prima sezione è un'introduzione con lo scopo di fornire una breve panoramica della funzione del sistema e le ragioni del suo sviluppo, della sua portata e dei suoi riferimenti al contesto di sviluppo (ad es. riferimento alla dichiarazione del problema scritta dal cliente, riferimenti a sistemi esistenti, studi di fattibilità).
L'introduzione include anche gli obiettivi e i criteri di successo del progetto.

### Purpose of the system  

### Domain understanding

Studiare l'ambiente e il sistema così com'è
- Organizzazione aziendale
- Dominio Applica3on
- Punti di forza e punti deboli del sistema così com'è

Il sistema UniPocket e i suoi servizi<!--elencare enventuali nomi per il servizio voti, statistiche etc.--> sono progettati per essere una singola applicazione destinata a dispositivi smartphone (iOS e Android ). <!--valutare se è la sezione giusta in cui inserire questo-->

### Scope of the system/Objectives and success criteria of the project

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

## Current system
In questa sezione viene descritto lo stato attuale delle cose. Se il nuovo sistema sostituirà un sistema esistente, questa sezione descrive la funzionalità e i problemi del sistema attuale, altrimenti, quali sono le attività supportate dal nuovo sistema.

<!--Descrizione dettagliata dell'ambiente corrente per identificare e supportare bisogni e obiettivi descritti nella sezione precedente: 
Quali sono i problemi attuali (supponendo l'assenza di questo il sistema)?
Quali problemi dovrebbe risolvere questo sistema?
Devi fare le cose manualmente, cosa ti piacerebbe automatizzare?
Hai problemi di prestazioni che devono essere modificati?
Avete limitazioni funzionali che vorreste cambiare?-->

### Product functions

L'applicazione universitaria UniPocket (per ora dedicata alla bicocca ma possibile ampliarla) prevede <n> importanti gruppi di funzionalità. 

- accesso con account universitario
- visibilità piano di studi, libretto voti
- statistiche per studenti (relative alla difficoltà esami, media voti, base di laurea, andamento della carriera, valutazioni ai professore, 
- statistiche per docenti (andamento studenti nei vari corsi)
- analisi dei dati a scopo statistico dall'amministrazione dell'università
- Possibilità di gestione delle aule da parte delle segreterie (prenotazioni)
- prenotazione aule laboratori per lezioni da parte degli insegnati
- creazione di appelli di esame dai docenti
- iscrizione degli studenti agli esami
- orari lezioni ed esami (con reminder)
- news dall’università (stessa newsletter della mail)
- (menu mensa)
- (controllo orari navetta)
- (vendita libri)

## Proposed system
La terza sezione documenta l'elicitazione dei requisiti e il modello di analisi del nuovo sistema.

### Panoramica/Overview
Viene presentata una panoramica funzionale del sistema, con un riepilogo descrittivo dell'approccio, dei metodi e della documentazione dei requisiti aziendali, tra cui: driver di progetto, parti interessate del progetto (stakeholders), funzioni principali che verranno eseguite dal sistema e una tempistica della documentazione dei requisiti generali.

<!--per la parte stakeholder: Sono compresi in questa categoria ... analisti di sistema (ad esempio, gli sviluppatori che partecipano ai requisiti). -->

<!--un piano che mostra e spiega in quale ordine sono le attività di elicitazione eseguite. Il piano deve indicare chiaramente qualsiasi dipendenza tra le attività.-->

### Stakeholders

Esistono quattro tipi principali "attori" nell'applicazione UniPocket:

#### Studente

#### Professore

#### Amministrazione università (per statistiche etc)

#### Segreterie

<!--una o più strategie di elicitazione associate a ciascun stakeholder: motivare le strategie e descrivere il tipo di informazioni che saranno acquisite sfruttando le strategie indicate.-->

Un requisito è una dichiarazione che identifica un attributo, una capacità, una caratteristica o una qualità necessari di un sistema affinché possa avere valore e utilità per uno stakeholder.

### Elenco dei requisiti funzionali

<!--valutare se tenere-->

<!--I requisiti funzionali descrivono la funzionalità di alto livello del sistema.-->     

### Nonfunctional requirements

<!--valutare se tenere-->

<!--I requisiti non funzionali descrivono i requisiti a livello utente che non sono direttamente relativi alle funzionalità.-->

<!--      3.3.1 Usability  
​      3.3.2 Reliability  
​      3.3.3 Performance  
​      3.3.4 Supportability  
​      3.3.5 Implementation  
​      3.3.6 Interface  
​      3.3.7 Packaging  
​      3.3.8 Legal	  -->

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

- quale tipo di informazioni che dovrebbero essere scoperte
- perché alcune domande sono state scelte
- come l'intervista / questionario è organizzato logicamente (gruppi di domande)
- perché un ordine specifico per le domande

## Questionnaires

- quale tipo di informazioni che dovrebbero essere scoperte
- perché alcune domande sono state scelte
- come l'intervista / questionario è organizzato logicamente (gruppi di domande)
- perché un ordine specifico per le domande

## <!-- Analisi dei risultati analizzati-->

## <!-- Segnalazione dei requisiti emergenti-->







## 