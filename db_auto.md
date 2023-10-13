# db-first 

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## auto 


| id | marca | modello| nazionalita | anno | usato | km | prezzo | alimentazione | note |
| -- | ----- | ------ | ----------- | ---- | ----- | -- | ------ | ------------- | ---- |
| BIGINT, NOTNULL, UNIQUE, AUTO_INCREMENT | NULL, VARCHAR(50) | NULL, VARCHAR(50) | NULL, VARCHAR(5) esempio: 'it-IT'| YEAR, NULL | TINYINT, default(0) | MEDIUMINT ,DEFAULT(0) | DECIMAL(8, 2 ESEMPIO: '999999,99') |  NULL, VARCHAR(30) | TEXT |
| esempio(☞ﾟヮﾟ)☞ 1 | toyota | trueno ae86 | JP | 1983 | 1 | 50000 | 25000$ | benzina | trazione posteriore, cofano in carbonio, motore non originale e livree ai lati con scritte in lingua straniera  ☜(ﾟヮﾟ☜) |
