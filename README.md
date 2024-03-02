# Prueba Técnica Devsu

¡Hola! Este es el repositorio donde se subieron ambos proyectos para la prueba técnica de Devsu.

---

## Descripción

Aquí se encontrarán los dos proyectos solicitados; sin embargo, para una mayor organización estarán también en distintos repositorios.

saucedemo-e2e-testing\
`https://github.com/ViralWharf/saucedemo-e2e-testing`

petstore-api-testing\
`https://github.com/ViralWharf/petstore-api-testing`

## Requisitos Previos
- Java Development Kit (JDK) 8 o superior.
- Maven.
- Google Chrome.
- El proyecto se creó en IntelliJ, entonces se recomienda usarlo.

---

## Ejecución prueba E2E

El proyecto `saucedemo-e2e-testing` está bajo un patrón de diseño POM, por lo que para ejecutar toda su funcionalidad, solo basta con lo siguiente:

1. Clona el repositorio: \
   `git clone https://github.com/ViralWharf/saucedemo-e2e-testing`
2. Abre y ejecuta el feature [ComprarProductosSatisfactoriamente.feature](saucedemo-e2e-testing%2Fsrc%2Ftest%2Fjava%2Ftest%2FComprarProductosSatisfactoriamente.feature), el cual se ubica en `src/test/java/test/ComprarProductosSatisfactoriamente.feature`
3. ¡Comprueba los resultados!

## Resultados!
<img width="1440" alt="image" src="https://github.com/ViralWharf/petstore-api-testing/assets/100390417/9a85f4ab-df93-4f01-abee-a25d890f5dd5">

---

## Ejecución prueba API

Para ejecutar el proyecto `petstore-api-testing` hay que seguir los siguientes pasos y tener en cuenta las recomendaciones:

1. Clona el repositorio: \
   `git clone https://github.com/ViralWharf/petstore-api-testing`
2. Aquí se pueden hacer dos cosas:
    1. Se pueden ejecutar los features de manera independiente, para esto solo hay que acceder a `src/test/resources/features` y seleccionar el feature a ejecutar.
    2. Se pueden ejecutar los test de manera parelela desde [TestRunner.java](petstore-api-testing%2Fsrc%2Ftest%2Fjava%2Ftests%2FTestRunner.java), ubicado en `src/test/java/tests/TestRunner.java`
3. El reporte generado se guardará en [karate-summary.html](target%2Fkarate-reports%2Fkarate-summary.html), su ruta es `target/karate-reports/karate-summary.html`
4. ¡Comprueba los resultados!

## Resultados!
<img width="1401" alt="image" src="https://github.com/ViralWharf/saucedemo-e2e-testing/assets/100390417/dbb0a3ad-3900-4a2a-bc20-c919cee8879b">



