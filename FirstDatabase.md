<!-- Istruzioni:
Create un file di testo per descrivere un database di un negozio di videogiochi.
Strutturate il file come fatto oggi in classe.  Specificate: il nome del database, la tabella e le potenziali colonne con i tipi di dato. -->

NOME DATABASE: NEGOZIO VIDEOGIOCHI

TABELLA: Videogiochi

COLONNE:
Id: PRIMARY_KEY NOTNULL AUTO_INCREMENT UNIQUE
Titolo: stringa VARCHAR(35) NOTNULL 
Genere: stringa VARCHAR(25) NOTNULL
Edizione: stringa VARCHAR(20) NULL
Anno di uscita: data YEAR NULL
Realizzato da: stringa VARCHAR(30) NULL
Pubblicato da: stringa VARCHAR(30) NULL
Serie: stringa VARCHAR(20) NULL
Trama: stringa TEXT NULL
Console: stringa VARCHAR(15) NOTNULL
Lingua: stringa VARCHAR(20) NOTNULL
Prezzo: numero FLOAT(3,2) NULL
Disponibilità: numero TINYINT NULL DEFAULT(0)
Immagine Copertina: stringa VARCHAR() NULL
Aggiunto al database: data DATETIME NOTNULL
Modificato: data DATETIME NULL
Durata Quest principale: SMALLINT NULL
Età minima: numero SMALLINT NULL

