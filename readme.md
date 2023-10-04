# TRACCIA

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Potete usare una tabellina markdown o un semplice file di testo se vi riesce più comodo!

### Mi raccomando: quello che ci interessa sono: il nome della colonna, il tipo di dato ed eventuali attributi!

## Esempio:

| COLONNA | TIPO        | ATTRIBUTI |
| ------- | ----------- | --------- |
| marca   | varchar(50) | NOT NULL  |
| modello | varchar(50) | NOT NULL  |

ecc..

### BONUS: nomi colonne in inglese

## SVOLGIMENTO

| COLONNA               | TIPO        | ATTRIBUTI           | COMMENTI                      |
| --------------------- | ----------- | ------------------- | ----------------------------- |
| targa                 | VARCHAR(10) | PRIMARY_KEY         |
| modello               | VARCHAR(50) | NOTNULL             |
| marca                 | VARCHAR(50) | NOTNULL             |
| colore_carrozzeria    | VARCHAR(15) | NULL                |
| alimentazione         | VARCHAR(1)  | NOTNULL             | B=benzina;D=disel;M=metano... |
| km_percorsi           | FLOAT(9,3)  | NOTNULL, DEFAULT(0) |
| airbag                | TINYINT(1)  | NULL, DEFAULT(0)    |
| numero_porte          | TINYINT(1)  | NULL, UNSIGNED      |
| cilindrata            | SMALLINT    | NULL, UNSIGNED      |
| anno_immatricolazione | YEAR        | NOTNULL             |
| costo_acquisto        | MEDIUMINT   | NOTNULL             |
| costo_riparazione     | SMALLINT    | NOTNULL, DEFAULT(0) |
| prezzo_minimo_vendita | MEDIUMINT   | NOTNULL             |
