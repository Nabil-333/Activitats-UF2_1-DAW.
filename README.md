
# ENTORNOS DE DESARROLLO

## ÍNDICE

INTRODUCCIÓN

- PRUEBAS
- INTEGRACIÓN
- CALIDAD

## INTRODUCCIÓN

En esta Unidad aprenderemos a:

+ Identificar los diferentes tipos de pruebas.
+ Definir casos de prueba.
Efectuar pruebas unitarias de clases y funciones.
Efectuar pruebas de integración, de sistema y de aceptación.
Realizar medidas de calidad sobre el software desarrollado.




## PRUEBAS


### FORMA DE LAS PRUEBAS

Pruebas dinámicas: Requieren la ejecución de la aplicación. Permiten medir el comportamiento de la aplicación desarrollada.
Pruebas estáticas: Se realizan sin ejecutar el código de la aplicación. Se examina el código fuente.

### ESTRATEGIAS DE PRUEBA

Caja negra: Se estudia el sistema desde fuera. Son pruebas de funcionalidad.
Caja blanca: Se examina el código fuente y su ejecución. Son pruebas estructurales.

### ESTRATEGIAS DE PRUEBA DE CAJA NEGRA

Se estudia el sistema desde fuera.
Se trabaja sobre la interfaz.
No se tienen en cuenta los detalles internos de funcionamiento.
Se proporcionan entradas y se estudian las salidas.
Principales técnicas:
Particiones de equivalencia
Valores límite

### ESTRATEGIAS DE PRUEBA DE CAJA BLANCA

Se examina el código fuente y su ejecución.
Se comprueban los flujos de ejecución dentro de cada unidad (función, clase, módulo, etc.)
También pueden comprobarse los flujos entre unidades durante la integración.
E incluso entre subsistemas, durante las pruebas de sistema.
Principales técnicas:
Cobertura de código
Prueba de bucles

### TIPOS DE PRUEBAS

Funcionales: Evaluan el cumplimiento de los requisitos.
No funcionales: Evaluan aspectos adicionales como rendimiento, seguridad, ...

### PRUEBAS FUNCIONALES

Pruebas unitarias (o de unidad)
Pruebas de regresión
Pruebas de integración
Pruebas de humo (smoke test)
Pruebas del sistema
Pruebas alfa y beta
Pruebas de aceptación (validación por parte del cliente)

### PRUEBAS NO FUNCIONALES

Pruebas de usabilidad
Pruebas de rendimiento
Pruebas de stress
Pruebas de seguridad
Pruebas de compatibilidad
Pruebas de portabilidad

### MECANISMOS DE PRUEBA

Manual
Mediante pruebas realizadas por personal de la empresa o externo.
Automático
Mediante software que ejecuta código de forma automatizada y compara los resultados obtenidos y los resultados esperados.

### SOPORTE DEL DEPURADOR

Puntos de ruptura
Ejecución paso a paso
Análisis de variables

### FRAMEWORKS PARA PRUEBAS

Java: JUnit, TestNG
C++: CppUnit, Google Test
PHP: PHPUnit
Javascript: Mocha

### JUNIT4 - ANOTACIONES II
@BeforeClass: el método es invocado antes de iniciar todos los tests. Sólo puede haber un método con esta anotación.
@AfterClass: el método es invocado después de finalizar todos los tests. Sólo puede haber un método con esta anotación.
@Before: Se ejecuta antes de cada test.
@After: Se ejecuta después de cada test.
@Ignore: Los métodos marcados con esta anotación no serán ejecutados.
@Test: Representa un test que se debe ejecutar.





## INTEGRACIÓN


### FORMAS DE INTEGRACIÓN

Integración Big bang
Integración Descendente
Integración Ascendente
Integración Continua (CI)

### SERVIDORES DE INTEGRACIÓN CONTINUA

CI : Integración continua
CD : Entrega continua
Jenkins
Bamboo
TravisCI
CircleCI

### COBERTURA DEL CÓDIGO

Es una medida que indica el porcentaje de código que ha sido ejecutado durante las pruebas.
Es aconsejable que sea lo más cercano a 100%.
Si es del 100% entonces se ha ejecutado todo el código fuente durante las pruebas.
Si es menor del 100% entonces existe código fuente que no se ha ejecutado durante las pruebas.
Es posible realizar la cobertura tanto desde el IDE como desde un servicio web apropiado.





## CALIDAD


### CONTROL DE CALIDAD

Para lograr una
Medición de la calidad de un producto
necesitamos realizar
Pruebas

### CALIDAD DEL PROCESO/PRODUCTO (QA/QC)

QA es un conjunto de actividades para garantizar la calidad en los procesos mediante los cuales se desarrollan los productos.
QC es un conjunto de actividades para garantizar la calidad de los productos. Las actividades se centran en identificar defectos en los productos reales producidos.

### FACTORES DE CALIDAD (I)

El modelo de calidad de McCall define 11 factores de calidad.
Estos factores se agrupan en 3 ámbitos
Operación del producto
Revisión del producto
Transición del producto

### FACTORES DE CALIDAD (II)

OPERACIÓN DEL PRODUCTO
Corrección
Fiabilidad
Eficiencia
Seguridad

### FACTORES DE CALIDAD (III)

REVISIÓN DEL PRODUCTO
Mantenibilidad
Flexibilidad

### FACTORES DE CALIDAD (IV)

TRANSICIÓN DEL PRODUCTO
Portabilidad
Reusabilidad
Interoperatividad
Facilidad de prueba
Facilidad de uso
