## Objetivo
Este repositorio documentará mi proceso de aprendizaje de desarrollo web desde los fundamentos hasta la creación de aplicaciones Full Stack.

Actualmente estoy comenzando desde conocimientos básicos, por lo que el objetivo no es solamente completar cursos o tutoriales, sino construir una base sólida y aprender mediante:

- Teoría
- Ejercicios
- Proyectos
- Git
- GitHub
- Issues
- Pull Requests
- Documentación
- Evidencia de aprendizaje

La meta es que cada tema aprendido quede documentado y acompañado de código que demuestre lo aprendido.

---
## Ruta de aprendizaje
La ruta general definida es:
![[roadmap.png]]
Git y GitHub también se utilizarán desde el principio, aunque su estudio formal aparezca más adelante en el roadmap.

---
## GitHub Project
Para organizar todo el aprendizaje se creó un GitHub Project llamado:
***WebDevelopmentRoadmap***

El project está vinculado al repositorio:
***web-development-learning***

La finalidad del Project es visualizar el avance del roadmap y tratar cada tema como una tarea real de desarrollo.

---
## Estados del Project
Se definieron cinco estados principales.

### Backlog
Contiene todas las tareas que foman parte del readmap pero que todavía no corresponde trabajar.
No significa que una tarea no sea importante.
**Significa:**
	Existe dentro del roadmap, pero todavía no es momento de trabajar en ella.

### ToDo
Contiene las tareas que están preparadas para comenzar próximamente.
Normalmente habrá muy pocas tareas en este estado.
**Significa:**
	Esta es la siguiente tarea que debo realizar.

### In Progress
Indica que la tarea se está trabajando actualmente.

### Review
La implementación o ejercicio ya fue realizado, pero todavía debe revisarse.
**Aquí comprobaré cosas como:**
- Que entiendo el tema
- Que el código funciona
- Que cumplí los criterios de Issue
- Que puedo explicar lo realizado
- Que el código está correctamente documentado
También será el momento de revisar el Pull Request antes de fusionarlo con main.

### Done
La tarea está completamente terminada.
Para llegar aquí no basta con haber leído la teoría.
Debo haber **cumplido los criterios establecidos en la Issue correspondiente**.

### El flujo completo es:
```
Backlog -> ToDo -> In progress -> Review -> Done
```

---
## GitHub Issues
Cada tema del roadmap fue convertido en un GitHub Issue.
Una Issue representa una tarea concreta de aprendizaje.

Por ejemplo:
```
HTML - Entender la estructura básica de un documento
```
Cada Issue contiene principalmente tres secciones.

### Objetivo
Describe qué debo aprender al completar la tarea.

Por ejemplo:
```
Entender cómo está estructurado un documento HTML y para qué sirven sus elementos principales.
```

### Temas
Define los conceptos principales que se estudiarán.

Por ejemplo:
```
<!DOCTYPE html>
<html>
<head>
<body>
<title>
<meta>
```

### Criterios para terminar
Son condiciones que debo cumplir antes de considerar terminada la Issue.

Por ejemplo:
```
- [] Entiendo para qué sirve cada elemento.
- [] Puedo crear un documento HTML básico desde cero.
- [] Puedo explicar la diferencia entre head y body.
- [] Realicé al menos un ejercicio usando esta estructura.
```
Esto evita marcar una tarea como terminada únicamente por haber visto un tutorial.

---

## Organización del repositorio
Las tecnologías no utilizarán ramas permanentes, en su lugar se utilizarán carpetas.

La estructura crecerá de esta forma:
```
web-development-learning/
	│
	├─ html/
	├─ css/
	├─ javascript/
	├─ dom/
	├─ http/
	├─ api/
	├─ react/
	├─ typescript/
	├─ backend/
	├─ sql/
	├─ full-stack/
	├─ deployment/
	├─ security/
	└─ clean-code/

```
Cada carpeta contendrá ejercicios y proyectos relacionados con esa tecnología.

Por ejemplo:
```
html/
├─ 01-document-structure/
├─ 02-text-headings/
├─ 03-links/
└─ ...
```

---

## Organización de branches
Las ramas representarán trabajos concretos y serán temporales.

No se crearán ramas permanentes como:
```
html
css
javascript
react
```
en su lugar se utilizarán ramas como:
```
html/01-document-structure
html/02-text-headings
html/03-links

css/01-selectors
css/02-colors-typography

javascript/01-running-javascript
javascript/02-variables
```
Cada rama estará relacionada con una Issue específica.
Cuando el trabajo termine, se integrará a main.

---

## Main
La rama main representará el estado oficial y estable del aprendizaje completado.
Solamente contendrá trabajo que ya haya sido revisado y terminado.

Conceptualmente:
```
main
│
├─ HTML completado
├─ CSS completado
├─ JavaScript completado
└─ ...
```
Con el tiempo, main se convertirá en un registro completo de todo lo aprendido.

---

## Flujo de trabajo por lección
Cada lección seguirá aproximadamente este proceso:
```
1. Seleccionar una Issue
2. Moverla de ToDo a In Progress
3. Crear una branch
4. Estudiar el tema
5. Escribir código
6. Realizar ejercicios
7. Documentar lo aprendido
8. Crear commits
9. Push a GitHub
10. Crear Pull Request
11. Mover Issue a Review
12. Revisar criterios
13. Merge a main
14. Eliminar branch
15. Mover Issue a Done
```

---

## Evidencia de aprendizaje
Cada lección deberá dejar alguna evidencia dentro del repositorio.
Dependiendo del tema podrá inluir:
- Código
- Ejercicios
- README
- Explicaciones
- Mini proyectos
- Proyectos completos
- Capturas
- Notas técnicas

Ejemplo:
```
html/
└─ 01-document-structure/
	├─ index.html
	└─ README.md
```
El index.html contiene la práctica.
El README.md explica qué aprendí.
La intención es evitar un repositorio únicamente de notas teóricas.
El código debe mostrar el aprendizaje.

---

## Objetivo final
Al finalizar este roadmap quiero ser capaz de:
- Crear interfaces web desde cero
- Comprender HTML y CSS correctamente
- Programar utilizando JavaScript
- Manipular el DOM
- Consumir APIs
- Crear aplicaciones con React
- Utilizar TypeScript
- Desarrollar backends
- Diseñar y consultar bases de datos
- Construir aplicaciones Full Stack
- Desplegar aplicaciones
- Aplicar principios básicos de seguridad
- Utilizar Git y GitHub profesionalmente
- Documentar mis proyectos
- Construir un portafolio con proyectos reales
Este repositorio funcionará como evidencia del proceso completo de aprendizaje.