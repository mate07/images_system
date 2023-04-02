<p align="center">
     <img src="https://raw.githubusercontent.com/mate07/images_system/cfe67b7b8c2255cb686c931833f7c94d31df1dfd/logo-abtech-soft-2.svg" height="250px">
    <h1 align="center">ABTECH SOFT Project</h1>
    <br>
</p>

## Integrantes
- Alfaro Martínez, Dannis Francisco
- Campos Cruz, Israel Alexander
- Ramos Cubias, Jessica Beatriz  
<br>

## Descripción del Cliente
ABTECH es una tienda que se dedica a la venta de productos tecnológicos como también artículos escolares, contando con 8 años de existencia, logrando tener variedad de productos para satisfacer la demanda de sus clientes.  
<br>

## Descripción del Proyecto
ABTECH es una tienda que se dedica a la venta de productos tecnológicos como también artículos escolares, contando con 8 años de existencia, logrando tener variedad de productos para satisfacer la demanda de sus clientes.  
<br>

## Objetivos del Proyecto

### Objetivo General:

Diseñar y desarrollar un sistema de facturación y manejo de inventario, para la optimización de los procesos de la empresa ABTECH.  

### Objetivos Especificos:
1. Identificar las necesidades del ABTECH para la formulación y descripción de los requerimientos de los procesos de manejo de inventario y facturación.
2. Definir y establecer los procesos que serán sistematizados para el manejo de los productos, controles de ventas y manejo del Kardex.
3. Establecer los componentes de la solución tecnológica para el diseño de una aplicación en ambiente web que optimice los procesos de la empresa ABTECH.
4. Modelar las diversas etapas del ciclo de vida de un proyecto de software para su adecuado funcionamiento.  
<br>

## Descripción de la Solución Tecnológica

**CAPA DE PRESENTACIÓN**

1. HTML: Se utilizará en su versión 5 para la maquetación de los elementos en la web.

2. CSS: Se utilizará la versión 3, es un lenguaje de diseño gráfico para definir y crear la presentación de un documento estructurado escrito en HTML.

3. BOOTSTRAP: Se utilizará la versión 5, es un framework para el diseño y desarrollo web, nos permite construir aplicaciones web adaptables.

<br>

**CAPA DE LÓGICA DEL NEGOCIO**

1. PHP: Se utilizará la versión 7.4, que se mantiene como la versión más estable del lenguaje, siendo uno de los más utilizados para el desarrollo de aplicaciones web.

2. JAVASCRIPT: Es un lenguaje interpretado, dialecto del estándar ECMAScript. Se define como orientado a objetos,  basado en prototipos, imperativo, débilmente tipado y dinámico.

3. Yii2: Se utilizará en su versión 2, es un framework completo que provee muchas características probadas y listas para usar, como los constructores de consultas y clases para las bases de datos relacionales y NoSQL, la compatibilidad con la arquitectura REST para desarrollar API, la compatibilidad de caché en varios niveles y muchas más.

4. APACHE: Se utilizará la versión 2.4, Apache es un servidor web HTTP de código abierto. Está desarrollado y mantenido por una comunidad de usuarios en torno a la Apache Software Foundation.

<br>

**CAPA DE DATOS**

1. MySQL: Se utilizará la versión 8.0, MySQL es un sistema de gestión de bases de datos que cuenta con una doble licencia. Por una parte, es de código abierto, pero por otra, cuenta con una versión comercial gestionada por la compañía Oracle.

## Yii 2
<p align="center">
    <a href="https://github.com/yiisoft" target="_blank">
        <img src="https://avatars0.githubusercontent.com/u/993323" height="100px">
    </a>
    <h1 align="center">Yii 2 Basic Project Template</h1>
</p>

Yii 2 Basic Project Template es una plantilla basada en el framework de Yii 2, es ideal para crear pequeños proyectos rápidamente.

La plantilla contiene las funciones básicas, incluido el inicio/cierre de sesión del usuario y una página de contacto, configurados en modo predeterminado. Incluye todas las configuraciones de uso común que le permitirían concentrarse en agregar nuevas funciones a su aplicación.

[![Latest Stable Version](https://img.shields.io/packagist/v/yiisoft/yii2-app-basic.svg)](https://packagist.org/packages/yiisoft/yii2-app-basic)
[![Total Downloads](https://img.shields.io/packagist/dt/yiisoft/yii2-app-basic.svg)](https://packagist.org/packages/yiisoft/yii2-app-basic)


## Estructura de Directorios en Yii 2

      assets/             contains assets definition
      commands/           contains console commands (controllers)
      config/             contains application configurations
      controllers/        contains Web controller classes
      mail/               contains view files for e-mails
      models/             contains model classes
      runtime/            contains files generated during runtime
      tests/              contains various tests for the basic application
      vendor/             contains dependent 3rd-party packages
      views/              contains view files for the Web application
      web/                contains the entry script and Web resources


## Configuración Básica para Bases de Datos

Edite el archivo config/db.php con datos reales, por ejemplo:

```php
return [
    'class' => 'yii\db\Connection',
    'dsn' => 'mysql:host=localhost;dbname=yii2basic',
    'username' => 'root',
    'password' => '1234',
    'charset' => 'utf8',
];
```
<br>

**NOTAS:**

1. Yii no creará la base de datos por ti, esto debe hacerse manualmente antes de que puedas acceder a ella.

2. Verifique y edite los otros archivos en el directorio `config/` para personalizar su aplicación según sea necesario.

3. Consulte el archivo README.md, incluido en el framewrok para obtener información específica sobre las pruebas de aplicaciones básicas.