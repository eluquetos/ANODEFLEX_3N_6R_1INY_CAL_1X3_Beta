# ANODEFLEX_3N_6R_1INY_CAL_1X3_Beta

Aplicación para calibrar seis ramas distribuidas en tres nodos, con dos ramas por nodo y una inyección. Ingrese el voltaje de fuente, V1 a V3 y las seis corrientes medidas con los reóstatos en 0 Ω. Las tensiones deben tener la misma referencia. La aplicación calcula Rc1 a Rc3 mediante las caídas de tensión y las resistencias fijas mediante las corrientes de rama.

En regulación, una fuente alimenta los tres nodos en serie. Puede aplicar una misma corriente objetivo a las seis ramas y calcular el ajuste de tensión mínima. Los casos se pueden exportar e importar.

Ejecute `node tests/model.test.js`, `node tests/static.test.js` y `node tests/app.test.js`. GitHub Pages publica la carpeta `docs`.
