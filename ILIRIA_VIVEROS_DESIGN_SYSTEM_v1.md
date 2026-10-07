# Iliria Viveros — sistema de diseño y arquitectura web

**Versión:** 1.0 · 28 septiembre 2026  
**Estado:** propuesta de dirección creativa; biografía, alcance de servicios, credenciales y canales pendientes de aprobación de Iliria.

## 1. Objetivo y posicionamiento

Sitio de marca personal de **Iliria Viveros**, abogada y maestra en amparo, con experiencia en derecho laboral y fiscal. El nombre completo **Iliria Hernández Viveros** se utiliza en la biografía, firma profesional y datos jurídicos. Su nombre de marca figura en logotipo, menú, portada, artículos y metadatos.

**Promesa editorial propuesta:** «Una defensa que empieza por comprender el problema y construir una estrategia». Comunicar análisis riguroso, claridad y atención personal; evitar promesas de victoria, urgencia artificial y clichés de “justicia implacable”.

**Audiencia inicial:** personas y organizaciones que ya enfrentan un acto de autoridad, controversia o conflicto y necesitan saber si su asunto corresponde a la práctica de Iliria. La prioridad entre clientes individuales y empresas debe validarse con ella antes de cerrar los ejemplos y textos.

## 2. Referentes observados

| Referencia | Señal útil | Aplicación en Iliria Viveros |
| --- | --- | --- |
| [Esme Torres](https://www.esmetorres.com/) | Marca personal, servicios legibles, proceso y contacto visibles | Nombre propio y camino claro hasta consulta, con tono más contenido |
| [TOGA Abogados](https://www.togabogados.com.mx/) | Formación y experiencia jurisdiccional como pruebas de autoridad | Trayectoria explicada con hechos y credenciales verificables |
| [Paulina González / Cuesta Campos](https://cuestacampos.com/en/paulina-gonzalez-2/) | Áreas descritas por tipos de asuntos | Tarjetas de práctica que ayudan al visitante a reconocerse |
| [Perfil público de Iliria en LinkedIn](https://mx.linkedin.com/in/iliria-h-viveros-2457aa99) | Juicios, fiscal, constitucional, amparo contra leyes, sector hacendario y Judicatura | Verificar estos términos y la manera exacta de describir su experiencia antes de publicar |

## 3. Arquitectura recomendada

### Navegación principal

**Marca Iliria Viveros** | **Inicio** | **Áreas de práctica** | **Trayectoria** | **Perspectivas** | **Contacto** · botón **Plantear mi asunto**

En móvil: marca a la izquierda, botón de menú a la derecha; menú vertical con las mismas rutas y CTA de ancho completo. El enlace «Contacto» permanece al final de cada página. No poner un botón flotante que cubra campos ni texto.

### Páginas para lanzamiento

| Ruta | Función | Secciones en orden |
| --- | --- | --- |
| `/` Inicio | Orientar y generar confianza | Hero → situaciones en que interviene → tres áreas → enfoque en tres pasos → presentación de Iliria → artículo destacado, si existe → contacto breve |
| `/areas-de-practica/` | Aclarar el alcance | Introducción → Amparo → Laboral → Fiscal → casos que requieren otra revisión → CTA |
| `/trayectoria/` | Probar autoridad personal | Retrato → historia profesional → formación y experiencia verificadas → forma de trabajo → CTA |
| `/contacto/` | Recibir consultas | Instrucción de qué enviar → formulario → canales confirmados → privacidad |
| `/perspectivas/` | Publicar análisis propios | Listado por tema → artículos. Puede esperar al lanzamiento si no hay contenido real |

**Páginas de crecimiento:** fichas `/amparo/`, `/derecho-laboral/`, `/derecho-fiscal/` cuando exista contenido específico; no crear páginas vacías. Aviso de privacidad en ruta propia. Un pie de página común muestra nombre profesional, ubicación y medios únicamente cuando estén confirmados.

### Recorrido de la portada

1. **Hero.** «Iliria Viveros» como firma visible y H1 descriptivo: **«Estrategia jurídica para asuntos que requieren una defensa cuidadosa»**. Bajada: «Amparo, derecho laboral y fiscal. Analizo cada asunto para definir sus opciones y el camino jurídico pertinente». CTA primario «Plantear mi asunto»; secundario «Conocer mi trayectoria». Retrato auténtico.
2. **Reconocimiento del problema.** Tres preguntas breves: «¿Recibiste un acto de autoridad?», «¿Enfrentas un conflicto laboral?», «¿Necesitas revisar una controversia fiscal?». Cada una conduce al área pertinente; confirmar que Iliria atiende esos supuestos concretos.
3. **Áreas de práctica.** Tres tarjetas con descripción de dos líneas y enlace «Explorar esta área».
4. **Enfoque.** «Escuchar y revisar», «Definir la estrategia», «Acompañar el proceso». La selección de acciones se ajusta al servicio real.
5. **Trayectoria.** Retrato secundario o detalle del retrato principal, párrafo en primera persona, maestría y experiencia redactadas con precisión confirmada.
6. **Perspectiva.** Una reflexión publicada y fechada; omitir el módulo si todavía no hay artículo.
7. **Contacto.** Invitación simple y vínculo a formulario completo: «Cuéntame lo esencial de tu asunto».

## 4. Fundamentos visuales

### Paleta semántica

| Token | HEX | Uso |
| --- | --- | --- |
| `color.brand.600` | `#81345F` | Botones, enlaces y acentos sobre fondos claros |
| `color.brand.800` | `#552342` | Secciones profundas y hover del CTA principal |
| `color.brand.100` | `#F3E8EE` | Fondo de tarjetas destacadas, bandas y estados suaves |
| `color.ink` | `#242128` | Texto y titulares sobre marfil |
| `color.canvas` | `#FAF7F4` | Fondo base |
| `color.surface` | `#FFFFFF` | Tarjetas, formulario |
| `color.border` | `#DDCED6` | Límites de tarjeta, divisores y campos |
| `color.muted` | `#625B62` | Descripciones secundarias |

**Aplicación proporcional:** 70 % marfil/blanco, 20 % tinta y neutros, 10 % bugambilia. El violeta se concentra en puntos de decisión, números de sección y citas. En fondos `brand.800`, utilizar texto blanco. Comprobar contraste de cada combinación en implementación, especialmente texto pequeño, foco y estados de error; no utilizar rosa pálido para texto sobre blanco.

### Tipografía

- **Titulares y citas cortas:** Cormorant Garamond, peso 500–600. Hero escritorio 64–76 px / línea 0.98–1.05; móvil 42–50 px / línea 1.05.
- **Interfaz y lectura:** Inter. Texto 17–18 px escritorio, 16–17 px móvil; interlineado 1.55–1.7. Navegación 14–15 px, peso 500.
- H2 escritorio 42–48 px, móvil 32–38 px. H3 24–28 px. Etiquetas 12–13 px en mayúsculas con espaciado moderado.
- Párrafos largos limitados a 66–72 caracteres por línea. Evitar párrafos centrados; alinear a la izquierda.

### Espaciado y geometría

Escala de 4/8 px: `4, 8, 12, 16, 24, 32, 48, 64, 96, 128`. Contenedor máximo **1200 px**; padding horizontal escritorio **48 px**, tableta **32 px**, móvil **20 px**. Espacio entre secciones: **96–128 px** escritorio y **64–80 px** móvil. Tarjetas con radio **12 px**; botones **8 px**; inputs **8 px**. Bordes finos de 1 px; sombra discreta solo en elevación interactiva. Fotografía: luz natural, retrato frontal o tres cuartos, fondo sobrio, sin libros o tribunales de stock.

### Motivo gráfico

Un trazo fino vertical bugambilia y numeración editorial **01 / 02 / 03** identifican secciones y pasos. Puede aparecer una curva abstracta inspirada en el contorno de una bugambilia como textura de baja opacidad, nunca como ilustración que compita con el texto. No usar balanza, mazo, columnas ni sellos que simulen acreditación.

## 5. Componentes y uso

### Encabezado

- **Escritorio:** altura 80 px, marca tipográfica a la izquierda, navegación al centro/derecha y CTA sólido al extremo derecho. Fondo marfil opaco al desplazarse.
- **Móvil:** altura 64 px; menú desplegado bajo el encabezado, enlaces de alto mínimo 48 px. Cerrar con Escape y al cambiar de ruta; devolver foco al botón al cerrar.
- Ruta actual indicada con subrayado y `aria-current="page"`.

### Botones y enlaces

- **Primario:** fondo `brand.600`, texto blanco, padding 14 × 22 px; hover `brand.800`; foco de 3 px visible; deshabilitado solo si el formulario no puede enviarse.
- **Secundario:** fondo transparente, borde `brand.600`, texto `brand.800`; hover rosa pálido.
- **Enlace textual:** subrayado persistente y flecha opcional. Nunca depender solo del color.

### Tarjeta de área de práctica

**Escritorio:** tres columnas iguales con separación de 24 px; cada tarjeta blanco, borde `color.border`, padding 32 px, alto de contenido equilibrado. Orden: índice `01` bugambilia → nombre → descripción en lenguaje común → enlace subrayado al pie. Hover: borde bugambilia y desplazamiento suave de 2 px; toda la tarjeta puede ser clicable solo si mantiene un único destino claro.

**Móvil:** una columna, separación 16 px, padding 24 px. Texto visible completo, sin carrusel ni contenido oculto tras hover. La descripción no debe implicar servicios no confirmados.

**Ejemplo de contenido:** «Amparo y defensa constitucional — Revisión de actos y normas que puedan afectar tus derechos. Estudio de procedencia y definición de estrategia según el caso». Validar el alcance con Iliria.

### Tarjeta de artículo

Fecha y categoría arriba, título de máximo tres líneas, resumen de dos a tres líneas y «Leer análisis». Sin miniatura decorativa obligatoria. En escritorio puede ir en una cuadrícula de dos; en móvil una columna. Mostrar fecha real y evitar rótulos como «últimas noticias» si no existe un calendario editorial.

### Módulo de trayectoria

Fotografía a la izquierda (40 %) y texto a la derecha (60 %) en escritorio. En móvil: retrato apaisado o cuadrado → título → texto → credenciales verificadas → CTA. Nombre completo en pie de módulo; ninguna sigla institucional o especialidad inventada.

### Contacto y formulario

**Escritorio:** fondo `brand.800` en banda exterior; columna izquierda con invitación y expectativas, columna derecha con formulario blanco, ancho máximo 560 px.

**Móvil:** título y contexto primero; formulario en una sola columna; CTA de ancho completo; información de privacidad inmediatamente debajo. Padding del módulo 24 px. Nada de dos campos en la misma fila.

Campos sugeridos: **Nombre**, **Correo**, **Tipo de asunto** (Amparo / Laboral / Fiscal / No estoy seguro), **Descripción breve**. Teléfono opcional solo si Iliria quiere usarlo. Texto previo: «Describe el asunto en términos generales. Evita compartir documentos o datos sensibles en este primer mensaje». Checkbox de aceptación del aviso de privacidad cuando corresponda al flujo implementado.

Estados: etiqueta siempre visible, ayuda contextual, foco claro, error bajo el campo en lenguaje específico y confirmación de recepción sin afirmar que el asunto fue aceptado. La opción de WhatsApp, si se habilita, llevará a un mensaje inicial discreto y nunca sustituirá el formulario sin decisión de Iliria.

### Pie de página

Marca, frase descriptiva breve, enlaces principales, contacto confirmado, aviso de privacidad y copyright. En escritorio tres columnas; en móvil bloques apilados con separadores. No publicar cédula, domicilio ni teléfono que Iliria no haya autorizado.

## 6. Composición visual de referencia

### Escritorio, portada — ancho conceptual 1440 px

| Franja | Composición | Comportamiento |
| --- | --- | --- |
| Header | Marca 25 % · navegación 50 % · CTA 25 % | Permanece legible al desplazar |
| Hero | Texto 55 % · retrato 45 % | H1 de 2–3 líneas; CTA junto al texto |
| Problemas | Encabezado estrecho + 3 preguntas | Una pregunta por bloque con enlace |
| Práctica | Título + 3 tarjetas iguales | Alturas homogéneas; contenido alineado |
| Enfoque | Fondo rosa pálido + 3 pasos numerados | Se lee en secuencia |
| Trayectoria | Retrato 40 % · relato 60 % | Fotografía auténtica |
| Contacto | Fondo violeta oscuro · invitación 40 % · formulario 60 % | CTA y privacidad visibles |

### Móvil — ancho de diseño 390 px

| Franja | Composición | Regla |
| --- | --- | --- |
| Header | Marca + menú | Una línea; objetivo táctil ≥44 px |
| Hero | Etiqueta → H1 → bajada → CTA primario → secundario → retrato | Sin texto superpuesto sobre la cara |
| Problemas | Tres filas verticales | Pregunta y enlace en cada fila |
| Práctica | Tres tarjetas apiladas | Descripciones completas |
| Enfoque | Pasos en columna | Números grandes; sin línea horizontal larga |
| Trayectoria | Retrato → texto | Evitar recortes de rostro |
| Contacto | Título → explicación → campos → privacidad | Una columna, campos de alto ≥48 px |

**Puntos de adaptación:** ≤767 px móvil; 768–1023 px tableta; ≥1024 px escritorio. En tableta, tarjetas pueden ir en dos columnas y la tercera ocupar una fila propia, o mantenerse en una columna si el contenido lo pide. Priorizar lectura sobre simetría.

## 7. Interacción y accesibilidad

Movimiento limitado a 150–220 ms en botones y tarjetas, sin animaciones que retrasen el contenido. Respetar `prefers-reduced-motion`. Navegación completa por teclado, indicadores de foco visibles, texto alternativo descriptivo para el retrato, jerarquía H1/H2/H3 coherente y mensajes de formulario asociados a sus campos. No usar testimonios, logos de clientes, cifras de éxito ni distintivos sin autorización y evidencia.

## 8. Contenido pendiente de validación

1. Redacción exacta del grado académico, institución y nombre de la maestría.
2. Qué servicios presta directamente y a quién: personas, empresas o ambos.
3. Alcance real de «amparo contra leyes», fiscal, laboral y experiencia en sector hacendario y Judicatura.
4. Ciudad o cobertura geográfica y modalidad de atención.
5. Retrato profesional, correo, teléfono/WhatsApp y tiempos de respuesta que desee comunicar.
6. Datos profesionales y texto de privacidad que autorice publicar.
7. Primer artículo propio para decidir si «Perspectivas» sale en la versión inicial.

## 9. Criterio de aceptación del diseño

En menos de 20 segundos, una persona debe poder identificar que está ante **Iliria Viveros**, entender sus tres ámbitos de práctica y encontrar cómo plantear su asunto. En móvil debe lograrlo sin zoom, carruseles ni menús confusos. La percepción final buscada es una abogada con criterio propio y trato directo, respaldada por información comprobable.
