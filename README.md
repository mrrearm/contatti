# contatti
Modulo Contatti collegato a Google Forms

Breve guida per collegare il tuo modulo contatti a Google Forms, e ricevere le risposte degli utenti nel tuo Google Forms. 

PER COLLEGARE IL TUO FORM DEVI CREARE 3 CAMPI IN GOOGLE FORM:

Link Google Forms: https://docs.google.com/forms/

Titolo: Contatti 
Descrizione: Modulo Contatti 

Campi da creare:

1.TIMESTAMP, RISPOSTA BREVE
2. EMAIL, PARAGRAFO 
3. MESSAGGIO, PARAGRAFO 

TUTTI E 3 DEVONO ESSERE CAMPI OBBLIGATORI. 

SALVA IL FORM E MODIFICA IL LINK PUBBLICO METTENDO /FORMRESPONSE ALLA FINE DEL CODICE ID, TOGLIENDO /viewform?usp=pp_url&

ESEMPIO:

https://docs.google.com/forms/d/e/1FAIPQLSCZJVRGRD6EFFVMMQME93HE420AC......../viewform?usp=pp_url&

Modifica in questo modo:

https://docs.google.com/forms/d/e/1FAIPQLSCZJVRGRD6EFFVMMQME93HE420AC......../formresponse

DAL LINK DEL FORM PUOI RICAVARE IL TUO ID FORM:

1FAIpQLScZjVRgrd6eFFVMMQmE93hE420ActpA0.......

(I PUNTINI RAPPRESENTANO ALTRI NUMERI E LETTERE, È UN ESEMPIO DI CODICE ID) 

PER RICAVARE GLI ID DEI CAMPI INVECE DEVI PREMERE SU IN ALTO IN GOOGLE FORM, 3 PALLINI, CREA FORM PRECOMPILATO.

METTI NEI CAMPI I SEGUENTI VALORI:

1. TIMESTAMP-TEST
2. EMAIL-TEST 
3. MESSAGGIO-TEST

ORA SALVA IL TUTTO GENERANDO IL LINK, NEL LINK GENERATO TROVERAI I 3 ID DEI CAMPI CHE DOVRAI COPIARE IN QUESTO FORMATO:

ESEMPIO:

Timestamp:
entry.1234567890

Email:
entry.4577891230

Messaggio:
entry.111222333444

ORA CHE HAI LINK DEL FORM CON FORMRESPONSE FINALE, E I 3 ID CAMPO, PUOI SOSTITUIRE QUESTI VALORI NEL MODULO E SALVARE IL TUTTO PER RICEVERE LE TUE RISPOSTE SUL TUO GOOGLE FORM. 

N. B.: Su Google Forms in "risposte" attiva "Consenti risposte", e se vuoi ricevere anche notifiche e-mail per ogni risposta puoi attivare anche queste. 
In *Impostazioni" non modificare altre impostazioni, altrimenti non riceverai le risposte. Opzioni come "Rendi tutti i campi obbligatori di default" e altre opzioni particolari, possono bloccare la ricezione delle mail. Se costruisci un modulo tuo da zero, rendi i 3 campi obbligatori, timestamp lo metti come non visibile nel modulo ma che si genera in automatico all'invio di una mail. Se invece vuoi utilizzare il modulo presentato qui, ricorda di modificare anche l'URL della pagina "Grazie.html".

Guida by Mr Rearm
