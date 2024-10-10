---
description: >-
  Tipos de licencias que pueden tener vinculadas los CMS con los que vamos a
  trabajar
---

# Tipos de licencias

## Software libre

El término **software libre** hace referencia a un tipo de software que otorga a los usuarios la libertad de **usar, estudiar, modificar y distribuir** el software. No se refiere necesariamente a que el software sea gratuito (aunque muchos programas de software libre lo son), sino a la libertad de hacer con el software lo que el usuario desee, bajo ciertas condiciones.

Las cuatro libertades esenciales que definen al **software libre** son:

1. **Libertad de usar el programa** con cualquier propósito (libertad 0).
   * Los usuarios pueden ejecutar el software para cualquier tipo de tarea o actividad, sin restricciones.
2. **Libertad de estudiar cómo funciona el programa** y adaptarlo a sus necesidades (libertad 1).
   * Esto implica que el código fuente del programa debe estar disponible para los usuarios, ya que sin el código fuente no es posible estudiarlo o modificarlo.
3. **Libertad de redistribuir copias** del programa para ayudar a otros (libertad 2).
   * Los usuarios tienen el derecho de compartir el software con otros, ya sea de manera gratuita o a cambio de un precio.
4. **Libertad de mejorar el programa** y distribuir esas mejoras al público (libertad 3).
   * Los usuarios pueden modificar el software para mejorar su funcionalidad o corregir errores, y luego distribuir sus versiones modificadas para que otros también se beneficien.

El término **software libre** fue acuñado por la **Free Software Foundation (FSF)**, y está estrechamente asociado con la filosofía del movimiento del software libre, que promueve la idea de que el software debe ser compartido y colaborativo para que la sociedad en su conjunto se beneficie de su desarrollo.

#### Diferencias entre software libre y otros tipos de software:

* **Software propietario**: En este caso, el desarrollador o la empresa propietaria restringe o prohíbe el acceso al código fuente, la redistribución o la modificación del software. Los usuarios solo tienen permiso para utilizar el programa bajo ciertas condiciones establecidas en el contrato de licencia.
* **Open source** (código abierto): Aunque a veces se usan indistintamente, el término "open source" se refiere más a la metodología de desarrollo colaborativo, mientras que "software libre" pone un énfasis mayor en los derechos y las libertades de los usuarios. Ambos conceptos son similares en la práctica, pero las motivaciones detrás del uso de estos términos pueden ser diferentes.

En resumen, **software libre** implica que los usuarios tienen el control sobre el software que utilizan, pudiendo estudiarlo, modificarlo y compartirlo libremente.

## Tipos de licencias

Existen varios tipos de licencias de software libre, cada una con diferentes condiciones para el uso, modificación y distribución del software. Aquí te explico las **licencias más comunes** que se utilizan en el software libre:

#### 1. **GPL (General Public License)**

* **Versión más usada**: GPLv2 y GPLv3.
* **Características principales**:
  * Es una licencia de **copyleft fuerte**: cualquier software que utilice código bajo la GPL debe ser liberado bajo la misma licencia GPL si se distribuye.
  * **Libertades**: Permite usar, estudiar, modificar y distribuir el software, pero obliga a que las versiones modificadas o derivadas mantengan la misma licencia GPL.
  * **Aplicaciones**: Usada por proyectos como Linux, WordPress, Drupal, Moodle, y otros.
* **GPLv3** introduce mejoras de seguridad y compatibilidad frente a la versión GPLv2, especialmente en términos de dispositivos con restricciones y patentes.

#### 2. **LGPL (Lesser General Public License)**

* **Características principales**:
  * Similar a la GPL, pero con un enfoque más **permisivo**: permite que el software que usa bibliotecas bajo LGPL pueda ser combinado con software propietario sin que el resultado deba ser GPL.
  * Muy usada en bibliotecas de software que pueden ser vinculadas con aplicaciones no libres.
  * **Libertades**: Los desarrolladores pueden usar y modificar el software bajo LGPL, pero no están obligados a liberar todo su software bajo LGPL o GPL, solo la biblioteca que usen.
  * **Aplicaciones**: Usada en bibliotecas como **GNU C Library** (glibc).

#### 3. **MIT License**

* **Características principales**:
  * Es una licencia muy **permisiva**: permite a los usuarios hacer prácticamente lo que quieran con el software, siempre y cuando incluyan una copia del aviso de derechos de autor y la licencia en las distribuciones del software.
  * **Libertades**: Permite usar, modificar, y redistribuir el software, incluso en proyectos propietarios, sin la obligación de liberar las modificaciones.
  * **Aplicaciones**: Usada en proyectos populares como **Ruby on Rails**, **jQuery**, y **Node.js**.

#### 4. **Apache License**

* **Características principales**:
  * Es una licencia **permisiva**, similar a la MIT, pero con disposiciones adicionales relacionadas con patentes.
  * **Libertades**: Permite usar, modificar y redistribuir el software en proyectos tanto libres como propietarios. Sin embargo, obliga a incluir una copia de la licencia y mencionar cualquier cambio realizado.
  * **Cláusulas de patentes**: Protege a los contribuyentes de posibles demandas relacionadas con patentes por parte de usuarios del software.
  * **Aplicaciones**: Usada por proyectos como **Apache HTTP Server**, **Hadoop**, y **Android**.

#### 5. **BSD License (Berkeley Software Distribution)**

* **Versiones más comunes**: BSD de 2 cláusulas, BSD de 3 cláusulas.
* **Características principales**:
  * También es una licencia muy **permisiva**, similar a la MIT.
  * **Libertades**: Permite el uso, modificación y redistribución del software. No impone muchas restricciones, más allá de incluir la licencia original en el código distribuido.
  * Las versiones más antiguas, como la BSD de 4 cláusulas, tenían una **cláusula publicitaria** que fue eliminada en versiones posteriores.
  * **Aplicaciones**: Usada por sistemas operativos como **FreeBSD**, **OpenBSD**, y **NetBSD**.

#### 6. **MPL (Mozilla Public License)**

* **Características principales**:
  * Es una licencia de **copyleft débil**: permite que el software licenciado bajo MPL sea combinado con software propietario, pero las modificaciones al código cubierto por MPL deben mantenerse bajo MPL.
  * Es más permisiva que la GPL pero más restrictiva que la Apache o MIT.
  * **Libertades**: Permite usar, modificar y redistribuir el software, pero las modificaciones hechas a los archivos originales del software deben ser distribuidas bajo la MPL.
  * **Aplicaciones**: Usada en **Mozilla Firefox**, **Thunderbird**, y otros productos de Mozilla.

#### 7. **EPL (Eclipse Public License)**

* **Características principales**:
  * Es una licencia de **copyleft débil**, similar a la MPL.
  * **Libertades**: Permite usar, modificar y redistribuir el software, pero las modificaciones deben ser redistribuidas bajo la EPL. Sin embargo, permite la combinación de software EPL con componentes propietarios.
  * **Aplicaciones**: Usada por el proyecto **Eclipse** y otros proyectos relacionados con el desarrollo de software.

#### 8. **AGPL (Affero General Public License)**

* **Características principales**:
  * Basada en la GPL, pero añade una cláusula especial para el software que se ejecuta en servidores (como aplicaciones web).
  * **Copyleft fuerte**: Obliga a que cualquier modificación hecha al software, incluso si solo se ofrece como servicio (SaaS), deba ser liberada bajo la misma licencia AGPL.
  * **Aplicaciones**: Usada en proyectos como **Nextcloud** y **MongoDB** (antes de cambiar a la SSPL).

Estas licencias son las más comunes en el ecosistema del software libre y de código abierto, cada una con diferentes grados de libertad y requisitos para la distribución y modificación del software.

## Copyleft

**Copyleft** es un concepto relacionado con las licencias de software libre que garantiza que un software, y todas sus versiones modificadas o derivadas, permanezcan libres para que los usuarios lo utilicen, modifiquen y distribuyan bajo las mismas condiciones. En otras palabras, el copyleft asegura que las libertades otorgadas por la licencia original se mantengan en todas las versiones del software, incluso cuando alguien lo modifique o lo combine con otros proyectos.

#### ¿Cómo funciona el copyleft?

Cuando un software se licencia bajo una licencia **copyleft**, cualquier persona puede usar, modificar y redistribuir el software. Sin embargo, si esa persona redistribuye una versión modificada del software, está obligada a hacerlo bajo la misma licencia que la original. Esto significa que no pueden convertirlo en software propietario ni restringir las libertades que otorga la licencia original.

#### Ejemplo sencillo:

* Un desarrollador descarga un programa que está licenciado bajo la **GPL** (una licencia copyleft).
* El desarrollador puede modificar el programa según sus necesidades.
* Si el desarrollador distribuye su versión modificada (ya sea vendiéndola o compartiéndola gratuitamente), está **obligado** a proporcionar el código fuente de esa versión y licenciarlo bajo los mismos términos de la GPL. Esto garantiza que el software permanezca libre para futuros usuarios.

#### Tipos de copyleft:

* **Copyleft fuerte**: Obliga a que todas las modificaciones, derivados y extensiones del software se distribuyan bajo la misma licencia copyleft. Ejemplo: la **GPL** (General Public License). Esto también se aplica a cualquier programa que incorpore partes del software original.
* **Copyleft débil**: Permite que el software se combine o utilice con software no libre o propietario, siempre que ciertas partes, como las bibliotecas originales, permanezcan libres. Ejemplo: la **LGPL** (Lesser General Public License) o la **MPL** (Mozilla Public License). Esto es común en bibliotecas que se quieren usar en programas propietarios.

#### Diferencia entre copyleft y licencias permisivas:

* Las licencias **permisivas** (como MIT o BSD) permiten que el software se utilice en cualquier tipo de proyecto, incluyendo software propietario, sin la obligación de liberar el código fuente de las modificaciones.
* Las licencias **copyleft** requieren que cualquier trabajo derivado también se libere bajo la misma licencia, manteniendo así el software y sus versiones futuras libres.

#### Objetivo del copyleft:

El copyleft busca **proteger la libertad** de los usuarios asegurándose de que nadie pueda tomar el software, modificarlo, y luego hacer que las modificaciones sean propietarias o restringidas. Es una forma de garantizar que el software libre siga siendo libre, independientemente de quién lo modifique o cómo se distribuya.

#### Ejemplos de licencias copyleft:

* **GPL (General Public License)**: La licencia más famosa de copyleft fuerte.
* **AGPL (Affero General Public License)**: Una versión de la GPL que extiende el copyleft al software usado en servidores (aplicaciones web).
* **LGPL (Lesser General Public License)**: Un ejemplo de copyleft débil, común en bibliotecas que pueden ser usadas en software propietario.
