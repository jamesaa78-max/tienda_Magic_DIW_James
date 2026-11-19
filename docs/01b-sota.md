# 01b · Estado del arte (SOTA) de mi proyecto

> **Plantilla.** En **H1 (26-nov-2026)** entregas una **versión breve** (2-3 páginas: apartados **1, 2 y 5**), junto al `01-analisis.md`. Los apartados 3, 4, 6, 7 y 8 se completan en **H2 (21-ene-2027)** hasta las **4-6 páginas** del documento final. Aquí estudias qué soluciones, **modelos de negocio** y **herramientas** existen ya para el problema que has elegido, y justificas tus decisiones con ello. Cada apartado indica el criterio de evaluación (CE) que alimenta. Borra los bloques «Guía» al rellenar.

> **Guía.** Calendario de H1: **ciclo 1, hasta el jueves 19-nov:** preguntas de búsqueda y tabla de soluciones (apartados 1 y 2) · **ciclo 2, hasta el jueves 26-nov:** hueco y diferenciación (apartado 5). Los apartados 3, 4, 6, 7 y 8 son de H2.
>
> **Reglas.**
>
> - Solo cuenta lo que tiene **enlace y fecha de acceso**.
> - Si usas IA para buscar, **abre cada fuente** y comprueba que existe y dice lo que te cuenta la IA. Puede inventar productos, precios o referencias. Anótalo en `asistenciaIA/bitacora.md`.
> - Usa **solo información pública** de las soluciones que estudias. **Nada** de la empresa de prácticas ni de clientes reales.
> - Compara herramientas con **los mismos criterios**, no por opinión. Salvo razón argumentada, prefiere lo que has visto en el ciclo (Java 21, Spring Boot, SQL).
> - Si algo no lo has podido comprobar, dilo en el apartado 8.

## 1. Problema y preguntas de búsqueda (CE 1c)

*El problema en **una frase**. Después, **3-5 preguntas** que vas a contestar con este documento (por ejemplo: «¿Qué soluciones existen?», «¿Cómo ganan dinero?», «¿Qué tecnologías usan?»). Indica **dónde y cuándo** buscaste (buscadores, tiendas de aplicaciones, repositorios, informes del sector).*

**Problema:** [RELLENAR: una frase]

| # | Pregunta | Dónde busqué | Fecha |
|---|---|---|---|
| P1 | ¿Qué soluciones existen para gestionar inventarios y ventas de cartas Magic? |Webs especializadas y buscadores | 19-11-2026|
| P2 | ¿Qué sistemas permiten consultar precios y disponibilidad de cartas automáticamente? |Scryfall, tiendas y plataformas de cartas | 19-11-2026|
| P3 | ¿Cuánto cuestan las soluciones existentes? |Webs oficiales de los productos |19-11-2026 |
| P4 | ¿Existen alternativas gratuitas o de código abierto? | GitHub y proyectos comunitarios|19-11-2026 |
| P5 | ¿Qué limitaciones tienen las soluciones actuales para una tienda sin atención permanente? |Documentación y características de las soluciones |19-11-2026 |

## 2. Soluciones existentes (CE 1a, 1c, 2a)

*Tabla de **5-8** soluciones (productos, servicios o proyectos de código abierto) que resuelven total o parcialmente el problema. Incluye alguna **alternativa gratuita o de código abierto** y alguna **no digital** (hoja de cálculo, papel) si existe.*

| Solución | Para quién | Qué hace | Modelo de precio | Enlace y fecha de acceso | Estado (`leído` / `sin leer`) |
|---|---|---|---|---|---|
| BinderPOS | Tiendas físicas especializadas en cartas coleccionables | Gestiona inventario, ventas, TPV, catálogo de cartas, precios automáticos y modo kiosco | Desde 100 $/mes; Pro 150 $/mes. Necesita Shopify | [Web oficial](https://seller.tcgplayer.com/point-of-sale), acceso 19-11-2026 | leído |
| TCGplayer Seller Portal | Tiendas y vendedores de cartas coleccionables | Permite publicar cartas, gestionar existencias, actualizar precios y vender online | Gratis para empezar; comisiones por venta. Tarifa estándar: 10,75 % + 2,5 % + 0,30 $ por transacción | [Web oficial](https://seller.tcgplayer.com/pro), acceso 19-11-2026 | leído |
| Cardmarket | Tiendas y vendedores europeos de cartas | Plataforma de compraventa de cartas Magic; permite publicar inventario y gestionar pedidos | 5 % del valor de cada artículo vendido | [Web oficial](https://www.cardmarket.com/es/Magic/Policies/Fees), acceso 19-11-2026 | leído |
| ManaBox | Jugadores y coleccionistas de Magic | Escanea cartas, organiza colecciones, consulta precios y construye mazos | Gratis con funciones adicionales PRO: 2,49 €/mes o 24,99 €/año | [Web oficial](https://manabox.app/), acceso 19-11-2026 | leído |
| Delver Lens | Jugadores, coleccionistas y vendedores de Magic | Reconoce cartas mediante la cámara, organiza colecciones, consulta precios y exporta inventarios | Gratis; versión PRO desde 4 $/mes | [Web oficial](https://delver.app/), acceso 19-11-2026 | leído |
| MTGJSON | Desarrolladores de aplicaciones y proyectos relacionados con Magic | Proporciona bases de datos de cartas, expansiones y precios en formatos JSON, CSV y SQL | Gratis y código abierto (licencia MIT) | [GitHub](https://github.com/mtgjson/mtgjson), acceso 19-11-2026 | leído |
| Hoja de cálculo y registro manual | Pequeñas tiendas de cartas con pocos recursos | Permite registrar cartas, cantidades, precios, ventas y movimientos de existencias manualmente | Gratis utilizando una hoja de cálculo | no aplica (solución no digital), 19-11-2026 | leído |

*Figura: comparativa de las soluciones (opcional, un cuadrante o un esquema).*

## 3. Modelos de negocio (CE 1d, 1e)

*Qué **patrones** se repiten en las soluciones del apartado 2 (suscripción, *freemium*, comisión por operación, licencia, publicidad, servicio gratuito o público) y por qué. Describe con un **Business Model Canvas** (opcional; el profesor te da el material) **2-3 casos**. Termina con el modelo que seguiría **tu** proyecto, o qué ahorra o mejora si no es un negocio.*

| Patrón | Soluciones que lo usan | Ventaja | Riesgo |
|---|---|---|---|
| [RELLENAR] | | | |

## 4. Herramientas y tecnologías (CE 2a, 2b)

*Para cada decisión técnica importante (lenguaje y *framework*, base de datos, despliegue, autenticación…), compara **2-3 opciones con los mismos criterios**. Marca la que eliges.*

| Decisión | Opción | Madurez | Licencia | Coste | Curva de aprendizaje | Encaje con el ciclo | Elegida |
|---|---|---|---|---|---|---|---|
| [RELLENAR: p. ej. base de datos] | | | | | | | |

*Cada decisión importante se convierte en una decisión registrada en `decisiones/` (la plantilla llega con el bloque de H2).*

## 5. Hueco y diferenciación (CE 1e)

*Qué **no cubren** las soluciones del apartado 2 y qué aporta tu proyecto. Es tu **propuesta de valor**, en 3-5 líneas, sin exagerar: si hay soluciones mejores que la tuya para algunos usuarios, dilo.*

## 6. Decisiones derivadas (CE 1e, 1f, 2b)

*Qué consecuencias tiene este estudio en tu proyecto.*

- **Tipo de proyecto elegido** (enlaza con el apartado 3 de [`01-analisis.md`](01-analisis.md)): [RELLENAR]
- **Requisitos que salen del estudio** (con su ID del apartado 4 de `01-analisis.md`): [RELLENAR]
- **Decisiones técnicas** (enlace a cada archivo de `decisiones/`): [RELLENAR]

## 7. Fuentes y calidad (CE 2a)

*Al menos **2 fuentes independientes** (no dos páginas de la misma empresa). Datos oficiales o primarios antes que blogs.*

| # | Fuente (enlace) | Tipo | Fecha de acceso | Fiabilidad (alta / media / baja) y por qué |
|---|---|---|---|---|
| F1 | [RELLENAR] | | | |

## 8. Límites

*Qué **no pudiste comprobar** y qué datos son estimaciones. Una lista corta y honesta es mejor que fingir certeza.*

- [RELLENAR]

---

## Criterios de evaluación que alimenta este documento (texto literal)

- **1a)** Se han clasificado las empresas del sector por sus características organizativas y el tipo de producto o servicio que ofrecen.
- **1c)** Se han identificado las necesidades más demandadas a las empresas.
- **1d)** Se han valorado las oportunidades de negocio previsibles en el sector.
- **1e)** Se ha identificado el tipo de proyecto requerido para dar respuesta a las demandas previstas.
- **1f)** Se han determinado las características específicas requeridas al proyecto.
- **2a)** Se ha recopilado información relativa a los aspectos que van a ser tratados en el proyecto.
- **2b)** Se ha realizado el estudio de viabilidad técnica del mismo.

> El SOTA **no añade criterios de evaluación**: reúne en un solo sitio lo que 1a-1f y 2a-2b ya piden. La evaluación sigue las listas de cotejo de H1 y H2.
