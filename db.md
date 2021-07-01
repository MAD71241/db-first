CARATTERISTICHE TECNICHE AUTO
=======
## Auto Usate
#informazioni generali
- Id                                                BIGINT PRIMARY KEY UNIQUE NOTNULL
- Marca                                             VARCHAR NOTNULL INDEX                   15
- Modello                                           VARCHAR NOTNULL INDEX                   50
- Generazione	                                    SMALLINT UNIQUE NOTNULL
- Cilindrata Motore 	                            TINYINT NOTNULL                         1,1
- Cavalli Motore                                    SMALLINT NOTNULL                        6,0
- Inizio anno di produzione	                        YEAR NOTNULL INDEX
- Anno di immatricolazione                          DATE NULL INDEX
- Chilometri percorsi                               MEDIUMINT INDEX                         6,0
- Architettura dell'unità di potenza	            VARCHAR
- Tipo di carrozzeria	                            VARCHAR
- Posti	                                            TINYINT                                 1,0
- Numero Porte                                      TINYINT                                 1,0
- Prezzo                                            DECIMAL NOTNULL INDEX                   6,2
- Descrizione                                       TEXT

## Prestazioni
- Tipo carburante	                                VARCHAR NOTNULL                         20
- Accelerazione 0 - 100 km/h	                    TINYINT                                 2,1
- Accelerazione 0 - 62 mph	                        TINYINT                                 1,1
- Accelerazione 0 - 60 mph                          TINYINT                                 1,1
- Velocità massima	                                TINYINT                                 3,0
- Classe di emissione gas di scarico	            VARCHAR

## Motore

- Sistema di alimentazione	                        VARCHAR
- Aspirazione del motore	                        VARCHAR
- Potenza	                                        VARCHAR
- Capacità per litro di volume di lavoro          	TINYINT                                 2,1
- Coppia massima                                    VARCHAR