# MARKDOWN
_El uso de markdown para la documentacion académica y técnica_
### ¿Qué es markdown?
Markdown es un lenguaje de marcado ligero creado por John Gruber y Aaron Swartz en 2004. Su objetivo principal es permitir que las personas escriban utilizando un formato de texto plano fácil de leer y de escribir, el cual se puede convertir de forma limpia en HTML estructurado. 

A diferencia de los procesadores de texto tradicionales (como Microsoft Word), donde usas una interfaz visual (WYSIWYG), en Markdown utilizas caracteres simples (como asteriscos o almohadillas) para dar formato al texto. 
### ¿Por qué se considera un lenguaje de marcado ligero? 
Se le llama "ligero" en comparación con lenguajes de marcado más complejos y robustos como HTML o XML. 
* __Sintaxis minimalista__: Utiliza caracteres comunes del teclado que no ensucian la lectura del documento original. Un archivo .md es perfectamente legible para un humano incluso si no está renderizado.
* __Curva de aprendizaje baja__: Se puede aprender en menos de 10 minutos.
* __Sin etiquetas de cierre complejas__: En lugar de escribir \<h1\>Título</h1\> (HTML), solo escribes # Título. 
### ¿Dónde se usa Markdown en ingeniería de software? 
Markdown es el estándar de facto en la industria del software para la documentación técnica gracias a su compatibilidad con sistemas de control de versiones como Git. Se utiliza principalmente en: 
Archivos README: El archivo de presentación obligatorio en repositorios de GitHub, GitLab o Bitbucket para explicar de qué trata un proyecto y cómo instalarlo. 

* __Documentación de APIs y código__: Plataformas como Read the Docs, Swagger, o generadores de sitios estáticos (Docusaurus, Hugo) se alimentan de Markdown. 
* __Plataformas de colaboración__: En los comentarios de Jira, issues de GitHub, mensajes de Slack or Microsoft Teams para dar formato al texto o compartir fragmentos de código. 
* __Plataformas de blogging técnico__: Sitios como Dev.to, Hashnode y Medium lo soportan de forma nativa.

### Encabezados o títulos
Se crean utilizando el símbolo de almohadilla (#). El número de almohadillas indica el nivel del encabezado (del 1 al 6). 

### Párrafos y saltos de línea 

* __Párrafos__: Se crean simplemente escribiendo texto normal. Para separar un párrafo de otro, debes dejar una línea en blanco. 
* __Saltos de línea__: Si quieres dar un salto de línea simple (sin crear un nuevo párrafo), debes dejar dos espacios en blanco al final de la línea y presionar Enter. 

### Negrita, cursiva y texto combinado 

Para dar estilo al texto, utilizas asteriscos (*) o guiones bajos (_). 
_Un (*) para cursiva_
__Dos (*) para negrita__
___Tres (*) para texto combinado___

### Listas ordenadas y no ordenadas 

+ __Listas no ordenadas (con viñetas)__: Puedes usar asteriscos (*), guiones (-) o signos de más (+). 
+ __Listas ordenadas (numeradas)__: Se utilizan números seguidos de un punto. Curiosamente, Markdown indexa automáticamente, por lo que puedes usar el número 1. para todos los elementos si lo deseas. 
