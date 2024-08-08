# Comandos útiles

Propietario: Diego Reséndiz Fernández
Etiquetas: Guías y procesos, Repositorio

<aside>
💡 Comandos más frecuentes. ****Agregar esta página a la [barra de favoritos](https://www.notion.so/es-la/help/navigate-with-the-sidebar) puede ser útil para tu equipo.

</aside>

# 🚚 Ejecución local

En el directorio de `acme`, ejecuta: 

```bash
acme run --local
```

Para acceder a una lista con todas las opciones, usa:

```bash
acme --help
```

Para ejecutar la comprobación de tipos en toda la base de código, ejecuta:

```bash
acme typecheck
```

# 🚢 Implementación

Al hacer una implementación en la fase de prueba o producción, ejecuta los siguientes servidores de implementación:

```bash
acme deploy --staging 
```

Reemplaza `--staging` por `--prod` si la implementación es en producción.