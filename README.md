# acreditacion-odontologia-chile
Evaluación de los criterios de acreditación de las carreras de Odontología en universidades chilenas

## Motivación
Recientemente se ha discutido que todas las carreras de odontología deberían estar acreditadas, como occure con pedagogía y medicina. Sin embargo la acreditación actual carece de criterios objetivos. Por ejemplo, no hay un número mínimo de docentes por estudiantes o revistas suscritas en biblioteca. Debido a que no está claro entonces que evalua la acreditación, se procederá a evaluar los informes de acreditación, para ver que ha resultado de la acreditación y evaluar si los criterios generales se aplican y si existen patrones detectables en los informes de acreditación. 

## Antecedentes
Criterios acreditación Odontología CNA: https://www.cnachile.cl/Criterios%20de%20carreras/Forms/DispForm.aspx?ID=19

## Métodología
1. Se descargan todos los acuerdos de acreditación disponibles en la CNA: https://www.cnachile.cl/Paginas/buscador-avanzado.aspx
2. Se tranforman a texto simple
3. Se consolidan todos los documentos por universidad
4. se procesan en R extrayendo los términos más utilizados
5. Se generan nubes de palabras y se realizan análisis de texto agrupados por universidad
6. Se generan palabras índice, por ejemplo "investigación, publicaciones, conferencias, isi, scielo" para definir el metaconcepto de investigación. Luego se comparan los índices por universidad
7. Se extraen índices en general
8. Se comparan los índices en general con el documento base de criterios de acreditación para evaluar discrepancias y similitudes. 

## Resultados
Nubes de palabras
Listado de términos y frecuencia de uso
Análisis de sentimiento
