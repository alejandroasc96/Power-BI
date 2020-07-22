# Power BI

## ¿Qué es Power BI?
Power BI es un servicio de análisis empresarial de Microsoft, su objetivo es proporcionar visualizaciones interactivas y capacidades de inteligencia empresarial con una interfaz lo suficientemente simple como para que los usuarios finales creen sus propios informes y paneles

## Tipos de licencias

Los tipos de licencias existentes vienen dadas según cómo vamos a consumir la información que creamos en Power BI

### Licensias de creación de contenido
#### 1. Power BI FREE
- Incluye 1 GB de almacenamiento en Modo Import.
- No se pueden compartir con otros usuarios (reportes, dashboards y datasets).
- Para compartir reportes solo es posible en modo público.
- No incluye Dataflows

#### 2. Power BI PRO
- Toda la funcionalidad de Power BI
- Costo Mensual de $ 10 USD por Usuario / Mes (más impuestos aplicables)
- Incluye 10 GB de Almacenamiento en Modo Import
- Se requiere suscripción anual, más información en [¿Cuánto cuesta Power BI?](https://powerbi.microsoft.com/es-es/pricing/)

#### 3. Power BI Premium
Licenciamiento ideal para implementar a gran escala Power BI

- Se requiere de suscripción mensual, más información en [Calculadora de Power BI Premium](https://powerbi.microsoft.com/es-es/calculator/)
- Tiene un costo base mínimo a cubrir
- Está basado en cantidad de recursos a utilizar
- Se recomienda esta opción a partir de 500 usuarios (Costo-Beneficio)
- Incluye adicionalmente licenciamiento de Power BI Report Server (On-Premise)
- Parte de la suscripción de Office 365

![Tabla_diferencias_licencia](https://github.com/alejandroasc96/Power-BI/blob/master/images/Power-BI-Licencias.png?raw=true)

> [**COMPARATIVA PRO Y PREMIUM**](https://powerbi.microsoft.com/es-es/pricing/#powerbi-comparison-table)

### Licencias para publicar

#### 4. Power BI Embedded
Licenciamiento recomendado para integrar en aplicaciones personalizadas [consultar precios](https://azure.microsoft.com/es-es/pricing/details/power-bi-embedded/)

- Licenciamiento según requerimientos, más información en Precios de Power BI Embedded
- Tiene un costo base mínimo a cubrir
- Está basado en cantidad de recursos a utilizar y no requiere licencias PRO para visualizar
- Para diseñar/modelar se requiere licencia PRO
- Tiene limitantes respecto a las versiones de Power BI Free / PRO
    - No incluye acceso a móviles

#### 5. Power BI Report Server
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


## ¿Qué tipo de lincencia escoger?

La respuesta a esta consulta vienen dada según cómo vamos a consumir la información que creamos en Power BI quedándose el siguiente resumen.

1.- Power BI(Free)
Cogeremos esta edición en el caso de:
    - Tener cuenta de Ofice 365 para poder hacer uso del portal [power bi](https://powerbi.microsoft.com/es-es/), el cual nos permitirá publicar lo infromes creados en nuestras aplicaciones web
    - No tener problema en compartir de forma pública el informe creado
    - Sin necesidad de compartir los informes dentro de un grupo de trabajo
    - En caso de no tener el portal de porwer bi no se podrán crear informes dinámicos
    - Imports de la base de datos de nos más de 1 GB

2.- Power BI PRO
Cogeremos esta edición en el caso de:
    - No requerir más de 10GB de almacenamiento por usuario
    - Querer compartir los informes dentro de un entorno de trabajo
    - Para pequeñas y medianas empresas, sin elevados volúmenes de datos y donde se necesiten pocas licencias de uso.
    - Querer incrustar los informaes en páginas web sin tener que poseer cuenta de microsoft Ofice 365

3.- Power BI Premium
Cogeremos esta edición en el caso de:
    - Requerir de 100TB de almacenamiento
    - Ir escalando el rendimiento a medida que cambien los requisitos de análisis de la empresa
    - Poseer una gran cantidad de usuarios que hagan uso de la herramienta ( Power BI Premium no se paga licencia individual, sino que se paga un fee mensual que permite que una gran cantidad de sus usuarios utilicen Power BI para ver los informes)
    - Para randes empresas donde muchos usuarios necesitan editar y visualizar los datos e informes.

4.- Power BI Embedded
Cogeremos esta edición en el caso de:
    -  Insertar paneles, cuadros de mando e informes interactivos de Power BI en sus aplicaciones (APIS).


## ¿Cómo saber qué licencia tengo?
La forma más rápida de ver qué tipos de licencia tenemos sería ingresando en la siguiente ruta con nuestra cuenta de trabajo o estudio de outlook [https://portal.office.com/account#subscriptions](https://portal.office.com/account#subscriptions)

![foto_tipo_licencia](https://github.com/alejandroasc96/Power-BI/blob/master/images/resumen_tipo_licencia.png?raw=true)


## Posibles de problemas

- [Activar código insercion para publicar en web](https://github.com/alejandroasc96/Power-BI/blob/master/codigoInsercion.md)

- [Compartir en Power BI sin licencia PRO]()
