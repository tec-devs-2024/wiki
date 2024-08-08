# Revisiones de código

Propietario: Diego Reséndiz Fernández
Etiquetas: Repositorio

> 💡 Esta plantilla documenta el proceso para hacer revisiones de código. Esta información sirve para que los nuevos integrantes del equipo y quienes trabajan a distancia estén bien informados.


# Filosofía

¿Por qué hacen revisiones de código? ¿Cuáles son las directrices a seguir para hacer estas revisiones?

Tal vez podrías mencionar otras páginas aquí, como las directrices de desarrollo. Para incluir el enlace a otra página, escribe `@` seguido del nombre de la página: [Directrices de desarrollo](./directrices_desarrollo.md)

# Preparar el código para la revisión

La preparación asegura que los revisores puedan hacer un buen trabajo.

### Mensajes de commit

Asegúrate de que los mensajes de commit sean descriptivos.

### Descripción de PR en Github

Tus descripciones de PR deberían ser continuaciones de los mensajes de commit. Escribe sobre los cambios del commit y sobre cómo se los implementó.

# Llevar a cabo la revisión

### Cómo hacer la revisión

- Revisa el PR dos veces si es demasiado largo.
    - La primera vez, intenta familiarizarte con el cambio del código a nivel global.
    - La segunda vez, préstale más atención a los detalles semánticos.

# Ejemplos

```jsx
var contadorComentarios = 0;
```

Puedes sugerir que esto sea un `let` en lugar de `var`.
