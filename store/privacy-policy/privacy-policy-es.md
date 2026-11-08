# Política de privacidad — Hilitely

**Última actualización:** 8 de noviembre de 2026

Esta política describe cómo trata la información la extensión **Hilitely** para Chrome y Firefox («la Extensión»).

## Quién ofrece la Extensión

La Extensión la publica **PeterShift**.
Contacto: **petershift.dev@gmail.com**

## Qué hace la Extensión

En un sitio que actives, la Extensión resalta un fragmento que selecciones y vuelve a encontrar ese resaltado después de recargar o de un cambio en la página, por las palabras y no por su lugar en el diseño. Las notas, las etiquetas y la biblioteca de citas se quedan en este equipo.

## Qué guarda la Extensión

Cuando resaltas texto, la Extensión guarda un registro en tu equipo:

- el texto citado y unos 100 caracteres antes y después, para poder encontrar el resaltado otra vez;
- la dirección de la página, su dirección canónica si la página declara una, y el título de la página;
- el color, y la nota y las etiquetas si las escribes;
- cuándo se creó y se modificó el resaltado, y si se encontró en la página la última vez.

Los ajustes también se quedan en este equipo: el último color elegido, si el cursor se coloca en el campo de la nota, cómo ordena la biblioteca los sitios y qué sitios activados desactivaste.

## Adónde van los datos

A ninguna parte. Los resaltados permanecen en el navegador, en la base de datos propia de la Extensión en este equipo. La Extensión no tiene servidor, ni cuenta, ni analítica. No hace peticiones de red. Nosotros no recibimos tus resaltados, tus notas ni las direcciones de las páginas que lees.

## Qué sitios puede leer

La Extensión no pide leer todos los sitios. Solo funciona en los sitios que activas desde el icono de la barra, de uno en uno, mediante el diálogo de permisos del navegador. En Chrome, un host en un puerto no estándar es un sitio aparte. En Firefox, el permiso de un host cubre ese host en cualquier puerto. Hasta que lo hagas, no añade nada a la página.

Desactivar un sitio lo pone en pausa. Los resaltados desaparecen de las pestañas abiertas de ese sitio, y el script no vuelve a iniciarse allí hasta que lo actives de nuevo. El permiso del navegador se conserva, así que volver a activarlo no pide permiso otra vez. «Remove access to this site» retira el permiso. La próxima vez que actives ese sitio, el navegador volverá a preguntar. Las citas guardadas siguen en la biblioteca en ambos casos.

## Copias de seguridad

El archivo de copia se crea solo cuando eliges Download backup. Se guarda donde el navegador guarda las descargas. La importación lee un archivo que eliges tú. Ninguno de los dos se envía a ninguna parte.

## Eliminar tus datos

Elimina un resaltado desde la página o desde la biblioteca, o usa Delete all on this site en la biblioteca. Quitar la Extensión borra todos sus datos locales con la limpieza habitual del navegador.

## Permisos

| Permiso | Por qué se solicita |
| --- | --- |
| `storage` | Guarda ajustes en este equipo: el último color de resaltado, si el cursor se coloca en la nota, qué sitios activados desactivaste y cómo ordena la biblioteca los sitios. Las citas están en la base de datos propia de la Extensión; este permiso no las guarda. |
| `activeTab` | Cuando pulsas el icono de la barra, la ventana lee la dirección de la pestaña actual para mostrar el interruptor de ese sitio y recorrer los resaltados de la página. |
| `scripting` | Inicia el resaltado en la pestaña actual justo después de activar el sitio, y en las pestañas de ese sitio que ya están abiertas, sin recargar la página. Al desactivar el sitio, quita los resaltados de esas pestañas. |
| Acceso a sitios | No se concede al instalar. El navegador pide un sitio cada vez, la primera vez que lo activas. En Chrome, un host en un puerto no estándar es un sitio aparte. En Firefox, el permiso de un host cubre ese host en cualquier puerto. El resaltado solo funciona en los sitios que permitiste y no desactivaste. Desactivarlo lo detiene allí y conserva el permiso. «Remove access to this site» lo retira. |

## Código remoto

La Extensión solo ejecuta los archivos locales incluidos en el paquete. No descarga ni ejecuta JavaScript remoto.

## Uso limitado

Los datos se usan solo para volver a mostrar tus resaltados y enumerarlos en la biblioteca. No se venden, no se ceden a nadie, no se usan para publicidad ni para valorar la solvencia, y nadie los lee. Este uso cumple la Chrome Web Store User Data Policy (https://developer.chrome.com/docs/webstore/program-policies/limited-use), incluidos los requisitos de Limited Use.

## Cambios

Si una versión posterior empieza a enviar datos a alguna parte, esta política lo dirá antes de que salga esa versión, y la Extensión te lo preguntará primero.

## Contacto

Preguntas sobre esta política: **petershift.dev@gmail.com**
