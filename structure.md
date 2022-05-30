<!-- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario -->

# Automobili usate

- id:               BIGINT          NOTNULL,AI, INIQUE
- marca:            VARCHAR         UNIQUE, NOTNULL
- modello:          VARCHAR(40)     NOTNULL, UNIQUE
- anno              YEAR            NOTNULL
- versione:         VARCHAR(30)     NOTNULL
- matricola:        VARCHAR(50)     NOTNULL
- optionals:        VARCHAR(255)   NOTNULL
- allestimento:     VARCHAR(50)     NOTNULL
- COLORE:           VARCHAR(30)     NOTNULL
- kilowatt:         FLOAT(4,2)      NOTNULL
- chilometri:       FLOAT(9,4)      NOTNULL
- carburante:       VARCHAT(10)     NOTNULL
- eco:              TINIINT         NOTNULL
- garanzia:         TINIINT         NOTNULL
- test_drive:       TINIINT         NOTNULL
- finanziabile:     TINIINT         NOTNULL
- n_proprietari:    SMALLINT        NOTNULL


       