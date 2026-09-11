# Algoritmo AQ - Inducción de Reglas de Clasificación

Este proyecto contiene una implementación en Python del **Algoritmo AQ** orientado a la inducción de reglas lógicas a partir de ejemplos positivos y negativos.

## Descripción

El algoritmo analiza una serie de atributos para generar una regla conceptual que identifique una clase objetivo (en este caso, la predisposición a adquirir un automóvil eléctrico o si se trata de un socio activo o no).

### ¿Cómo funciona?
1. **Atributos**: Identifica las características de los datos (`edad`, `ingreso`, `tiene_garaje`, `distancia_trabajo`).
2. **Comparación**: Contrata los valores presentes en el conjunto de ejemplos `positivos` frente al conjunto de `negativos`.
3. **Selección de atributos**: Aísla aquellos valores que aparecen exclusivamente en la clase positiva.
4. **Inducción**: Construye el conjunto final de condiciones de la regla.
