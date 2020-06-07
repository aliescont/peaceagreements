# Gender peace agreements 1990-2019

En este repositorio se pueden encontrar los documentos elaborados para crear la visualización sobre los acuerdos de paz relacionados con la mujer, la violencia y el género, obtenidos de la web peaceagreements.org/wsearch

- pax_data_363_agreements_11-04-20.csv: es el fichero descargado del buscador de la web antes mencionada, seleccionando todas las categorías.

- PEC2.ipynb: es el cuaderno jupyter utilizado para la exploración y transformación de los datos

- describe_obj_int.csv: es el documento que se ha extraido del cuaderno de Jupyter con la descripción de todas las variables int para su mejor visualización. Aunque se puede observar, que aunque los valores de la mayoría de las variables son int, realmente representan si la variable está presente en alguna provisión del acuerdo, se han dejado como int porque permiten el cálculo de otras variables de una forma más directa.

- pax_vis_pec3.csv: es el documento resultante luego de la limpieza y la transformación inicial de los datos, obtenido en el cuaderno jupyter PEC2.ipynb

- aescontrelar_final_pec4.twb: visualización creada en Tableau
