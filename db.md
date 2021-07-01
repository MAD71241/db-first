CARATTERISTICHE TECNICHE AUTO
=======
#informazioni generali
- Id                                                BIGINT PRIMARY KEY UNIQUE NOTNULL
- Marca                                             VARCHAR NOTNULL
- Modello                                           VARCHAR NOTNULL
- Generazione	                                    SMALLINT UNIQUE NOTNULL
- Cilindrata Motore 	                            TINYINT NOTNULL        1,1
- Cavalli Motore                                    SMALLINT NOTNULL       6,0
- Inizio anno di produzione	                        SMALLINT YEAR
- Fine anno di produzione	                        SMALLINT YEAR
- Architettura dell'unità di potenza	            VARCHAR
- Tipo di carrozzeria	                            VARCHAR
- Posti	                                            TINYINT         1,0
- Numero Porte                                      TINYINT         1,0
- Prezzo                                            SMALLINT        3,0

#Prestazioni
- Tipo carburante	                                VARCHAR NOTNULL
- Accelerazione 0 - 100 km/h	                    TINYINT         2,1
- Accelerazione 0 - 62 mph	                        TINYINT         1,1
- Accelerazione 0 - 60 mph                          TINYINT         1,1
- Velocità massima	                                TINYINT         3,0
- Classe di emissione gas di scarico	            VARCHAR

#Motore

- Sistema di alimentazione	                        VARCHAR
- Aspirazione del motore	                        VARCHAR
- Potenza	                                        VARCHAR
- Capacità per litro di volume di lavoro          	TINYINT         2,1
- Coppia massima                                    VARCHAR