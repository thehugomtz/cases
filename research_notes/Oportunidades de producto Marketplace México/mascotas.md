# Mascotas (perros y gatos): candidatos de producto para Facebook Marketplace México con abasto nacional/dropshipping, octubre 2026

Convenciones de estas notas:
- **HECHO** = dato observado en una fuente citada. Todas las URLs se consultaron el **2026-10-22** (se indica "acc. 2026-10-22").
- **ESTIMACIÓN** = cálculo propio; se muestran los datos de entrada.
- **HIPÓTESIS** = juicio o inferencia sin verificación directa.
- "N/D" o "No disponible" = no se pudo verificar públicamente; no se estimó.
- Etiqueta de Amazon "X+ comprados el mes pasado": es una insignia pública de Amazon con umbral (50+, 100+, 200+…), se refiere al mes anterior y a ese listado (puede agrupar variantes). Es un **piso** y solo cubre Amazon México; no son las ventas totales del mercado.
- El ranking de Amazon (BSR, "nº X en…") es una **posición relativa** en el momento de la consulta, **no** es volumen.
- Los conteos de reseñas de Amazon pueden incluir reseñas de otros países de Amazon (HIPÓTESIS: conteos como 100,997 o 157,669 en listados importados parecen globales). No equivalen a unidades vendidas en México.

---

## 0. Metodología, acceso a fuentes y contexto de mercado

### Takeaway
Amazon México y Google Trends (MX) se pudieron consultar directamente. **Mercado Libre México bloqueó todo el acceso automatizado** (búsquedas, fichas y "Más vendidos" redirigen a una verificación de cuenta anti-bot), así que **toda la evidencia de ML (precios, "+X vendidos", opiniones, número de resultados y ranking en Más vendidos) queda como "No disponible — requiere verificación manual"**. Facebook Marketplace tampoco se pudo consultar (requiere iniciar sesión). Las búsquedas web se agotaron a mitad del trabajo (límite compartido de la sesión), lo que limitó sobre todo la búsqueda de proveedores mayoristas.

### Cited Findings
- HECHO: Contexto de mercado: el 69.8% de los hogares de México tiene algún tipo de mascota; hay un total acumulado de 80 millones de mascotas: 43.8 millones de perros, 16.2 millones de gatos y 20 millones de otras especies (ENBIARE 2021). — [INEGI, boletín ENBIARE 2021 (PDF)](https://www.inegi.org.mx/contenidos/saladeprensa/boletines/2021/EstSociodemo/ENBIARE_2021.pdf) (acc. 2026-10-22)
- HECHO: Las URLs de Mercado Libre México (listado.mercadolibre.com.mx/…, /p/MLM…, articulo.mercadolibre.com.mx/…, /mas-vendidos/MLM1071, /c/animales-y-mascotas) redirigieron a `mercadolibre.com.mx/gz/account-verification` (verificación anti-bot) y la API pública `api.mercadolibre.com/sites/MLM/search` respondió 403 "forbidden". WebFetch también recibió 403. — p. ej. [ML búsqueda "rodillo quita pelo mascotas"](https://listado.mercadolibre.com.mx/rodillo-quita-pelo-mascotas) y [ML Más vendidos](https://www.mercadolibre.com.mx/mas-vendidos) (acc. 2026-10-22)
- HECHO: Las páginas Movers & Shakers ("Productos del momento") de Amazon México en Mascotas, Perros y Gatos mostraron: "Lo sentimos, no hay Productos del momento disponibles en esta categoría. Vuelve más tarde." — [Amazon MX Movers & Shakers – Mascotas](https://www.amazon.com.mx/gp/movers-and-shakers/pet-supplies), [Perros](https://www.amazon.com.mx/gp/movers-and-shakers/pet-supplies/12478521011), [Gatos](https://www.amazon.com.mx/gp/movers-and-shakers/pet-supplies/12478519011) (acc. 2026-10-22)
- HECHO: El Top 30 general de Más vendidos de Mascotas de Amazon MX está dominado por alimento, arena, premios y suplementos; los únicos artículos fuera de esas categorías son el **arnés MESVIER con correa (#6, $249, 4.7★, 9,899 valoraciones)**, las bolsas para heces con dispensador Amazon Basics (#5, $282) y los pañales desechables Amazon Basics (#30, $364.90). El arnés es el único accesorio duradero del Top 30. — [Amazon MX Más vendidos – Productos para animales](https://www.amazon.com.mx/gp/bestsellers/pet-supplies) (acc. 2026-10-22)
- HECHO: Se pudo consultar Google Trends México (12 meses, 2025-10-22 a 2026-10-22, resolución semanal) mediante los mismos endpoints de datos que usa la página Explore. Los términos de cola larga ("tapete arenero", "rodillo quita pelo", "comedero elevado", "cubre asientos perro", "protector de sillon", "escalera para perro", "transportadora para gato") devolvieron series casi todas en 0 con picos aislados de 100, y "guante quita pelo" no devolvió datos. — p. ej. [Google Trends MX "pechera para perro"](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=pechera%20para%20perro) (acc. 2026-10-22)

### Inferences
- HIPÓTESIS: Una serie de Trends con casi todas las semanas en 0 y un solo pico de 100 indica **volumen de búsqueda insuficiente para una serie confiable**, no una tendencia al alza. En estos casos se reporta "No concluyente" y se usa un término general como proxy (p. ej., "arenero para gato" para el tapete atrapa-arena).
- HIPÓTESIS: Que Movers & Shakers no tenga datos impide usar esa señal de crecimiento de corto plazo. Como señal de demanda en Amazon se usan las insignias "comprados el mes pasado" y la presencia en los Más vendidos por subcategoría.

### Gaps
- Mercado Libre: precios, etiqueta "+X vendidos" (acumulada desde que se creó la publicación, **no mensual**), calificación, número de opiniones, número de resultados y ranking en "Más vendidos" (categoría Animales y Mascotas, ID MLM1071, por confirmar): **No disponible** para todos los candidatos por el bloqueo anti-bot. Hay que verificarlo a mano en un navegador con sesión iniciada (se dan las URLs de búsqueda en cada candidato).
- Facebook Marketplace: **No disponible — requiere verificación manual** para todos los candidatos (ver la lista de verificación en la sección 10).
- Proveedores mayoristas nacionales con precio unitario, MOQ y envío a cliente final: casi todo **No disponible**. Con las búsquedas web agotadas solo se pudo verificar una plataforma (Dropi México), y su catálogo y sus precios requieren registro.

---

## 1. Candidato: Tapete atrapa-arena doble capa para arenero (gato)

### Takeaway
Es la **menor saturación observada en Amazon MX** de todos los candidatos (473 resultados frente a >20,000 en los demás). El producto está bien calificado (4.6–4.7★), no hay marcas grandes, es ligero y no es frágil. Su debilidad es el ticket: $199–$299 MXN, en el límite inferior del rango objetivo. Conviene venderlo en tamaño grande (60×90 cm) o en kit (tapete + guante quitapelo), un formato que ya existe en Amazon con 50+ compras al mes.

### Cited Findings
- **Producto y variantes (HECHO):** alfombrilla de EVA de doble capa tipo panal (la arena cae a la capa interior), impermeable y antideslizante. Medidas listadas: 45×60 cm, 60×90 cm, 80×56 cm, 86×56 cm y 60×37 cm. Colores: gris, negro y caqui. — [Amazon MX búsqueda "tapete para arenero gato"](https://www.amazon.com.mx/s?k=tapete+para+arenero+gato) (acc. 2026-10-22)
- **Saturación en Amazon (HECHO):** "1 a 48 de 473 resultados para 'tapete para arenero gato'". En los primeros 20 resultados los precios van de $139 a $299 MXN (mediana $250). — [Amazon MX búsqueda](https://www.amazon.com.mx/s?k=tapete+para+arenero+gato) (acc. 2026-10-22)
- **Listado líder (HECHO):** LYSSIID "Alfombrilla Doble para Caja de Arena, EVA, impermeable", $249.99, 4.6★, 344 calificaciones; nº476 en Productos para animales y **nº1 en "Contenedores de Desechos de Arena para Gatos"**; enviado por Amazon; país de origen China; aparece en el puesto #30 de Más vendidos de "Adiestramiento y Arena para Gatos". — [Amazon MX ficha B0DKP3K512](https://www.amazon.com.mx/dp/B0DKP3K512); [Amazon MX Más vendidos Arena gatos](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478569011) (acc. 2026-10-22)
- **Otros listados (HECHO):** Wolfi tapete arenero, $199.99, 4.6★ (84), "50+ comprados el mes pasado"; tapete EVA doble capa 45×60, $199, 4.7★ (89), 50+/mes; **kit "Tapete para Arena de Gatos + Guante Quita Pelos" 45×60, $239, 4.6★ (19), 50+/mes** (B0FX9SN3LD); estera 90×60 cm, $299, 4.6★ (51); B0B6P9SPWH, $259, 4.6★ (733); PUBAMALL, $139, 4.3★ (303). — [Amazon MX búsqueda](https://www.amazon.com.mx/s?k=tapete+para+arenero+gato); [kit B0FX9SN3LD](https://www.amazon.com.mx/dp/B0FX9SN3LD) (acc. 2026-10-22)
- **Lo que dicen los compradores (HECHO, resumen automático de Amazon):** "super útil para evitar que la arena se esparza… retiene la arena", "las medidas concuerdan con lo esperado", "fácil de limpiar y se seca muy rápido". Todos los aspectos que muestra son positivos: calidad (43 menciones), retención de arena (28), tamaño (16), facilidad de limpieza (10). No se mostraron aspectos negativos. — [Amazon MX B0DKP3K512](https://www.amazon.com.mx/dp/B0DKP3K512) (acc. 2026-10-22)
- **Mercado Libre (snippet de buscador, NO verificado en la página; fecha de indexación desconocida):** un resultado de ML México con el título "Tapete Atrapa Arena Para Arenero De Gato Impermeable 45x60cm" aparecía a ~$159.87 MXN antes de descuento (precio ambiguo). — [ML listado "arenero-de-gato"](https://listado.mercadolibre.com.mx/arenero-de-gato) (acc. 2026-10-22, acceso directo bloqueado)
- **Google Trends (HECHO):** "tapete arenero" y "tapete para arenero" tienen volumen insuficiente (serie casi toda en 0) → **No concluyente**. Como proxy, "arenero para gato" muestra interés **alto y estable**: promedio 70.8/100; promedios mensuales entre 54 (feb–mar 2026) y 95 (jul 2026); oct 2026 = 74. En comparación directa tiene un volumen similar a "pechera para perro" (37.5 frente a 32.7 de promedio). — [Trends "arenero para gato"](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=arenero%20para%20gato); [comparación](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=pechera%20para%20perro,arenero%20para%20gato,rascador%20para%20gato,cama%20para%20perro,transportadora%20para%20gato) (acc. 2026-10-22)
- **Proveedor nacional:** No disponible (ver sección 9 para Dropi México, cuyo catálogo requiere registro).

### Inferences
- ESTIMACIÓN (piso de demanda en Amazon MX): 3 listados con insignia de 50+ (Wolfi, EVA 45×60 y kit con guante) ⇒ **≥150 unidades al mes** solo en esos listados visibles. Es un piso, no un total.
- ESTIMACIÓN de saturación: **baja-media**. Hay 473 resultados en Amazon, el líder tiene 344 calificaciones y no aparecen marcas grandes. La dispersión de precios es estrecha ($139–$299).
- HIPÓTESIS (comprador): dueños de gatos en departamentos de CDMX/Edomex con arenero en baño o cocina, donde la arena regada es un dolor diario. Es una compra complementaria al arenero.
- HIPÓTESIS (riesgo de devolución bajo): no hay tallas ni electrónica, y el material (EVA) no es frágil. Riesgo menor: que la medida no le quede al arenero → publicar medidas en cm.
- HIPÓTESIS (táctica de ticket): $199–$299 queda en el borde inferior; un kit (tapete 60×90 + guante, o 2 tapetes) podría venderse en $299–$399. El kit de Amazon con 50+/mes es una señal de que el formato funciona.

### Gaps
- ML: precios, "+X vendidos" (acumulado), opiniones, número de resultados y Más vendidos → **No disponible** (verificar en https://listado.mercadolibre.com.mx/tapete-arenero-gato).
- Peso exacto: no aparece en la ficha. HIPÓTESIS: <1 kg para 45×60, sin verificar.
- Proveedor nacional con costo unitario y MOQ: **No disponible**.
- Facebook Marketplace: **No disponible — requiere verificación manual**.

---

## 2. Candidato: Comedero elevado ajustable para perro (2 tazones de acero + plato lento, "3 en 1")

### Takeaway
Es la **señal de demanda mensual más fuerte en Amazon MX** entre los candidatos dentro del ticket: varios listados con 100–300+ compras al mes, de $340 a $399 MXN, con calificaciones de 4.7–4.8★. No hay marcas dominantes. Riesgos: peso de ~0.9 kg, competencia alta (>30,000 resultados) y variación de calidad entre genéricos.

### Cited Findings
- **Variantes (HECHO):** altura ajustable (3–5 niveles) y ángulo; 2 tazones de acero inoxidable + 1 plato de alimentación lenta ("3PCS"); bases de metal o plástico; tallas por raza (chico/mediano/grande). — [Amazon MX Más vendidos "Artículos para Comida y Agua para Perros"](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478591011) (acc. 2026-10-22)
- **Presencia en Más vendidos (HECHO, subcategoría Comida y Agua para Perros):** #6 ZQSQD ajustable en altura y ángulo, $369, 4.8★ (383); #7 OSLIFE 5 alturas, $396.70, 4.7★ (144); #9 3PCS (2 tazones de acero + plato lento), $399, 4.7★ (536); #13 LUKITO 3pcs, $354.60, 4.9★ (15); #15 3PCS, $340.10, 4.7★ (40). Platos lentos sueltos aparecen en el #27 ($99) y el #29 ($95). — [Amazon MX Más vendidos](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478591011) (acc. 2026-10-22)
- **Ficha del líder (HECHO):** ZQSQD B0D9QC5GVY, $369, 4.8★ (383); **nº372 en Productos para animales, nº1 en "Comedores para Perros"**; 37×17×19.5 cm; **900 g**; acero inoxidable; en Amazon.com.mx desde el 19 de julio de 2024. — [Amazon MX B0D9QC5GVY](https://www.amazon.com.mx/dp/B0D9QC5GVY) (acc. 2026-10-22)
- **Insignias mensuales (HECHO):** OSLIFE "300+ comprados el mes pasado"; 3PCS B0CSBC43VY 300+; ZQSQD 200+; LUKITO 100+; B0G4LNX3KC 100+; B0D2CSNYTB, B0D1FNY1LM, B0CDX2ZVLH, B0DPF3DBTV y B0GVS7RBHZ con 50+ cada uno. Hay "más de 30,000 resultados" y en el top 20 los precios van de $259 a $498 (mediana $393). — [Amazon MX búsqueda "comedero elevado perro"](https://www.amazon.com.mx/s?k=comedero+elevado+perro) (acc. 2026-10-22)
- **Lo que dicen los compradores (HECHO):** "muy bonito y tal cual como aparece en la foto… fácil de armar… gran adaptabilidad de alturas", "opiniones diversas sobre el tamaño". Aspectos: apariencia (57 menciones positivas), fácil de armar (31), ajuste de altura (29); **tamaño mixto (30)**. — [Amazon MX B0D9QC5GVY](https://www.amazon.com.mx/dp/B0D9QC5GVY) (acc. 2026-10-22)
- **Variación de calidad (HECHO):** en la misma búsqueda aparecen genéricos con 2.8★ (B0G2BTFS8C, 22 calificaciones), 3.7★ (B0DPF3DBTV, 61) y 3.8★ (B0G8HL5R7M, 11). — [Amazon MX búsqueda](https://www.amazon.com.mx/s?k=comedero+elevado+perro) (acc. 2026-10-22)
- **Google Trends (HECHO):** "comedero elevado" tiene volumen insuficiente (casi todo 0) → **No concluyente**. "comedero para perro" devolvió una serie igual de escasa (y numéricamente idéntica a la de "quitapelusas", lo que es sospechoso) → **No concluyente**. — [Trends "comedero elevado"](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=comedero%20elevado) (acc. 2026-10-22)
- **Proveedor nacional:** No disponible.

### Inferences
- ESTIMACIÓN (piso de demanda en Amazon MX): sumando insignias de listados distintos (300 + 300 + 200 + 100 + 100 + 4×50) ⇒ **≥1,200 unidades al mes**. Se excluye el duplicado B0GVS7RBHZ porque comparte las 383 calificaciones de ZQSQD (misma familia).
- ESTIMACIÓN de saturación: **alta en número de listados** (>30,000 resultados), pero **sin marcas grandes**. Los líderes tienen pocas calificaciones (144–536) y los precios están concentrados en $340–$400.
- HIPÓTESIS (comprador): dueños de perros medianos o grandes y de perros mayores (postura al comer), y de perros que comen muy rápido (plato lento). Es un regalo plausible para diciembre.
- HIPÓTESIS (riesgo): pocas devoluciones si la medida está clara; el tamaño es el principal punto mixto. Hay que **evitar versiones de cerámica o vidrio** (son frágiles y están excluidas). Con 0.9 kg el envío es más caro que el de un tapete.

### Gaps
- ML: **No disponible** (verificar https://listado.mercadolibre.com.mx/comedero-elevado-perro).
- Tendencia de búsqueda en Google: no concluyente por volumen insuficiente.
- Proveedor nacional y costo: **No disponible**.
- Facebook Marketplace: **No disponible — requiere verificación manual**.

---

## 3. Candidato: Cubreasientos / hamaca impermeable de auto para perro

### Takeaway
Tiene una **demanda mensual fuerte en Amazon MX** (≥1,400 unidades al mes sumando insignias) y una **brecha de calidad documentada**: el listado más barato y más vendido (Raganet, $189–$198) acumula 145 menciones negativas por durabilidad. El ticket ($364–$599 para opciones de calidad) cae bien en el rango. En contra: casi no hay búsquedas en Google y existe riesgo de que no le quede al vehículo.

### Cited Findings
- **Variantes (HECHO):** hamaca 4 en 1 con paneles laterales (54×55 pulgadas), con ventana de malla, con base rígida, extensor de asiento trasero, forro de cajuela para SUV, cubierta de banca simple; materiales Oxford 600D o nailon/poliéster. — [Amazon MX Más vendidos "Transportadoras y Productos de Viaje para Perros"](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478602011) (acc. 2026-10-22)
- **Presencia en Más vendidos (HECHO, Viaje Perros):** #2 Raganet cubierta, $198, 4.2★ (1,785); #3 Mancro hamaca 4 en 1, $364, 4.4★ (8,754); #4 PUBAMALL, $429, 4.7★ (1,041); #10 Gurkitsy, $399.97, 4.6★ (291); #12 forro de carga SUV, $559, 4.6★ (514); #15 ENGREPO, $599, 4.5★ (209); #18 AFujia, $369, 4.5★ (1,547). — [Amazon MX Más vendidos](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478602011) (acc. 2026-10-22)
- **Fichas (HECHO):** Raganet B0BDBVTS18, $189, 4.2★ (1,785), **nº133 en Productos para animales, nº1 en "Protectores de tapicería para Perros"**, "200+ comprados el mes pasado" (otra variante, B0CN7CRSLH, muestra 500+). Mancro B085VYPGMD, $364, 4.4★ (8,754), nº257 / nº2 en Protectores de tapicería, 200+/mes. — [Amazon MX B0BDBVTS18](https://www.amazon.com.mx/dp/B0BDBVTS18); [Amazon MX B085VYPGMD](https://www.amazon.com.mx/dp/B085VYPGMD); [búsqueda](https://www.amazon.com.mx/s?k=cubre+asientos+auto+perro) (acc. 2026-10-22)
- **Quejas (HECHO):** Raganet: resumen de Amazon: "algunos usuarios reportan problemas de durabilidad, ya que se rompen muy rápido y se rasgan en las uniones"; aspecto **"durabilidad" negativo (145 menciones)**, material mixto (73), ajuste mixto (51). Reseña 1★: "Pésima calidad al primer viaje llegó todo roto… este ni una semana". Mancro: "opiniones diversas sobre el ajuste y el tamaño"; reseñas 3★: "Es muy chico y no tapa bien los respaldos", "la parte de la base es muy angosta". — [Amazon MX B0BDBVTS18](https://www.amazon.com.mx/dp/B0BDBVTS18); [Amazon MX B085VYPGMD](https://www.amazon.com.mx/dp/B085VYPGMD) (acc. 2026-10-22)
- **Saturación y precio (HECHO):** "más de 50,000 resultados" para "cubre asientos auto perro"; top 20 entre $189 y $1,239 (mediana $458). Insignias: PUBAMALL 300+, Raganet 200+/500+, Mancro 200+, ENGREPO 100+, vantisan 100+, B0BKL34WGK 100+, forro de carga 100+, B0CQNNS8WQ 100+, Jasonwell, GALASALA, URPOW y B0FH7JFMYY 50+ cada uno. — [Amazon MX búsqueda](https://www.amazon.com.mx/s?k=cubre+asientos+auto+perro) (acc. 2026-10-22)
- **Mercado Libre (snippet de buscador, NO verificado):** una página de vendedor de ML México mostraba "Cubre Cajuela Asientos Mascotas Perro Auto Funda Impermeable" con calificación de 4.6/5. — [ML página de vendedor GG2128](https://www.mercadolibre.com.mx/pagina/gg2128) (acc. 2026-10-22)
- **Google Trends (HECHO):** "cubre asientos perro" (promedio 2.2, casi todo 0) y "cubre asiento para perro" (0.5 en comparación con "pechera para perro" = 65.7) → **interés de búsqueda en Google muy bajo / No concluyente**. — [Trends comparación](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=pechera%20para%20perro,pa%C3%B1ales%20para%20perro,cama%20para%20gato,mochila%20para%20perro,cubre%20asiento%20para%20perro) (acc. 2026-10-22)
- **Proveedor nacional:** No disponible.

### Inferences
- ESTIMACIÓN (piso en Amazon MX, listados distintos): 300 + 500 (Raganet, variante más alta) + 200 + 100×5 + 50×4 ⇒ **≥1,700 al mes** si se toman las insignias de Raganet por separado, o **≥1,400 al mes** contando solo la variante de 200+ (B0FXWM99X3 se excluye por compartir familia con B0BKL34WGK). Es un piso.
- HIPÓTESIS: el desfase entre muchas compras en Amazon y casi nada de búsquedas en Google sugiere que el comprador **descubre el producto dentro del marketplace** o lo busca con otros términos ("funda", "protector de asiento"). Es una señal favorable para Marketplace, donde la venta es visual.
- ESTIMACIÓN de saturación: **media-alta** en número de listados, pero **sin marcas grandes**. El precio piso de $189 (Raganet) con mala durabilidad deja hueco para una versión "reforzada" de $399–$549.
- HIPÓTESIS (comprador): familias de CDMX/Edomex con auto que llevan al perro al veterinario, a parques o de viaje de fin de semana.
- HIPÓTESIS (devoluciones): riesgo **medio** porque depende de que le quede al vehículo (sedán/SUV). Hay que publicar medidas y tipo de auto compatible. No es frágil; peso no verificado.

### Gaps
- ML: **No disponible** (verificar https://listado.mercadolibre.com.mx/cubre-asientos-auto-perro).
- Peso y volumen empacado: no aparecen en las fichas consultadas.
- Proveedor nacional y costo: **No disponible**.
- Facebook Marketplace: **No disponible — requiere verificación manual**.

---

## 4. Candidato (contraintuitivo): Protector antiarañazos para sillón (cinta transparente o tapete rascador autoadhesivo para sofá)

### Takeaway
Es una categoría **poco obvia con demanda real en Amazon MX** (≥500 unidades al mes en insignias; 7 listados en el top 30 de Camas y Muebles para Gatos). El dolor es claro (gatos que dañan sillones) y hay una **brecha medible**: el pegamento falla (54 menciones negativas de "adherencia" en un listado). Es muy ligero (100–350 g). Su debilidad es el ticket unitario ($149–$262), así que conviene vender paquetes.

### Cited Findings
- **Variantes (HECHO):** cinta transparente de PVC de 30 cm×5 m, 20 cm×5 m, 40×500 cm o 45 cm×5 m; juegos de 12 piezas adhesivas; tapete rascador autoadhesivo recortable de 40×200 cm ("DIY"); fundas cubre sillón antiarañazos. — [Amazon MX búsqueda "protector sillon gatos antiarañazos"](https://www.amazon.com.mx/s?k=protector+sillon+gatos+antiara%C3%B1azos) (acc. 2026-10-22)
- **Presencia en Más vendidos (HECHO, Camas y Muebles para Gatos):** #6 NIAWEA tapete rascador 40×200 cm, $262.24, 4.2★ (138); #11 YELIY cinta antiarañazos 30 cm×5 m, $179.10, 4.2★ (77); #18 tapete rascador protector para sofá, $288, 4.0★ (311); #19 cinta rascadora, $249.99, 3.9★ (131); #22 XLDHYLL cinta transparente, $189, 4.8★ (8); #23 protector, $242.10, 4.3★ (17); #25 RUAKIVA tapetes rascadores, $170.10, 4.4★ (278). — [Amazon MX Más vendidos Camas y Muebles Gatos](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478573011) (acc. 2026-10-22)
- **Fichas (HECHO):** YELIY B0F91K9GX2: $179.10, 4.2★ (77), **"200+ comprados el mes pasado"**, nº554 en Productos para animales, nº2 en "Tapetes Rascadores para Gatos", **350 g**, en Amazon desde el 17 de mayo de 2025. TAGNEFLOR B0GZWRK39V (tapete 40×200 cm): $242.10, 4.0★ (311), nº739 / nº4 en Tapetes Rascadores, paquete de **100 g** (43.3×15.6×8.7 cm), en Amazon desde el 7 de mayo de 2026. — [Amazon MX B0F91K9GX2](https://www.amazon.com.mx/dp/B0F91K9GX2); [Amazon MX B0GZWRK39V](https://www.amazon.com.mx/dp/B0GZWRK39V) (acc. 2026-10-22)
- **Quejas (HECHO):** TAGNEFLOR: "algunos usuarios señalan que el pegamento no resiste mucho y se despega"; aspecto **"adherencia" negativo (54 menciones)**; reseña 1★: "Se despegan y se caen solos… se le quedan atrapadas las uñas a los gatos". YELIY: durabilidad mixta (13); reseña 1★: "es muy delgado, desde la primera vez mi gato lo rompió". — [Amazon MX B0GZWRK39V](https://www.amazon.com.mx/dp/B0GZWRK39V); [Amazon MX B0F91K9GX2](https://www.amazon.com.mx/dp/B0F91K9GX2) (acc. 2026-10-22)
- **Saturación y precio (HECHO):** "más de 20,000 resultados"; top 20 entre $149 y $394 (mediana $210). Insignias: YELIY 200+, NIAWEA 100+, y XLDHYLL, B0GD87K132, B0GVKNBHXV y B0F29H4BLD con 50+ cada uno. — [Amazon MX búsqueda](https://www.amazon.com.mx/s?k=protector+sillon+gatos+antiara%C3%B1azos) (acc. 2026-10-22)
- **Google Trends (HECHO):** "protector de sillon" con volumen insuficiente → **No concluyente**. "rascador para gato" tiene un interés bajo e irregular (promedio 11.4; 2.3 frente a 32.7 de "pechera para perro" en comparación). — [Trends comparación](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=tapete%20para%20arenero,rodillo%20quita%20pelo,comedero%20elevado,protector%20de%20sillon,escalera%20para%20perro) (acc. 2026-10-22)
- **Proveedor nacional:** No disponible.

### Inferences
- ESTIMACIÓN (piso en Amazon MX): 200 + 100 + 4×50 ⇒ **≥500 unidades al mes** en listados visibles.
- ESTIMACIÓN de saturación: **media**. Hay muchos listados genéricos, sin marcas grandes y con calificaciones mediocres (3.7–4.3★ en la mayoría), lo que indica un **hueco de calidad** (mejor adhesivo o material más grueso).
- HIPÓTESIS (comprador): dueños de gatos en departamentos o casas rentadas de CDMX que quieren proteger sillones o puertas sin perforar; también arrendatarios que temen perder el depósito. El "antes y después" se presta a fotos y video en Marketplace.
- HIPÓTESIS (ticket): una unidad cuesta <$250; un paquete "2 rollos" o "cinta + tapete rascador" podría venderse en $299–$399.
- HIPÓTESIS (devoluciones): bajas por tallas (es recortable), pero hay riesgo de reclamo si el adhesivo falla: conviene probar el lote antes de vender. No es frágil.

### Gaps
- ML: **No disponible** (verificar https://listado.mercadolibre.com.mx/protector-sillon-gatos).
- Tendencia de búsqueda en Google: no concluyente.
- Proveedor nacional y costo: **No disponible**.
- Facebook Marketplace: **No disponible — requiere verificación manual**.

---

## 5. Candidato: Rodillo quitapelo reutilizable (tipo "rodillo con depósito autolimpiante")

### Takeaway
La demanda está comprobada (el líder es #141 en todo Mascotas y #1 en su nicho, con 200+ compras al mes), pero es **muy competida**: más de 30,000 resultados, un líder con 100,997 calificaciones y la marca original ChomChom presente. Hay una brecha de calidad: los genéricos baratos tienen 3.5–3.8★ y quejas de que "no funciona". Es viable solo con un producto probado y sin usar la marca ChomChom en el anuncio (sería imitación de marca, excluida).

### Cited Findings
- **Variantes (HECHO):** rodillo manual con cepillo de tela y depósito autolimpiante, sin repuestos; dimensiones 23.4×12.7×3.3 cm; nailon y plástico; colores blanco, gris y morado; también versiones "4 en 1". — [Amazon MX B0819XVK92](https://www.amazon.com.mx/dp/B0819XVK92) (acc. 2026-10-22)
- **Presencia en Más vendidos (HECHO, Higiene Gatos):** **#1 ACE2ACE Quitapelos y Rodillos, $377.99, 4.6★ (100,997)**; #3 Wouble rodillo reutilizable, $263.11, 4.5★ (1,541); #14 ChomChom Roller (marca original), $591.60, 4.7★ (9,696). En Higiene Perros: #4 PetLovers hojas quita pelusa (adhesivo, no reutilizable), $499, 4.7★ (37,177). — [Amazon MX Más vendidos Higiene Gatos](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478577011); [Higiene Perros](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478597011) (acc. 2026-10-22)
- **Ficha del líder (HECHO):** ACE2ACE: nº141 en Productos para animales, nº1 en "Guantes y Rodillos Quita Pelo para Gatos". Resumen de Amazon: "muy práctico y útil… las opiniones sobre la resistencia, durabilidad y calidad del material son variadas"; aspecto resistencia mixto (19). — [Amazon MX B0819XVK92](https://www.amazon.com.mx/dp/B0819XVK92) (acc. 2026-10-22)
- **Brecha de calidad en genéricos (HECHO):** rodillo genérico B0FWYH1C5V, $129.99, **3.8★ (22)**, 50+/mes, nº3,160 en Productos para animales. Reseñas: 2★ "Recoge solo algunos pelos… embarra polvo, no lo recomiendo"; 1★ "No sirve!!"; 1★ "No es lo que parece no funciona muy bien". — [Amazon MX B0FWYH1C5V](https://www.amazon.com.mx/dp/B0FWYH1C5V) (acc. 2026-10-22)
- **Saturación y precio (HECHO):** "más de 30,000 resultados"; top 20 entre $40 y $499 (mediana $146). Insignias: ACE2ACE 200+; HeiLuon (lavable, para ropa) 100+; AVEDISTANTE 100+ (4.3★, 9,536); Wouble, Fancy Pets ($151, 4.6★, 1,814) y genérico B0FWYH1C5V con 50+ cada uno; Scotch-Brite rodillo adhesivo (no reutilizable) 800+. — [Amazon MX búsqueda](https://www.amazon.com.mx/s?k=rodillo+quita+pelo+mascotas+reutilizable) (acc. 2026-10-22)
- **Mercado Libre (snippet de buscador, NO verificado; precios posiblemente desactualizados):** en la búsqueda "quita-pelusa" aparecían un rodillo quita pelo para mascotas, ropa y muebles a $89 con envío gratis (vendedor "Universo en Línea"), un kit Ryvoxel de 10 rodillos adhesivos a $298 y un pack ITAWINA con 12 repuestos a $328. Estos dos últimos son adhesivos, no reutilizables. — [ML listado "quita-pelusa"](https://listado.mercadolibre.com.mx/quita-pelusa) (acc. 2026-10-22, acceso directo bloqueado)
- **Google Trends (HECHO):** "quita pelo mascotas" (promedio 3.4) y "rodillo quita pelo" (1.9) tienen volumen insuficiente → **No concluyente**. — [Trends "quita pelo mascotas"](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=quita%20pelo%20mascotas) (acc. 2026-10-22)
- **Proveedor nacional:** No disponible. Fancy Pets (marca mexicana) vende un "Rodillo Removedor Quitapelos" en Amazon a $151 (4.6★, 1,814) y tiene un catálogo de Grooming e Higiene en su sitio, pero no publica precios de mayoreo. — [Amazon MX B09SNR2B97](https://www.amazon.com.mx/dp/B09SNR2B97); [Fancy Pets](https://www.fancypets.mx/) (acc. 2026-10-22)

### Inferences
- ESTIMACIÓN (piso en Amazon MX, solo rodillos reutilizables para mascotas): 200 (ACE2ACE) + 100 (AVEDISTANTE) + 50 (Wouble) + 50 (Fancy Pets) + 50 (genérico) ⇒ **≥450 unidades al mes**.
- ESTIMACIÓN de saturación: **alta**. Más de 30,000 resultados, un líder con más de 100k calificaciones (probablemente globales, HIPÓTESIS), marca original presente y precios de $40 a $591.
- HIPÓTESIS (comprador): dueños de gatos o perros de pelo largo con sillones de tela, en especial en temporada de muda. Es un regalo barato y fácil de demostrar en video.
- HIPÓTESIS (riesgo): la **variación de calidad** (rodillos que "no recogen") es el principal riesgo de reclamo. El precio de referencia en Marketplace probablemente queda por debajo de $250 (genéricos de $120–$150 en Amazon), lo que **presiona el margen**. Peso bajo (~23×13×3 cm) y no es frágil.
- HIPÓTESIS (cumplimiento): no usar "ChomChom" en el título ni en las fotos (marca registrada; una réplica sería imitación, excluida).

### Gaps
- ML: **No disponible** (verificar https://listado.mercadolibre.com.mx/rodillo-quita-pelo-mascotas).
- Tendencia de búsqueda en Google: no concluyente.
- Proveedor nacional, costo y MOQ: **No disponible**.
- Facebook Marketplace: **No disponible — requiere verificación manual**.

---

## 6. Candidato (contraintuitivo, estacional): Saco de dormir / cama cueva térmica para gato

### Takeaway
Es una **señal estacional temprana**: el 22 de octubre de 2026 un saco térmico genérico estaba en el **nº134 de todo Mascotas** en Amazon MX y era nº1 en "Cobijas para cama para gatos", con apenas 50 calificaciones. Es ligero (250 g), no es frágil y cuesta $250–$400. Las quejas apuntan a una brecha clara: tamaño diminuto y tela delgada. Sus límites son la ventana estacional (HIPÓTESIS: oct–feb) y la calidad desigual.

### Cited Findings
- **Variantes (HECHO):** tallas S/M/L; exterior de pana con forro polar; semicerrado; "autocalentable"; cuevas tipo sherpa; también "nido invernal". — [Amazon MX búsqueda "saco de dormir gato"](https://www.amazon.com.mx/s?k=saco+de+dormir+gato) (acc. 2026-10-22)
- **Presencia en Más vendidos (HECHO, Camas y Muebles para Gatos):** #3 "Saco de Dormir para Gatos, Cama Térmica Semicerrada para Invierno, L", $398, 4.0★ (50); #15 Fancy Pets Cama Tipo Cueva Sherpa, $314, 4.5★ (228); #17 NEWKIBOU cama cueva portátil, $399, 3.9★ (457); #26 Cat Sleeping Bag, $169, 4.2★ (3). — [Amazon MX Más vendidos Camas y Muebles Gatos](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478573011) (acc. 2026-10-22)
- **Ficha (HECHO):** NEWKIBOU B0F9XF9PYN: $398 (talla L), 4.0★ (50), **nº134 en Productos para animales, nº1 en "Cobijas para Cama para Gatos"**, "50+ comprados el mes pasado"; **250 g**; paquete de 41×32×10.2 cm; en Amazon desde el 26 de mayo de 2025. — [Amazon MX B0F9XF9PYN](https://www.amazon.com.mx/dp/B0F9XF9PYN) (acc. 2026-10-22)
- **Quejas (HECHO):** 3★ "muy pesado en la parte de la entrada y no se mantiene abierto… mejor se acuesta arriba"; 1★ "Son diminutos… para gato recién nacido"; 2★ "Muy delgado el saquito". — [Amazon MX B0F9XF9PYN](https://www.amazon.com.mx/dp/B0F9XF9PYN) (acc. 2026-10-22)
- **Saturación y precio (HECHO):** "más de 10,000 resultados"; top 20 entre $146 y $653 (mediana $286); solo un listado del top 20 tiene insignia mensual (50+). Hay listados recientes sin calificaciones (B0HMFL9DYN, B0HMVC89SX, B0HMDPP73H a $146–$186), lo que sugiere nuevos vendedores entrando. — [Amazon MX búsqueda](https://www.amazon.com.mx/s?k=saco+de+dormir+gato) (acc. 2026-10-22)
- **Google Trends (HECHO):** "cama para gato" tiene interés **medio-alto y estable**: promedio 46.8; promedios mensuales de 30 (ene 2026) a 65 (sep 2026); dic 2025 = 57. En comparación directa equivale a ~43% de "pechera para perro" (28.3 frente a 65.7). La categoría vecina "cama para perro" muestra **estacionalidad invernal**: dic 2025 = 85, ene 2026 = 78, frente a 52–59 de mar a jun 2026. — [Trends "cama para gato"](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=cama%20para%20gato); [Trends "cama para perro"](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=cama%20para%20perro) (acc. 2026-10-22)
- **Proveedor nacional:** No disponible. Fancy Pets tiene una línea "Textiles" para gato en su catálogo (sin precios de mayoreo públicos). — [Fancy Pets](https://www.fancypets.mx/) (acc. 2026-10-22)

### Inferences
- HIPÓTESIS (estacionalidad): por la estacionalidad invernal de "cama para perro" y el nº134 general a finales de octubre, la ventana de venta sería **oct–feb**, con pico en dic–ene. Hay que confirmarlo con Trends a 5 años antes de comprometer inventario.
- ESTIMACIÓN de saturación: **baja-media**. Hay pocos listados con historial (50–457 calificaciones), calificaciones mediocres (3.9–4.0★) y no hay marcas grandes. Hay hueco para una versión "talla real" y "acolchado grueso".
- HIPÓTESIS (comprador): dueños de gatos en CDMX/Edomex (noches frías en invierno en el Valle de México). Es una compra emocional o de regalo ("para que no tenga frío").
- HIPÓTESIS (devoluciones): el riesgo **medio** viene de la talla. Hay que publicar medidas internas en cm y el peso del gato recomendado. No es frágil.

### Gaps
- ML: **No disponible** (verificar https://listado.mercadolibre.com.mx/saco-dormir-gato).
- Trends a 5 años para confirmar la estacionalidad: no consultado (se evitó para no exceder la cuota de Trends).
- Proveedor nacional y costo: **No disponible**.
- Facebook Marketplace: **No disponible — requiere verificación manual**.

---

## 7. Candidato: Pañales lavables para perro (envoltura para hembra en celo / banda para macho)

### Takeaway
Es un **problema recurrente** (celo, incontinencia de perros mayores, marcaje) y el término general "pañales para perro" tiene un **interés de búsqueda alto** (≈45% de "pechera para perro"). En Amazon MX la demanda es moderada (≥150 al mes en insignias) y los precios están en rango ($238–$459). Riesgos: tallas (devoluciones) y que se trata de un artículo de higiene, que no se puede revender una vez usado.

### Cited Findings
- **Variantes (HECHO):** juegos de 3–4 piezas; tallas XS–XL; envoltura para hembra o banda abdominal para macho; estampados y colores; almohadillas lavables. — [Amazon MX búsqueda "pañales lavables perro"](https://www.amazon.com.mx/s?k=pa%C3%B1ales+lavables+perro) (acc. 2026-10-22)
- **Presencia en Más vendidos (HECHO, "Artículos de Adiestramiento para Evacuar para Perros"):** #21 Jasinber set de 4 pañales para hembra, lavables, $359.10; #26 SlowTon pañales lavables para macho (set de 3 bandas), $289.99; #20 almohadillas lavables, $349.99. Esta subcategoría la dominan consumibles desechables (bolsas Amazon Basics #1, pañales desechables #2–#3, tapetes entrenadores). — [Amazon MX Más vendidos](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478589011) (acc. 2026-10-22)
- **Ficha (HECHO):** Jasinber B09QX6B5SL: $359.10, 4.6★ (1,609), "100+ comprados el mes pasado", **nº215 en Productos para animales, nº3 en "Pañales para Perros"**; paquete de 22×21.1×7.4 cm, **220 g**; en Amazon desde el 30 de diciembre de 2021. Resumen de Amazon: "les queda perfecto… fácil de lavar… buena talla, aunque las opiniones sobre la absorción son variadas"; aspecto **absorción mixto (71 menciones)**. — [Amazon MX B09QX6B5SL](https://www.amazon.com.mx/dp/B09QX6B5SL) (acc. 2026-10-22)
- **Saturación y precio (HECHO):** "más de 40,000 resultados"; top 20 entre $238 y $459 (mediana $293). Insignias: Jasinber 100+; SlowTon macho 50+; dos listados de almohadillas lavables con 50+. Hay un listado SlowTon de 4 pañales para macho con **1.3★ (4)**. — [Amazon MX búsqueda](https://www.amazon.com.mx/s?k=pa%C3%B1ales+lavables+perro) (acc. 2026-10-22)
- **Google Trends (HECHO; el término incluye pañales desechables):** "pañales para perro" tiene un promedio de 52.8; picos en dic 2025 (91) y jul 2026 (81); oct 2026 = 49. En comparación vale 29.7 frente a 65.7 de "pechera para perro". — [Trends "pañales para perro"](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=pa%C3%B1ales%20para%20perro); [comparación](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=pechera%20para%20perro,pa%C3%B1ales%20para%20perro,cama%20para%20gato,mochila%20para%20perro,cubre%20asiento%20para%20perro) (acc. 2026-10-22)
- **Proveedor nacional:** No disponible.

### Inferences
- ESTIMACIÓN (piso en Amazon MX, solo pañales lavables): 100 + 50 ⇒ **≥150 unidades al mes**. Es un piso bajo frente a la búsqueda en Google, lo que sugiere que buena parte de la demanda va a desechables (HIPÓTESIS).
- ESTIMACIÓN de saturación: **media**. Hay muchos listados, pero pocos líderes de marca (Jasinber y SlowTon son marcas nativas de Amazon) y las calificaciones varían mucho.
- HIPÓTESIS (comprador): dueñas y dueños de perritas sin esterilizar (celo), de perros mayores con incontinencia y de machos que marcan en departamentos. El argumento de ahorro frente a desechables (lavable y reutilizable) funciona para la venta.
- HIPÓTESIS (riesgos): **devoluciones por talla** (riesgo medio-alto; hay que dar una guía de medidas de cintura en cm). Al ser artículo de higiene, conviene aclarar la política de cambios solo sin uso. Muy ligero (220 g) y no es frágil.

### Gaps
- ML: **No disponible** (verificar https://listado.mercadolibre.com.mx/panales-lavables-perro).
- Separar en Trends la intención "lavable" de la "desechable": no posible con los datos obtenidos.
- Proveedor nacional y costo: **No disponible**.
- Facebook Marketplace: **No disponible — requiere verificación manual**.

---

## 8. Candidato: Arnés pechera antijalones con correa (reflejante)

### Takeaway
Es el **accesorio con más demanda y búsquedas** de la categoría: #6 de todo Mascotas en Amazon MX y "pechera para perro" es el término más fuerte y estable en Trends. Pero es también el **más saturado**: compiten marcas grandes (PetSafe, Halti, rabbitgoo, OneTigris), los precios van de $99 a $1,097 y hay un riesgo alto de devolución por talla. La brecha es baja. Solo tiene sentido como producto de tráfico o en un kit diferenciado.

### Cited Findings
- **Variantes (HECHO):** tallas XS–XL; arnés tipo chaleco con 3 hebillas, anillas delantera y trasera (antitirón), tiras reflejantes, funda para AirTag; correa de 1.5 m incluida; colores rosa, fucsia, verde menta, negro y azul. — [Amazon MX Más vendidos Collares, Arneses y Correas](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478595011) (acc. 2026-10-22)
- **Presencia en Más vendidos (HECHO):** MESVIER arnés con correa de 1.5 m, $249, 4.7★ (9,899): **#6 en Productos para animales**, #3 en Artículos para Perros, #1 en Collares/Arneses/Correas. En la misma subcategoría: UNA MASCOTA pechera con correa $219 (#5) y $109 (#9); rabbitgoo $364.65, 4.8★ (157,669) (#7); SlowTon antitirones con correa $399.99 (#8); SAN KARA con correa $99 (#11); MESVIER con funda AirTag $289 (#17). — [Amazon MX Más vendidos – Productos para animales](https://www.amazon.com.mx/gp/bestsellers/pet-supplies); [Collares, Arneses y Correas](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478595011) (acc. 2026-10-22)
- **Ficha (HECHO):** MESVIER B0CYXHFXNW: $249, 4.7★ (9,899), "200+ comprados el mes pasado", nº6 en Productos para animales, **nº1 en "Pecheras para Perros"**; paquete de 28.3×24.4×5.6 cm, **360 g**; en Amazon desde el 13 de abril de 2024. Resumen de Amazon: "muy buena calidad y excelente relación calidad-precio… opiniones diversas sobre la talla"; aspecto **talla mixto (299 menciones)**. — [Amazon MX B0CYXHFXNW](https://www.amazon.com.mx/dp/B0CYXHFXNW) (acc. 2026-10-22)
- **Marcas grandes y dispersión de precios (HECHO):** PetSafe Easy Walk $521.93, 4.6★ (45,923); Halti antitirones $489.28, 4.2★ (14,520); PetSafe 3 en 1 $643.09; OneTigris táctico $548.98–$1,097.09. Hay "más de 2,000 resultados" para "arnes antijalones perro" y el top 20 va de $169 a $1,097 (mediana $446). — [Amazon MX búsqueda](https://www.amazon.com.mx/s?k=arnes+antijalones+perro) (acc. 2026-10-22)
- **Google Trends (HECHO):** "pechera para perro" tiene un interés **alto y estable**: promedio 65.5/100; promedios mensuales entre 50 (jun 2026) y 78 (dic 2025); oct 2026 = 60. "arnes para perro" tiene mucho menos volumen (promedio 18.7, serie irregular). — [Trends "pechera para perro"](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=pechera%20para%20perro); [Trends "arnes para perro"](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=arnes%20para%20perro) (acc. 2026-10-22)
- **Proveedor nacional:** No disponible.

### Inferences
- ESTIMACIÓN de saturación: **muy alta**. Hay marcas globales, un vendedor (MESVIER) que ancla el precio en $249 con correa incluida, opciones desde $99, y una dispersión de $99 a $1,097.
- HIPÓTESIS (comprador): dueños de perros que jalan en paseos urbanos (CDMX) y dueños de cachorros. "Pechera" es el término coloquial mexicano (supera a "arnés" en Trends).
- HIPÓTESIS (riesgos): **devoluciones y cambios de talla altos** (aspecto de talla mixto con 299 menciones en el líder). La pechera es un elemento de sujeción del perro, así que una hebilla o costura de mala calidad puede provocar escapes: es un riesgo de seguridad medio, por lo que hay que verificar las hebillas del lote.
- HIPÓTESIS (margen): con un precio ancla de $249 que incluye correa, el margen de un genérico en Marketplace probablemente es bajo.

### Gaps
- ML: **No disponible** (verificar https://listado.mercadolibre.com.mx/arnes-antijalones-perro y https://listado.mercadolibre.com.mx/pechera-para-perro).
- Proveedor nacional y costo: **No disponible**.
- Facebook Marketplace: **No disponible — requiere verificación manual**.

---

## 9. Proveedores nacionales / dropshipping (transversal a todos los candidatos)

### Takeaway
No se verificó **ningún proveedor nacional con precio unitario, MOQ y envío a cliente final** para ningún candidato. La única plataforma de dropshipping verificada con operación en México (Dropi México) **exige registro para ver catálogo y precios**. Las fichas de Amazon revisadas muestran fabricantes chinos o marcas genéricas importadas, lo que sugiere que el abasto nacional pasa por importadores o almacenes locales.

### Cited Findings
- HECHO: Dropi México se presenta como plataforma de "Dropshipping y logística ecommerce". Dice que "conecta con proveedores locales verificados y centraliza la logística con transportadoras", menciona "más de 63.000 dropshippers en Latinoamérica" y "más de 160.000 productos" en su catálogo, y el registro es gratuito. El catálogo y los precios no son públicos (hay que iniciar sesión o registrarse). — [Dropi México](https://dropi.co/mx); [Dropi – soluciones para dropshippers](https://dropi.co/mx/soluciones-para-dropshippers) (acc. 2026-10-22)
- HECHO: Fancy Pets (marca mexicana de accesorios) publica un catálogo por categorías (Perro: Alimentadores, Dispensadores, Entrenamiento, Grooming, Hábitat, Higiene, Juguetes, Textiles; Gato: Grooming, Hábitat, Higiene, Textiles…). No muestra precios de mayoreo ni un programa de dropshipping en la portada. Sus productos están en Amazon MX: rodillo removedor $151, rascadores de cartón $63–$298, cama cueva sherpa para gato $314. — [Fancy Pets](https://www.fancypets.mx/); [Amazon MX búsqueda "rascador carton gato"](https://www.amazon.com.mx/s?k=rascador+carton+gato) (acc. 2026-10-22)
- HECHO: el sitio dropshippingmexico.com.mx vende franquicias de tecnología desde $70,990 MXN (HP, Lenovo, etc.); **no es relevante** para mascotas. — [Franquicias Dropshipping México](https://www.dropshippingmexico.com.mx/) (acc. 2026-10-22)
- HECHO: fabricantes y origen en las fichas de Amazon MX: tapete arenero LYSSIID ("País de origen China"); comedero ZQSQD; arnés MESVIER (fabricante "MUCHEN TECH"); cinta antiarañazos YELIY; saco para gato NEWKIBOU; tapete rascador TAGNEFLOR; cubreasientos Mancro (fabricante "Kidsgo"); la mochila y la cubierta Raganet indican "Fabricante: Raganet". — fichas [B0DKP3K512](https://www.amazon.com.mx/dp/B0DKP3K512), [B0D9QC5GVY](https://www.amazon.com.mx/dp/B0D9QC5GVY), [B0CYXHFXNW](https://www.amazon.com.mx/dp/B0CYXHFXNW), [B0F91K9GX2](https://www.amazon.com.mx/dp/B0F91K9GX2), [B0F9XF9PYN](https://www.amazon.com.mx/dp/B0F9XF9PYN), [B0GZWRK39V](https://www.amazon.com.mx/dp/B0GZWRK39V), [B085VYPGMD](https://www.amazon.com.mx/dp/B085VYPGMD), [B0BDBVTS18](https://www.amazon.com.mx/dp/B0BDBVTS18) (acc. 2026-10-22)

### Inferences
- HIPÓTESIS: para validar el abasto conviene (1) registrarse gratis en Dropi México y buscar cada candidato (precio al dropshipper, stock, si envía a cliente final con o sin pago contra entrega, y tiempos); (2) revisar en ML a mano los listados de "mayoreo" / "paquete 10 piezas" de cada candidato; (3) contactar distribuidores o marcas nacionales (p. ej., Fancy Pets) para pedir lista de precios de distribuidor. Nada de esto se verificó.
- HIPÓTESIS (precio techo de compra): el **precio piso de los genéricos en Amazon MX** sirve como techo práctico. Si el costo puesto en CDMX no queda claramente por debajo de ese piso, no hay margen. Pisos observados: rodillo $40–$130, tapete $139, comedero $259, cubreasientos $189, protector $149, saco para gato $146, pañales $238, arnés $99 (búsquedas citadas en cada candidato).

### Gaps
- Costo unitario, MOQ y envío a cliente final por candidato: **No disponible** para los 8 candidatos.
- Mayoristas físicos de CDMX: no se pudieron buscar (búsquedas agotadas) → **No disponible**.

---

## 10. Facebook Marketplace (transversal) y verificación manual pendiente

### Takeaway
**No disponible — requiere verificación manual.** Marketplace requiere iniciar sesión y no se accedió. Abajo está lo que hay que revisar a mano para cada candidato.

### Cited Findings
- No se obtuvo ningún dato de Facebook Marketplace (no hay fuente consultable sin sesión).

### Inferences
- Lista de verificación manual (HIPÓTESIS de método), en un radio de ~40 km de CDMX y para cada término ("tapete arenero", "comedero elevado", "cubre asientos perro", "protector sillon gato", "quita pelo mascotas", "saco dormir gato", "pañales lavables perro", "pechera perro"):
  1. Número aproximado de publicaciones activas y cuántas tienen menos de 7 días.
  2. Rango de precios y precio modal.
  3. Cuántos vendedores repiten las mismas fotos de catálogo (señal de dropshippers o revendedores).
  4. Si ofrecen envío o solo entrega en persona, y en qué zonas (metro, plazas).
  5. Interacción visible (publicaciones marcadas como vendidas o "pendiente").
  6. Que el artículo no caiga en categorías restringidas por las Políticas de Comercio de Meta (accesorios no consumibles para mascotas: HIPÓTESIS de que están permitidos; los animales vivos y los medicamentos no lo están; verificar en el centro de políticas de Meta).
- Verificación manual en ML (con sesión): para cada URL de búsqueda indicada, anotar el número de resultados, los 3–4 listados principales con precio, la etiqueta "+X vendidos" (**acumulada desde la creación, no mensual**), la calificación y el número de opiniones, y si aparecen en "Más vendidos" de Animales y Mascotas y en qué posición.

### Gaps
- Todos los datos de Facebook Marketplace y de Mercado Libre.

---

## 11. Ideas evaluadas y rechazadas (o en lista de observación)

### Takeaway
Se descartan sobre todo por **ticket bajo** (guante, tapete lamedor, rascador de cartón, bolsas), **volumen o peso de envío** (escalera de espuma, camas de perro), **riesgo de electrónica** (fuentes y comederos automáticos), **ajuste y fragilidad** (mochila con domo de PVC) o **tallas y temporada corta** (ropa y disfraces).

### Cited Findings
- **Mochila transportadora (lista de observación):** Raganet mochila $259, 4.6★ (3,145), nº368 en Productos para animales, nº1 en "Mochilas para llevar Perros", 42×31×18 cm, PVC; Raganet maleta $169 con "400+ comprados el mes pasado". Quejas: aspecto tamaño mixto (109 menciones), ajuste mixto (75), durabilidad mixta (71); reseña 3★: "la parte de la cúpula transparente es algo blanda". Trends: "mochila para perro" subió en ago–oct 2026 (promedios mensuales de 54, 55 y 65 frente a 0–41 antes; serie ruidosa). Motivo del descarte: un piso de precio muy bajo ($169–$259) impuesto por una marca local fuerte, más riesgo de ajuste y fragilidad del domo. — [Amazon MX B0B45BTNJS](https://www.amazon.com.mx/dp/B0B45BTNJS); [búsqueda](https://www.amazon.com.mx/s?k=mochila+transportadora+gato); [Trends "mochila para perro"](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=mochila%20para%20perro) (acc. 2026-10-22)
- **Escalera o rampa de espuma para perro (lista de observación):** Feandrea 3 peldaños $753.13, 4.5★ (2,441), nº233 en Productos para animales, nº1 en "Escaleras y Escalones para Perros", 100+/mes, **1.9 kg y 57×40×40 cm**. Solo hay 317 resultados para "escalera para perro" (saturación baja) y el top 20 va de $498 a $1,399. Motivo: el volumen voluminoso encarece el envío y el ticket supera $900 en las tallas de 4–5 peldaños. — [Amazon MX B0DZC33MRF](https://www.amazon.com.mx/dp/B0DZC33MRF); [búsqueda](https://www.amazon.com.mx/s?k=escalera+para+perro) (acc. 2026-10-22)
- **Guante quitapelo:** top 20 entre $89 y $239 (mediana $153); SlowTon $158.38, 4.4★ (4,120), 100+/mes; varios genéricos con 3.0–3.7★. Motivo: ticket por debajo de $250 y calidad irregular; sirve como **complemento de un kit** (p. ej., con el tapete arenero). — [Amazon MX búsqueda](https://www.amazon.com.mx/s?k=guante+quita+pelo+mascotas) (acc. 2026-10-22)
- **Tapete lamedor:** listados de $115 a $299 (p. ej., $131.99–$134.99 con 4.4★ y 200 calificaciones; Fancy Pets $115); en Más vendidos de Comida y Agua para Perros aparece en el #16 ($79) y el #25 ($131.99). Motivo: ticket bajo; mejor como complemento. — [Amazon MX búsqueda](https://www.amazon.com.mx/s?k=tapete+lamedor+perro); [Más vendidos](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478591011) (acc. 2026-10-22)
- **Rascador de cartón:** Fancy Pets $63 (200+/mes), $98.99, $126 (100+/mes); el #2 de Camas y Muebles para Gatos es un rascador Fancy Pets de $98.99. Motivo: ticket muy bajo, voluminoso y una marca nacional con precio piso. — [Amazon MX búsqueda](https://www.amazon.com.mx/s?k=rascador+carton+gato); [Más vendidos](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478573011) (acc. 2026-10-22)
- **Dispensador de bolsas para heces:** Amazon Basics 540 bolsas con dispensador, $282, #5 en todo Mascotas. Motivo: consumible commodity dominado por Amazon Basics. — [Amazon MX Más vendidos](https://www.amazon.com.mx/gp/bestsellers/pet-supplies) (acc. 2026-10-22)
- **Fuentes de agua y comederos automáticos (electrónica, RIESGO):** el Top 30 de "Agua y Comida para Gatos" lo dominan fuentes eléctricas ($239–$599) y repuestos de filtros; los comederos WiFi cuestan $719–$1,299 con 4.2–4.3★. Motivo: electrónica de calidad incierta, excluida por criterio. — [Amazon MX Más vendidos Alimentación Gatos](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478572011); [Comida y Agua Perros](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478591011) (acc. 2026-10-22)
- **Ropa y disfraces para perro:** el 22 de octubre el Top 30 de "Accesorios y Ropa para Perros" lo dominan disfraces de Halloween ($98–$239) y suéteres o chamarras ($170–$379). Motivo: muchas devoluciones por talla y ventanas estacionales cortas (HIPÓTESIS). — [Amazon MX Más vendidos Accesorios y Ropa Perros](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478588011) (acc. 2026-10-22)
- **Cama tipo dona o antiestrés para perro:** "cama para perro" tiene búsqueda alta con pico invernal (dic 2025 = 85), pero el Top 30 de Camas y Muebles para Perros lo dominan Feandrea y Pets Apparel Hills ($194–$2,290). Motivo: volumen y peso de envío, y marcas establecidas. — [Amazon MX Más vendidos Camas Perros](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478593011); [Trends](https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=cama%20para%20perro) (acc. 2026-10-22)
- **Plato de comedero lento suelto y pechera reflejante sola:** los platos lentos sueltos cuestan $95–$99 (Más vendidos #27 y #29), así que se integran al comedero elevado 3 en 1. La pechera reflejante se integra al candidato 8. — [Amazon MX Más vendidos](https://www.amazon.com.mx/gp/bestsellers/pet-supplies/12478591011) (acc. 2026-10-22)

### Inferences
- HIPÓTESIS: guante, tapete lamedor y plato lento funcionan como **complementos** para subir el ticket de los candidatos principales (kits), no como productos independientes.

### Gaps
- Evidencia de ML y de Facebook Marketplace para las ideas rechazadas: **No disponible**.

---

## 12. Síntesis: tabla resumen y recomendación preliminar

### Takeaway
Los tres más prometedores con la evidencia disponible (solo Amazon MX y Trends; ML y Facebook Marketplace pendientes de verificar a mano):
1. **Comedero elevado ajustable 3 en 1**: la demanda mensual más fuerte (≥1,200 al mes en Amazon) dentro del ticket, buenas calificaciones y sin marcas dominantes.
2. **Tapete atrapa-arena doble capa (en kit)**: la menor saturación (473 resultados), producto bien calificado, ligero y con pocas devoluciones; se recomienda vender en kit para subir el ticket.
3. **Cubreasientos / hamaca de auto reforzado**: demanda fuerte (≥1,400 al mes) y una brecha de durabilidad documentada en el líder barato.

Alternativas contraintuitivas: **protector antiarañazos de sillón** (brecha de adhesivo) y **saco térmico para gato** (ventana estacional oct–feb).

### Cited Findings
Tabla resumen. Fuentes: secciones 1–8. Precios en MXN, Amazon MX, acc. 2026-10-22. Demanda de Amazon = suma de insignias "comprados el mes pasado" (ESTIMACIÓN, piso). Señales = juicio preliminar (HIPÓTESIS) salvo donde se indica N/D.

| # | Candidato | Precio ML | Evidencia ML | Evidencia Amazon MX (HECHO) | Trends MX 12m (HECHO) | Proveedor nacional + costo | Peso/fragilidad | Demanda | Crecimiento | Brecha competitiva | Margen | Facilidad de abasto |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Tapete atrapa-arena doble capa (gato) | N/D (snippet no verificado ~$160) | No disponible (bloqueo) | $139–$299 (med. $250); líder 4.6★ (344), nº1 en su nodo, nº476 en Mascotas; 473 resultados; ≥150/mes | Término específico: no concluyente; proxy "arenero para gato" alto y estable (prom. 70.8) | No disponible | Ligero (peso N/D), EVA, no frágil | Media | Media (proxy estable) | **Alta** (baja saturación) | Media-baja (ticket bajo → kit) | N/D |
| 2 | Comedero elevado ajustable 3 en 1 | N/D | No disponible | $259–$498 (med. $393); ZQSQD 4.8★ (383), nº1 Comedores, nº372 en Mascotas; 5 listados en el top 15 de su subcategoría; ≥1,200/mes | No concluyente (volumen insuficiente) | No disponible | 900 g, acero, no frágil (evitar cerámica) | **Alta** | N/D | Media (muchos listados, sin marcas) | Media (ticket $340–$400) | N/D |
| 3 | Cubreasientos / hamaca auto | N/D | No disponible (snippet: un listado con 4.6★) | $189–$1,239 (med. $458); Raganet nº133, Mancro 8,754 calificaciones; ≥1,400/mes; Raganet con durabilidad negativa (145) | Muy bajo / no concluyente | No disponible | Peso N/D, tela plegable, no frágil | **Alta** | N/D | Media-alta (hueco de calidad) | Media-alta (ticket $364–$599) | N/D |
| 4 | Protector antiarañazos de sillón (cinta / tapete autoadhesivo) | N/D | No disponible | $149–$394 (med. $210); 7 listados en el top 30 de Camas y Muebles Gatos; YELIY 200+/mes; adherencia negativa (54); ≥500/mes | No concluyente | No disponible | 100–350 g, no frágil | Media | N/D (listados recientes de 2025–2026) | Media-alta (calidad de adhesivo) | Media-baja (ticket bajo → paquete) | N/D |
| 5 | Rodillo quitapelo reutilizable | N/D (snippet $89 no verificado) | No disponible | $40–$499 (med. $146); ACE2ACE nº141 en Mascotas, nº1 en su nodo, 200+/mes; >30,000 resultados; genéricos con 3.8★ y "no sirve"; ≥450/mes | No concluyente | No disponible (Fancy Pets sin mayoreo público) | ~23×13×3 cm, ligero, no frágil | Alta | N/D | Baja (saturado + marca original) | Baja (precio de referencia bajo) | N/D |
| 6 | Saco de dormir / cama cueva térmica gato | N/D | No disponible | $146–$653 (med. $286); nº134 en Mascotas y nº1 Cobijas gatos el 22-oct; 50+/mes; quejas de tamaño y grosor | "cama para gato" prom. 46.8 y estable; "cama para perro" con pico en dic–ene | No disponible | 250 g, no frágil | Media (estacional) | Media-alta (estacional, HIPÓTESIS) | Media-alta | Media | N/D |
| 7 | Pañales lavables perro (hembra/macho) | N/D | No disponible | $238–$459 (med. $293); Jasinber nº215 en Mascotas, nº3 Pañales, 100+/mes; absorción mixta (71); ≥150/mes | "pañales para perro" prom. 52.8 (incluye desechables), picos en dic y jul | No disponible | 220 g, no frágil | Media | Media | Media | Media | N/D |
| 8 | Arnés pechera antijalones + correa | N/D | No disponible | $99–$1,097 (med. $446); MESVIER #6 en todo Mascotas, 200+/mes, talla mixta (299); PetSafe, Halti, rabbitgoo presentes | "pechera para perro" alto y estable (prom. 65.5) | No disponible | 360 g, no frágil; riesgo de talla y de hebillas | **Alta** | Estable | **Baja** | Baja | N/D |

### Inferences
- **Top 1 – Comedero elevado ajustable 3 en 1 (HIPÓTESIS de prioridad):** es el único candidato con varios listados de 200–300+ compras al mes dentro de $340–$400, calificaciones de 4.7–4.8★ (el producto cumple), sin marcas grandes y no frágil si es de acero. Riesgos: 0.9 kg encarece el envío y hay genéricos de mala calidad (2.8–3.8★), así que hay que probar una muestra.
- **Top 2 – Tapete atrapa-arena doble capa en kit (HIPÓTESIS):** tiene la menor competencia observada (473 resultados), resuelve un dolor diario de dueños de gatos en departamento, es ligero, sin tallas y no frágil. El kit tapete + guante ya existe con 50+/mes en Amazon. Riesgo: ticket bajo y margen dependiente del costo (N/D).
- **Top 3 – Cubreasientos reforzado (HIPÓTESIS):** tiene demanda fuerte y una queja dominante (durabilidad) en el líder de precio bajo. El ticket objetivo de $399–$549 cae en el rango. Riesgos: ajuste al vehículo y poca búsqueda en Google (depende de que el producto se descubra visualmente, lo que favorece a Marketplace).
- **Contraintuitivos a validar:** protector antiarañazos (calidad de adhesivo como diferenciador; vender en paquete) y saco térmico para gato (ventana oct–feb; conviene validar ML y Marketplace **esta misma temporada**).
- **Antes de decidir, falta (crítico):** (1) los datos de ML de cada candidato (precio, "+X vendidos" acumulado, opiniones, Más vendidos); (2) un proveedor nacional con costo unitario y envío a cliente final (Dropi México con registro, mayoreo en ML, distribuidores); (3) la revisión manual de Facebook Marketplace en CDMX/Edomex. Sin el costo no se puede calcular el margen; las señales de margen de la tabla solo reflejan ticket y precio piso competitivo.

### Gaps
- Margen real: **No disponible** para todos los candidatos (no hay costo de proveedor verificado).
- Crecimiento: Amazon Movers & Shakers sin datos y Trends no concluyente en términos de cola larga. Solo hay señales de estabilidad en términos generales ("pechera para perro", "arenero para gato", "cama para gato", "pañales para perro").
- Mercado Libre y Facebook Marketplace: **No disponible — requiere verificación manual** (ver sección 10).
