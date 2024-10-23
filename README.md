### Ejemplo 4.5.2

Trabajemos en el sistema de dos partículas más simple y no trivial: cada partícula solo puede estar en dos puntos. Consideremos el estado

$$
|\psi\rangle = |x_0\rangle \otimes |y_0\rangle + |x_1\rangle \otimes |y_1\rangle. \tag{4.103}
$$

Para aclarar lo que se deja fuera, podríamos escribir esto como

$$
|\psi\rangle = 1|x_0\rangle \otimes |y_0\rangle + 0|x_0\rangle \otimes |y_1\rangle + 0|x_1\rangle \otimes |y_0\rangle + 1|x_1\rangle \otimes |y_1\rangle. \tag{4.104}
$$

Veamos si podemos escribir \( |\psi\rangle \) como el producto tensorial de dos estados provenientes de los dos subsistemas. Cualquier vector que represente la primera partícula en la línea se puede escribir como

$$
c_0 |x_0\rangle + c_1 |x_1\rangle. \tag{4.105}
$$

De manera similar, cualquier vector que represente la segunda partícula en la línea se puede escribir como

$$
c_0 |y_0\rangle + c_1 |y_1\rangle. \tag{4.106}
$$

Por lo tanto, si \( |\psi\rangle \) proviniera del producto tensorial de los dos subsistemas, tendríamos

$$
(c_0 |x_0\rangle + c_1 |x_1\rangle) \otimes (c_0 |y_0\rangle + c_1 |y_1\rangle) = c_0 c_0 |x_0\rangle \otimes |y_0\rangle + c_0 c_1 |x_0\rangle \otimes |y_1\rangle + c_1 c_0 |x_1\rangle \otimes |y_0\rangle + c_1 c_1 |x_1\rangle \otimes |y_1\rangle.
$$

### Conclusiones

1. **Estructura del Estado Cuántico**: El estado \( |\psi\rangle \) se puede expresar como una combinación lineal de productos tensoriales de estados de partículas individuales.

2. **Importancia del Producto Tensorial**: Esto resalta la naturaleza del sistema cuántico, donde las propiedades de las partículas no son independientes, y el estado total es una combinación de las contribuciones de cada subsistema.

3. **Amplitudes de Probabilidad**: La representación muestra que cada estado individual está asociado con coeficientes \( c_0 \) y \( c_1 \), que representan las amplitudes de probabilidad de cada estado, fundamentales en la mecánica cuántica.

4. **Indeterminación Cuántica**: La forma del estado refleja la indeterminación inherente de los sistemas cuánticos, donde el resultado de una medición no se determina hasta que se realiza.

5. **Relevancia en Computación Cuántica**: La comprensión de cómo estos estados se combinan es esencial para aplicaciones en computación cuántica, donde las propiedades de superposición y entrelazamiento ofrecen ventajas computacionales.
