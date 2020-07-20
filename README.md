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
Licenciamiento recomendado para integrar en aplicaciones personalizadas

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


## ¿Cómo saber qué licencia tengo?
La forma más rápida de ver qué tipos de licencia tenemos sería ingresando en la siguiente ruta con nuestra cuenta de trabajo o estudio de outlook [https://portal.office.com/account#subscriptions](https://portal.office.com/account#subscriptions)

![foto_tipo_licencia](https://github.com/alejandroasc96/Power-BI/blob/master/images/resumen_tipo_licencia.png?raw=true)

## Compartir con usuarios que tienen Power BI

### Compartir en Power BI sin licencia PRO
Si tienes una cuenta de Office 365 tendrás una cuenta de Power BI. Si posees una cuenta en el servicio de Power BI, pero no eres usuario PRO, tienes una alternativa para compartir los reportes creados sin dar acceso de edición:

Publicar el reporte en la web: Para publicar un informe debes ir a Archivo y seleccionar la opción “Publicar en la web”. Este método te proporcionará un enlace para acceder desde cualquier ordenador al informe u otro link HTML y poder incrustar el informe en un blog o sitio web.
Además, todos los cambios que realices en el informe se sincronizarán con el publicado, por lo que gente visualizará siempre la última versión del informe.

Si bien es un método gratuito, debes tener en cuenta algunas desventajas de este método:

El informe podrá compartirse por web o correo electrónico con otras personas. También puede ser compartido por medio de redes sociales accediendo a un icono de la página. Es por esto que esta forma de compartir no es segura, y debe ser sólo usada cuando quiera compartir los datos en forma pública.
Todas las páginas del informe estarán visibles. No es posible ocultar las páginas que no queremos que sean publicadas en la web.
