# 1. Markdown

## ¿Qué es Markdown?

Markdown es un lenguaje de marcado ligero que permite dar formato a documentos de texto de una forma sencilla, utilizando símbolos y caracteres especiales.

Se utiliza principalmente para crear archivos `README.md`, documentación, apuntes y explicaciones de proyectos.

Los archivos Markdown tienen la extensión `.md`.

## 1.1. Títulos

Para crear títulos se utiliza el símbolo `#`.

Cuantos más símbolos se utilicen, menor será el nivel del título.

**Ejemplo:**

```markdown
# Título principal
## Subtítulo
### Título de tercer nivel
#### Título de cuarto nivel
```

## 1.2. Texto en negrita y cursiva

- Para escribir en **negrita**, se utilizan dos asteriscos `**`.
- Para escribir en *cursiva*, se utiliza un asterisco `*`.
- Para escribir en ~~tachado~~, se utilizan dos virgulillas `~~`.

**Ejemplo:**

```markdown
**Texto en negrita**

*Texto en cursiva*

~~Texto tachado~~
```

## 1.3. Listas

Existen dos tipos principales de listas:

**Listas desordenadas:**

Se utiliza `-`, `*` o `+`.

```markdown
- Java
- Python
- C++
```

Resultado:
- Java
- Python
- C++

**Listas ordenadas:**

Se utilizan números seguidos de un punto.

```markdown
1. Instalar Java
2. Crear un proyecto
3. Ejecutar el programa
```

Resultado:
1. Instalar Java
2. Crear un proyecto
3. Ejecutar el programa

## 1.4. Enlaces

Para insertar un enlace se utiliza esta estructura:

```markdown
[Texto del enlace](URL)
```

**Ejemplo:**

```markdown
[Google](https://www.google.com)
```

## 1.5. Imágenes

Para insertar una imagen se utiliza:

```markdown
![Texto alternativo](ruta-de-la-imagen)
```

**Ejemplo:**

```markdown
![Logo de GitHub](imagenes/github.png)
```

El texto alternativo sirve para describir la imagen.

## 1.6. Código

Para escribir código dentro de una línea se utilizan acentos graves:

```markdown
Utilizamos `System.out.println()` para mostrar texto.
```

Para mostrar bloques de código se utilizan tres acentos graves y se puede indicar el lenguaje.

**Ejemplo:**

````markdown
```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hola mundo");
    }
}
```
````

## 1.7. Tablas

Las tablas se crean utilizando barras verticales `|` y guiones `-`.

**Ejemplo:**

```markdown
| Lenguaje | Tipo |
|---|---|
| Java | Programación |
| HTML | Marcado |
| CSS | Estilos |
```

Resultado:

| Lenguaje | Tipo |
|---|---|
| Java | Programación |
| HTML | Marcado |
| CSS | Estilos |

## 1.8. Citas

Para crear una cita se utiliza el símbolo `>`.

```markdown
> El código es una forma de resolver problemas.
```

Resultado:

> El código es una forma de resolver problemas.

## 1.9. Listas de tareas

Se utilizan corchetes para indicar tareas pendientes o completadas.

```markdown
- [x] Instalar Git
- [x] Crear una cuenta de GitHub
- [ ] Subir un proyecto
```

---
