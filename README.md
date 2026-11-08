# ANODEFLEX_4N_8R_1INY_CAL_1X4_Beta

Aplicación Beta para calibrar 8 ramas en 4 nodos mediante tensiones de fuente y de nodo y corrientes medidas con los reóstatos en 0 Ω. Las tensiones deben medirse respecto a una misma referencia.

La medición A comprende los nodos 1 a 4. Cada Rc es la caída de tensión en el tramo dividida por la corriente de ese tramo. Cada resistencia fija es la tensión del nodo dividida por la corriente de la rama. Se rechazan tensiones crecientes aguas abajo.

Una sola fuente alimenta los 4 nodos en regulación. El voltaje de trabajo es independiente de los voltajes de medición. La aplicación permite ajustar los reóstatos, exportar e importar casos e imprimir resultados.

Ejecute `node tests/model.test.js`, `node tests/static.test.js` y `node tests/app.test.js`.

En regulación, ingrese una corriente común y pulse «Aplicar a las 8 ramas». Después puede cambiar cada objetivo individualmente. El ajuste asistido calcula la tensión mínima y reemplaza los valores de los reóstatos.
