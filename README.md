# APS_s

Casi d'uso Rubrica

-------------------------------------------------------------------------------------------------------------------------

Nome del caso d’uso:
Inserisci Contatto

Portata:
Sistema Rubrica

Livello:
Obiettivo Utente

Attore primario:
Utente

Parti interessate e interessi:
Utente;
L'utente vuole poter inserire contatti in rubrica

Pre-condizioni:
Il contatto non è già salvato in rubrica

Post-condizioni:
Il contatto viene salvato in rubrica

Scenario principale di successo:
- 1. L'utente apre la rubrica
- 2. L'utente seleziona di voler inserire un contatto
- 3. La rubrica chiede di inserire i dati del contatto: nome, descrizione, uno o più numeri
- 4. L'utente inserisce i dati
- 5. L'utente termina l'inserimento dei dati e lo notifica alla rubrica
- 6. La rubrica aggiunge il contatto tra quelli salvati e notifica l'utente

Estensioni:
-	6a. Limite dei 100 contatti raggiunto
-	6a1. La rubrica notifica all'utente che il numero massimo dei contatti salvati è stato 		raggiunto
-	6a2. La rubrica annulla l'inserimenrto
-	6b. Numero di telefono incorretto
-	6b1. La rubrica notifica all'utente che il numero di telefono inserito non è corretto (nel caso 	di più numeri specific quale)
-	6b2. L'utente corregge o elimina il numero e ritorna all'inserimento dei dati
-	6c. Nome non valido
-	6c1. La rubrica notifica l'utente dell'invalidità del nome perchè già presente in rubrica
-	6c2. L'utente cambia il nome e torna all'inserimento dei dati


Extended:
Inserisci Contatto Protetto
L'utente seleziona di voler inserire un contatto protetto anziché un contatto

Frequenza di ripetizione:
Potenzialmente infinita

-------------------------------------------------------------------------------------------------------------------------

Nome del caso d’uso:
Rimuovi Contatto

Portata:
Sistema Rubrica

Livello:
Obiettivo Utente

Attore primario:
Utente

Parti interessate e interessi:
Utente;
L'utente vuole poter rimuovere contatti salvati in rubrica

Pre-condizioni:
Il contatto è già salvato in rubrica

Post-condizioni:
Il contatto non è più salvato in rubrica

Scenario principale di successo:
. 1. L'utente apre la rubrica
. 2. L'utente seleziona un contatto
- 3. L'utente seleziona di voler rimuovere il contatto
- 4. La rubrica chiede se l'utente è certo di voler rimuovere il contatto
- 5. L'utente seleziona l'opzione affermativa
- 6. La rubrica rimuove il contatto e notifica l'utente

Estensioni:
- 6a. Utente non certo
- 6a1. L'utente seleziona l'opzione negativa 
- 6a2. La rubrica annulla la rimozione
- 6b. Contatto protetto
- 6b1. La rubrica notifica all'utente che il contatto è di tipo protetto e non può essere rimosso
- 6b2. La rubrica annulla la rimozione

Frequenza di ripetizione:
Potenzialmente infinita


