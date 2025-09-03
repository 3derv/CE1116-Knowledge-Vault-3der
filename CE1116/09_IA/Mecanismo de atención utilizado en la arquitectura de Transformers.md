---
Fecha de creación: 2025-09-02 19:09
Fecha de Modificación: 2025-09-02 19:09
tags:
  - IA
Tema: inteligencia-artificial
---


## 📚 Idea/Concepto 
Los mecanismos de atención en transformadores es un proceso que permite al modelo enfocarse en las palabras más relevantes del contexto, poseen dos vectores principales que son proyecciones lineales de los embeddings, el vector de querys (Q) y keys (k) que interactúan entre ellas con producto punto escalado (normalizado)  para medir la similitud sobre el cual  se aplica la función softmax , luego en la matriz de valores (V) se suman ponderadamente estos valores para obtener  los pesos de atención. Esta atención es se divide en múltiples cabezas de atención que trabajan en paralelo, cada uno se enfoca en cierto tipo de relaciones en el texto y este usa una red feed forward que procesa cada token independientemente para profundizar el entendimiento semántico. Los embeddings también incorporan codificaciones posicionales para incluir información sobre el orden de los tokens

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[ ]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 