# SmartWarehouse Web — Programación Avanzada 2.º DAM

Aplicación didáctica 100 % cliente con HTML, CSS y JavaScript puro. No necesita instalar paquetes ni arrancar un servidor.

## Cómo ejecutarla

Abre `index.html` en un navegador moderno. El inventario inicial está integrado en `app.js`; también se proporciona `inventario.json` para importarlo mediante el botón **Importar JSON**. Las modificaciones se guardan en `localStorage` y se pueden exportar a un archivo JSON. El navegador no sobrescribe automáticamente el archivo original.

## Fases para el alumnado

1. **Divide y vencerás**: implementar `maxDyV` para encontrar el producto de mayor peso.
2. **Ordenación**: implementar `mergeSort` por código.
3. **Búsqueda**: implementar `binarySearch` sobre el inventario ordenado.
4. **Elemento mayoritario**: implementar `majorityCandidate` y verificar que supera el 50 %.
5. **Backtracking**: implementar `exact` para maximizar el peso utilizado sin superar la capacidad.
6. **Heurística greedy**: implementar `greedy` ordenando por peso descendente.
7. **Búsqueda local**: implementar `localSearch` y comparar resultados.

## Caso de prueba

Con productos de pesos 8, 7 y 6 kg, y una caja de 13 kg, el algoritmo voraz utiliza 8 kg, mientras que backtracking encuentra 7 + 6 = 13 kg.

## Precauciones

El algoritmo exacto tiene complejidad exponencial y se limita a 22 productos para evitar bloquear el navegador. Los tiempos de ejecución son orientativos. Los datos importados se validan y los nombres de productos se escapan al mostrarse en HTML.

## Propuesta de entrega

Para cada fase, pedir: código, explicación del algoritmo, captura de ejecución y comparación de resultados. En el RA3, añadir la clasificación de las heurísticas y justificar cuándo elegir una solución aproximada frente a la exacta.
