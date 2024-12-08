## 📘 Guía para escribir en Markdown

Básicos de Markdown
Títulos: Usa # para títulos grandes. Más # para subtítulos.

Ejemplo:
# Título 1
## Título 2
### Título 3

Negritas y cursivas:
Negritas: **texto** → texto

Cursiva: *texto* → texto
Negritas y cursivas: ***texto*** → texto

Listas:

Lista ordenada:
1. Elemento 1
2. Elemento 2
3. Elemento 3
4. 
Lista desordenada:
- Elemento 1
- Elemento 2
  
Enlaces: [Texto](URL)
Ejemplo:
[Google](https://www.google.com)

Imágenes:

1. Si la imagen está en la misma carpeta que tu archivo .md:
![Descripción de la imagen](imagen.png)
Esto mostrará la imagen directamente en la página.

2. Si la imagen está en una subcarpeta llamada imagenes:
![Descripción de la imagen](imagenes/imagen.png)

3. Puedes ajustar el tamaño de la imagen usando HTML dentro del Markdown:
<img src="imagenes/imagen.png" alt="Descripción de la imagen" width="300" />
Esto cambia el ancho de la imagen a 300 píxeles, manteniendo la proporción.

Avanzado
Tablas:
| Columna 1 | Columna 2 |
|-----------|-----------|
| Dato 1    | Dato 2    |

Citas:
> Esto es una cita.
> 
Código:
En línea: `código`

Bloques de código:
```lenguaje

