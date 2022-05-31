# Database Biblioteca

## Books
- id:                   Primary key (PK), NOTNULL, UNIQUE, INDEX, AUTOINCREMENTAL(AI),
- title:                VARCHAR(50), NOTNULL, INDEX
- plot:                 TEXT, NULL
- pages:                SMALLINT, NULL
- year:                 YEAR          
- cover-img:            VARCHAR(255),  NULL
___________________________
- availibility:
- price:
- online_content:
- language:
- bestseller:
- nr_chapters:
- edition:
- new_release:
- rarity:
- quantity: 

## Copies

- id:                   Primary key (PK), NOTNULL, UNIQUE, INDEX, AUTOINCREMENTAL(AI),
- ean:                  VARCHAR(16), NULL
- isbn:                 VARCHAR(13), NULL
- ?publisher?:          VARCHAR(15) NULL
- position:             VARCHAR(15), NULL
- language:             VARCHAR(5), NULL, DEFAULT("it-IT")


## Users
- id:                   Primary key (PK), NOTNULL, UNIQUE, INDEX, AUTOINCREMENTAL(AI),
- name:                 VARCHAR(50), NOTNULL   
- lastname:             VARCHAR(50), NOTNULL
- age:                  TINYINT, NULL
- email:                VARCHAR(50), NOTNULL, UNIQUE
- tel_number:           VARCHAR(15), NULL
- address:              VARCHAR(100), NOTNULL

## Loans

- id:                   Primary key (PK), NOTNULL, UNIQUE, INDEX, AUTOINCREMENTAL(AI),
- start_date:           DATETIME, NOTNULL
- end_date:             DATETIME, NOTNULL


## Genres

- id:                   Primary key (PK), NOTNULL, UNIQUE, INDEX, AUTOINCREMENTAL(AI),
- nome:                 VARCHAR(20) NOTNULL, INDEX

## Authors
- id:                   Primary key (PK), NOTNULL, UNIQUE, INDEX, AUTOINCREMENTAL(AI),
- name:                 VARCHAR(50) NOTNULL, INDEX
- surname:              VARCHAR(50) NOTNULL, INDEX
- nationality:          VARCHAR(30) NOTNULL

## Publishers

- id:                   Primary key (PK), NOTNULL, UNIQUE, INDEX, AUTOINCREMENTAL(AI),
- name:                 VARCHAR(50) NOTNULL, INDEX

## Conditions
- id:                   Primary key (PK), NOTNULL, UNIQUE, INDEX, AUTOINCREMENTAL(AI),
- nome:                 VARCHAR(150) NOTNULL, INDEX    
