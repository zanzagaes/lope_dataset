# Lope_dataset: generación de texto al estilo de Lope de Vega
En este trabajo se ofrece una selección de texto en formato plano proveniente de comedias de Lope de Vega en el dominio público para entrenar modelos de lenguaje de forma no supervisada. Concretamente se ha recogido el texto de las obras:

- Fuente Ovejuna
- Amor, pleita y desafío
- Amor con vista
- La prueba de los amigos
- Un pastoral albergue
- El premio de la hermosura
- El remedio en la desdicha
- El mejor alcalde, el rey
- La moza de cántaro
- El peregrino en su patria

## Fragmento del conjunto de datos

	ÁLV:
	¿Sabeis quién soy?
	
	PAD:
	Sé que tan léjos estoy
	De hacerle agravio, que apelo
	De vuestro engañado celo,
	Y justas quejas os doy.
	
El conjunto de datos está formado por unas 53.000 líneas con diálogos como el mostrado. Se han eliminado todas las acotaciones, comentarios y anotaciones presentes en las obras y se han unificado los signos de puntuación. La separación entre obras no está marcada y el nombre de algunos personajes se encuentra abreviado, siguiendo la edición original.