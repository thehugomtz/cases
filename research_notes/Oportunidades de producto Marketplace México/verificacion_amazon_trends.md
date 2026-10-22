# Verificación directa Amazon México + Google Trends México (hogar, limpieza, auto/moto) — corte 2026-10-22

> Pase de cierre de huecos. Sustituye las cifras de Amazon que las notas `hogar_organizacion.md`, `limpieza_herramientas.md` y `auto_moto.md` habían tomado de fragmentos de buscador sin fecha. Todo lo marcado **HECHO** se observó directamente el 2026-10-22 en amazon.com.mx o en Google Trends (geo=MX). **ESTIMACIÓN** = cálculo propio con insumos visibles. **HIPÓTESIS** = interpretación no verificada. Mercado Libre no se consultó (bloquea el acceso automatizado).

## 0. ¿Qué se pudo observar directamente y cómo leer cada métrica?

### Takeaway
Amazon MX sí respondió (búsqueda de escritorio, fichas /dp/ y páginas de Más vendidos) y Google Trends también (5 lotes de 5 términos + 13 consultas individuales, solo un 429 recuperado con reintento). Así se reemplazaron casi todas las cifras de snippets. **Las cifras observadas contradicen varias de las conclusiones previas** (ver sección 5).

### Cited Findings
- **HECHO (acceso):** Con navegador simulado (cabeceras de navegador completas) las búsquedas `amazon.com.mx/s?k=…` devolvieron HTTP 200 y la línea "1 a 48 de … resultados para". Una primera petición sin cabeceras devolvió **HTTP 503** ("Algo falló"), igual que WebFetch. No se evadió ningún captcha. — p. ej. [Amazon MX "guardapolvo para puerta"](https://www.amazon.com.mx/s?k=guardapolvo+para+puerta) (acc. 2026-10-22)
- **HECHO (insignia mensual y semanal):** las búsquedas muestran "X+ comprados el mes pasado" (mínimo visible: 50+; tramos 50+, 100+, 200+…, "1 k+", "4 k+"). En las fichas de los líderes Amazon muestra **además** una insignia **semanal** ("X+ comprados la semana pasada"), p. ej. SONGMICS 18 cajas: 900+/mes y 100+/semana; ESQUIMAL protector individual: 1 k+/mes y 200+/semana. — [Amazon MX B084VGDD7M](https://www.amazon.com.mx/dp/B084VGDD7M); [B0BLTKZBMQ](https://www.amazon.com.mx/dp/B0BLTKZBMQ) (acc. 2026-10-22)
- **HECHO (reseñas compartidas o globales):** hay conteos de calificaciones repetidos entre ASIN distintos, lo que indica reseñas agrupadas por familia de variantes. Ejemplos: RagaBasics y Raganet (ganchos) muestran ambos 1,337; OUARTV B0B59KLHX7 y B0H3NL65KK muestran 1,216. También aparecen conteos enormes en marcas importadas que muy probablemente incluyen reseñas de otros países: Linenspa 111,997; FURemover 103,517; Amazon Basics bolsas 81,588; Lamicall 51,716. — [búsqueda ganchos](https://www.amazon.com.mx/s?k=ganchos+de+terciopelo+50+piezas); [búsqueda guardapolvo](https://www.amazon.com.mx/s?k=guardapolvo+para+puerta) (acc. 2026-10-22)
- **HECHO (Trends):** endpoints `api/explore` + `widgetdata/multiline` (los mismos que usa la página Explore), geo=MX, "today 12-m", serie semanal del 19–25 oct 2025 al 18–24 oct 2026 (última semana parcial, 53 puntos). "zapatera" se usó como **ancla común** en 5 lotes. En los lotes 1, 3, 4 y 5 vale 100 en su pico (escala idéntica). En el lote 2 "regadera" domina y "zapatera" baja a un promedio de 14.2. Una sola respuesta 429, resuelta con reintento. — [Trends lote 1](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=zapatera,guardapolvo%20puerta,bolsas%20al%20vac%C3%ADo,ganchos%20de%20terciopelo,protector%20de%20colch%C3%B3n) (acc. 2026-10-22)

### Inferences
- **Cómo leer las métricas (reglas):**
  - "X+ comprados el mes pasado" es un **piso mensual por listado** en Amazon, no el mercado. La "suma mínima top 5" es solo un piso de lo que Amazon vendió con esas 5 publicaciones.
  - Las calificaciones son **acumuladas**: no son ventas mensuales.
  - "nºN en …" (BSR) es una **posición relativa**, no un volumen.
  - Trends mide **interés de búsqueda relativo**, no compras.
- **HIPÓTESIS:** Un listado sin insignia probablemente vendió menos de 50 unidades el mes pasado (umbral típico de Amazon, no confirmado por Amazon MX en esta sesión).
- **ESTIMACIÓN (re-escalado del lote 2):** factor = 65.7 / 14.2 ≈ 4.63, porque "zapatera" promedia 65.7 en los lotes 1 y 3–5 y 14.2 en el lote 2. Con ese factor, los valores del lote 2 se pueden comparar con los demás.
- **El número de resultados de búsqueda NO mide demanda.** Depende de la redacción de la consulta: "protector de colchon impermeable" da 426 resultados y "tendedero retractil de pared" da más de 40,000. Se reporta solo como contexto.

### Gaps
- Reseñas individuales de 1–3★: no se leyeron (requieren sesión). Las quejas vienen del resumen "Los clientes dicen" (generado con IA por Amazon) y de los aspectos con conteo positivo/negativo.
- Movers & Shakers: no se consultó en este pase.

---

## 1. Hogar (productos 1–7): ¿qué muestra Amazon MX hoy?

### Takeaway
Las señales mensuales más fuertes de todo el estudio están en **ganchos de terciopelo** (un listado con "4 k+"/mes y otro en el **nº3 de todo Hogar y Cocina**), en el **protector de colchón** (ESQUIMAL con 1 k+/mes, nº4 en Hogar y Cocina) y en las **cajas para zapatos** (SONGMICS 900+/mes). El **guardapolvo** tiene muchos listados con insignia pero tickets bajos ($55–$230). El **carrito o base para garrafón** y el **organizador bajo tarja** muestran señales delgadas en Amazon.

### Cited Findings

**1) Kit guardapolvo bajo puerta / burlete**
- **Resultados (HECHO):** "1 a 48 de 436 resultados" para "guardapolvo para puerta"; "más de 3,000" para "burlete puerta". — [búsqueda guardapolvo](https://www.amazon.com.mx/s?k=guardapolvo+para+puerta); [búsqueda burlete](https://www.amazon.com.mx/s?k=burlete+puerta) (acc. 2026-10-22)
- **Top orgánico "guardapolvo para puerta" (HECHO):**
  - #1 Lock 16GPF foam con cubierta PVC 95 cm: $55, 4.3★ (64), **300+/mes**.
  - #2 Guardapolvo silicón "premium": $199, 4.5★ (123), 200+/mes.
  - #3 NIAWEA 2 pzs 5 m: $175, 4.5★ (296), 50+/mes, "Más vendido".
  - #4 OUARTV 2 piezas: $175.11, 4.2★ (3,332), 100+/mes.
  - #5 3 PCS de 3 capas: $197.99, 4.6★ (258), 100+/mes.
  - **19 de los 20** primeros orgánicos tienen insignia mensual. Precios del top 20 orgánico: $55–$295 (mediana $132). — [búsqueda](https://www.amazon.com.mx/s?k=guardapolvo+para+puerta) (acc. 2026-10-22)
- **Fichas de líderes (HECHO):**
  - CARYWON 5 m silicón (B092HVFW8P): $228, 4.1★ (2,079), **400+/mes**, nº154 en Herramientas y Mejoras del Hogar, nº3 en "Cintas de Impermeabilización".
  - 3 PCS 5×100 cm (B0DNZ3HZFR): $149.99, 4.6★ (258), **400+/mes**, **nº35** en Herramientas y Mejoras del Hogar, **nº1** en Cintas de Impermeabilización.
  - OUARTV (B095S88X4L): $108.98, 4.2★ (3,332), 200+/mes, nº102 / **nº1 en "Topes"**.
  - Lock 16GPF (B0F7ZZNFFQ): BSR no visible.
  - Fuentes: [B092HVFW8P](https://www.amazon.com.mx/dp/B092HVFW8P); [B0DNZ3HZFR](https://www.amazon.com.mx/dp/B0DNZ3HZFR); [B095S88X4L](https://www.amazon.com.mx/dp/B095S88X4L); [B0F7ZZNFFQ](https://www.amazon.com.mx/dp/B0F7ZZNFFQ) (acc. 2026-10-22)
- **Suma mínima top 5 orgánico (HECHO, piso):** 300+200+50+100+100 = **750/mes** ("guardapolvo"). Para "burlete": 50+100+200+400+50 = **800/mes**. — búsquedas citadas (acc. 2026-10-22)
- **Quejas (HECHO, "Los clientes dicen"):**
  - CARYWON: "algunos mencionan que el pegamento no dura y no tiene buena adherencia". Aspectos: **adherencia 206 menciones (60 positivas / 146 negativas)**, grosor 35 (5/30), durabilidad 48 (19/29). 1★ = 9%.
  - OUARTV: "al abrir y cerrar la puerta se mueve y se sale de lugar, no se queda en la puerta". Adherencia 63 (12/51), resistencia 48 (12/36).
  - Rabbitstorm 90 cm doble borde (B087TDFWQK): la ficha dice **"No disponible por el momento"** (sin precio en la caja de compra). 4.0★ (1,654), **sin insignia mensual**, nº51,439 / nº138 en "Burletes y Aislantes para Puertas". "Al empacarlo queda quebrado… queda muy suelto en la puerta y se cae a cada rato". Ajuste 40 (9/31), durabilidad 43 (7/36).
  - Fuentes: [B092HVFW8P](https://www.amazon.com.mx/dp/B092HVFW8P); [B095S88X4L](https://www.amazon.com.mx/dp/B095S88X4L); [B087TDFWQK](https://www.amazon.com.mx/dp/B087TDFWQK) (acc. 2026-10-22)

**2) Bolsas al vacío para ropa con bomba manual**
- **Resultados (HECHO):** "más de 10,000" para "bolsas al vacio para ropa con bomba". — [búsqueda](https://www.amazon.com.mx/s?k=bolsas+al+vacio+para+ropa+con+bomba) (acc. 2026-10-22)
- **Dominio de la bomba eléctrica (HECHO):** en el top 20 orgánico, **12 títulos dicen "bomba eléctrica" y solo 2 "bomba manual"**. Los 5 primeros orgánicos son de bomba eléctrica:
  - 16 pzs: $260.75, 300+/mes.
  - 2PCS de viaje: $769, 100+.
  - 20 pzs: $498, 4.4★ (958), 100+.
  - Esquimal + bomba eléctrica 6 pzs: $351.12, 100+.
  - 12 PCS: $298, 100+.
  - Suma mínima: **700/mes**. Top 20: $179–$1,800 (mediana $382). — [búsqueda](https://www.amazon.com.mx/s?k=bolsas+al+vacio+para+ropa+con+bomba) (acc. 2026-10-22)
- **Con bomba manual (HECHO):**
  - TOCOZOC 12 pzs: $179.10, 4.4★ (327), 50+.
  - 10 pack: $159, 4.4★ (2,174), **300+/mes**.
  - JEECOLI 15 pzs con bomba manual (B0F8L9MPVQ): $292.52, 4.3★ (186), **300+/mes**, nº1,033 en Hogar y Cocina, nº10 en "Bolsas Ahorradoras de Espacio".
  - Fuentes: [búsqueda "bomba manual"](https://www.amazon.com.mx/s?k=bolsas+al+vacio+bomba+manual); [B0F8L9MPVQ](https://www.amazon.com.mx/dp/B0F8L9MPVQ) (acc. 2026-10-22)
- **Más vendidos "Bolsas Ahorradoras de Espacio" (HECHO):**
  - **#1 ESQUIMAL** (B0C8W7BQJV): $335.20, 4.6★ (2,928); en la ficha: **nº36 en Hogar y Cocina**, 100+/mes.
  - **#2 Amazon Basics** con bomba de mano: $391.10, 4.7★ (81,588).
  - #3 12 pzs con bomba eléctrica: $339.
  - #7 ANNIEMOOM 11 pack: $169.
  - #10 JEECOLI.
  - Fuentes: [Más vendidos](https://www.amazon.com.mx/gp/bestsellers/kitchen/9756876011); [B0C8W7BQJV](https://www.amazon.com.mx/dp/B0C8W7BQJV) (acc. 2026-10-22)
- **Quejas (HECHO):**
  - JEECOLI: "opiniones diversas sobre la resistencia y el sellado de las bolsas". Resistencia 14 (7/7), sellado 9 (4/5), 1★ = 7%.
  - ESQUIMAL: resistencia 146 (108/38), tamaño 146 (110/36).
  - Fuentes: [B0F8L9MPVQ](https://www.amazon.com.mx/dp/B0F8L9MPVQ); [B0C8W7BQJV](https://www.amazon.com.mx/dp/B0C8W7BQJV) (acc. 2026-10-22)

**3) Ganchos de terciopelo 50 piezas**
- **Resultados (HECHO):** "más de 2,000". — [búsqueda](https://www.amazon.com.mx/s?k=ganchos+de+terciopelo+50+piezas) (acc. 2026-10-22)
- **Top orgánico (HECHO):**
  - #1 **RagaBasics 50 pzs** (B0CFX3B9ZS): $278.98, 4.7★ (1,337), **"4 k+ comprados el mes pasado"**, "Más vendido".
  - #2 SELECTSHOP 50: $259, 4.7★ (2,244), 200+.
  - #3 Raganet 50 beige: $277.42, 600+, "Más vendido".
  - #4 MAGMALIFE 50: $289, 4.8★ (526), 600+.
  - #5 genérico: $227, sin calificaciones.
  - Otros: Raganet 100 pzs $478.98, 4.6★ (18), "1 k+"; RagaBasics infantil $198.99, 900+; MAGMALIFE dorado $295, 4.8★ (1,631), 200+.
  - **17 de 20** con insignia. Top 20: $198.99–$478.98 (mediana $289). **Suma mínima top 5: 5,400/mes** (piso). — [búsqueda](https://www.amazon.com.mx/s?k=ganchos+de+terciopelo+50+piezas) (acc. 2026-10-22)
- **Fichas (HECHO):**
  - Raganet 50 beige (B0GHWNY9NG): **nº3 en todo Hogar y Cocina**, nº1 en "Ganchos Estándar", 600+/mes y **100+/semana**.
  - MAGMALIFE (B0D9C2HNXR): nº144 en Hogar y Cocina, nº3 en Ganchos Estándar, 600+/mes, 50+/semana.
  - RagaBasics infantil (B0G62PTTD4): nº757 / nº10, 900+/mes, 100+/semana.
  - Fuentes: [B0GHWNY9NG](https://www.amazon.com.mx/dp/B0GHWNY9NG); [B0D9C2HNXR](https://www.amazon.com.mx/dp/B0D9C2HNXR); [B0G62PTTD4](https://www.amazon.com.mx/dp/B0G62PTTD4) (acc. 2026-10-22)
- **Quejas (HECHO):**
  - Raganet: "opiniones diversas sobre… la resistencia, la absorción de pelusa y el grosor". Resistencia **83 (46/37)**, pelusa 15 (7/8), grosor 11 (7/4).
  - MAGMALIFE: "algunos las encuentran frágiles".
  - RagaBasics infantil: resistencia 12 (7/5), tamaño 11 (6/5).
  - Fuentes: fichas citadas (acc. 2026-10-22)

**4) Cajas apilables para zapatos**
- **Resultados (HECHO):** "más de 7,000". Top orgánico:
  - #1 **SONGMICS 18 cajas** (B084VGDD7M): $799.99, 4.3★ (8,961), **900+/mes**, "Más vendido".
  - #2 SONGMICS 12: $400.94, 4.4★ (311), 100+.
  - #3 SONGMICS 18 (otra variante): $899.99, 300+.
  - #4 SONGMICS 12 transparente, talla 43: $449.99, **3.4★ (136)**, 200+.
  - #5 8 pzs: $699, 4.1★ (140), 50+.
  - Solo 9 de 20 con insignia. Top 20: $208–$1,709 (mediana $709). **Suma mínima top 5: 1,550/mes**. — [búsqueda](https://www.amazon.com.mx/s?k=cajas+apilables+para+zapatos) (acc. 2026-10-22)
- **Ficha SONGMICS (HECHO):** nº83 en Hogar y Cocina, **nº1 en "Cajas para Botas y Zapatos"**, 100+/semana.
  - Quejas: "opiniones diversas sobre la facilidad de armado, resistencia y relación calidad-precio". Facilidad de armado **232 (146/86)**, resistencia **155 (69/86)**, calidad-precio 111 (77/34). 1★ = 9%.
  - Fuente: [B084VGDD7M](https://www.amazon.com.mx/dp/B084VGDD7M) (acc. 2026-10-22)
- **HECHO:** otros juegos de 9–12 cajas tienen 3.4–3.9★ (SIMPLELIFE 3.4★ (20), HOMEASY 3.9★ (91), cajas con puerta 3.7★ (4)). — [búsqueda](https://www.amazon.com.mx/s?k=cajas+apilables+para+zapatos) (acc. 2026-10-22)

**5) Protector de colchón impermeable**
- **Resultados (HECHO):** "1 a 48 de 426 resultados". Top orgánico:
  - #1 **ESQUIMAL individual** (B0BLTKZBMQ): $271.92, 4.6★ (5,683), **1 k+/mes**, "Más vendido".
  - #2 **Dreamlab Queen** (B0899BJWLW): $398, 4.7★ (7,895), **600+/mes**.
  - #3 Linenspa individual: $263.97, 4.6★ (111,997), 100+, "Más vendido".
  - #4 ESQUIMAL matrimonial con fundas: $390.15, 50+.
  - #5 AI-PIKA: $379, 4.6★ (299), 100+.
  - El ESQUIMAL matrimonial (patrocinado) también muestra 1 k+. Top 20: $239–$799 (mediana $385). **Suma mínima top 5: 1,850/mes**. — [búsqueda](https://www.amazon.com.mx/s?k=protector+de+colchon+impermeable) (acc. 2026-10-22)
- **Fichas (HECHO):**
  - ESQUIMAL individual: **nº4 en Hogar y Cocina**, nº1 en "Protectores de Colchón para Cama", 200+/semana.
  - Dreamlab Queen: nº56 / nº2, 50+/semana.
  - Fuentes: [B0BLTKZBMQ](https://www.amazon.com.mx/dp/B0BLTKZBMQ); [B0899BJWLW](https://www.amazon.com.mx/dp/B0899BJWLW) (acc. 2026-10-22)
- **Quejas (HECHO):**
  - Dreamlab: "algunos usuarios señalan que el material es muy delgado y esperaban que el plástico fuera más grueso". Delgadez **149 (44/105)**, ruido 126 (76/50), impermeabilidad 219 (163/56).
  - ESQUIMAL: delgadez 139 (48/91), calidad del material 128 (85/43), ruido 117 (77/40).
  - Fuentes: fichas citadas (acc. 2026-10-22)

**6) Carrito / base para garrafón**
- **Resultados (HECHO):** "carrito para garrafon" = 533; "base para garrafon" = 382. — [búsqueda carrito](https://www.amazon.com.mx/s?k=carrito+para+garrafon); [búsqueda base](https://www.amazon.com.mx/s?k=base+para+garrafon) (acc. 2026-10-22)
- **Carritos (HECHO):** el top orgánico mezcla carritos de garrafón con diablitos y carritos de mandado genéricos:
  - "Diablito Reforzado para Garrafón" (B0H51LL41G): $598, **3.8★ (6)**, 100+/mes, "Más vendido". En la ficha no se ve BSR y el 23% de las calificaciones son de 1★.
  - Carro plegable: $341.04, 4.3★ (541), 100+.
  - Pretul DIA-100P (diablo de carga genérico): $745, 4.6★ (1,523), 200+.
  - Raganet carrito utilitario: $698, 3.8★ (8), 200+.
  - Los "Carrito Reforzado para Garrafón" específicos ($580–$698) tienen 0–5 calificaciones y no tienen insignia.
  - Solo 8 de 20 con insignia. **Suma mínima top 5: 400/mes** (incluye carritos no específicos).
  - Fuentes: [búsqueda](https://www.amazon.com.mx/s?k=carrito+para+garrafon); [B0H51LL41G](https://www.amazon.com.mx/dp/B0H51LL41G) (acc. 2026-10-22)
- **Bases y estantes (HECHO):**
  - YUDSKU estante de 4 niveles (B0FKSWZN8M): $1,099 en búsqueda, 4.6★ (273), 50+, nº2,913 en Hogar y Cocina.
  - Soporte de 3 niveles: $1,068, 4.8★ (59), 50+.
  - **Raganet estante para 3 garrafones** (B0CP4HJDRM): $498, 4.6★ (490), **200+/mes**, nº2,362 en Hogar y Cocina, nº26 en "Enfriadores de Agua, Filtros y cartuchos".
  - MU:4LIFE soporte de mesa con 2 válvulas: $259, 4.2★ (28).
  - **MU:4LIFE soporte inclinable 360°** (B0GSX7R37R): **$589, 4.2★ (9), sin insignia**, nº18,687 en Hogar y Cocina, nº43 en "PortaBotellas".
  - Soporte de mesa genérico: $149, **2.6★ (25)**.
  - Solo 4 de 20 con insignia. **Suma mínima top 5: 100/mes**.
  - Fuentes: [búsqueda](https://www.amazon.com.mx/s?k=base+para+garrafon); [B0CP4HJDRM](https://www.amazon.com.mx/dp/B0CP4HJDRM); [B0GSX7R37R](https://www.amazon.com.mx/dp/B0GSX7R37R); [B0FKSWZN8M](https://www.amazon.com.mx/dp/B0FKSWZN8M) (acc. 2026-10-22)
- **Quejas:** No disponible para carritos específicos (no hay resumen IA con tan pocas reseñas). Raganet (estante): aspectos positivos; resistencia 49 (43/6). — [B0CP4HJDRM](https://www.amazon.com.mx/dp/B0CP4HJDRM) (acc. 2026-10-22)

**7) Organizador bajo tarja / fregadero de 2 niveles**
- **Resultados (HECHO):** "más de 20,000" para "organizador bajo fregadero 2 niveles". Top orgánico:
  - INGEQUIS: $269.09, 4.1★ (4), 50+.
  - Hisemy: $398, 4.5★ (221), sin insignia.
  - B0HJ2TBMK7: $689.99, 4.6★ (104), 50+.
  - B0CHBB8H86: $399.99, 4.4★ (56), sin insignia.
  - B0G2BPNFJ9 en L: $449.99, 4.5★ (365), 50+.
  - Solo 4 de 20 con insignia. Top 20: $269–$899 (mediana $602). **Suma mínima top 5: 150/mes**. — [búsqueda](https://www.amazon.com.mx/s?k=organizador+bajo+fregadero+2+niveles) (acc. 2026-10-22)
- **HAWOO 2 pack (B0CWLD39L3, patrocinado) (HECHO):** $755.92 en búsqueda, 4.2★ (341), **200+/mes**, nº2,302 en Hogar y Cocina, nº2 en "Organizadores de Cajones de Cocina".
  - Quejas: **deslizamiento 17 (4/13)**, tamaño 20 (15/5); 1★ = 7% y 2★ = 7%.
  - Fuente: [B0CWLD39L3](https://www.amazon.com.mx/dp/B0CWLD39L3) (acc. 2026-10-22)
- **Más vendidos "Organizadores para Armarios" (HECHO):**
  - #1 Lifewit organizador de tapas: $279.99.
  - #3 NETEL 2-pack de cajones extraíbles: $989.10.
  - #4 organizador de fregadero de acero de 2 niveles: $419, 4.4★ (67).
  - #6 **Delamu 2 juegos de 2 niveles: $539.99, 4.4★ (11,838)**.
  - #7 Delamu paquete de 2: $649.99.
  - #10 B0G2BPNFJ9.
  - Fuente: [Más vendidos](https://www.amazon.com.mx/gp/bestsellers/kitchen/9725283011) (acc. 2026-10-22)

### Inferences
- **ESTIMACIÓN (fuerza relativa de la demanda en Amazon, por la suma mínima del top 5):** ganchos (5,400) ≫ protector de colchón (1,850) > cajas para zapatos (1,550) > burlete/guardapolvo (750–800) ≈ bolsas al vacío (700) > carrito de garrafón (400, mezclado) > organizador bajo tarja (150) ≈ base de garrafón (100).
- **HIPÓTESIS (guardapolvo):** El dolor dominante es la **adherencia**: las quejas negativas superan a las positivas en CARYWON y OUARTV. Un kit que resuelva la fijación (adhesivo reforzado, versión con tornillos o tipo "U" deslizable) atacaría la queja principal. El reto es el **precio piso**: hay listados con insignia a $55–$110.
- **HIPÓTESIS (bolsas al vacío):** El posicionamiento "bomba manual" ya no es el centro de la categoría en Amazon MX; la bomba eléctrica domina los primeros lugares. Un kit manual competiría en precio contra packs de $159–$293 con 300+/mes.
- **HIPÓTESIS (ganchos):** Hay demanda muy alta, pero el mercado está concentrado en Raganet/RagaBasics (misma familia de reseñas) a $199–$279 por 50 piezas, con distribución Amazon. La queja "resistencia" (37 negativas) es la única brecha visible.
- **HIPÓTESIS (garrafón):** La demanda en Amazon del accesorio específico es delgada. Los carritos específicos casi no tienen reseñas, y el estante Raganet ($498, 200+/mes) es la señal más clara. El canal local (Marketplace) podría pesar más que Amazon para este producto (no verificado).

### Gaps
- Peso y medidas de los líderes: no extraídos en este pase.
- Amazon Basics ganchos 100 pzs ($877.12 según snippet previo): no se verificó.
- ML: fuera de alcance (bloqueado).

---

## 2. Limpieza (productos 8–12): ¿qué muestra Amazon MX hoy?

### Takeaway
La **regadera con filtro** y el **tendedero retráctil** tienen demanda mensual clara (500+/mes en los líderes de regadera, 100–200+/mes repartidos en muchos tendederos). La **escoba de goma** y el **trapeador con atomizador** tienen muchas reseñas acumuladas pero **casi ninguna insignia mensual**. Las **cintas antiderrapante y selladora** muestran señales débiles.

### Cited Findings

**8) Regadera de mano alta presión con filtro**
- **Resultados (HECHO):** "más de 30,000" para "regadera alta presion con filtro". Top orgánico:
  - #1 2 en 1 con filtro: $999.99, 5.0★ (6), sin insignia.
  - #2 **cabezal 6" con filtro de 15 etapas** (B0B5JR9F3N): $448.20, 4.6★ (1,267), **500+/mes**.
  - #3 B0DPQK4WTJ 10" con 20 capas: $682.05, 4.1★ (337), 50+, "Más vendido".
  - #4 Aguacero: $1,935, **3.7★ (58)**, 200+.
  - #5 8" con 2 filtros: $473.20, 4.0★ (39), 50+.
  - Otros: Jasinber combo (sin filtro) $498, 4.6★ (3,086), 500+, "Más vendido"; AZULDIMEN B0DK53X8JT $469, 4.6★ (169), 100+; JESWO $378.38, 100+.
  - 13 de 20 con insignia. Top 20: $298–$1,935 (mediana $459). **Suma mínima top 5: 800/mes**. — [búsqueda](https://www.amazon.com.mx/s?k=regadera+alta+presion+con+filtro) (acc. 2026-10-22)
- **Fichas (HECHO):**
  - B0B5JR9F3N: BSR no visible. "Opiniones diversas sobre el flujo de agua". Flujo 61 (42/19), presión 62 (52/10).
  - Jasinber (B09DG4W7N8): **nº11 en Herramientas y Mejoras del Hogar, nº1 en "Regaderas de Mano" y nº1 en "Regaderas Fijas"**. Material 80 (40/40).
  - Fuentes: [B0B5JR9F3N](https://www.amazon.com.mx/dp/B0B5JR9F3N); [B09DG4W7N8](https://www.amazon.com.mx/dp/B09DG4W7N8) (acc. 2026-10-22)

**9) Tendedero retráctil de pared**
- **Resultados (HECHO):** "más de 40,000". Top orgánico:
  - #1 acero inoxidable 5.1 m: $498, 4.6★ (23), 100+.
  - #2 Sugarzoon 2 pzs 2.8 m: $298, 4.4★ (683), 100+.
  - #3 15 m 2PCS (B0DCVP64PL): $298, 4.5★ (207), **200+**.
  - #4 AI-PIKA 5.1 m: $215, 4.7★ (47), 50+.
  - #5 plegable de pared: $437.40, 4.7★ (551), 50+.
  - Otros: KIROGILY $369, 4.4★ (87), 100+; GALASALA 5.2 m $369, 4.5★ (150), 100+.
  - 14 de 20 con insignia. Top 20: $179–$895 (mediana $369). **Suma mínima top 5: 500/mes**. — [búsqueda](https://www.amazon.com.mx/s?k=tendedero+retractil+de+pared) (acc. 2026-10-22)
- **Más vendidos "Tendederos" (HECHO):**
  - **#1 SONGMICS plegable de 2 niveles (de piso, no retráctil): $1,199.99, 4.8★ (1,935)**.
  - #3 B0DCVP64PL: $298.
  - #4 AI-PIKA: $215.
  - #5 Sugarzoon: $298.
  - #8 2PCS retráctil: $389.99, 4.5★ (694).
  - Fichas: B0DCVP64PL nº1,460 en Hogar y Cocina / **nº3 en Tendederos**; KIROGILY nº3,121 / nº13.
  - Fuentes: [Más vendidos](https://www.amazon.com.mx/gp/bestsellers/kitchen/9756907011); [B0DCVP64PL](https://www.amazon.com.mx/dp/B0DCVP64PL); [B0F59VB6YT](https://www.amazon.com.mx/dp/B0F59VB6YT) (acc. 2026-10-22)
- **Quejas (HECHO):**
  - B0DCVP64PL: "algunos usuarios reportan que se afloja cuando se tiende la ropa y que pierde la tensión fácilmente". Ajuste 8 (2/6), resistencia al peso 5 (2/3).
  - KIROGILY: durabilidad 5 (2/3).
  - Fuentes: fichas citadas (acc. 2026-10-22)

**10) Escoba de goma / silicón**
- **Resultados (HECHO):** 477. Top orgánico:
  - Escoba de goma B0C3QR3DL1: $228, 4.4★ (390), sin insignia.
  - Garselay: $255.56, 4.3★ (101), sin insignia.
  - **MR.SIGA (B08HN63XK9): $499.99, 4.5★ (14,858), 50+**.
  - B0FNWKKNMY: $368, 4.4★ (23), sin insignia.
  - B0FVD5LM3Z: $259, 4.4★ (10), sin insignia.
  - **Solo 4 de 20 con insignia. Suma mínima top 5: 50/mes**. Top 20: $100–$500 (mediana $261). — [búsqueda](https://www.amazon.com.mx/s?k=escoba+de+goma) (acc. 2026-10-22)
- **Fichas (HECHO):**
  - MR.SIGA: nº10,154 en Hogar y Cocina, nº20 en "Escobillas de Goma".
  - **FURemover (B000EFDOOA): $320.15 en búsqueda (la ficha dice "Actualmente no disponible"), 4.7★ (103,517), sin insignia mensual, nº29,734 en Hogar y Cocina, nº33 en "Escobas"**. Ajuste de altura del mango 19 (12/7), resistencia 17 (10/7).
  - Jalador 3 en 1 con cepillo de goma: **2.7★ (21)**, 50+.
  - Fuentes: [B08HN63XK9](https://www.amazon.com.mx/dp/B08HN63XK9); [B000EFDOOA](https://www.amazon.com.mx/dp/B000EFDOOA) (acc. 2026-10-22)

**11) Trapeador con atomizador (spray mop)**
- **Resultados (HECHO):** 418 para "trapeador con atomizador". Top orgánico:
  - #1 B0CXDHZYFS: $398, 4.3★ (261), **100+**.
  - #2 MEXERRIS: $378.91, 4.4★ (7,132), sin insignia.
  - #3 B0C4GRW4J9: $398, 4.2★ (372), 50+.
  - #4 Rubbermaid Reveal: $902.02, 4.4★ (2,518), sin insignia.
  - #5 fregona en aerosol: $475.24, 4.6★ (1,812), sin insignia.
  - Otros: MEXERRIS B07V5TNCKH $502.86, 4.4★ (18,593), "Más vendido" sin insignia mensual; Magitel $266.27, 4.1★ (125); **Vileda Promist MAX $978, 4.2★ (9)**; genéricos con 2.0★ (4) y 2.6★ (11).
  - 5 de 20 con insignia. Top 20: $139–$1,246 (mediana $472). **Suma mínima top 5: 150/mes**. — [búsqueda](https://www.amazon.com.mx/s?k=trapeador+con+atomizador) (acc. 2026-10-22)
- **Fichas (HECHO):**
  - B0CXDHZYFS: nº3,056 en Hogar y Cocina, nº7 en "Trapeador Húmedo y Seco Doméstico". "Preocupaciones significativas sobre su durabilidad, ya que algunos mencionan que se rompió en el primer uso". **Durabilidad 16 (1/15)**, funcionalidad 30 (19/11).
  - MEXERRIS B07V5TNCKH: nº521 en Industria, Empresas y Ciencia, nº1 en "Trapeadores Húmedos Comerciales".
  - Fuentes: [B0CXDHZYFS](https://www.amazon.com.mx/dp/B0CXDHZYFS); [B07V5TNCKH](https://www.amazon.com.mx/dp/B07V5TNCKH) (acc. 2026-10-22)

**12) Cinta antiderrapante para regadera / cinta selladora para tarja**
- **Antiderrapante (HECHO):** "más de 40,000" resultados. Top orgánico:
  - **3M Safety-Walk (B009NP1N0Y): $263.38, 4.4★ (5,230), 50+, nº4,709 en Hogar y Cocina, nº1 en "Calcomanías Antiderrapantes para Tina"**.
  - 3M (otra presentación): $489, 50+.
  - **Truper CIAH-25T 5 m transparente (B0BNWKZRV2): $200, 4.4★ (67), 50+**, nº28 en "Cinta Adhesiva para Embalar".
  - BOMEI 50 mm×10 m: $270.89, 4.7★ (120), 100+, "Más vendido".
  - Calcomanías de 24 piezas con 3.0–3.9★.
  - 7 de 20 con insignia. **Suma mínima top 5: 150/mes**. Top 20: $160–$679 (mediana $234).
  - Fuentes: [búsqueda](https://www.amazon.com.mx/s?k=cinta+antiderrapante+regadera); [B009NP1N0Y](https://www.amazon.com.mx/dp/B009NP1N0Y); [B0BNWKZRV2](https://www.amazon.com.mx/dp/B0BNWKZRV2) (acc. 2026-10-22)
- **Quejas 3M (HECHO):** "expresan descontento con la durabilidad". **Adherencia 114 (70/44)**, durabilidad 17 (3/14). — [B009NP1N0Y](https://www.amazon.com.mx/dp/B009NP1N0Y) (acc. 2026-10-22)
- **Selladora (HECHO):** "más de 4,000" resultados. Top orgánico:
  - SHERCHPRY: $241.69, sin calificaciones.
  - Calafateo: $133.20, 4.1★ (294).
  - Silicón media caña 2 m (B0H73QBTKH): $369, 4.5★ (57), 50+, nº446 en Cintas de Impermeabilización.
  - $159, 4.0★ (25).
  - $114.80, 4.0★ (17).
  - Fuera del top 5: B0C37PD9KZ PVC a $89, 4.1★ (1,193), 50+; varias con 3.4–3.8★.
  - **Solo 2 de 20 con insignia. Suma mínima top 5: 50/mes**.
  - Fuentes: [búsqueda](https://www.amazon.com.mx/s?k=cinta+selladora+para+tarja); [B0H73QBTKH](https://www.amazon.com.mx/dp/B0H73QBTKH) (acc. 2026-10-22)

### Inferences
- **ESTIMACIÓN (fuerza en Amazon por suma mínima top 5):** regadera (800) > tendedero (500) > trapeador con atomizador (150) ≈ cinta antiderrapante (150) > escoba de goma (50) ≈ cinta selladora (50).
- **HIPÓTESIS (escoba de goma):** Las decenas de miles de reseñas de FURemover y MR.SIGA son acumuladas y, en el caso de FURemover, probablemente globales. La demanda mensual actual en Amazon MX es baja: casi no hay insignias y los BSR están en nº10,000–30,000 de Hogar y Cocina.
- **HIPÓTESIS (regadera):** La queja "no aumentó la presión" de la nota previa no domina en el líder. Lo que aparece son opiniones mixtas sobre el **flujo de agua** (19 negativas de 61). El mensaje de venta debería prometer filtración y comodidad, no "más presión".
- **HIPÓTESIS (tendedero):** El hueco de calidad visible es la **pérdida de tensión del cordón**. Un modelo con cable de acero y trinquete respondería a esa queja.

### Gaps
- Trends de "escoba de goma" y de las cintas: no se consultaron (no estaban en la lista pedida).
- BSR del cabezal de regadera B0B5JR9F3N: no visible en la ficha.

---

## 3. Auto/moto (productos 13–19): ¿qué muestra Amazon MX hoy?

### Takeaway
La **funda para moto** es el único producto de moto con demanda mensual fuerte en Amazon MX: 500+/mes y el **nº1 de "Motos, Accesorios y Piezas"**. El **soporte de celular** y el **organizador de cajuela** tienen líderes de 100–200+/mes. La **mochila térmica**, el **impermeable** y los **cubre puños/manoplas** muestran señales débiles en Amazon (pocas insignias, pocas reseñas). La **hamaca para perro** confirma lo que ya reportaba `mascotas.md`.

### Cited Findings

**13) Mochila térmica para repartidor**
- **Resultados (HECHO):** "más de 3,000". Top orgánico:
  - Ytonet 60 L gris: $598, 4.6★ (780), sin insignia.
  - **Ytonet 60 L negra (B0H5RK7ZGQ): $598, 4.6★ (780), 50+, nº5,956 en Hogar y Cocina, nº3 en "Bolsas Térmicas"**.
  - B0F31TJDM5: $599.99, 4.2★ (44), 50+.
  - B0FPFGJKL7: $539, 4.5★ (3).
  - B0HK64L2P6: $849, sin calificaciones.
  - BREEZEE: $529, 4.4★ (74), sin insignia.
  - **Solo 2 de 20 con insignia. Suma mínima top 5: 100/mes**. Top 20: $369–$2,960 (mediana $760).
  - Quejas Ytonet: "opiniones diversas sobre su resistencia" (6/6).
  - Fuentes: [búsqueda](https://www.amazon.com.mx/s?k=mochila+termica+para+repartidor); [B0H5RK7ZGQ](https://www.amazon.com.mx/dp/B0H5RK7ZGQ) (acc. 2026-10-22)

**14) Impermeable para moto de 2 piezas**
- **Resultados (HECHO):** "más de 2,000". Top orgánico:
  - 3 pzs: $298, 4.4★ (19), sin insignia.
  - Reflejante con capucha: $431.10, 4.7★ (31), 50+.
  - **2 piezas (B0GDWX5Y17): $399, 4.4★ (25), 100+, nº24,357 en Ropa, Zapatos y Accesorios, nº71 en "Ropa Impermeable y de Nieve para Hombre"**.
  - Con reflectante 360°: $279, 4.4★ (33), 50+.
  - B0CG33QHNV: $532.38, 4.5★ (383), sin insignia.
  - 6 de 20 con insignia. **Suma mínima top 5: 200/mes**. Top 20: $132–$1,637 (mediana $469).
  - Resumen IA: no visible (pocas reseñas). 1★ = 10% en B0GDWX5Y17.
  - Fuentes: [búsqueda](https://www.amazon.com.mx/s?k=impermeable+para+moto); [B0GDWX5Y17](https://www.amazon.com.mx/dp/B0GDWX5Y17) (acc. 2026-10-22)

**15) Cubre puños / manoplas para moto**
- **HECHO:** "cubre puños para moto" da "más de 3,000" resultados, pero el top son **protectores rígidos (handguards) con LED**, no manoplas térmicas. Ejemplos: $182 4.1★ (15); $198.98 4.5★ (2); $169.99 5.0★ (9) con 50+. **Solo 1 de 20 con insignia; suma mínima top 5: 50/mes**. — [búsqueda](https://www.amazon.com.mx/s?k=cubre+pu%C3%B1os+para+moto) (acc. 2026-10-22)
- **HECHO (manoplas térmicas):** "manoplas para moto" devuelve sobre todo guantes. Manoplas de manillar:
  - B0FMDTB9WL: $438.10, 4.0★ (74), **sin insignia**, nº39,791 en Automotriz y Motocicletas, nº4,721 en "Motos, Accesorios y Piezas". "Mantienen las manos calientes gracias a su forro cálido". **1★ = 16%**.
  - KIMISS: $305, 4.7★ (7).
  - Dos patrocinadas sin calificaciones: $163.19 y $479.11.
  - Guantes hanylish: $115.55–$119, 4.6★ (4,711), 100+.
  - Fuentes: [búsqueda](https://www.amazon.com.mx/s?k=manoplas+para+moto); [B0FMDTB9WL](https://www.amazon.com.mx/dp/B0FMDTB9WL) (acc. 2026-10-22)

**16) Organizador plegable para cajuela**
- **Resultados (HECHO):** "más de 2,000". Top orgánico:
  - **B0FRM1LKFR: $263.09, 4.7★ (127), 100+, nº43 en Automotriz y Motocicletas, nº1 en "Organizadores de Maletero de Automóvil"**.
  - B0FWR37ZH7: $265, 4.8★ (22), 100+.
  - Hisemy con hielera: $663.10, 4.7★ (47), 50+, "Más vendido".
  - Colgante 90×27 cm: $175.99, 4.3★ (41).
  - B0CRBKJ5NP: $135, 4.2★ (174).
  - 5 de 20 con insignia. **Suma mínima top 5: 250/mes**. Top 20: $100–$750 (mediana $275).
  - Fuentes: [búsqueda](https://www.amazon.com.mx/s?k=organizador+para+cajuela); [B0FRM1LKFR](https://www.amazon.com.mx/dp/B0FRM1LKFR) (acc. 2026-10-22)
- **Quejas (HECHO):** del velcro de la base, "algunos mencionan que no se queda pegado"; tamaño 9 (6/3). Hay genéricos con 3.1★ (5) y 3.3★ (7). — [B0FRM1LKFR](https://www.amazon.com.mx/dp/B0FRM1LKFR); [búsqueda](https://www.amazon.com.mx/s?k=organizador+para+cajuela) (acc. 2026-10-22)

**17) Funda / cubierta impermeable para moto**
- **Resultados (HECHO):** 394 para "funda para moto impermeable". Top orgánico:
  - **VEKENSEE 210D (B0CKXJNY2Z): $242.10, 4.3★ (1,228), 500+/mes, "Más vendido"**.
  - EASYTAO grande: $199, 4.2★ (7), 200+.
  - B0H6JKSGS1: $247.99, 4.2★ (132), 50+, "Más vendido".
  - **PUBAMALL (B07PZ9J97D): $259.65, 4.5★ (7,375), 200+**.
  - B0GL8FYMMD: $228.99, 4.7★ (38), 100+.
  - 11 de 20 con insignia. **Suma mínima top 5: 1,050/mes**. Top 20: $189–$1,000 (mediana $239).
  - Fuente: [búsqueda](https://www.amazon.com.mx/s?k=funda+para+moto+impermeable) (acc. 2026-10-22)
- **Fichas y Más vendidos (HECHO):**
  - VEKENSEE: **nº14 en Automotriz y Motocicletas, nº1 en "Motos, Accesorios y Piezas"**, 100+/semana.
  - PUBAMALL: nº28 / **nº2**, 50+/semana.
  - En Más vendidos "Motos, Accesorios y Piezas": #1 VEKENSEE, #2 PUBAMALL, #3 guantes PUNKZZ, #4 EASYTAO, #6 guantes hanylish, #10 funda 190T.
  - Fuentes: [B0CKXJNY2Z](https://www.amazon.com.mx/dp/B0CKXJNY2Z); [B07PZ9J97D](https://www.amazon.com.mx/dp/B07PZ9J97D); [Más vendidos](https://www.amazon.com.mx/gp/bestsellers/automotive/14327173011) (acc. 2026-10-22)
- **Quejas (HECHO):**
  - VEKENSEE: "señalan que no es impermeable y que sí pasa el agua cuando llueve". **Impermeabilidad 65 (16/49)**, delgadez 61 (22/39).
  - PUBAMALL: "mencionan que se rompe muy rápido y no dura nada". **Durabilidad 339 (91/248)**, delgadez 188 (31/157), impermeabilidad 189 (97/92).
  - Fuentes: fichas citadas (acc. 2026-10-22)

**18) Hamaca / cubreasiento para perro en auto (solo huecos; el detalle está en `mascotas.md`)**
- **HECHO:** "más de 40,000" resultados para "hamaca para perro auto". Top orgánico:
  - Jasonwell: $398.99, 4.7★ (201), 50+.
  - ENGREPO: $599, 4.5★ (209), 100+.
  - B0CQNNS8WQ: $539.10, 4.4★ (86), 100+.
  - Extensor rígido: $899.99, 4.1★ (29), 50+.
  - **Raganet B0CN7CRSLH: $198, 4.2★ (1,785), 500+, "Más vendido"**.
  - Otros: Mancro $364 (200+); PUBAMALL $429 (300+).
  - 10 de 20 con insignia. **Suma mínima top 5: 800/mes**. Top 20: $198–$1,210 (mediana $499). Coincide con `mascotas.md` (BSR, quejas de durabilidad de Raganet y Trends ya documentados ahí).
  - Fuente: [búsqueda](https://www.amazon.com.mx/s?k=hamaca+para+perro+auto) (acc. 2026-10-22)

**19) Soporte de celular para moto**
- **Resultados (HECHO):** 342 para "soporte celular para moto". Top orgánico:
  - **Lamicall B085DMV7XD: $449, 4.6★ (51,716), 200+ en búsqueda (100+ en la ficha), nº1,263 en Electrónicos, nº1 en "Monturas de Manillar de Celular"**.
  - Antivibración: $298, sin calificaciones.
  - Universal B0HBSVZK1F: $99, 5.0★ (1), 200+, "Más vendido" (ficha: nº15,597 en Electrónicos, nº18 en Monturas).
  - Lamicall 720° con amortiguador: $999, 4.7★ (168).
  - FHZLAJ: $379, 4.6★ (80).
  - Otros: Lamicall antivibración $699, 4.7★ (9,071), 100+; Archy $149.99, 4.1★ (377); Lamicall de bloqueo rápido $339, 50+.
  - 4 de 20 con insignia. **Suma mínima top 5: 400/mes**. Top 20: $99–$999 (mediana $299).
  - Fuentes: [búsqueda](https://www.amazon.com.mx/s?k=soporte+celular+para+moto); [B085DMV7XD](https://www.amazon.com.mx/dp/B085DMV7XD); [B0HBSVZK1F](https://www.amazon.com.mx/dp/B0HBSVZK1F) (acc. 2026-10-22)
- **Quejas Lamicall (HECHO):** predominan las positivas. Estabilidad 191 (158/33), ajuste 86 (66/20). — [B085DMV7XD](https://www.amazon.com.mx/dp/B085DMV7XD) (acc. 2026-10-22)

### Inferences
- **ESTIMACIÓN (fuerza en Amazon por suma mínima top 5):** funda para moto (1,050) > hamaca para perro (800) > soporte de celular (400) > organizador de cajuela (250) > impermeable (200) > mochila térmica (100) > cubre puños (50) ≈ manoplas (0 en el top 5 orgánico).
- **HIPÓTESIS (funda para moto):** Hay demanda clara y una **brecha de calidad documentada**: los dos líderes acumulan quejas de "no es impermeable" y "se rompe rápido". Una funda de tela más gruesa (≥210D con recubrimiento real) a $300–$400 tendría argumento. El reto es un precio piso de $199–$260.
- **HIPÓTESIS (productos para repartidor):** La mochila térmica, el impermeable y las manoplas tienen poca tracción en Amazon MX. Esto puede indicar que el repartidor compra en tianguis, ML o tiendas físicas, no que la demanda sea baja (no verificado; ML bloqueado).
- **HIPÓTESIS (cubre puños):** En Amazon el término se asocia a protectores rígidos. Al anunciar manoplas térmicas conviene usar "manoplas térmicas para moto" o "guantes para manubrio".

### Gaps
- Precio y BSR de manoplas térmicas con más reseñas: no existe un líder claro en Amazon MX.
- Mochila térmica: no se revisó la categoría de Más vendidos "Bolsas Térmicas".

---

## 4. Google Trends México (12 meses, geo=MX): ¿qué interés de búsqueda tienen los términos?

### Takeaway
Con volumen suficiente y series estables: **"regadera"** (≈6× "zapatera"), **"zapatera"**, **"tendedero"** (≈0.6× zapatera), **"cubre colchon"**, **"funda para moto"** (al alza) y **"porta garrafon"**. Con volumen bajo pero con forma estacional legible: "guardapolvo puerta", "burlete", "cubre puños moto" (pico invernal) e "impermeable para moto" (pico en lluvias). **Volumen insuficiente:** "ganchos de terciopelo", "spray mop", "mochila térmica", "organizador cajuela", "protector de colchón" (con acento y frase exacta), "bolsas al vacío" (con acento), "soporte celular moto", "mochila repartidor" y "organizador fregadero".

### Cited Findings
Valores = promedio semanal del periodo (0–100) dentro de cada lote. "Ind." = consulta individual del término (escala propia, útil para ver el pico y la forma). Los promedios mensuales son cálculo propio sobre las semanas de cada mes. Oct 2025 tiene 2 semanas y oct 2026 es parcial.

**Lote 1** (zapatera, guardapolvo puerta, bolsas al vacío, ganchos de terciopelo, protector de colchón) — [Trends](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=zapatera,guardapolvo%20puerta,bolsas%20al%20vac%C3%ADo,ganchos%20de%20terciopelo,protector%20de%20colch%C3%B3n) (acc. 2026-10-22)
- **zapatera (HECHO):** promedio 65.7; 0 semanas en 0.
  - Pico mensual: **ene 2026 (84.0)**; dic 2025 = 80.2.
  - Mínimos: jun 2026 (55.8) y oct 2026 (54.3).
  - Dirección: **estable con pico dic–ene**.
- **guardapolvo puerta (HECHO):** promedio 3.6 en el lote (≈5% de zapatera); 13/53 semanas en 0.
  - Ind.: promedio 37.3; pico mensual **jul 2026 (54.2)**, may 2026 = 53.4, ene 2026 = 48.2, mínimo feb 2026 = 11.2.
  - Nov–ene = 38.7 frente a jul–sep = 45.2 → **estable/ligeramente al alza; volumen bajo**.
  - [Ind.](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=guardapolvo%20puerta)
- **bolsas al vacío (con acento) (HECHO):** promedio 0.7; 41/53 semanas en 0 → **volumen insuficiente**.
- **ganchos de terciopelo (HECHO):** promedio 0.8; 41/53 en 0 → **volumen insuficiente**. Ind.: pico ene 2026, serie ruidosa.
  - [Ind.](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=ganchos%20de%20terciopelo)
- **protector de colchón (HECHO):** promedio 2.0; 28/53 en 0 → **volumen insuficiente**.

**Lote 2** (zapatera, tendedero, regadera, spray mop, mochila térmica) — [Trends](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=zapatera,tendedero,regadera,spray%20mop,mochila%20t%C3%A9rmica) (acc. 2026-10-22)
- **regadera (HECHO):** promedio 85.0 frente a zapatera 14.2 en el mismo lote (**≈6.0×**).
  - Pico **ene 2026 (94.5)**, mínimo jun 2026 (69.5); oct 2026 = 90.7.
  - Nov–ene = 90.3 frente a jul–sep = 87.2 → **estable, alto**.
- **tendedero (HECHO):** promedio 9.0 frente a zapatera 14.2 (**≈0.63×**).
  - Ind.: promedio 79.4; pico **oct 2026 (93.7)**, ene 2026 = 86.0; mínimos jul–ago 2026 (≈72).
  - → **estable, con repunte en oct 2026**.
  - [Ind.](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=tendedero)
- **spray mop (HECHO):** 53/53 semanas en 0 en el lote; en Ind., 51/53 en 0 → **volumen insuficiente**.
- **mochila térmica (HECHO):** 51/53 en 0 → **volumen insuficiente**.

**Lote 3** (zapatera, impermeable para moto, cubre puños moto, organizador cajuela, funda para moto) — [Trends](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=zapatera,impermeable%20para%20moto,cubre%20pu%C3%B1os%20moto,organizador%20cajuela,funda%20para%20moto) (acc. 2026-10-22)
- **funda para moto (HECHO):** promedio 12.9 (≈20% de zapatera); 0 semanas en 0.
  - Ind.: promedio 60.1; pico **dic 2025 (68.5)**; oct 2025 = 40.5 → sep 2026 = 65.5.
  - Nov–ene = 59.0 frente a jul–sep = 65.0 → **al alza/estable**.
  - [Ind.](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=funda%20para%20moto)
- **impermeable para moto (HECHO):** promedio 2.7; 30/53 en 0.
  - Ind.: pico **jun 2026 (59.5)**, may 2026 = 52.4; nov 2025–feb 2026 ≈ 0–6; oct 2026 = 44.0 (parcial).
  - → **estacional (temporada de lluvias); volumen bajo**.
  - [Ind.](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=impermeable%20para%20moto)
- **cubre puños moto (HECHO):** promedio 2.8; 21/53 en 0.
  - Ind.: pico **dic 2025 (79.5)**, feb 2026 = 62.5; mínimo may 2026 (15.4); repunte ago 2026 (56.6); oct 2026 = 56.3.
  - → **estacional invernal; volumen bajo**.
  - [Ind.](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=cubre%20pu%C3%B1os%20moto)
- **organizador cajuela (HECHO):** 52/53 en 0 → **volumen insuficiente**.

**Lote 4: variantes coloquiales** (zapatera, burlete, cubre colchon, bolsas al vacio, trapeador) — [Trends](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=zapatera,burlete,cubre%20colchon,bolsas%20al%20vacio,trapeador) (acc. 2026-10-22)
- **cubre colchon (HECHO):** promedio 25.5 (≈39% de zapatera); 0 semanas en 0.
  - Pico **dic 2025 (33.2)**, nov 2025 = 32.4; oct 2026 = 22.3.
  - Nov–ene = 31.2 frente a jul–sep = 24.0 → **estacional nov–dic; estable**.
- **bolsas al vacio (sin acento) (HECHO):** promedio 6.3; 2/53 en 0.
  - Pico **ene 2026 (8.5)**, feb 2026 = 7.8; sep 2026 = 3.8; oct 2026 = 4.3.
  - → **estable/ligera baja; pico ene–feb**.
- **burlete (HECHO):** promedio 5.7; 6/53 en 0.
  - Pico **jul 2026 (8.8)**; nov–dic 2025 = 3.8.
  - Nov–ene = 4.1 frente a jul–sep = 7.7 → **pico en may–sep, no en invierno**.
- **trapeador (HECHO, proxy amplio de spray mop):** promedio 70.5 (≈1.07× zapatera).
  - Pico ene 2026 (75.8) → **estable, alto**.

**Lote 5** (zapatera, mochila repartidor, soporte celular moto, porta garrafon, organizador fregadero) — [Trends](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=zapatera,mochila%20repartidor,soporte%20celular%20moto,porta%20garrafon,organizador%20fregadero) (acc. 2026-10-22)
- **porta garrafon (HECHO):** promedio 9.4 (≈14% de zapatera); 0 semanas en 0.
  - Pico ene 2026 (10.8), mínimo jun 2026 (7.2) → **estable**.
- **mochila repartidor** (1.2; 37/53 en 0), **soporte celular moto** (1.3; 35/53 en 0) y **organizador fregadero** (0.2; 49/53 en 0) → **volumen insuficiente**.

### Inferences
- **ESTIMACIÓN (escala común = zapatera):**
  - regadera ≈ 85.0 × 4.63 ≈ 394.
  - trapeador ≈ 70.5.
  - zapatera = 65.7.
  - tendedero ≈ 9.0 × 4.63 ≈ 42.
  - cubre colchon ≈ 25.5.
  - funda para moto ≈ 12.9.
  - porta garrafon ≈ 9.4.
  - bolsas al vacio ≈ 6.3.
  - burlete ≈ 5.7.
  - guardapolvo puerta ≈ 3.6.
  - cubre puños moto ≈ 2.8.
  - impermeable para moto ≈ 2.7.
  - Todos los demás < 2.
  - Solo es un orden **relativo** de interés de búsqueda.
- **HIPÓTESIS (términos amplios):** "regadera" incluye la regadera de jardín y la de baño completa, y "zapatera" incluye muebles zapateros. Su volumen sobreestima el interés por la variante concreta (regadera con filtro, cajas apilables).
- **HIPÓTESIS (estacionalidad útil para el calendario):**
  - Burlete y guardapolvo tienen su pico en may–jul (lluvias, polvo, insectos), no en frentes fríos. Esto contradice el supuesto de las notas de hogar ("frío nov–feb: burletes"). Las búsquedas no confirman un pico invernal.
  - Cubre puños: pico en dic–feb.
  - Impermeable para moto: pico en may–jun.
  - Zapatera, bolsas al vacío y cubre colchón: pico en dic–ene.
  - Tendedero: no tiene pico en lluvias (su mínimo es jul–ago) y repunta en oct.
- **Las búsquedas exactas en Google son un mal termómetro para varios productos de nicho:** "ganchos de terciopelo" no tiene volumen en Trends, pero en Amazon es el producto más vendido del grupo (4 k+/mes en un listado).

### Gaps
- "escoba de goma", "cinta antiderrapante" y "organizador bajo tarja" (con esa redacción): no consultados o sin volumen.
- Trends no distingue la intención de compra ni el canal.

---

## 5. ¿Dónde contradicen los datos observados a las cifras previas (snippets)?

### Takeaway
Varias cifras previas estaban desactualizadas o mal atribuidas. Las correcciones más importantes:
- Bolsas al vacío: el #1 de Más vendidos es ESQUIMAL, no Amazon Basics.
- Funda para moto: VEKENSEE es #1, no #4.
- Organizador bajo tarja: NETEL no es #1.
- Escoba de goma: no tiene "la demanda más grande" (casi sin ventas mensuales visibles).
- Guardapolvo: el líder por reseñas (Rabbitstorm) ya no vende de forma visible.
- Trends ya **sí** está disponible.

### Cited Findings
- **Bolsas al vacío:** la nota previa ponía a Amazon Basics como #1 (y en conflicto, a ESQUIMAL como #1). **Observado:** #1 ESQUIMAL (4.6★, 2,928), #2 Amazon Basics (4.7★, 81,588). — [Más vendidos](https://www.amazon.com.mx/gp/bestsellers/kitchen/9756876011) (acc. 2026-10-22)
- **Guardapolvo:** la nota previa destacaba a Rabbitstorm (4.0★, 1,634) como "el que más reseñas tiene". **Observado:** 1,654 calificaciones, **"No disponible por el momento"** (agotado), **sin insignia mensual** y nº51,439 en Herramientas. Los líderes actuales son CARYWON, el kit de 3 PCS (400+/mes cada uno) y OUARTV (3,332 calificaciones, 200+/mes). El LSXD que la nota daba a $139 con 4.6★ (433) aparece ahora como LSXD 37" a $119 con 4.0★ (925) y 100+/mes (podría ser otra variante). — [B087TDFWQK](https://www.amazon.com.mx/dp/B087TDFWQK); [búsqueda](https://www.amazon.com.mx/s?k=guardapolvo+para+puerta) (acc. 2026-10-22)
- **Ganchos:** la nota previa decía Raganet 100 pzs a $729. **Observado:** Raganet 100 pzs a $478.98 con "1 k+/mes". Los "Rank: No disponible" ahora son nº3 en Hogar y Cocina (Raganet 50). — [búsqueda](https://www.amazon.com.mx/s?k=ganchos+de+terciopelo+50+piezas); [B0GHWNY9NG](https://www.amazon.com.mx/dp/B0GHWNY9NG) (acc. 2026-10-22)
- **Cajas para zapatos:** **se confirma** SONGMICS 18 con 900+/mes y nº1 en "Cajas para Botas y Zapatos" (8,961 calificaciones frente a 8.9 mil en el snippet). Kuject (21.4 mil) no apareció en el top 20 observado. — [B084VGDD7M](https://www.amazon.com.mx/dp/B084VGDD7M) (acc. 2026-10-22)
- **Protector de colchón:** el snippet decía Dreamlab "900+/mes"; **observado:** Dreamlab Queen con 600+/mes. ESQUIMAL "1000+/mes" **se confirma** (1 k+/mes en individual y matrimonial). — [búsqueda](https://www.amazon.com.mx/s?k=protector+de+colchon+impermeable) (acc. 2026-10-22)
- **Organizador bajo tarja:** la nota previa decía "NETEL #1 en Organizadores para Armarios". **Observado:** #1 es Lifewit (organizador de tapas) y NETEL (cajones extraíbles) es #3. Delamu pasó de 10,618 a 11,838 calificaciones. HAWOO 200+/mes **se confirma**. — [Más vendidos](https://www.amazon.com.mx/gp/bestsellers/kitchen/9725283011) (acc. 2026-10-22)
- **Garrafón:** el precio de MU:4LIFE inclinable figuraba como "no capturado". **Observado:** $589, 4.2★ (9), sin insignia. — [B0GSX7R37R](https://www.amazon.com.mx/dp/B0GSX7R37R) (acc. 2026-10-22)
- **Tendedero:** la nota previa decía B0F9LJBT8H con 4.7★ (163), 50+ y #4 en Tendederos, y KIROGILY con 200+. **Observado:** B0F9LJBT8H a $895 con 4.7★ (187) y 100+; KIROGILY con 100+ y nº13 en Tendederos; el #4 de Tendederos es ahora AI-PIKA. SONGMICS #1 **se confirma** (es plegable de piso). — [búsqueda](https://www.amazon.com.mx/s?k=tendedero+retractil+de+pared); [Más vendidos](https://www.amazon.com.mx/gp/bestsellers/kitchen/9756907011) (acc. 2026-10-22)
- **Regadera:** CAILESER B0DPQK4WTJ tenía 4.1★ (316); **observado** 4.1★ (337), 50+, "Más vendido", $682.05. AZULDIMEN pasó de 4.6★ (156) a 4.6★ (169), con 100+/mes y $469. DOBEVI (895) no apareció en el top observado. — [búsqueda](https://www.amazon.com.mx/s?k=regadera+alta+presion+con+filtro) (acc. 2026-10-22)
- **Escoba de goma:** la nota de limpieza infería que el "kit anti-pelo" tenía "la demanda en Amazon más grande del grupo (más de 1,000 reseñas en varias publicaciones)". **Observado:** las reseñas son acumuladas y casi no hay insignias mensuales (suma top 5 = 50/mes). FURemover está en nº29,734 de Hogar y Cocina. **La inferencia previa no se sostiene con la señal mensual.** — [búsqueda](https://www.amazon.com.mx/s?k=escoba+de+goma); [B000EFDOOA](https://www.amazon.com.mx/dp/B000EFDOOA) (acc. 2026-10-22)
- **Spray mop:** la inconsistencia de Vileda Promist MAX (8,728 frente a 9) **se resuelve a favor de 9** (B0CN1HFMNK: $978, 4.2★ (9)). El listado con 100+/mes **se confirma** (B0CXDHZYFS, ahora nº7 en su subcategoría frente al "#4" de VIOPY citado antes). — [búsqueda](https://www.amazon.com.mx/s?k=trapeador+con+atomizador) (acc. 2026-10-22)
- **Funda para moto:** el snippet decía "PUBAMALL #2, VEKENSEE #4, SRIMMIT #8". **Observado:** **VEKENSEE #1**, PUBAMALL #2, EASYTAO #4; SRIMMIT no está en el top 10. PUBAMALL pasó de 7,207 a 7,375 calificaciones. — [Más vendidos](https://www.amazon.com.mx/gp/bestsellers/automotive/14327173011) (acc. 2026-10-22)
- **Organizador de cajuela:** Homeve (~16 mil), FORTEM (~7.6 mil) y Honey-Can-Do (~13.7 mil) **no aparecieron** en el top 16 observado. El nº1 de "Organizadores de Maletero" tiene solo 127 calificaciones. — [búsqueda](https://www.amazon.com.mx/s?k=organizador+para+cajuela) (acc. 2026-10-22)
- **Soporte de celular:** JOYROOM (16.3k) no apareció en el top observado. El líder es Lamicall (51,716; nº1 en Monturas de Manillar). — [búsqueda](https://www.amazon.com.mx/s?k=soporte+celular+para+moto) (acc. 2026-10-22)
- **Mochila repartidor:** Ytonet tenía 4.6★ (767); **observado** 4.6★ (780) y 50+/mes. BREEZEE 4.4★ (74) **se confirma**, sin insignia. — [búsqueda](https://www.amazon.com.mx/s?k=mochila+termica+para+repartidor) (acc. 2026-10-22)
- **Trends:** todas las notas previas decían "No disponible (429)". Ahora hay series para los 13 términos pedidos más 9 variantes (sección 4).

### Inferences
- **HIPÓTESIS:** Los snippets sobreestimaban productos con muchas reseñas acumuladas o globales (escoba de goma, organizador de cajuela, soporte JOYROOM) y subestimaban a los vendedores chinos recientes con muchas ventas mensuales y pocas reseñas (ganchos Raganet, guardapolvo 3 PCS, funda VEKENSEE). Para elegir producto conviene ponderar la insignia mensual por encima del conteo de reseñas.

### Gaps
- No se re-verificaron los precios de ML de las notas previas (ML bloqueado).

---

## 6. Tabla resumen (corte 2026-10-22)

### Takeaway
Por **evidencia mensual en Amazon MX** el orden es: ganchos ≫ protector de colchón > cajas para zapatos > funda para moto > regadera con filtro ≈ guardapolvo/burlete ≈ hamaca para perro > bolsas al vacío > tendedero > soporte de celular. Las señales más débiles están en escoba de goma, cinta selladora, cubre puños/manoplas, mochila térmica y organizador bajo tarja.

### Cited Findings
Fuentes: las búsquedas, fichas y lotes de Trends citados en las secciones 1–4 (todas consultadas el 2026-10-22). "comprados/mes" = insignia "X+ comprados el mes pasado" (piso). Suma mínima top 5 = suma de esas insignias en los 5 primeros resultados orgánicos (piso para Amazon; no es el mercado). Trends = promedio en escala "zapatera = 65.7" (lote 2 re-escalado ×4.63, ESTIMACIÓN), pico mensual y dirección.

| # | producto | resultados Amazon | top listing (precio, ★, # calificaciones, comprados/mes) | suma mínima comprados/mes (top 5) | BSR | quejas | Trends (promedio, pico, dirección) | confianza |
|---|---|---|---|---|---|---|---|---|
| 1 | Guardapolvo bajo puerta / burlete | 436 ("guardapolvo para puerta"); >3,000 ("burlete puerta") | Lock 16GPF $55, 4.3★, 64, 300+ · CARYWON 5 m $228, 4.1★, 2,079, 400+ · 3 PCS $149.99, 4.6★, 258, 400+ | 750 (guardapolvo) / 800 (burlete) | 3 PCS: nº35 Herramientas, nº1 Cintas de Impermeabilización; OUARTV nº1 Topes | Adherencia (CARYWON 146 negativas de 206), se sale al abrir la puerta, grosor | guardapolvo puerta 3.6, pico jul 2026, estable/↑ (bajo); burlete 5.7, pico jul 2026, ↑ en may–sep | Amazon alta / Trends baja |
| 2 | Bolsas al vacío con bomba manual | >10,000 | JEECOLI 15 pzs manual $292.52, 4.3★, 186, 300+ · ESQUIMAL $335.20, 4.6★, 2,928, 100+ (#1 Más vendidos) | 700 (las 5 son de bomba eléctrica) | ESQUIMAL nº36 Hogar y Cocina, nº1 Bolsas Ahorradoras; JEECOLI nº10 | Resistencia y sellado mixtos | "bolsas al vacío" 0.7 (insuficiente); "bolsas al vacio" 6.3, pico ene 2026, estable/↓ | Alta |
| 3 | Ganchos de terciopelo 50 pzs | >2,000 | RagaBasics $278.98, 4.7★, 1,337, **4 k+** · Raganet $277.42, 4.7★, 1,337, 600+ | **5,400** | Raganet **nº3 Hogar y Cocina**, nº1 Ganchos Estándar | Resistencia mixta (37 negativas de 83), pelusa, grosor | 0.8 (insuficiente) | Amazon alta / Trends no concluyente |
| 4 | Cajas apilables para zapatos | >7,000 | SONGMICS 18 $799.99, 4.3★, 8,961, 900+ (100+/semana) | 1,550 | nº83 Hogar y Cocina, nº1 Cajas para Botas y Zapatos | Armado (86 negativas), resistencia (86 negativas), varios 12-packs con 3.4–3.9★ | zapatera 65.7 (término amplio), pico ene 2026, estable con pico dic–ene | Alta |
| 5 | Protector de colchón impermeable | 426 | ESQUIMAL individual $271.92, 4.6★, 5,683, **1 k+** (200+/semana) · Dreamlab Queen $398, 4.7★, 7,895, 600+ | 1,850 | ESQUIMAL **nº4 Hogar y Cocina**, nº1 Protectores de Colchón | Material delgado (105 negativas en Dreamlab), ruido | "protector de colchón" 2.0 (insuficiente); "cubre colchon" 25.5, pico dic 2025, estacional nov–dic, estable | Alta |
| 6 | Carrito / base para garrafón | 533 (carrito); 382 (base) | Diablito garrafón $598, 3.8★, 6, 100+ · Raganet estante 3 garrafones $498, 4.6★, 490, 200+ · MU:4LIFE inclinable $589, 4.2★, 9, sin insignia | 400 (carrito, incluye genéricos) / 100 (base) | Raganet nº2,362 Hogar y Cocina; MU:4LIFE nº18,687 | No disponible (pocas reseñas); diablito con 23% de 1★ | "porta garrafon" 9.4, pico ene 2026, estable | Media-baja |
| 7 | Organizador bajo tarja de 2 niveles | >20,000 | HAWOO 2 pack $755.92, 4.2★, 341, 200+ (patrocinado) · Delamu $539.99, 4.4★, 11,838 (#6 Organizadores para Armarios) | 150 | HAWOO nº2,302 Hogar y Cocina, nº2 Organizadores de Cajones | Deslizamiento (13 negativas de 17), tamaño | "organizador fregadero" 0.2 (insuficiente) | Media |
| 8 | Regadera alta presión con filtro | >30,000 | Cabezal 6" con filtro de 15 etapas $448.20, 4.6★, 1,267, 500+ · Jasinber combo $498, 4.6★, 3,086, 500+ | 800 | B0B5JR9F3N no visible; Jasinber nº11 Herramientas, nº1 Regaderas de Mano | Flujo de agua mixto (19 negativas de 61); Aguacero 3.7★ | "regadera" ≈394 (≈6× zapatera; amplio), pico ene 2026, estable | Alta |
| 9 | Tendedero retráctil de pared | >40,000 | 15 m 2PCS $298, 4.5★, 207, 200+ · Sugarzoon $298, 4.4★, 683, 100+ | 500 | nº3 Tendederos (nº1,460 Hogar y Cocina); #1 de la categoría = SONGMICS de piso | Pierde tensión, se afloja | "tendedero" ≈42, pico oct 2026, estable con repunte | Alta |
| 10 | Escoba de goma / silicón | 477 | MR.SIGA $499.99, 4.5★, 14,858, 50+ · FURemover $320.15, 4.7★, 103,517, sin insignia | **50** | MR.SIGA nº10,154; FURemover nº29,734 Hogar y Cocina | Mango y resistencia mixtos; jalador 3 en 1 con 2.7★ | No consultado | Alta (señal débil) |
| 11 | Trapeador con atomizador | 418 | B0CXDHZYFS $398, 4.3★, 261, 100+ · MEXERRIS $502.86, 4.4★, 18,593, sin insignia | 150 | nº7 Trapeador Húmedo y Seco Doméstico (nº3,056 Hogar y Cocina) | Durabilidad ("se rompió en el primer uso", 15 negativas de 16) | "spray mop" insuficiente; "trapeador" 70.5, pico ene 2026, estable | Media |
| 12 | Cinta antiderrapante / selladora | >40,000 (antiderrapante); >4,000 (selladora) | 3M Safety-Walk $263.38, 4.4★, 5,230, 50+ · Truper 5 m $200, 4.4★, 67, 50+ · selladora de silicón $369, 4.5★, 57, 50+ | 150 / 50 | 3M nº1 Calcomanías Antiderrapantes para Tina (nº4,709 Hogar y Cocina) | Adherencia (44 negativas de 114) y durabilidad; selladoras con 3.4–3.8★ | No consultado | Media |
| 13 | Mochila térmica para repartidor | >3,000 | Ytonet 60 L $598, 4.6★, 780, 50+ | 100 | nº3 Bolsas Térmicas (nº5,956 Hogar y Cocina) | Resistencia mixta | "mochila térmica" y "mochila repartidor": insuficiente | Media-baja |
| 14 | Impermeable para moto de 2 piezas | >2,000 | 2 piezas $399, 4.4★, 25, 100+ | 200 | nº71 Ropa Impermeable Hombre (nº24,357 Ropa) | No disponible (pocas reseñas); 1★ = 10% | 2.7, pico jun 2026, estacional en lluvias | Media-baja |
| 15 | Cubre puños / manoplas para moto | >3,000 (casi todo protectores rígidos) | Manoplas B0FMDTB9WL $438.10, 4.0★, 74, sin insignia · protector LED $169.99, 5.0★, 9, 50+ | 50 (cubre puños) / 0 (manoplas) | Manoplas nº4,721 Motos, Accesorios y Piezas | 1★ = 16%; facilidad de uso mixta | 2.8, pico dic 2025, estacional invernal | Baja |
| 16 | Organizador plegable para cajuela | >2,000 | B0FRM1LKFR $263.09, 4.7★, 127, 100+ | 250 | **nº1 Organizadores de Maletero**, nº43 Automotriz | El velcro no se pega; tamaño | Insuficiente | Media |
| 17 | Funda impermeable para moto | 394 | VEKENSEE $242.10, 4.3★, 1,228, 500+ (100+/semana) · PUBAMALL $259.65, 4.5★, 7,375, 200+ | **1,050** | VEKENSEE **nº1 Motos, Accesorios y Piezas**, nº14 Automotriz | "No es impermeable" (49 negativas de 65); "se rompe rápido" (PUBAMALL: durabilidad 248 negativas) | 12.9, pico dic 2025, ↑/estable | Alta |
| 18 | Hamaca / cubreasiento para perro (auto) | >40,000 | Raganet $198, 4.2★, 1,785, 500+ · PUBAMALL $429, 4.7★, 1,041, 300+ | 800 | Ver mascotas.md (Raganet nº1 Protectores de tapicería para Perros) | Durabilidad (mascotas.md) | Ver mascotas.md ("cubre asientos perro" insuficiente) | Alta |
| 19 | Soporte de celular para moto | 342 | Lamicall $449, 4.6★, 51,716, 200+ (100+ en la ficha) | 400 | nº1 Monturas de Manillar de Celular, nº1,263 Electrónicos | Estabilidad y ajuste (pocas negativas) | "soporte celular moto" insuficiente | Media-alta |

### Inferences
- **ESTIMACIÓN (lectura conjunta):** Hay **alta demanda en Amazon con interés de búsqueda bajo o nulo en Google** en ganchos, guardapolvo/burlete y funda para moto. Son productos de compra por catálogo más que por búsqueda informativa. Hay **demanda baja en Amazon con interés amplio en Google** en trapeador y garrafón. Esa demanda podría estar en otros canales (supermercado, ML, tienda física; HIPÓTESIS).
- **HIPÓTESIS (para la priorización del reporte):**
  - Los candidatos de hogar y limpieza más respaldados por datos directos son: ganchos (demanda muy alta pero concentrada), protector de colchón (alta; brecha: material delgado o ruido), cajas para zapatos (alta; brecha: resistencia y armado), funda para moto (alta; brecha: impermeabilidad real), guardapolvo (media-alta; brecha: adherencia), regadera con filtro y tendedero.
  - Los menos respaldados: escoba de goma, cinta selladora, cubre puños/manoplas, mochila térmica y organizador bajo tarja.

### Gaps
- Facebook Marketplace (oferta local, precios en CDMX/Edomex): No disponible. Requiere verificación manual.
- Mercado Libre: No disponible (bloqueo anti-bot).
- Las insignias son aproximadas y redondeadas a la baja. Pueden aplicarse por variante o por familia de variantes (no verificado).
