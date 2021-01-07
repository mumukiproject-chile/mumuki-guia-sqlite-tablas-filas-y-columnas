Fíjate qué te puede servir del ejercicio anterior:

```sql 
SELECT id_contenido, titulo, formato, estreno, puntaje FROM series_peliculas WHERE titulo LIKE "%planeta de los simios%" AND (estreno >= 1974 OR puntaje >= 8) AND NOT formato LIKE "cómic"; 
``` 
Ojo que podría haber algún caso que sea anterior al 2003 con puntaje mayor a 8.6, lo cual también debería estar considerado.  