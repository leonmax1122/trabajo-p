## 2. Descripción del Árbol DOM (Estructura de mi página)

El Árbol DOM es la forma en que se organizan las etiquetas una dentro de otra (Jerarquía). Para mi tarjeta personal (proyecto_final_clase.html), la estructura quedó así:

* **html**: Es la etiqueta raíz (la que envuelve todo).
    * **head**: Contiene la configuración de la página (no se ve).
    * **body**: Es el padre de todo el contenido visible.
        * **main**: Es el hijo principal de body.
            * **article**: Es el hijo de main. Representa mi tarjeta completa.
                * **header**: Es hijo de article. Aquí puse mi nombre y grado.
                * **section**: Es hijo de article y hermano de header. Aquí puse mi descripción.
                * **aside**: Es hijo de article y hermano de los anteriores. Aquí puse mi contacto.
                    * **address**: Es el hijo de aside (aquí está mi correo).
        * **footer**: Es hermano de main y contiene el cierre de la página.