# TAREA LMSGI JSON vs YAML
![Imagen de encabezado](https://needone.app/content/images/size/w1000/2022/12/yaml-vs-json.png)

# Objetivos

- [x] Crear repositorio público github
- [x] Buscar información sobre YAML
- [x] Buscar información sobre JSON
- [x] Elaborar un comparativo con los datos mas importantes

# Documentación sobre YAML y JSON

## YAML [^1]

### Descripción

YAML es un formato de serialización de datos que las personas pueden comprender y fácil de escribir (YAML no es un lenguaje de marcas). A menudo se utiliza para la configuración de aplicaciones y archivos de datos donde es esencial que sea legible y entendible. 

### Características Principales

- **Legible por humanos:** YAML utiliza un formato indentado para representar la estructura de datos, lo que lo hace fácilmente legible para los humanos.

- **Sintaxis simple:** La sintaxis de YAML es simple y concisa, lo que facilita la creación y edición manual de archivos YAML.

- **Soporte para estructuras complejas:** YAML admite listas, diccionarios y tipos de datos anidados, lo que lo hace adecuado para representar estructuras de datos complejas.

- **Extensibilidad:** Puede definir tipos de datos personalizados y utilizarlos en documentos YAML.

### Ejemplo Básico yaml

```yaml

nombre: Jose Fajardo

edad: 35

ciudad: Valencia

intereses:

  - Automocion

  - Informatica

```

## JSON [^2]

### Descripción

JSON es un formato de intercambio de datos ligero y fácil de leer. Se utiliza comúnmente para transmitir datos entre un servidor y una aplicación web, usualmente se emplea como alternativa a XML. Aunque su nombre incluye "JavaScript," JSON es un formato independiente de cualquier lenguaje de programación.

### Características Principales

- **Fácil de entender:** La estructura de JSON es simple y fácil de entender, lo que facilita la lectura y escritura de datos.

- **Soporte para tipos de datos:** JSON admite tipos de datos como cadenas de texto, números, booleanos, listas y objetos anidados.

- **Independiente del lenguaje:** Puede ser utilizado con cualquier lenguaje de programación debido a su simplicidad y universalidad.

- **Utilizado en la web:** JSON es comúnmente utilizado para intercambiar datos entre el servidor y las aplicaciones web, ya que puede ser fácilmente interpretado por los navegadores web.

### Ejemplo Básico json

```json

{
  "nombre": "Jose Fajardo",
  "edad": 35,
  "ciudad": "Valencia",
  "intereses": [
    "Automocion",
    "informática"
  ]
}

```

> [!IMPORTANT]
> ## Conclusión
>Tanto YAML como JSON son formatos de serialización de datos para el intercambio de los mismo legibles por el ser humano. La elección entre ellos depende de las preferencias y requisitos específicos del proyecto. Ambos son ampliamente utilizados en el desarrollo de software y la transmisión de datos en la web.

[^1]: Su nombre es un acrónimo que significa "YAML Ain't Markup Language".
[^2]: Su nombre es un acrónimo que significa JavaScript Object Notation.
