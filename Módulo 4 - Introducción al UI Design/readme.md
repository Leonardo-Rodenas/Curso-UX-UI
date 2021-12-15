<center>

# **Curso UX/UI Design - Nuclio**
#### Leonardo Rodenas E.
</center>

---

<center>

## **Temario**

</center>

4. Introducción al UI Design
    4.1 [Bases y leyes principales de diseño](#id1)
    4.2 [¿Qué es un Design System y para qué sirve?](#id2)
    4.3 [Componentes y variantes en Figma](#id3)
    4.4 [Componentes y variantes en Figma (práctica)](#id4)
  

## **3. Introducción al UI Design**

<div id='id1'>
### **4.1 Bases y leyes principales de diseño:**<a name="id1"></a>

**UI - Interfaz de Usuario:** Lo que el usuario ve. Es la representación visual de aquellas decisiones acordes a las necesidades y funcionalidades. Adaptando los elementos visuales a la marca del producto o servicio.

|UX|UI|
|--|--|
|Que siente mientras interactua|Con lo que Interactua|
<br>

**Principios de diseño visual:** No existen verdades absolutas, pero si estudios del comportamiento humano, patrones que nos ayudan a comunicarnos con el usuario de manera efectiva.

<center>

![pepsi](https://i.imgur.com/73JYR4Q.png)
Leemos Pepsi, pero... ¿Vemos Coca-Cola no?, el poder del diseño del branding

</center>

**Paleta de color:** Tener en cuenta colores principales, secundarios, neutros y auxiliares (Ej: Banco, colores principales azul-negro, secundarios 3 variaciones en claro - oscuro de los principales, neutro una escala de grises y auxiliares rojo para algo falló/error y verde para algo correcto/exitoso).

**Jerarquía:** La jerarquización de textos sirve para definir el orden de la lectura  en la interfaz, guiando al usuario y permitiéndole hacer un escaneo rápido del contenido de cada página.

<center>

![nociones de diseño](https://i.imgur.com/vUMeFet.png)

</center>

**Familia Tipográfica:** Escoger una que se lea bien en pantalla, especialmente en espacios pequeños.

**Tips para elegir tipografía:**

- Define el tono de proyecto.
- Con serifa (clásico), sin serifa (moderno).
- Definir escala y jerarquías
- Legibilidad.
- Una sola fuentes mantiene las cosas simples.
- **Ojo:** Según Leo, letra Roboto siempre es buena :D.

**Layout:** Permite tomar decisiones de una manera coherente y escalable. Tomar en cuenta tamaño de pantallas y propiedades escalables para vista del usuario y trabajar con la "regla del 8" (usar múltiplos de 8 para definir dimensiones, espaciamiento y margen de elementos).

**Leyes principales de diseño:**

Se basan en principios psicológicos y de percepción de los usuarios que os ayudarán a tomar decisiones de diseño y a argumentar vuestras propuestas.

**Principios de la GESTALT:**

1. La proximidad.
2. Principio de similitud.
3. Principio de continuidad.
4. Principio de igualdad.
5. Relación figura-fondo.
6. Dirección común.
7. Principio de cierre. 

**Las 10 heurísticas de Nielsen:**

1. Visibilidad del estado del sistema.
2. Relación sistema / mundo real.
3. Control y libertad del usuario.
4. **Consistencia y estándares**
5. Prevención de errores.
6. Reconocimiento antes que recuerdo.
7. Flexibilidad y eficiencia de uso.
8. **Estética minimalista en el diseño**
9. Ayudar a diagnosticar y solucionar errores.
10. Ayuda y documentación.

**Ley de UI - Efecto de la Usabilidad Estética (Aesthetic Usability Effect):**

Los usuarios a menudo perciben un diseño "estéticamente agradable" como un diseño más usable. A raíz de esto, una buena UI puede hacer que los usuarios sean más tolerantes a problemas menores de usabilidad. Crea uan respuesta positiva en el cerebro de las personas y las lleva a creer que el diseño realmente funciona mejor. Total... que la gente tiende a creer que las cosas que se ven mejor funcionarán mejor.

**Principios de diseño visual:**

1. **Contraste:** Diferencia entre cosas.
2. **Proximidad:** Relación entre elementos.
3. **Jerarquía:** Orden de importancia.
4. **Alineación:** Relación de elementos con los que le rodean. 

**Mobile First Design:**

Los celulares son prácticos, pero hay que hacer que su navegación sea especialmente pensada para ellos, por ende, las **ventajas** de una navegación optimizada a móvil son: priorización de contenidos, más atención a la arquitectura de información, usabilidad y accesibilidad y optimización de web.

**Responsive Design:** 

Este concepto fue creado con el objetivo de adaptar las páginas web a las pantallas más pequeñas (tablet, móvil, etc) sin necesidad de tener que invertir en aplicaciones nativas. Las **ventajas** de esto son: Evitar tener múltiples versiones de un sitio, minimizar el tiempo de mantenimiento, experiencia al usuario transversal y homogénea y ahorro en constes de dinero.

<center>

![responsive](https://i.imgur.com/fDf9NCO.png)

</center>

**Mobile Reachability:** Estudio de las 3 formas básicas de tomar el teléfono.

<center>

![tomartelefono](https://i.imgur.com/W3tjuo2.png)

</center>

De esto se desprende el siguiente análisis:

<center>

![movilesquema](https://i.imgur.com/ibcqTaz.png)

</center>

<div id='id2'>
### **4.2 ¿Qué es un Design System y para qué sirve?:**<a name="id2"></a>

**Design System:** Está formado de partes más tangibles o visibles que otras. En un lenguaje de diseño en el que todas las personas involucradas pueden participar, entender y aportar al producto. Con el objetivo de crear un producto escalable, consistente e intuitivo.

**UI Kit:** No confundir con el anterior, este es un archivo que incluye varios elementos ya diseñados (botones, íconos, tablas, formularios, sliders, etc.) para ayudarnos en el desarrollo de nuestras interfaces e usuario.

**Style Guide:** Documento que describe los patrones, estilos, componentes, prácticas y principios de una compañia y que enseña cómo deben aplicarse estos. 

**¿Qué contiene un Design System?**

1. Design principles (conceptos clave y valores).
2. Style Guide (la base de la interfaz).
3. Grid sizes (diagramación y espacios).
4. Core (design Tokens).
5. Components (parte central del UI, elementos con un propósito).
6. Patterns (varios pasos o repetirse en los proyectos).
7. Repositorio (como la fuente de todo actualizado).
8. Documentación.
9. Voice & tone.
10. Transiciones y micro-interacciones.
11. Accesibilidad.
12. Un nombre! 

***SI NO ESTÁ ESCRITO, NO EXISTE -->*** Nadie tiene que andar adivinando las cosas, hay que dejar registro de todo.

**Creación de la guía de estilo:** 

<center>

![creacionstyleguide](https://i.imgur.com/97u6ir4.png)

</center>

**Por donde empezar:**

1. **Benchmark:** Reúne y organiza referencias interactivas, best practices y estilos visuales.
2. **Define Estilo:** Ten un brief, busca imágenes que te representen (moodboard).
3. **Brand:** Selecciona la combinación de colores y tipografía que te representen.
4. **Elementos:** Piensa en otros elementos que puedas necesitar.
5. **Empezar con lo mínimo:** Tener las cosas que sé que voy a necesitar desde un inicio.

<center>

![ejemplo](https://i.imgur.com/ZNNK6r4.png)
Ejemplo de guía de estilo de Airbnb

</center>

**Creación de una librería (UI Kit):**

- Debemos estandarizar nuestros estilos.
- Crear normas de relación entre los elementos.
- Aplicaremos estos estilos a los distintos elementos que forman parte de nuestro diseño.
- Parecido al diseño editorial (establecemos estilos de texto, párrafo, colores,estilos de objeto).

**Trabajar con estilos y componentes:**

|**Estilos**|**Componente**|
|-----------|--------------|
|Parámetros de tu marca (branding)|Diferentes partes que componen la interfaz|

**Diseño por componentes desde una unidad mínima**

<center>

![atom pages](https://i.imgur.com/QnDP4vY.png)
Izq: Sistema // Der: Producto

![ejem](https://i.imgur.com/R8JQTZu.png)

</center>

**Ventajas de un Design System**

<center>

![ventajas](https://i.imgur.com/saEtJhj.png)

</center>


**Referencias**

- [Design System Repo](https://designsystemsrepo.com)
- [The component Gallery](https://component.gallery/design-systems/)
- [Design System Gallery](https://www.designsystems.io/design-system-gallery/)

<div id='id3'>
### **4.3 Componentes y variantes en Figma:**<a name="id3"></a>

<center>

![img](https://i.imgur.com/fxLz7k0.png)

</center>

Como se puede ver figma es de las más potentes y útiles del mercado:

**Ventajas de Figma:**

1. Trabajo colaborativo.
2. Enfocado al diseño Producto Digital.
3. Todo en uno.
4. Exportación de assets.
5. Autolayout.
6. Smart animate.
7. Variants.
8. Componentes interactivos (BETA).

<div id='id4'>
### **4.4 Componentes y variantes en Figma (práctica):**<a name="id4"></a>
    
- [Herramienta web a utilizar](https://www.figma.com/files/recent?fuid=997162766004607704).
  
<center>

**FIGMA**

![img](https://i.imgur.com/5Uf0akw.png)

</center>

**Creación de Estilos**

- Color.
- Texto.
- Espacio.

En Sketch, propiedades de estilo van en conjunto (no separables), en Figma cada propiedad tiene sus propios estilos (más adaptable al usuario, permite copiar-pegar estilos).

Los estilos son creados en primera instancia analizado los atajos de teclado (click derecho, "keyboard shortcuts" si no me los sé), luego creando una forma/texto y dandole click en os 4 puntitos al lado de los atributos, esto permite con la pantalla que sale dar click en el "+" y crear este estilo, el que permite aplicar a cada uno de los componentes que siguen a continuación (mantiene el branding a través del documento).

Se pueden tener varios estilos, recordadando que no se pueden repetir y que se les puede agrupar dentro de uno mas grande como subcategorías (esto se hace poniendolo la barra "/" al lado para demostrar su pertenencia a otro estilo mayor).

También destaca la importancia de trabajar con grids (guías) para mantener el orden al crear los wireframe y como estas pueden ocultarse o hacerse visibles al momento de crear el diseño.

**Creación de Componentes**

**¿Cuando crearlos?:** Cuando sean todos los componentes susceptibles de repetición.

Es importante trabajar con autolayout (propiedad de diseño a la derecha), la cual permite que los componentes se ajusten a la vista (wrap_content || match_parent, similares), ademas de colocar imagenes y crear paddings entre elementos fijos (se puede crear un carrusel y mostrar u ocultar imagenes para ver como se adapta la vista al requerimiento).

<center>

![autolauout](https://i.imgur.com/lkfbQ5L.png)

</center>

Los componentes en sí se pueden crear de 3 formas:

<center>

![creaciocomponente](https://i.imgur.com/J8QCZW1.png)

</center>

Tomar en cuenta que al crear un componente, este inicial es el master, y que a aprtir del master se crear instancias que permiten aplicar las propiedades de master a los hijos (no al revés) (master es como el molde del que se heredan propiedades).

La profe tambien muestra el trabajar con las modificaciones en los hijos (no el master) y como se utilizan las variants para agilizar el trabajo de diseño (muestra una bottom navigation bar y como puede fácilmente cambiar el estado de los botones a "activo" e "inactivo").

<center>

![tabbarr](https://i.imgur.com/lLt0sff.png)

</center>

Se sugiere crear una nueva página de componentes con un pool de estos para reutilizar (copiar y pegar donde se necesite). Se muestran ejemplos de como crea un carrusel, de spotify y cambiar la imagen, además de distintos componentes y variants.

**Resumen Leo:** Me gusta la utilidad de Figma, debo meterle más power y manejarla mejor, pues me permitirá ordenar ideas y crear una mejor apariencia de las apps de cara al usuario.


