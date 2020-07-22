# Power BI

**Índice**   
1. [ ¿Qué es Power BI?](#id1)
2. [ Tipos de licencias](#id2)
    - [Power BI FREE](#id2.1)
    - [Power BI PRO](#id2.2)
    - [Power BI Premium](#id2.3)
    - [Power BI Embedded](#id2.4)
    - [Power BI Report Server](#id2.5)
3. [¿Qué tipo de lincencia escoger?](#id3)
4. [Resolucion de Problemas](#id4)

## ¿Qué es Power BI? <a name="id1"></a>
Power BI es un servicio de análisis empresarial de Microsoft, su objetivo es proporcionar visualizaciones interactivas y capacidades de inteligencia empresarial con una interfaz lo suficientemente simple como para que los usuarios finales creen sus propios informes y paneles

## Tipos de licencias <a name="id2"></a>

Los tipos de licencias existentes vienen dadas según cómo vamos a consumir la información que creamos en Power BI

### Licensias de creación de contenido para web
#### 1. Power BI FREE <a name="id2.1"></a>
- Incluye 1 GB de almacenamiento en Modo Import.
- No se pueden compartir con otros usuarios (reportes, dashboards y datasets).
- Para compartir reportes solo es posible en modo público.
- No incluye Dataflows

#### 2. Power BI PRO <a name="id2.2"></a>
- Toda la funcionalidad de Power BI
- Costo Mensual de $ 10 USD por Usuario / Mes (más impuestos aplicables)
- Incluye 10 GB de Almacenamiento en Modo Import
- Se requiere suscripción anual, más información en [¿Cuánto cuesta Power BI?](https://powerbi.microsoft.com/es-es/pricing/)

#### 3. Power BI Premium <a name="id2.3"></a>
Licenciamiento ideal para implementar a gran escala Power BI

- Se requiere de suscripción mensual, más información en [Calculadora de Power BI Premium](https://powerbi.microsoft.com/es-es/calculator/)
- Tiene un costo base mínimo a cubrir
- Está basado en cantidad de recursos a utilizar
- Se recomienda esta opción a partir de 500 usuarios (Costo-Beneficio)
- Incluye adicionalmente licenciamiento de Power BI Report Server (On-Premise)
- Parte de la suscripción de Office 365

![Tabla_diferencias_licencia](https://github.com/alejandroasc96/Power-BI/blob/master/images/Power-BI-Licencias.png?raw=true)

> [**COMPARATIVA PRO Y PREMIUM**](https://powerbi.microsoft.com/es-es/pricing/#powerbi-comparison-table)

### Licencias para publicar aplicaciones web y móviles

#### 4. Power BI Embedded <a name="id2.4"></a>
Licenciamiento recomendado para integrar en aplicaciones personalizadas [consultar precios](https://azure.microsoft.com/es-es/pricing/details/power-bi-embedded/)

- Licenciamiento según requerimientos, más información en Precios de Power BI Embedded
- Tiene un costo base mínimo a cubrir
- Está basado en cantidad de recursos a utilizar y no requiere licencias PRO para visualizar
- Para diseñar/modelar se requiere licencia PRO
- Tiene limitantes respecto a las versiones de Power BI Free / PRO
    - No incluye acceso a móviles

#### 5. Power BI Report Server <a name="id2.5"></a>
Licenciamiento incluido con las ediciones Enterprise de SQL Server 2016 y superiores

- Incluido en SQL Server Enterprise (2016 o Superior) + Software Assurance
- Instalación On Premise
- Tiene algunas variantes respecto al Power BI FREE / PRO
- No requiere licencias adicionales para usuarios consumidores de reportes
- No requiere licencias PRO para diseñar/modelar
- Incluye Reportes Paginados
- Requiere una versión especial de Power BI Desktop
    - La versión de Power BI Desktop para Report Server se actualiza cada 4 meses

[¿Power BI Embedded O Power BI Report Server?]()


## ¿Qué tipo de lincencia escoger? <a name="id3"></a>

La respuesta a esta consulta vienen dada según cómo vamos a consumir la información que creamos en Power BI quedándose el siguiente resumen.

1.- Power BI(Free)

Cogeremos esta edición en el caso de:

- Tener cuenta de Office 365 para poder hacer uso del portal [power bi](https://powerbi.microsoft.com/es-es/), el cual nos permitirá publicar lo infromes creados en nuestras aplicaciones web
- No tener problema en compartir de forma pública el informe creado
- Sin necesidad de compartir los informes dentro de un grupo de trabajo
- En caso de no tener el portal de porwer bi no se podrán crear informes dinámicos
- Imports de la base de datos de no más de 1 GB

2.- Power BI PRO

Cogeremos esta edición en el caso de:

- No requerir más de 10GB de almacenamiento por usuario
- Querer compartir los informes dentro de un entorno de trabajo
- Para pequeñas y medianas empresas, sin elevados volúmenes de datos y donde se necesiten pocas licencias de uso.
- Querer incrustar los informaes en páginas web sin tener que poseer cuenta de microsoft Office 365

3.- Power BI Premium

Cogeremos esta edición en el caso de:

- Requerir de 100TB de almacenamiento
- Tamaño máximo de un conjunto de datos individual 10G
- Ir escalando el rendimiento a medida que cambien los requisitos de análisis de la empresa
- Poseer una gran cantidad de usuarios que hagan uso de la herramienta ( Power BI Premium no se paga licencia individual, sino que se paga un fee mensual que permite que una gran cantidad de sus usuarios utilicen Power BI para ver los informes)
- Para randes empresas donde muchos usuarios necesitan editar y visualizar los datos e informes.

4.- Power BI Embedded

Cogeremos esta edición en el caso de:

-  Insertar paneles, cuadros de mando e informes interactivos de Power BI en sus aplicaciones (APIS).

## Conclusión

El resumen de los comentado arriba según las características principales sería 

- Power BI(free) con acceso al portal power Bi: Para crear informes dinámicos en web de forma pública sin poder compartir los documentos dentro de usuarios de la misma empresa

- Power Bi pro : para medianas empresas que necesitan compartir informacion entre sus trabajadores y que deseen publicar los informes en web de forma privada

- Power Bi premium : para grandes empresas que necesitan compartir informacion entre un gran número de sus trabajadores y que deseen publicar los informes en web de forma privada

- Power BI Embedded: Servicio que nos posibilita la inscrustacion de nuestros informes en aplicaciones moviles, se cobra por tiempo de visualización [coste](https://azure.microsoft.com/es-es/pricing/details/power-bi-embedded/)

- Power BI Report Server: Mismo servicio que el anterior pero esta licencia puede contratarse en forma de pack.



## Posibles de problemas <a name="id4"></a>

- [¿Cómo saber qué licencia tengo?](https://github.com/alejandroasc96/Power-BI/blob/master/comoSaberQueLicenciaTengo.md)

- [Activar código insercion para publicar en web](https://github.com/alejandroasc96/Power-BI/blob/master/codigoInsercion.md)

- [Compartir en Power BI sin licencia PRO](https://github.com/alejandroasc96/Power-BI/blob/master/compartirSinLicenciaPro.md)
