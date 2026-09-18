# Prueba técnica: Front End

Prueba técnica para candidatos a desarrollo front end en INUE Universidad.

## El encargo

Reconstruye la página de inicio de https://inue.edu.mx usando Astro.

No buscamos una copia pixel por pixel. La tipografía y las imágenes no tienen que ser las mismas: puedes usar fuentes parecidas e imágenes de relleno. Lo que sí debe coincidir es la composición, es decir, el orden de las secciones, la forma en que se acomodan los bloques dentro de cada una y el peso visual de cada elemento.

Revisa el sitio original con calma antes de escribir código. Es la única referencia y la fuente de verdad para cualquier duda de diseño.

## Secciones que debe tener la página

1. **Encabezado.** Fijo en la parte superior. Logo a la izquierda, navegación principal (Programas, Inglés, Acerca de, Campus en línea) y dos botones a la derecha (Contacto y Portal de alumnos). Programas abre un panel con los tres grupos de oferta educativa: Bachillerato, Licenciatura y Posgrado (Maestría y Doctorado).

2. **Portada.** Bloque negro con un título muy grande, un párrafo corto debajo y, al pie, una franja con cuatro accesos a los programas: Bachillerato y Licenciatura sobre amarillo, Maestría y Doctorado sobre negro, cada uno con su texto de apoyo y una flecha.

3. **Bloque institucional.** Columna de texto a la izquierda sobre negro (antetítulo, título en amarillo y un párrafo anclado al fondo de la columna) e imagen a la derecha.

4. **Lista de razones.** Título ancho y debajo cinco columnas numeradas del 01 al 05, separadas por líneas verticales, cada una con un ícono de trazo y una frase.

5. **Validez oficial.** Sección partida a la mitad: a la izquierda, sobre amarillo, título, dos párrafos, los logos de RVOE y SEP y un botón; a la derecha, una imagen que ocupa toda esa mitad.

6. **Logos de instituciones.** Fondo negro, título centrado con su bajada y dos hileras de logos que se desplazan de forma continua en sentidos opuestos.

7. **Preguntas frecuentes.** Acordeón a la izquierda con seis preguntas, la primera abierta y resaltada en amarillo; imagen a la derecha.

8. **Blog.** Fondo negro, título a la izquierda, botón "Ver todo" a la derecha y tres tarjetas con imagen, título, extracto y fecha.

9. **Formulario de contacto.** Título, párrafo de apoyo y un formulario de campos con línea inferior: nombre, correo, teléfono con prefijo de país, dos listas desplegables (programa y modalidad), mensaje y botón Enviar.

10. **Cierre.** Franja con una frase grande y un botón amarillo.

11. **Pie de página.** Queda detrás del contenido y se descubre conforme la página termina de recorrerse. Contiene los logos, los enlaces a redes sociales y el aviso de privacidad.

Solo se evalúa la página de inicio. Los enlaces pueden apuntar a rutas vacías o a ningún lado.

## Requisitos técnicos

- Astro 7, que es la versión mayor más reciente. No uses otro framework como base.
- Node 20 o superior.
- El estilizado es libre: Tailwind, CSS nativo, módulos de CSS o lo que domines.
- Puedes resolver el carrusel y el acordeón a mano o con la librería que prefieras.
- El formulario no necesita backend. Basta con que valide los campos y muestre un estado al enviarse.
- `npm install` y `npm run dev` deben funcionar en una máquina limpia, sin pasos manuales extra.

## Entrega

1. Un repositorio público en tu cuenta de GitHub, con historial de commits. Evita subir todo en un solo commit.
2. El sitio desplegado en Railway, público y accesible sin contraseña. Railway da crédito de prueba suficiente para este ejercicio.
3. Un README propio en tu repositorio donde expliques cómo levantar el proyecto y qué decisiones tomaste.
4. Manda los dos enlaces a inue.developer@inue.edu.mx con el asunto "Prueba técnica front end" y tu nombre.

Tu reclutador te indicará la fecha límite de entrega.

## Cómo se evalúa

Revisamos el sitio desplegado en el navegador y el código del repositorio. Pesan qué tan fiel es la composición al original, cómo está organizado el proyecto y la calidad general de la implementación.

No damos una lista de puntos a cubrir. Parte de lo que se evalúa es tu criterio para decidir qué hace bueno a un sitio.

## Dudas

Si algo del encargo no queda claro, escribe a inue.developer@inue.edu.mx. Preguntar no resta puntos.
