# meta-tags
Etiquetas meta para seo
No todas las etiquetas deben ponerse en todos los casos. Las etiquetas de tamaño de imagen son opcionales. La de robot se pondrá si sus valores son distintos a index, follow o si hay alguna limitación que queremos poner a los buscadores. La etiqueta de cache se usará para evitar que se almacene el caché o para ponerle un tiempo de almacenamiento.

Caché
meta http-equiv="cache-control" content="no-cache" 
meta http-equiv="expires" content="tiempo de expiración en segundos"

Tamaño de la imagen en redes sociales
meta property="og:image:width" content="800"
meta property="og:image:height" content="800"

Internet Explorer
meta http-equiv="X-UA-Compatible" content="IE=7"
meta http-equiv="X-UA-Compatible" content="ie=edge"

Robot
meta name="robots" content="index, follow"
o también
meta name="robots" content="all"
