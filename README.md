# Esercizio del 2024-02-05

### nome repo: db-university

Modellizzare la struttura di un database per memorizzare tutti i dati riguardanti una università:

- Sono presenti diversi Dipartimenti (es.: Lettere e Filosofia, Matematica, Ingegneria ecc.);
- Ogni Dipartimento offre più Corsi di Laurea (es.: Civiltà e Letterature Classiche, Informatica, Ingegneria Elettronica ecc..)
- Ogni Corso di Laurea prevede diversi Corsi(Materie) (es.: Letteratura Latina, Sistemi Operativi 1, Analisi Matematica 2 ecc.);
- Ogni Corso può essere tenuto da diversi Insegnanti;
- Ogni Corso prevede più appelli d'Esame;
- Ogni Studente è iscritto ad un solo Corso di Laurea;
- Ogni Studente può iscriversi a più appelli di Esame;
- Per ogni appello d'Esame a cui lo Studente ha partecipato, è necessario memorizzare il voto ottenuto, anche se non sufficiente.

Pensiamo a quali entità (tabelle) creare per il nostro database e cerchiamo poi di stabilirne le relazioni. Infine, andiamo a definire le colonne e i tipi di dato di ogni tabella.

Utilizzare [diagrams](https://www.diagrams.net/) per la creazione dello schema.

Esportare quindi il diagramma in jpg e caricarlo nella repo.
Buon lavoro!

# Esercizio del 2024-02-06

### nome repo: db-university

Dopo aver creato un nuovo database nel vostro phpMyAdmin e aver importato lo schema allegato (non dovete scompattare il file zip, semplicemente andate nella sezione importa, e fate drag and drop oppure prendetelo dai file delle vostre cartelle, esattamente come visto a lezione), eseguite le query del file allegato.

### Cosa consegnare?

Dopo aver testato le vostre query con phpMyAdmin, riportatele in un file txt, md o altro e caricatelo nella vostra repo.


## BONUS:
Selezionare nome, descrizione e periodo di tutti i corsi che hanno sito web diverso da null, cfu compresi tra 9 e 12 e che sono del primo anno ed ordinarli in ordine decrescente

P.S. Ad ogni query fatta corrisponde un push.
Buon lavoro.