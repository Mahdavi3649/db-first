<!-- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario
Potete usare uno dei seguenti metodi per consegnare l'esercizio:
fate un file di markdown come visto in classe e pushatelo
fate un diagramma ed esportatelo in formato png
fate una tabella con google sheet o excell ed esportatela come immagine o pdf -->

# auto-shop

## Modello: Car

## Table: Cars

- id BIGINT PK, NOTNULL, AI, UNIQUE
- color VARCHAR(20) NOTNULL
- Image VARCHAR(255) NULL
- price DECIMAL(11,2) NOTNULL
- brand VARCHAR(25) NOTNULL
- model VARCHAR(50) NOTNULL
- description TEXT NULL
- option VARCHAR(50) NULL
- year_product YEAR NULL
- power MEDIUMINT NULL
- type VARCHAR(25) NOTNULL
