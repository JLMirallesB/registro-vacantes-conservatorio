# Registro de vacantes y refuerzos

Plantilla de Excel para llevar el registro de las vacantes horarias y de los
refuerzos de un conservatorio de música: qué huecos quedan libres, por qué,
cómo se cubren y qué se hace con los que no se cubren.

Sin macros, sin conexiones externas y sin dependencias: se abre en Excel de
Windows, de Mac y en Excel para web, y funciona con edición compartida en
OneDrive o SharePoint.

**Descarga:** [`registro-vacantes-conservatorio.xlsx`](registro-vacantes-conservatorio.xlsx)

---

## ⚠️ Marco normativo

La plantilla está construida sobre la **Orden 8/2026, de 24 de abril**
(DOGV 10352), de admisión al alumnado en las enseñanzas elementales y
profesionales de Música y Danza de la Comunitat Valenciana, en vigor desde el
**30 de abril de 2026** y sin régimen transitorio.

Esa orden derogó el bloque de admisión, pruebas de acceso y matrícula de la
Orden 28/2011, y con él la vía por la que una vacante podía ofrecerse como
**segunda especialidad de elemental sin prueba de acceso**. Si vienes de una
herramienta anterior, ese es el cambio que más te va a afectar.

Lo que la plantilla codifica:

| Concepto | Dónde está en la norma |
|---|---|
| Orden de prelación para cubrir una vacante en curso | art. 22.3 |
| Traslado de expediente durante el curso | art. 24 |
| Renuncia, baja y renuncia excepcional | art. 25 |
| Segunda y sucesivas especialidades | arts. 11.2, 15 |
| Niveles de prioridad y criterios de ordenación | arts. 18 y 19 |

**Si trabajas fuera de la Comunitat Valenciana**, la mecánica del libro sirve
igual, pero los plazos y el orden de prelación son los valencianos: revísalos
contra tu normativa antes de usarlo.

---

## Empezar en cinco minutos

1. **Abre la Portada** y rellena las tres casillas que salen en rojo: nombre del
   centro, código del centro y fecha de fin del 2.º trimestre. Esa última la fija
   cada centro en su PGA; suele ser el último día lectivo antes de Pascua.
2. **Lee la hoja Instrucciones.** Son cinco minutos y te ahorra las dudas
   habituales.
3. **Ve a la hoja Docentes** y añade profesorado. No hace falta meterlos todos de
   golpe: puedes ir añadiéndolos según los necesites.
4. **Da de alta tu primera vacante** en la hoja Registro. Empieza por la
   especialidad: hasta que no la eliges, la fila no reclama nada.
5. **Mira la columna Comprobación**, la última por la derecha. Te va diciendo qué
   falta hasta que pone «Completa».

---

## Qué hay dentro

Dieciséis hojas, de las cuales solo tocas cuatro.

### Las que usas

| Hoja | Para qué |
|---|---|
| **Portada** | Identidad del centro, curso y la línea que dice qué vías de cobertura siguen abiertas hoy |
| **Instrucciones** | El manual, dentro del propio libro |
| **Docentes** | La lista del profesorado, que alimenta los desplegables |
| **Registro** | Una fila por hueco horario vacante |
| **Registro Refuerzo** | Refuerzos de asignaturas que no son de especialidad |

### Las que miras

| Hoja | Para qué |
|---|---|
| **Dashboard** | Vacantes disponibles por especialidad, resumen del curso y quién puede escribir en el libro |
| **Contador Refuerzo** | Refuerzos activos por especialidad, separando los que salen de una vacante de los que no |
| **Seis informes** | Para imprimir. Ver abajo |

### Las que no

`Validaciones`, `Aux` y `Aux Refuerzo` están ocultas y protegidas: son el motor
de los desplegables y de los cuadros de resumen.

### La regla que hay que entender

> **Si un alumno nuevo podría sentarse en esa hora, va a `Registro`.
> Si no hay plaza que ofertar —asignaturas que no son de especialidad—,
> va a `Registro Refuerzo`. Nunca en las dos.**

El apoyo instrumental a alumnado ya matriculado va a `Registro`, marcado como
«No disponible»: ocupa una hora del docente, pero no es una plaza ofertable.

---

## Los seis informes

Todos preparados para imprimir o exportar a PDF: horizontal, ajustados a una
página de ancho, con la cabecera repetida en cada página y un pie con la fecha y
la numeración. El nombre y el código del centro se traen de la Portada. Si hay
más filas de las que caben, **avisan** en vez de cortar en silencio.

| Informe | Qué lista |
|---|---|
| **Bajas** | Los cuatro motivos en que alguien se va, con desglose por la frontera del 30 de noviembre |
| **Horas disponibles** | Una línea por vacante, con horas completas y medias contadas aparte |
| **Capacidad ociosa** | Disponible **y** sin usar como refuerzo: lo que no está haciendo nada |
| **Refuerzos del centro** | Dos bloques, con vacante detrás y sin ella |
| **Horas libres por docente** | La vista por profesor, que el resto del libro no da |
| **Memoria anual** | 26 indicadores, con el desglose por las tres vías del art. 22.3 |

---

## Datos personales

El libro guarda nombres, apellidos y NIA del alumnado, porque la normativa obliga
a poder identificar quién deja cada plaza y quién la ocupa. Está pensado para
vivir en un **entorno protegido** (OneDrive corporativo de la GVA o equivalente).

**Un PDF impreso sale de ese entorno.** Por eso el informe de Bajas —el único que
muestra identidad de alumnado— lleva un conmutador:

- **Visibles** — se imprime tal cual, y la cabecera del informe dice
  «CONTIENE DATOS PERSONALES».
- **Anonimizados** — primer apellido completo, segundo apellido con inicial y
  asteriscos, nombres con inicial y asteriscos, y NIA con asteriscos en las
  posiciones 2 a 5. La cabecera dice «DATOS ANONIMIZADOS».

Así el PDF declara en su propia cara qué versión es.

---

## Protección

Las dieciséis hojas están protegidas **sin contraseña**. No es un candado: es un
seguro contra accidentes.

**Bloqueado:** editar las celdas calculadas, dar formato, insertar y borrar filas
y columnas, y **ordenar**. Lo de ordenar no es manía: los contadores acumulados
del libro dependen del orden de las filas, y una ordenación los rompería sin dar
ningún error.

**Permitido:** escribir en las celdas de entrada, seleccionar cualquier celda
para leer o copiar, y usar el autofiltro.

Para una tarea de mantenimiento: **Revisar → Desproteger hoja**, hacer el cambio,
y volver a proteger sin escribir contraseña. Si vas a tocar fórmulas, prueba
antes en una copia.

---

## Cada curso

1. En la **Portada**: curso académico y fecha de fin del 2.º trimestre. El nombre
   y el código del centro se ponen una sola vez.
2. En **Docentes**: repasa altas y bajas. Uno por fila y sin dejar huecos — el
   desplegable cuenta las filas escritas, así que un hueco corta la lista.
3. En el **Dashboard**, al final: quién puede escribir en el libro.

---

## Limitaciones conocidas

- **Apellidos compuestos en la anonimización.** La regla parte por el primer
  espacio, así que «de la Fuente Ruiz» se corta antes de tiempo. El fallo va del
  lado seguro —oculta más de lo pedido, nunca menos— pero deja el informe menos
  legible.
- **Añadir o quitar una especialidad no se puede hacer a mano.** Obliga a tocar
  seis hojas cuadrando la correspondencia de filas una a una, y si solo cambias
  la lista de validaciones el Dashboard queda desalineado sin dar ningún error.
  Abre un aviso en el repositorio y se hace bien.
- **Capacidad:** 500 vacantes y 200 refuerzos por curso, 12 slots por
  especialidad en los cuadros de resumen y 250 docentes. Todo avisa al
  desbordarse, ninguno corta en silencio.
- **La fecha de fin del 2.º trimestre no se puede calcular.** No hay ninguna
  norma que divida el curso en trimestres: la fija cada centro en su PGA. Por eso
  es una celda editable y no un dato deducido.

---

## Pedir un cambio o avisar de un fallo

Abre una *issue* en este repositorio. Si es un fallo, ayuda mucho decir en qué
hoja y en qué celda, y qué esperabas que pasara.

Si adaptas la plantilla para otro centro o para otras enseñanzas, cuéntalo: es
información útil para quien venga detrás.

---

## Créditos

Creado por **José Luis Miralles Bono**, con ayuda de Claude.

Contacto: [joseluismirallesbono@gmail.com](mailto:joseluismirallesbono@gmail.com)

Si te ha ahorrado trabajo, puedes [invitarme a una orxata](https://ko-fi.com/miralles).

## Licencia

**[CC BY 4.0](LICENSE)** — Creative Commons Reconocimiento 4.0 Internacional.

Puedes copiarlo, redistribuirlo, adaptarlo y construir sobre ello, también con
fines comerciales, siempre que reconozcas la autoría. Si lo adaptas para tu
centro, indícalo. Ver [NOTICE.md](NOTICE.md) para cómo citar.
