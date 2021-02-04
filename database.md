
# database name : Gamestop
# nome tabella : Videogames Database

- id BIGINT PRIMARYKEY 
- cd-key string VARCHAR(10) NOTNULL UNIQUE
- title string TEXT(1500) NOTNULL
- description string TEXT NULL
- author string VARCHAR(30) NOTNULL
- release_date  YEAR NOTNULL
- genre string VARCHAR(15) NOTNULL
- price int FLOAT(6,2) 9999,99 NULL
- edition string VARCHAR(35)
- publisher string VARCHAR(25) NULL
- availability int TINYINT NULL DEFAULT(1)
- cover_img string VARCHAR() NULL
- language string VARCHAR(20) NOTNULL
- dubbing string VARCHAR(20) NOTNULL
- edition string VARCHAR(20) NULL
- quantity int SMALLINT NULL DEFAULT(0)
- format string VARCHAR (25) NULL
- plaforms string VARCHAR(25) NULL
- cover material string VARCHAR(25) NULL
- updated_in date DATETIME NULL
