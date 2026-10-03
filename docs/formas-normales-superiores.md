# Formas Normales Superiores

Existen formas normales superiores a la tercera forma normal, que se utilizan para mejorar aún más la estructura de una base de datos y reducir la redundancia y las anomalías. Estas incluyen:

* **Cuarta forma normal** (4FN): La cuarta forma normal (o Forma Normal de Boyce-Codd) se centra en eliminar las dependencias multivaluadas. Una tabla está en cuarta forma normal si está en tercera forma normal y no tiene dependencias multivaluadas. Esto significa que no debe haber atributos que dependan de manera independiente de la clave primaria, lo que puede generar redundancia y problemas de integridad.
* **Quinta forma normal** (5FN): La quinta forma normal se centra en eliminar las dependencias de unión. Una tabla está en quinta forma normal si está en cuarta forma normal y no tiene dependencias de unión. Esto significa que no debe haber atributos que dependan de manera conjunta de la clave primaria, lo que puede generar redundancia y problemas de integridad.

Aunque las formas normales superiores pueden ser útiles en ciertos casos, es importante tener en cuenta que no siempre es necesario llegar a la forma normal más alta. En algunos casos, puede ser más beneficioso mantener cierta redundancia para mejorar el rendimiento de las consultas y reducir la complejidad del diseño.

Hasta ahora, solo pediremos llegar a 3FN, ya que es suficiente para la mayoría de los casos y garantiza una buena estructura de la base de datos. Sin embargo, es importante conocer las formas normales superiores y saber cuándo pueden ser útiles en el diseño de bases de datos más complejas.