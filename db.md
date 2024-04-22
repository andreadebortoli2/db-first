## Descrizione
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

DB_NAME: car_dealer

table name: cars

- id | INDEX | BIGINT | PK | NOTNULL | AI | UNIQUE
- brand | VARCHAR(20) | NOTNULL
- modello | VARCHAR(20) | NOTNULL
- sub-modello | VARCHAR(50) | NULL
- VIN | VARCHAR(17) | NOTNULL | UNIQUE
- data_immatricolazione | DATE | NOTNULL
- targa | VARCHAR(10) | NOTNULL
- revisione | CHAR(1) | NOTNULL
- data_revisione | DATE | NULL
- prezzo | MEDIUMINT | NOTNULL
- condizione | VARCHAR(5) | NOTNULL
- carrozzeria | VARCHAR(10) | NULL
- immagine | VARCHAR(255) | DEFEAULT('url_image_placeholder')
- colore_carrozzeria | VARCHAR(20) | NULL
- colore_interni | VARCHAR(20) | NULL
- materiale_interni | VARCHAR(20) | NULL
- posti | CHAR(1) | NULL
- porte | CHAR(1) | NULL
- chilometraggio | MEDIUMINT | NULL
- alimentazione | VARCHAR(20) | NULL
- classe_emissioni | CHAR(1) | NULL
- emissioni | TINYINT | NULL
- consumi_combinato | TINYINT | NULL
- consumi_urbano | TINYINT | NULL
- consumi_extraurbano | TINYINT | NULL
- potenza_kw | TINYINT | NULL
- potenza_cv | TINYINT | NULL
- cilindrata | SMALLINT | NULL
- cilindri | CHAR(1) | NULL
- cambio | VARCHAR(15) | NULL
- marce | CHAR(1) | NULL
- trazione | VARCHAR(10) | NULL
- note | TEXT | NULL