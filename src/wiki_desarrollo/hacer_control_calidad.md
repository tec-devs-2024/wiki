# Cómo hacer control de calidad

Propietario: Diego Reséndiz Fernández
Etiquetas: Guías y procesos, Pruebas

> 💡 Esta plantilla explica el proceso de control de calidad necesario para desarrollar un software libre de errores.


# Filosofía de control de calidad

Escribe sobre tu método de control de calidad y por qué es fundamental para el éxito del producto. 

# Procesos

### Cambios en el código

- Controla las PR en detalle antes de solicitar una revisión.
- Incluye en la descripción de la PR los casos de prueba que seguiste para hacer el control.

### Revisión del código

- Si el cambio es sustancial y visible para el usuario, trabaja en un espacio aislado antes de implementar el cambio.
- Realiza controles de los casos (especialmente casos límite) que la persona que haya creado la PR pueda haber olvidado.

### Control de calidad

- Analiza la lista de elementos que se lanzarán el próximo día.
- Repasa los elementos de la lista uno a la vez y controla los cambios detalladamente.
