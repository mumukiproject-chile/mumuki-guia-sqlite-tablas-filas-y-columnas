Los sistemas informáticos utilizan distintos tipos de bases de datos que estructuran los datos de determinada manera. 

Entre ellas están las bases de datos relacionales que, manteniendo la misma idea de tablas que acabamos de ver, definen los campos necesarios que debe tener cada registro particular. 

Además, sería medio tonto poner como año de estreno: "mil novecientos noventa y tres":laughing:, así que es importante también diferenciar el tipo de dato acorde a cada caso. 

Se usa un DER (Diagrama Entidad Relación) como el siguiente para describir los campos y tipos de datos de cada tabla.

<div class='mu-erd'
  data-entities='{
    "series_peliculas": {
      "titulo": {
        "type": "Text"
      },
      "descripcion": {
        "type": "Text"
      },
      "creador": {
        "type": "Text"
      },
      "personajes": {
        "type": "Text"
      },
      "temporadas": {
        "type": "Integer"
      },
      "estreno": {
        "type": "Integer"
      },
      "puntaje": {
        "type": "Real"
      }
    }
  }'>
</div>

El nombre de este diagrama se refiere a que representa entidades y sus relaciones :stuck\_out\_tongue\_winking\_eye:. Pero tranquilos que más adelante vamos a ver qué es esto.

Solo para que entiendas... estas _entidades_ son abstracciones de cualquier cosa que nos pueda interesar y que tenga atributos/datos para guardar. Para facilitarte la idea, de ahora en adelante vamos a hablar simplemente de _tablas_. 