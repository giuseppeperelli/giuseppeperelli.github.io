---
layout: page
title: Basi di Dati 
description: CdS Informatica
importance: 2
category: current
---

 - **Docente**: Giuseppe Perelli
 - **[Google Classroom](https://classroom.google.com/c/NzExMDI4ODk5NTAw?cjc=uph5u4s)**: Iscriviti per restare aggiornato sul corso.
<!--  - **[Canale M-Z](https://sites.google.com/a/di.uniroma1.it/basidati-modulo1-mz/home-page)**: da qui è possibile accedere al sito del corso per il canale M-Z, della [Prof.ssa De Marsico](https://sites.google.com/a/di.uniroma1.it/maria-de-marsico/), contenente ulteriori informazioni e materiale didattico. -->
  - **Codice OPIS**: 6RDTX5S6 ([Vademecum](https://www.uniroma1.it/it/pagina/rilevazione-opinioni-studenti-opis))
 
------

#### Materiale didattico
- Le [dispense](https://drive.google.com/drive/folders/1UrkpkqsKYDZc0lVb6J7dihBmiNj6NAxf?usp=sharing) della Prof.ssa Moscarini sono parte integrante del materiale didattico.
Le slide rappresentano le lezioni del corso, basate sul contenuto delle dispense e integrate con esempi ed annotazioni. 

- Testi consigliati:
  - [B1] J. D. Ullman: Principles of Database & Knowledge-Base Systems, Vol. 1: Classical Database Systems
  - [B2] Lemahieu, W., vanden Broucke, S., & Baesens, B. (2018). Principles of Database Management: The Practical Guide to Storing, Managing and Analyzing Big and Small Data. Cambridge University Press
  - [B3] [A. Albano, G. Ghelli, R. Orsini: Fondamenti di Basi di Dati](https://www.fondamentidibasididati.it/) **Testo gratuito**

- [Slides](https://drive.google.com/drive/folders/1EoE2JC2embpKOCacUkikDAZfpXmFami8?usp=sharing) **ATTENZIONE**: le slide sono in Inglese poiché condivise con il corso di Data Management and Analysis del CdS in Applied Computer Science and Artificial Intelligence (ACSAI).
- [Appunti](https://drive.google.com/drive/folders/12YOdTpneBSp8hhmSqzJwPvkqhAgsVBSE?usp=sharing) **ATTENZIONE**: potete segnalare eventuali errori inviandomi una email.
- [Esercizi](https://drive.google.com/drive/folders/1QOCK7AH_EAsXF9O8VkjT857pkg91c1q6?usp=sharing)
- [Tracce esami precedenti](https://drive.google.com/drive/folders/1oM1vfoahHk9_7yUsAkjScHhQ43AUx-8T?usp=sharing)
- [Simulazioni d'esame](https://drive.google.com/drive/folders/1pS9mx_8nD_AJ3J4s7EcgOYSkfVucxWcm?usp=sharing)


##### **<span style="color:red"> ATTENZIONE </span>**

A causa di alcuni ritardi dovuti a lavori in corso, alcune lezioni del corso si terranno in un'aula diversa da quella allocata per tutto il resto del corso.


 - La lezione di **Lunedì 11 Novembre** alle **13:00** si terrà in **Aula A1 Luigi Capozzi** del dipartimento di [SOMF](https://somaf.web.uniroma1.it/it/dove-siamo) (RM101-E01PTEL008 Via Caserta, 6).

 - La lezione di **Giovedì 14 Novembre** alle **13:00** si terrà in **Aula A1 Luigi Capozzi** del dipartimento di [SOMF](https://somaf.web.uniroma1.it/it/dove-siamo) (RM101-E01PTEL008 Via Caserta, 6).

 - La lezione di **Lunedì 18 Novembre** alle **13:00** si terrà in **Aula A1 Luigi Capozzi** del dipartimento di [SOMF](https://somaf.web.uniroma1.it/it/dove-siamo) (RM101-E01PTEL008 Via Caserta, 6).

 - La lezione di **Giovedì 21 Novembre** alle **13:00** si terrà in **Aula A1 Luigi Capozzi** del dipartimento di [SOMF](https://somaf.web.uniroma1.it/it/dove-siamo) (RM101-E01PTEL008 Via Caserta, 6).


Si prega ti monitorare gli aggiornamenti sul sito del CdS, alla pagina Frequentare, nella tabella "Orario delle lezioni": [https://corsidilaurea.uniroma1.it/it/corso/2024/29923/programmazione](https://corsidilaurea.uniroma1.it/it/corso/2024/29923/programmazione)


-------


##### **Orario**

  Le Lezioni si terranno a partire da Lunedì 23 Settembre secondo il seguende calendario.

- **Lunedì**: dalle **13:00** alle **15:00**: **Aula De Lollis 4** (Attenzione, leggere l'avviso sopra sulle aule!)
- **Giovedì**: dalle **13:00** alle **16:00**: **Aula De Lollis 4** (Attenzione, leggere l'avviso sopra sulle aule!)

##### **<span style="color:red"> Ricevimento </span>**

Il ricevimento è **<span style="color:red">previo appuntamento</span>**. Inizierà Mercoledì 9 Ottobre in orario e data come segue.

- Mercoledì: dalle 16:00 alle 18:00 al Dipartimento di Informatica, Edificio E, Viale Regina Elena, 295.

In caso di necessità, si può concordare un appuntamento fuori dall'orario di ricevimento.
 
#### Programma

- Introduzione ai sistemi di gestione di basi di dati
  - Cenni storici. Aspetti caratterizzanti dei sistemi di gestione di basi di dati. Evoluzione di modelli e sistemi.

- Il modello relazionale
  - Concetti di base: dominio, attributo, relazione, n-upla, schema. I linguaggi di interrogazione (algebra relazionale, linguaggi relazionalmente completi). Teoria della normalizzazione. Dipendenze funzionali. Chiave di una relazione Terza forma normale. Assiomi di Armstrong e chiusura di un insieme di dipendenze. Chiusura di un insieme di attributi. Copertura minimale di un insieme di dipendenze. Scomposizioni che hanno un join senza perdita. Scomposizioni che preservano le dipendenze.
- L’organizzazione fisica dei dati
  - La memoria secondaria. Record fisici e record logici. Puntatori. Blocchi. File heap. File hash. File con indice (ISAM). B-tree
<!-- La gestione della concorrenza -->
<!--   - Transazioni. Schedule seriale. Serializzabilità. Modelli di transazioni e meccanismi di locking. Livelock e deadlock. Protocolli a due fasi. Protocolli conservativi e aggressivi. Dati “sporchi”. Rollback a cascata. Timestamp.-->

#### Diario del corso

 - **23-09-2024** - Il modello relazionale di una base di dati.
 - **26-09-2024** - Algebra Relazionale: Proiezione, Selezione, operazioni Union Compatibili, Prodotto Cartesiano, Join Naturale.
 - **30-09-2024** - Algebra Relazionale: Prodotto Cartesiano, join naturale, \\(\theta\\)-join, Quantificazione Universale.
 - **03-10-2024** - Algebra Relazionale: Esercitazione.
 - **07-10-2024** - Algebra Relazionale: Esercitazione - Teoria Relazionale: ridondanza e anomalie di gestione.
 - **10-10-2024** - Teoria Relazionale: schemi relazionali, tuple, istanze, dipendenze funzionali, chiusura di \\(F\\), chiavi.
 - **14-10-2024** - Teoria Relazionale: Assiomi di Armstrong, chiusura di \\(X\\), equivalenza \\(F^+=F^A\\).
 - **17-10-2024** - Teoria Relazionale: 3NF.
 - **28-10-2024** - Teoria Relazionale: 3NF e BCNF. Esercitazione di Algebra Relazionale.
 - **31-10-2024** - Teoria Relazionale: Chiusura di \\(X\\), calcolo delle chiavi e verifica della 3NF, esercitazione su chiavi e 3NF.
 - **04-11-2024** - Teoria Relazionale: Esercitazione sulla ricerca di chiavi e verifica della 3NF.
 - **07-11-2024** - Teoria Relazionale: decomposizioni che preservano \\(F\\). Calcolo di \\(X^{+}_{G}\\) tramite \\(F\\). Verifica  che una decomposizione preserva \\(F\\).
 - **11-11-2024** - Teoria Relazionale: eserizi sulla verifica che una decomposizione preserva \\(F\\).
 - **14-11-2024** - Teoria Relazionale: Join Senza Perdita, definizione e algoritmo di verifica.


#### Modalità d'esame (**Leggere attentamente**)

- L'esame del Modulo 1 consiste in una parte scritta e una parte orale.
  - La parte scritta (circa 2 ore e mezza) consiste in una sezione di domande a risposta multipla sulla teoria e una sezione di tre esercizi su: Algebra Relazionale, Teoria Relazionale, Organizzazione Fisica.
    - Per le domande a risposta multipla, ad ogni risposta corretta si aggiunge un punto, per ogni risposta sbagliata, si sottrae mezzo punto. È necessario raggiungere **almeno** 6 punti su 10 per considerare questa sezione superata.
    - Gli esercizi della seconda sezione sono valutati 10 punti. Se **tutti** gli esercizi sono valutati con un punteggio sufficiente (6/10), la sezione viene considerata superata.
    - Se la prova scritta è superata, viene assegnato un voto secondo la seguente tabella

    | **Voto Scritto** | **Voto Finale** |
    |------------------|-----------------|
    |   18             |     18          |
    |   19             |     19          |
    |   20             |     19          |
    |   21             |     20          |
    |   22             |     20          |
    |   23             |     21          |
    |   24             |     21          |
    |   25             |     22          |
    |   26             |     22          |
    |   27             |     23          |
    |   28             |     23          |
    |   29             |     24          |
    |   30             |     24          |


  - Il voto finale può essere aggiustato sostenendo un *orale facoltativo*. L'esame orale può **aggiungere o sottrarre** fino a 10 punti dal voto dello scritto.
  - La parte orale consiste in domande su:
    - Definizioni e nozioni di base sulla Teoria Relazionale
    - Dimostrazioni di teoremi in Teoria Relazionale
    - Organizzazione fisica
<!--     - Concorrenza -->
  - L'esame orale si svolge **solitamente** una settimana dopo la prova scritta. Tuttavia, questo dipende molto dal tempo necessario per correggere tutte le prove scritte, che è soggetto a variazioni, a causa dei miei impegni e del numero di studenti che sostengono l'esame.

<!--- Le lezioni si svolgono **in presenza** e non sono registrate.
- Gli esami si svolgono *esclusivamente* in presenza. Non è più consentito svolgere esami da remoto.-->


#### Verbalizzazione (**Leggere attentamente**)
- Il corso è il primo dei due moduli di Basi di Dati. Il secondo modulo è tenuto nel secondo semestre dal [Prof. Toni Mancini](http://tmancini.di.uniroma1.it/index.php).
- Per verbalizzare l'intero esame da 12 crediti, bisogna superare entrambi i moduli separatamente. Questo vale senza eccezione alcuna, compresi gli studenti Erasmus. Non c'è limite di tempo tra il superamento dei due moduli per la verbalizzazione finale.
- Per ragioni amministrative, gli studenti che superano il Modulo 1, ma che non hanno ancora superato il Modulo 2, saranno registrati con un *rinuncia* sul verbale. Contestualmente, riceveranno un'email dal docente con la conferma del superamento del modulo, data e valutazione, a garanzia del superamento stesso.



------

#### Edizioni Precedenti

- **A.A. 2023-24**
  - **[Google Classroom](https://classroom.google.com/c/NjMzNTU2MTY4NjQz?cjc=7s3zywu)**: Iscriviti per restare aggiornato sul corso.

- **A.A. 2022-23**
  - **[Google Classroom](https://classroom.google.com/c/NTI2MzczNjQ2NzQw?cjc=o37fjh7)**: Iscriviti per restare aggiornato sul corso.
