# Limpieza, lavandería y herramientas domésticas: candidatos para Facebook Marketplace México (dropshipping nacional), octubre 2026

Fecha de consulta de todas las fuentes: **2026-10-22**, salvo que se indique otra.
Convenciones: **HECHO** = verificado y citado. **ESTIMACIÓN** = cálculo propio con los insumos a la vista. **HIPÓTESIS** = idea razonable sin respaldo citado.
"+X vendidos" en Mercado Libre (ML) = **acumulado desde que se creó la publicación, NO ventas mensuales**. "Más vendido" o "#N en categoría" = **posición relativa, no volumen absoluto**. "X+ comprados el mes pasado" en Amazon = insignia **mensual** de Amazon.

---

## 0. Método y limitaciones de acceso (léase antes que los datos)

### Takeaway
No pude abrir directamente Mercado Libre, Amazon México ni Google Trends: los tres bloquean el acceso automatizado. Los datos de ML y Amazon vienen de **resúmenes del buscador web sobre páginas de esas tiendas**, con fecha de indexación desconocida. Los precios de proveedores sí se verificaron directo en sus sitios (ELE-GATE, MayoreoTotal, Dropi MX).

### Cited Findings
- **HECHO:** las búsquedas y publicaciones de ML (listado.mercadolibre.com.mx, articulo.mercadolibre.com.mx, /mas-vendidos) redirigen a `https://www.mercadolibre.com.mx/gz/account-verification` (verificación de cuenta), y WebFetch devuelve **HTTP 403**. Por eso no se pudo leer en vivo el conteo de resultados de búsqueda ni el ranking de "Más vendidos". Prueba directa el 2026-10-22: [ML búsqueda](https://listado.mercadolibre.com.mx/escoba-silicon-pelo-mascota), [ML Más vendidos](https://www.mercadolibre.com.mx/mas-vendidos).
- **HECHO:** la API pública de ML (`api.mercadolibre.com/sites/MLM/search`) devolvió **HTTP 403**.
- **HECHO:** Amazon México devolvió **HTTP 503** (página antibots) en Best Sellers y Movers & Shakers: [Best Sellers hi](https://www.amazon.com.mx/gp/bestsellers/hi), [Movers & Shakers hi](https://www.amazon.com.mx/gp/movers-and-shakers/hi).
- **HECHO:** Google Trends (endpoint explore, geo=MX, today 12-m) devolvió **HTTP 429** (límite de solicitudes). **Google Trends = "No disponible" para todos los candidatos.** Verificación manual sugerida: `https://trends.google.com/trends/explore?geo=MX&date=today%2012-m&q=<término>`.
- **HECHO:** se agotó a mitad de la investigación el presupuesto de búsquedas web de esta sesión (200 por turno, compartido entre todos los agentes). Por eso varias semillas no se evaluaron (ver sección 9).
- **Advertencia de atribución:** cuando el buscador resume varias URLs de ML o Amazon a la vez, la cifra (p. ej. "4.5/636 opiniones") se asigna a la URL **más probable** según título y contenido. Va marcada "(atribución probable)" cuando no es inequívoca. Todas estas cifras deben **verificarse a mano** antes de decidir.

### Inferences
- **HIPÓTESIS:** las cifras de ML y Amazon pueden estar desfasadas semanas o meses respecto al 2026-10-22, porque dependen del índice del buscador.

### Gaps
- Conteo de resultados de búsqueda en ML por término: **No disponible** (bloqueo).
- Ranking actual de ML "Más vendidos" por categoría: solo hay referencias indirectas.
- Amazon Movers & Shakers: **No disponible**.
- Google Trends México 12 meses: **No disponible** (HTTP 429).

---

## 1. Candidato 1: regadera de alta presión con filtro (anti-sarro y anti-cloro), ahorradora

**Nombres y variantes en México:** "Regadera ahorradora alta presión con filtro", "Regadera aumentadora de presión para agua dura", "Regadera con filtro 15/20 etapas", "Regadera de mano alta presión 3/5 modos con filtro y pausa", "Regadera tipo lluvia acero inoxidable con filtro".

### Takeaway
Es el candidato mejor documentado de punta a punta. Tiene varias publicaciones en ML con etiqueta "MÁS VENDIDO" y cientos de calificaciones, publicaciones en Amazon MX con cientos de reseñas, y un proveedor nacional con existencias en CDMX, precio por mayoreo escalonado (desde $85) y envío directo al cliente final. Pesa 0.5 kg y no es frágil.

### Cited Findings
**Mercado Libre (cifras del resumen del buscador; verificar):**
- **HECHO:** "Skbe 5 modos con 2 filtros": etiqueta **MÁS VENDIDO**, **4.6/5 con 390 calificaciones**, **$395.86** con descuento. URL individual no capturada; aparece en las búsquedas [Regadera con filtro](https://listado.mercadolibre.com.mx/regadera-con-filtro) y [Regadera ahorradora](https://listado.mercadolibre.com.mx/regadera-ahorradora).
- **HECHO:** "Ommo Cabezal OM503 con filtro de 20 etapas": **4.8/5 con 291 calificaciones**, **$394.17**. Mismas búsquedas.
- **HECHO:** "Regadera Acero Inoxidable con Filtro 20 Etapas … 8 Pulgadas OMMO Silver": **MÁS VENDIDO**, **+100 vendidos (acumulado)**, **$619.04**. Filtro integrado para reducir cloro y partículas. [ML MLM55518111](https://www.mercadolibre.com.mx/regadera-acero-inoxidable-con-filtro-20-etapas-de-alta-presion-de-agua-8-pulgadas-ommo-silver/p/MLM55518111)
- **HECHO:** existe la publicación de catálogo "Regadera Aumentadora De Presión Para Agua Dura" [ML MLM49359931](https://www.mercadolibre.com.mx/regadera-aumentadora-de-presion-para-agua-dura-color-satinado/p/MLM49359931). Otra muestra **"MÁS VENDIDO" 4.7/5 con 34 calificaciones a $549.45** (Fenbeli cuadrada acero inox). Ver también [ML MLM-1934112773](https://articulo.mercadolibre.com.mx/MLM-1934112773-regadera-cabezal-de-ducha-ahorradora-alta-presion-acero-inox-_JM).
- **HECHO (ancla de precio bajo):** las regaderas fijas ahorradoras básicas cuestan **$72–80**: Sanplom 6 L/min a $72.19 (4.7/132) y Raptores a $79.78 (4.6/35). Hay modelos que declaran NOM-008-CONAGUA (5–6 L/min) y "perlas anti sarro". [Regadera ahorradora](https://listado.mercadolibre.com.mx/regadera-ahorradora)
- **HECHO (queja):** una regadera "ahorradora alta presión" con promedio **3.7** tiene reseñas mixtas. Mismas búsquedas.

**Amazon México:**
- **HECHO:** DOBEVI combo 12" lluvia + regadera de mano: **4.3/5, 895 calificaciones**, categoría Herramientas y Mejoras del Hogar. [Amazon B0BZVH9VVS](https://www.amazon.com.mx/DOBEVI-Regaderas-Pulgadas-Regadera-Cuadrada/dp/B0BZVH9VVS)
- **HECHO:** VMASSTONE HM-003, regadera de mano filtrada para agua dura: **4.4/5, 159 calificaciones**. [Amazon B0FNDTW5W8](https://www.amazon.com.mx/Regadera-Filtrada-Rociados-Desmontable-Ajustable/dp/B0FNDTW5W8)
- **HECHO:** AZULDIMEN con filtro de 15 etapas: **4.6/5, 156 calificaciones**. [Amazon B0DK53X8JT](https://www.amazon.com.mx/AZULDIMEN-Regaderas-Presi%C3%B3n-Elimina-Impurezas/dp/B0DK53X8JT)
- **HECHO:** CAILESER 10" con 20 capas de filtrado: **4.1/5, 316 calificaciones**. [Amazon B0DPQK4WTJ](https://www.amazon.com.mx/Regaderas-Filtro-Cabezal-Ducha-Filtrado/dp/B0DPQK4WTJ)
- **HECHO (queja principal):** la "Regadera Aumentadora de Presión Para Agua Dura" (VASA Filtros) tiene **4.1/5 con 13 calificaciones**. Una reseña de 1 estrella dice que **"no aumentó en nada la presión"**. [Amazon B0D6WTRBXM](https://www.amazon.com.mx/Regadera-Aumentadora-Presi%C3%B3n-Para-Blanco/dp/B0D6WTRBXM) / [Amazon B0D6X92JLX](https://www.amazon.com.mx/Regadera-Aumentadora-Presi%C3%B3n-Para-Negro/dp/B0D6X92JLX)
- Posición en Best Sellers o Movers & Shakers: **No disponible** (Amazon 503).

**Proveedor nacional (verificado directo en el sitio):**
- **HECHO:** ELE-GATE, "Regadera de Mano Alta Presión 3 Modos con Filtro y Pausa" (SKU HOG.349). Precio por mayoreo: **1–9 pzas $110; 10–49 $100; 50–99 $95; 100+ $85** (precio tachado $120). Existencias: "Ejecentral32: 73", "U14: 16", "Ecommerce: 43". Peso **0.500 kg**. [ELE-GATE HOG.349](https://www.ele-gate.com/producto/regadera-mano-alta-presion-3-modos-filtro-pausa/)
- **HECHO:** ELE-GATE, "Regadera Cuadrada Tipo Lluvia De Acero Inoxidable" (HOG.116): **1–9 $120; 10–49 $100; 50–99 $90; 100+ $80**, "solo quedan 13". [ELE-GATE HOG.116](https://www.ele-gate.com/producto/regadera-cuadrada-tipo-lluvia-de-acero-inoxidable/)
- **HECHO (modelo de ELE-GATE):** dropshipping sin inventario con **$0 de inversión inicial**. "Nosotros lo empacamos y enviamos directamente a tu cliente", despacho en **48 h hábiles**, paquetería J&T Express, iMile o Cainiao con costo según destino, factura **CFDI 4.0**. Si el producto llega dañado por error de empaque, lo reponen sin costo. Menciona **Facebook Marketplace** entre las plataformas compatibles. [ELE-GATE dropshipping](https://www.ele-gate.com/dropshipping-ele-gate/)
- **HECHO (referencia minorista con pago contra entrega):** MayoreoTotal vende "CABEZAL DE REGADERA DUCHA" a **$299** (tachado $499) con pago contra entrega en toda la república. [MayoreoTotal](https://www.mayoreototal.mx/products/cabezal-de-regadera-ducha)

### Inferences
- **ESTIMACIÓN (margen bruto antes de envío, comisiones y anuncios):** a un precio de venta de $349, contra un costo ELE-GATE de $110 (1–9 pzas), quedan **≈$239 (68%)**. Con 10–49 pzas a $100 quedan ≈$249. El costo del envío nacional falta (ELE-GATE lo cotiza por destino) y puede comerse una parte grande del margen.
- **ESTIMACIÓN de saturación: media.** En ML hay varias publicaciones "MÁS VENDIDO" con 290–390 calificaciones y marcas de importación como Ommo, Skbe y Fenbeli. No se ve una marca nacional dominante en el segmento con filtro. El segmento básico ahorrador ($72–80) sí está muy saturado.
- **HIPÓTESIS (ángulo México):** en CDMX y Edomex muchas casas reciben el agua por gravedad desde el **tinaco**, con poca presión, y el agua dura deja **sarro** en regaderas. El mensaje "más presión y menos sarro o cloro en piel y cabello" encaja con dolores locales. No tengo fuente citada sobre dureza del agua ni presión; validar.
- **HIPÓTESIS (riesgo de devolución):** el riesgo principal es la **expectativa de presión**. Con el tinaco a muy poca altura, ninguna regadera "aumenta" la presión (ver la queja en Amazon). Otros riesgos son la incompatibilidad de rosca (½" estándar, conviene confirmar) y fugas si el cliente no usa cinta teflón. Mitigación: incluir cinta teflón y un filtro de repuesto (paquete de $349–$449) y aclarar "ideal para presión baja o media".
- **Peso/fragilidad:** 0.5 kg según ELE-GATE, de plástico y sin piezas frágiles. Las dimensiones publicadas (6×5×3 cm) parecen un dato genérico; verificar.

### Gaps
- Google Trends "regadera con filtro" / "regadera alta presión": **No disponible** (HTTP 429).
- Si los precios de ELE-GATE incluyen IVA: no verificado.
- Costo real de envío ELE-GATE a CDMX/Edomex: no publicado.
- Facebook Marketplace: **No disponible, requiere verificación manual.** Revisar en un radio de 40 km de CDMX cuántas publicaciones activas hay de "regadera con filtro" y "regadera alta presión", el rango de precios, si los vendedores ofrecen envío o solo entrega en punto (metro o plaza), y si hay anuncios repetidos de revendedores (señal de saturación).

---

## 2. Candidato 2: tendedero retráctil de pared (y plegable para interior)

**Nombres y variantes:** "Tendedero retráctil de pared 2/3/4/5 líneas", "Tendedero plegable retráctil reforzado metal", "Tendedero retráctil acero inoxidable 2.8 m / 4.2 m / 5.2 m", "Tendedero retráctil sin perforación", "Tendedero plegable 3 niveles con ruedas".

### Takeaway
Tiene una demanda fuerte y estable, con una publicación de ML de 636 opiniones y publicaciones en Amazon con "200+ comprados el mes pasado". Además encaja con un rasgo muy mexicano: departamentos chicos, azotea compartida y lluvias que obligan a secar dentro. **No encontré un proveedor mayorista nacional con precio público**, solo precios de menudeo y pago contra entrega.

### Cited Findings
**Mercado Libre (cifras del resumen del buscador; verificar):**
- **HECHO:** tendedero retráctil de 3 líneas interior/exterior: **4.5/5 con 636 opiniones**, la cifra más alta de los resultados. Queja: "la cuerda se atora si no se tensa bien con el seguro". [ML MLM-809426412](https://articulo.mercadolibre.com.mx/MLM-809426412-tendedero-retractil-plegable-pared-interior-exterior-3lineas-_JM) (atribución probable)
- **HECHO:** tendedero retráctil de 2 líneas (vendedor MercadoLíder): **4.8/5 con 237 opiniones**. Se elogia que no se oxida; un comprador dice que es mejor para ropa ligera que para cobijas. [ML MLM-1600857226](https://articulo.mercadolibre.com.mx/MLM-1600857226-tendederos-plegables-tendedero-retractil-de-pared-2-lineas-_JM) (atribución probable)
- **HECHO:** Harmei: **#3 en la categoría Tendederos de ML**, 4.5/5 con 62 opiniones. [ML MLM45283785](https://www.mercadolibre.com.mx/harmei-tendedero-plegable-retractil-de-paredtendedero-para-ropa-y-cobijas-pesadas-con-pinzas-y-cuerda-con-alambrereforzado-con-metalcompacto-ahorro-de-espaciocapacidad-de-carga-resistente/p/MLM45283785)
- **HECHO:** Tensoline T3 (3 cables de 450 cm): **#7 en Tendederos**, 4.4/5 con 72 opiniones. [ML MLM29693334](https://www.mercadolibre.com.mx/tendedero-retractil-tensoline-t3-de-pared-color-blanco-de-3-cables-medida-de-cada-cable-450cm-ajustable/p/MLM29693334)
- **HECHO (queja principal):** un tendedero de 4 líneas tiene **3.9/5 con 264 opiniones** y varios reportes de **cordones de plástico o tela que se rompen con peso**. Otro de 4 líneas tiene una reseña de 1 estrella por cordones rotos a las pocas semanas. [ML MLM-1399188532](https://articulo.mercadolibre.com.mx/MLM-1399188532-tendedero-ropa-retractil-de-pared-interior-exterior-4-lineas-_JM), [ML MLM-1402074010](https://articulo.mercadolibre.com.mx/MLM-1402074010-tendedero-retractil-plegable-pared-interior-exterior-4lineas-_JM) (atribución probable)
- **HECHO:** los tendederos plegables y retráctiles van de **≈$170 a más de $1,000 MXN**. Los retráctiles de pared suelen traer cuerda de 15–20 m, 20 pinzas y declaran 120–160 kg (dato del vendedor, poco creíble). [Tendederos de ropa plegables](https://listado.mercadolibre.com.mx/tendederos-de-ropa-plegables), [Tendedero retráctil](https://listado.mercadolibre.com.mx/tendedero-retractil)

**Amazon México:**
- **HECHO:** existe una lista de Best Sellers propia de "Tendederos". El **#1 es SONGMICS plegable de 2 niveles** (33 barras); le siguen MXCOCO, Sugarzoon, MOONPAI y AKASENKO. Fecha de la captura desconocida. [Amazon Best Sellers Tendederos](https://www.amazon.com.mx/gp/bestsellers/kitchen/9756907011)
- **HECHO:** tendedero retráctil genérico de 20 m: **4.7/5 (163)**, **50+ comprados el mes pasado**, **#4 en Tendederos**. [Amazon B0F9LJBT8H](https://www.amazon.com.mx/Gen%C3%A9rico-TENDEDERO-RETRACTIL-Pared-retractiles/dp/B0F9LJBT8H)
- **HECHO:** KIROGILY 5.2 m / 25 kg: **4.5/5 (73)**, **200+ comprados el mes pasado**. [Amazon B0F59VB6YT](https://www.amazon.com.mx/KIROGILY-Tendedero-Interiores-Retractiles-Instalaci%C3%B3n/dp/B0F59VB6YT)
- **HECHO:** genérico de 4.2 m: **4.7/5 (180)**, **#10 en Tendederos**. [Amazon B0DL91BB62](https://www.amazon.com.mx/Gen%C3%A9rico-TENDEDERO-RETRACTIL-Pared-retractiles/dp/B0DL91BB62). BOJA 2.8 m inox 304: **4.3/5 (297)**, **#61 en Tendederos**. [Amazon B0B6GGXJPF](https://www.amazon.com.mx/BOJA-Tendedero-Retr%C3%A1ctil-Inoxidable-Resistente/dp/B0B6GGXJPF)
- **HECHO (variante para quien renta):** vantisan, retráctil "**sin perforación**", 2×5.2 m, carga de hasta 15 kg. [Amazon B0CSDFLKQ5](https://www.amazon.com.mx/vantisan-Tendedero-Retractil-Inoxidable-Perforaci%C3%B3n/dp/B0CSDFLKQ5)

**Proveedores y referencias de precio (no son mayoristas con precio público):**
- **HECHO:** MayoreoTotal, "Tendedero Retráctil 2.8 m": **$269** (tachado $450), acero inoxidable 304, pago contra entrega en toda la república. "Tendedero retráctil de 4 cuerdas": **$399**. [MayoreoTotal 2.8 m](https://www.mayoreototal.mx/products/tendedero-retractil-2-8-m), [MayoreoTotal 4 cuerdas](https://www.mayoreototal.mx/products/tendedero-retractil-de-4-cuerdas). Su política: entrega a domicilio sin mínimo de compra solo en CDMX y área metropolitana, efectivo contra entrega en pedidos menores a $5,000 [Cómo comprar](https://www.mayoreototal.mx/pages/como-comprar), y mejora de precio solo en compras de más de **$50,000** de un producto [Compra por mayoreo](https://www.mayoreototal.mx/pages/compra-por-mayoreo).
- **HECHO (anclas de menudeo):** Home Depot MX vende un retráctil de 3.5 m a **$149** [Home Depot](https://www.homedepot.com.mx/p/home-home-tendedero-retractil-35-metros-85-x-6-x-14-cm-blanco-wom210-143125). Sodimac vende el Tenvil de 3 cables × 4.5 m a **$549** [Sodimac Tendederos](https://www.sodimac.com.mx/sodimac-mx/category/cat11596/Tendederos). Muebles para Baño (distribuidor) tiene el JSuites a **$267.26** [mueblesparabano.mx](https://mueblesparabano.mx/categorias/tendederos).
- **HECHO:** ELE-GATE no devolvió tendederos en su buscador interno, solo canastas para pinzas. [ELE-GATE búsqueda](https://www.ele-gate.com/?s=tendedero&post_type=product)

### Inferences
- **ESTIMACIÓN de margen:** sin costo mayorista verificado no se puede calcular. Comprando a precio de menudeo en MayoreoTotal ($269) y vendiendo a $399–449 quedarían $130–180 antes de envío, un margen ajustado. **Hace falta cotizar con un importador o mayorista** (Centro CDMX o Dropi con registro).
- **ESTIMACIÓN de saturación: media-alta.** Hay muchas marcas genéricas y precios de menudeo desde $149 en tiendas de autoservicio. La diferenciación posible está en la calidad del cable (acero frente a cordón de tela, que es la queja documentada) y en el modelo "sin perforación" para quien renta.
- **HIPÓTESIS (ángulo México):** departamentos chicos sin patio, azoteas compartidas con riesgo de robo de ropa y la temporada de lluvias (aprox. junio a septiembre en el Valle de México) empujan a secar dentro (baño, balcón, cuarto de lavado). Pico esperado entre mayo y septiembre; falta validar con Trends.
- **Peso/fragilidad/devoluciones (HIPÓTESIS):** el retráctil de carcasa ABS o inox pesa aproximadamente 0.5–1.5 kg (no verificado), es compacto y no frágil. El riesgo de devolución viene de la instalación (taladro y taquetes), de cordones rotos y de expectativas de carga exageradas (120–160 kg declarados). Hay que vender con la carga real.

### Gaps
- Precio mayorista nacional, pedido mínimo y envío directo al cliente: **No disponible**.
- Google Trends "tendedero retráctil": **No disponible**.
- Peso exacto del producto: no verificado (MayoreoTotal registra 1,000 g, aparentemente un valor genérico).
- Facebook Marketplace: **No disponible, requiere verificación manual.** Contar los anuncios de "tendedero retráctil" y "tendedero plegable" en CDMX y Edomex, revisar si dominan los tendederos de pie (más voluminosos) o los de pared, y los precios típicos frente a $149 (Home Depot).

---

## 3. Candidato 3: escoba de goma o silicón quita pelo de mascota (con jalador), idealmente en "kit anti-pelo"

**Nombres y variantes:** "Escoba de goma para removedor de pelo de mascotas", "Escoba de silicón con jalador 2 en 1", "Escoba Pro 2 en 1 cerdas de hule y jalador", "Escoba de goma con mango telescópico". Paquete sugerido: escoba + rodillo quitapelusa reutilizable + guante quita pelo.

### Takeaway
Amazon MX tiene varias escobas de goma con más de 1,000 reseñas, y en ML la "Escoba Pro 2 en 1 con cerdas de hule y jalador" aparece como 1° Más vendido en Escobas. La demanda está probada. La competencia de marcas (Practiclean, Betterware) es fuerte y **no encontré proveedor nacional con precio mayorista**.

### Cited Findings
**Mercado Libre (cifras del resumen del buscador; verificar):**
- **HECHO:** "Escoba De Goma Para Removedor De Pelo De Mascotas": etiqueta **MÁS VENDIDO**, **4.6/5 con 51 calificaciones**, **$290** (−10%). [ML MLM2051814075](https://www.mercadolibre.com.mx/escoba-de-goma-para-removedor-de-pelo-de-mascotas/p/MLM2051814075) (atribución probable)
- **HECHO:** otra escoba del mismo tipo marca **"+100 vendidos" (acumulado)**, de un vendedor con más de 10 mil ventas, a **$187** (antes $275). Las importaciones desde China muestran +5 vendidos a $91–$254. [Escobas de goma](https://listado.mercadolibre.com.mx/escobas-de-goma), [Escoba para pelos de perro o gato](https://listado.mercadolibre.com.mx/escoba-para-pelos-de-perro-o-gato)
- **HECHO:** en el listado de la categoría Escobas, la "Escoba Pro 2 en 1 con cerdas de hule y jalador para líquidos y pelo" (Practiclean, Betterware) aparece como **1° MÁS VENDIDO, 4.7/5 (240 calificaciones)**. [Accesorios de limpieza – Escobas](https://listado.mercadolibre.com.mx/hogar-muebles-jardin/cuidado-hogar-lavanderia/accesorios-limpieza/escobas/)
- **HECHO:** en la página "Más vendidos" de Escobas, el #1 es un **kit organizador de escobas y trapeador Reynera**, el #2 la **Escoba Barredora Mágica Manual Reynera** y el #5 la "Escoba Pro con jalador multifuncional". Posición ≠ volumen. [ML Más vendidos MLM156015](https://www.mercadolibre.com.mx/mas-vendidos/MLM156015). Un artículo de blog de ML de 2024 menciona a PRACTICLEAN y la "Escoba Mágica" como las escobas más vendidas [ML blog escobas](https://www.mercadolibre.com.mx/blog/mas-vendidos/escobas) (es de 2024, puede estar desactualizado).
- **HECHO (componente del kit):** rodillo quitapelo "2 en 1" lavable: **+1000 vendidos, 4.5/5 (124), $111** [ML MLM19944626](https://www.mercadolibre.com.mx/rodillo-quita-pelo-removedor-pelusa-2-en-1-lavable/p/MLM19944626). Rodillo lavable de 5 piezas: **+1000 vendidos, $35** [ML MLM28965713](https://www.mercadolibre.com.mx/rodillo-quita-pelusa-lavable-5-rodillos-removedor-de-pelo/p/MLM28965713). Kit JANUS con mangos reutilizables: **MÁS VENDIDO, 4.8 (82), $299** [Rodillo quita pelusa reutilizable](https://listado.mercadolibre.com.mx/rodillo-quita-pelusa-reutilizable).

**Amazon México:**
- **HECHO:** LJXZXMY (mango de 132 cm): **4.5/5, 1,345 calificaciones** [Amazon B08933625K](https://www.amazon.com.mx/LJXZXMY-eliminar-escobilla-ajustable-eliminaci%C3%B3n/dp/B08933625K). TreeLen (59"): **4.2/5, 1,669** [Amazon B087WVLZ5C](https://www.amazon.com.mx/eliminar-rastrillo-mascotas-pulgadas-ventanas/dp/B087WVLZ5C). Homilifibra (57" con rasqueta): **4.2/5, 2,103** [Amazon B0BFBJ647S](https://www.amazon.com.mx/mascotas-alfombras-rastrillo-pulgadas-port%C3%A1til/dp/B0BFBJ647S).
- **HECHO:** FURemover, juego de 2: **4.3/5, 1,172** [Amazon B08JD33T3M](https://www.amazon.com.mx/FURemover-Resistente-Interiores-Exteriores-Extragrande/dp/B08JD33T3M). DOTOTO: **4.5/5, 299** [Amazon B0C3QR3DL1](https://www.amazon.com.mx/DOTOTO-Escoba-Goma-removedor-Mascotas/dp/B0C3QR3DL1). BERLFY: **3.2/5 con solo 6** [Amazon B0BGBBTDLB](https://www.amazon.com.mx/BERLFY-removedor-mascotas-escobilla-alfombras/dp/B0BGBBTDLB).
- Posición en Best Sellers o Movers & Shakers: **No disponible**.

**Proveedor:**
- **HECHO:** no encontré un mayorista o dropshipper nacional con precio publicado para escoba de goma o silicón. En ML no aparecieron lotes de mayoreo de escoba de silicón, solo lotes de escobas de fibra (p. ej. 18 piezas sin bastón a $815; 10 piezas Klintek a $899). [Escobas por mayoreo](https://listado.mercadolibre.com.mx/escobas-por-mayoreo)
- **HECHO (componentes del kit disponibles en ELE-GATE):** "Guante Quita Pelo Para Mascotas" a **$25** (tachado $30) en el listado de búsqueda; no se revisaron los niveles de mayoreo. [ELE-GATE guante](https://www.ele-gate.com/producto/guante-quita-pelo-para-mascotas/)
- **HECHO:** ELE-GATE vende la "Escoba Barredora Mágica Aspiradora Manual" (la variante #2 en ML Más vendidos) a **1–9 $170 → 100+ $140** [ELE-GATE HOG.03](https://www.ele-gate.com/producto/escoba-barredora-magica-aspiradora-manual-recogedor-basura/). MayoreoTotal la vende al público a **$169** (tachado $250) [MayoreoTotal Escoba mágica](https://www.mayoreototal.mx/products/escoba-magica). Ver rechazo en la sección 8.

### Inferences
- **ESTIMACIÓN de saturación: alta** en la escoba sola, por la presencia de Betterware y Practiclean y de precios desde $187. Un **"kit anti-pelo" de $299–$399** (escoba + rodillo reutilizable + guante) diferencia y sube el ticket. Ejemplo de referencia: el kit JANUS de $299 aparece con "MÁS VENDIDO".
- **HIPÓTESIS (ángulo México):** muchos hogares de CDMX tienen perro o gato y piso de loseta o cerámica, donde la escoba de goma también sirve como jalador de agua tras trapear o lavar el patio. Falta cita sobre tenencia de mascotas.
- **Peso/fragilidad (HIPÓTESIS):** aproximadamente 0.6–1 kg y poco frágil, pero **largo** (mango de 130–150 cm, por lo general en 3–4 tramos). Hay que confirmar que el empaque mida menos de 60 cm para no pagar envío por volumen. Riesgo de devolución bajo, salvo cerdas que se despegan (no documentado).

### Gaps
- Proveedor nacional con costo unitario, pedido mínimo y envío al cliente: **No disponible**.
- Google Trends "escoba de goma" / "escoba para pelo de perro": **No disponible**.
- Quejas específicas citadas sobre escobas de goma: no capturadas (solo calificaciones).
- Facebook Marketplace: **No disponible, requiere verificación manual.** Buscar "escoba de silicón", "escoba quita pelo" y "escoba mágica" y ver si el producto ya circula en anuncios de catálogo tipo Betterware vendidos por distribuidoras locales (competencia fuerte en Marketplace).

---

## 4. Candidato 4: trapeador con atomizador (spray mop) de microfibra

**Nombres y variantes:** "Trapeador Spray Mop con atomizador", "Mop con rociador 360°", "Trapeador con atomizador microfibra 3/4/5 almohadillas", "Spray Mop Betterware".

### Takeaway
Hay demanda acumulada alta: dos publicaciones de ML con "+1000 vendidos" y en Amazon puestos de top 5 en subcategoría y "100+ comprados el mes pasado". Es ligero en comparación con el mop de cubeta. **No hay proveedor mayorista nacional verificado**, y Betterware y Vileda marcan las referencias de precio.

### Cited Findings
**Mercado Libre (resumen del buscador; verificar):**
- **HECHO:** "Trapeador Spray Mop Microfibra Atomizador 4 Almohadillas": **≈$410**, etiqueta **MÁS VENDIDO**, **4.7/5 (29 opiniones)**. El resumen también lo asocia a **"+1000 vendidos"**, una combinación que habría que verificar (pocas opiniones para tantas ventas). [Trapeador con atomizador](https://listado.mercadolibre.com.mx/trapeador-con-atomizador), [Trapeador Spray Mop](https://listado.mercadolibre.com.mx/trapeador-spray-mop)
- **HECHO:** "Mopa Trapeador Piso Iqual 1612 Spray Mop Max C/ Rociador 360": **+1000 vendidos (acumulado)**. [ML MLM20077596](https://www.mercadolibre.com.mx/mopa-trapeador-piso-iqual-1612-spray-mop-max-c-rociador-360/p/MLM20077596)
- **HECHO:** los modelos de microfibra con 3–5 almohadillas cuestan **≈$300–$550**, y los Betterware **≈$600–$660**. Marcas frecuentes: Betterware, Practiclean y Magitel. [ML MLM49784032](https://www.mercadolibre.com.mx/trapeador-spray-mop-limpiador-75cm-con-microfibra-atomizador/p/MLM49784032), [ML Betterware MLM-1855182805](https://articulo.mercadolibre.com.mx/MLM-1855182805-trapeador-spray-mop-betterware-con-atomizador-_JM), [Categoría trapeador atomizador](https://hogar.mercadolibre.com.mx/accesorios-limpieza/mop/trapeador-atomizador)

**Amazon México:**
- **HECHO:** VIOPY Mopa en Spray: **4.2/5 (121)**, **#4 en "Trapeador Húmedo y Seco Doméstico"**. [Amazon B0CFKS29BW](https://www.amazon.com.mx/VIOPY-Trapeador-Microfibra-Atomizador-Almohadillas/dp/B0CFKS29BW)
- **HECHO:** trapeador de microfibra con atomizador de 350 ml y 5 almohadillas: **4.3/5 (261)**, **100+ comprados el mes pasado**. [Amazon B0CXDHZYFS](https://www.amazon.com.mx/Microfibra%EF%BC%8CMopa-H%C3%BAmedo%EF%BC%8Ctrapeador-atomizador-Atomizador%EF%BC%8CCabezal-Almohadillas/dp/B0CXDHZYFS)
- **HECHO:** Magitel Spray Mop: **4.0/5 (124)** [Amazon B0B2TLQ6M7](https://www.amazon.com.mx/Magitel-Trapeador-atomizador-Microfibra-48546PT/dp/B0B2TLQ6M7). Betterware Trapeador Rociador tiene publicación propia [Amazon B096GBWRG2](https://www.amazon.com.mx/Betterware-Trapeador-Rociador-Atomizador-Microfibra/dp/B096GBWRG2).
- **HECHO (dato contradictorio):** Vileda Promist MAX aparece con **4.1/5 y 8,728 calificaciones** en un listado y con **4.2 (9)** en otra página del mismo producto. Hay inconsistencia. [Mop con rociador](https://www.amazon.com.mx/mop-con-rociador/s?k=mop+con+rociador)
- **HECHO:** en la subcategoría "Trapeador Húmedo y Seco Doméstico", Vileda Easy Wring lleva la etiqueta de más vendido. [Amazon trapeador doméstico](https://www.amazon.com.mx/trapeador-dom%C3%A9stico/s?k=trapeador+dom%C3%A9stico)

**Proveedor:**
- **HECHO:** MayoreoTotal vende "TRAPEADOR SPRAY CON MICROFIBRA" a **$807**, precio de menudeo que no sirve como costo. [MayoreoTotal](https://www.mayoreototal.mx/products/trapeador-spray-con-microfribra)
- Mayorista o dropshipper nacional con precio unitario: **No disponible** (ELE-GATE no devolvió spray mops en su búsqueda interna).

### Inferences
- **ESTIMACIÓN de saturación: alta.** Hay dos publicaciones con +1000 vendidos, marcas conocidas (Vileda, Betterware) y precios genéricos desde $300.
- **HIPÓTESIS (ángulo México):** en departamentos chicos de CDMX con piso cerámico, el spray mop evita la cubeta (sin espacio de guardado ni patio para tirar agua). El argumento es "trapear sin cubeta".
- **HIPÓTESIS (riesgos):** gatillo o atomizador que gotea o se tapa y mango de 3–4 tramos que se afloja. No pude citar quejas concretas. Peso aproximado de 1–1.5 kg (no verificado) y caja larga.
- **HIPÓTESIS (cumplimiento):** vender el trapeador **sin** líquido limpiador, para no meter químicos en el envío.

### Gaps
- Costo mayorista nacional: **No disponible**.
- Google Trends "trapeador con atomizador": **No disponible**.
- Quejas citadas de compradores: no capturadas.
- Facebook Marketplace: **No disponible, requiere verificación manual.** Ver cuántas vendedoras por catálogo (Betterware, Avon Home, etc.) ofrecen el spray mop en CDMX y a qué precio.

---

## 5. Candidato 5: kit de herramientas básicas para el hogar (53–100 piezas) y juego de destornilladores multipunta

**Nombres y variantes:** "Kit de herramientas para el hogar 100 piezas con estuche", "Caja de herramientas básica 53 piezas", "Juego de desarmadores 30 en 1 con puntas magnéticas", "Kit 7 piezas reparaciones del hogar".

### Takeaway
Es el candidato con la **mejor cadena de suministro nacional verificada**: ELE-GATE tiene existencias de cientos de unidades en bodega, cuatro niveles de precio por mayoreo y envía directo al cliente. La demanda en ML se ve sobre todo en etiquetas "más vendido" con calificaciones de 49–236. No conseguí datos de Amazon. El kit de 100 piezas incluye un voltímetro, un componente eléctrico de calidad incierta que conviene señalar.

### Cited Findings
**Mercado Libre (resumen del buscador; verificar):**
- **HECHO:** kit de 100 piezas de herramientas manuales: etiqueta **"más vendido"**, **4.2/5 (49)**, **$888** (−43%). [Kit de herramientas para hogar](https://listado.mercadolibre.com.mx/kit-de-herramientas-para-hogar), [Caja con herramientas básicas](https://listado.mercadolibre.com.mx/caja-con-herramientas-basicas)
- **HECHO:** GOXAWEE 108 piezas (automotriz y doméstico): **"más vendido"**, **4.8/5 (236)**. Mismas búsquedas. Otro ejemplo de catálogo: [ML Homex 108 piezas MLM41464209](https://www.mercadolibre.com.mx/juego-kit-de-herramientas-mecanicas-domesticas-caja-108-piezas-homex/p/MLM41464209).
- **HECHO:** "Caja Herramientas Básica Imprescindible El Hogar (100 Piezas)", de envío internacional desde China, a **$540**. [Caja herramientas básica](https://listado.mercadolibre.com.mx/caja-herramientas-b%C3%A1sica)
- **HECHO:** el resumen del buscador no mostró conteos "+X vendidos" en estas publicaciones.

**Amazon México:** **No disponible.** No hubo búsqueda específica antes de agotarse el presupuesto, y la página Best Sellers "hi" devolvió 503.

**Proveedor nacional (verificado directo):**
- **HECHO:** ELE-GATE, "Set de Herramientas 100 Piezas con Estuche" (HERM.36): **1–9 $490; 10–49 $470; 50–99 $450; 100+ $430**. Existencias: "Bodega: 100+", "U19: 18", "U14: 11", "Ejecentral32: 15". La descripción incluye **"Voltímetro para comprobación eléctrica"**, martillo, sierra, cinta métrica, desarmadores, pinzas y tornillería. [ELE-GATE HERM.36](https://www.ele-gate.com/producto/set-de-herramientas-100-piezas-con-estuche/)
- **HECHO:** ELE-GATE, "Kit de Herramientas con Estuche (53 Piezas)" (HERM.35): **1–9 $160; 10–49 $150; 50–99 $140; 100+ $130**. [ELE-GATE HERM.35](https://www.ele-gate.com/producto/kit-de-herramientas-con-estuche-53-piezas/)
- **HECHO:** ELE-GATE, "Kit de 7 Piezas … Reparaciones del Hogar" (HERM.20): **1–9 $70 → 100+ $50**, "Bodega: 500+". [ELE-GATE HERM.20](https://www.ele-gate.com/producto/kit-de-7-piezas-de-alta-calidad-herramientas-para-reparaciones-del-hogar/)
- **HECHO:** ELE-GATE, "Juego de Destornilladores 30 en 1 con Puntas Magnéticas": **1–2 $90; 3–4 $80; 5–9 $70; 10+ $60**. Quedan solo 17. [ELE-GATE destornilladores](https://www.ele-gate.com/producto/juego-de-destornilladores-32-en-1-herramientas-multifuncionales-con-puntas-magneticas/)
- **HECHO (referencias minoristas):** MayoreoTotal vende el "Maletín Herramientas Básicas Rosas 39 Piezas" a $790.76 y el "Kit Juego De Herramientas Dados" a $399. [MayoreoTotal maletín](https://www.mayoreototal.mx/products/maletin-herramientas-basicas-rosas)

### Inferences
- **ESTIMACIÓN de margen:** con el kit de 53 piezas, venta a $399 contra costo de $160 deja **≈$239 (60%)** antes de envío y anuncios. Con el kit de 100 piezas, venta a $849–$899 (rango de ML) contra $490 deja ≈$360–410, pero el envío pesa más. Con el juego 30 en 1, venta a $249 contra $90 deja ≈$159; conviene como complemento o regalo.
- **ESTIMACIÓN de saturación: alta.** Truper y Pretul dominan la confianza en ferretería, y hay importaciones baratas desde China ($540 por 100 piezas). Para diferenciar sirven el ángulo de regalo ("primer depa", Día del Padre, Navidad) y la entrega rápida en CDMX.
- **HIPÓTESIS (riesgo):** la calidad de las herramientas genéricas es incierta (puntas que se barren, martillo ligero). **El voltímetro del kit de 100 piezas es un componente eléctrico de calidad dudosa: hay que señalarlo y no promocionarlo como herramienta de seguridad.** Riesgo de devolución medio.
- **HIPÓTESIS (peso):** un kit de 100 piezas con estuche rígido suele pesar más de 2 kg (no verificado; ELE-GATE no publica peso), lo que sube el costo del envío. El de 53 piezas debería ser más ligero.

### Gaps
- Amazon (rango, reseñas, precio): **No disponible**.
- Google Trends "kit de herramientas": **No disponible** (probable estacionalidad en diciembre y junio; HIPÓTESIS).
- Peso de los kits ELE-GATE: no publicado.
- Facebook Marketplace: **No disponible, requiere verificación manual.** Ver los precios de kits genéricos frente a Truper en anuncios locales, la presencia de ferreterías anunciándose y si hay kits "de regalo" (rosa o femeninos) con buena respuesta.

---

## 6. Candidato 6 (con advertencia de electrónica): cepillo eléctrico giratorio inalámbrico para baño y azulejo (spin scrubber)

**Nombres y variantes:** "Cepillo eléctrico giratorio de limpieza inalámbrico 7/8/9 cabezales con mango telescópico", "Estropajo eléctrico para baño", "Cepillo giratorio azulejo".

### Takeaway
Hay un proveedor nacional sólido (ELE-GATE, costo de $192–$236, 1.1 kg, más de 100 unidades en bodega) y un dolor muy mexicano: sarro y moho en baños sin ventilación y juntas de azulejo. Pero la evidencia de demanda en ML es débil (pocos "vendidos" visibles) y, al ser un aparato con batería de origen incierto, el riesgo de calidad y devolución es mayor. **Es un producto electrónico de calidad incierta: hay que tomarlo con precaución.**

### Cited Findings
**Mercado Libre (resumen del buscador; verificar):**
- **HECHO:** cepillo Homtronics: etiqueta **MÁS VENDIDO**, **29 calificaciones**, **$833.12**. Otras publicaciones muestran solo 1–4 vendidos. Precios desde **$129** hasta más de **$2,000** antes de descuento, con muchos descuentos del 20–50% y muchas publicaciones "COMPRA INTERNACIONAL" desde China. Un modelo MASTHOME (tienda oficial) trae 8 cabezales, extensión y 60 min de uso. [Cepillo eléctrico giratorio de limpieza](https://listado.mercadolibre.com.mx/cepillo-electrico-giratorio-de-limpieza), [ML MLM2003586026](https://www.mercadolibre.com.mx/cepillo-de-limpieza-inalambrico-electrico-con-9-cabezales/p/MLM2003586026), [ML MLM-3494201808](https://articulo.mercadolibre.com.mx/MLM-3494201808-cepillo-de-limpieza-electrico-para-bano-estropajo-giratorio-_JM)

**Amazon México:** **No disponible** (sin búsqueda antes de agotarse el presupuesto).

**Proveedor nacional (verificado directo):**
- **HECHO:** ELE-GATE, "Cepillo Eléctrico Inalámbrico de Limpieza 25W con Mango Telescópico y 9 Cabezales" (HOG.WZYJ16): **1–9 $236; 10–49 $223; 50–99 $206; 100+ $192**. Existencias: "Bodega: 100+", "Ejecentral32: 29", "U14: 20". **Peso 1.100 kg; 42 × 14 × 7 cm**. [ELE-GATE HOG.WZYJ16](https://www.ele-gate.com/producto/cepillo-electrico-inalambrico-limpieza-25w-9-cabezales/)
- **HECHO:** ELE-GATE, "Cepillo Eléctrico Giratorio … 7 Cabezales" (HOG.321): **1–9 $235 → 100+ $190**, "Ecommerce: 100+". [ELE-GATE HOG.321](https://www.ele-gate.com/producto/cepillo-electrico-giratorio-de-limpieza-inalambrico-con-7-cabezales/)
- **HECHO (referencias minoristas):** MayoreoTotal vende el "Cepillo giratorio portátil" a $299 (tachado $499), el "Cepillo de limpieza eléctrico giratorio multifuncional 5 en 1" a $399 y el "CEPILLO GIRATORIO 360" a $699. [MayoreoTotal cepillo giratorio](https://www.mayoreototal.mx/products/cepillo-giratorio-portatil)

### Inferences
- **ESTIMACIÓN de margen:** venta a $549 contra costo de $236 deja **≈$313 (57%)** antes de envío. Paquete de 1.1 kg y 42 cm.
- **ESTIMACIÓN de saturación: media.** Hay muchas publicaciones, pero pocas con ventas visibles. Ninguna marca domina; Homtronics y MASTHOME aparecen.
- **HIPÓTESIS (ángulo México):** el sarro en canceles y azulejo (agua dura) y el moho en baños sin ventana son muy comunes en vivienda de interés social y departamentos de CDMX. Un video demostrativo (antes y después en juntas) encaja con Marketplace. Sin cita.
- **HIPÓTESIS (riesgos):** batería de litio con duración y garantía inciertas, cargador USB y posibles fallas de motor. La devolución y la garantía son más probables que en productos sin electrónica. Algunas paqueterías piden declarar la batería de litio. **Señal de alerta explícita según los criterios de exclusión.**

### Gaps
- Amazon: **No disponible**.
- Google Trends "cepillo eléctrico de limpieza": **No disponible**.
- Quejas específicas citadas: no capturadas.
- Política de garantía de ELE-GATE para electrónicos: no revisada en detalle.
- Facebook Marketplace: **No disponible, requiere verificación manual.**

---

## 7. Candidato 7: kit "baño seguro y sellado" con cinta antiderrapante para regadera o escalones y cinta selladora autoadhesiva para tarja o lavabo

**Nombres y variantes:** "Cinta antiderrapante transparente para regadera 5 m (Truper)", "Cinta antiderrapante para escalones 50 mm × 4.57 m", "Cinta selladora autoadhesiva para baño y cocina 3.2 m × 3.8 cm", "Tira de sellado para ducha 5 m × 2.2 cm".

### Takeaway
Las dos cintas son ligeras, irrompibles y resuelven dolores frecuentes (resbalones en la regadera; moho y filtración en la unión entre tarja y pared). Por separado su ticket es bajo ($56–$179), así que **solo funcionan como paquete** ($249–$349). La evidencia de demanda es moderada y no encontré mayorista con precio.

### Cited Findings
- **HECHO:** la cinta antiderrapante **transparente de Truper de 5 m** para tinas y regaderas aparece entre las más vendidas, a **$134–$179** según el vendedor. Para escalones hay cintas negras y amarillas de 4.57 m × 50 mm a **$119–$469** y rollos de 18–20 m. Una guía de ML indica que **no están pensadas para superficies sumergidas de forma constante**. [ML blog cintas antideslizantes](https://www.mercadolibre.com.mx/blog/mas-vendidos/cintas-antideslizantes), [Antiderrapante para regadera](https://listado.mercadolibre.com.mx/antiderrapante-para-regadera), [Cinta antiderrapante para escalones](https://listado.mercadolibre.com.mx/cinta-antiderrapante-para-escalones)
- **HECHO:** las cintas selladoras "para baño" en ML son en su mayoría de **PVC con adhesivo acrílico, no de silicón**. Medidas comunes: 300 cm × 2.2 cm, 5 m × 2.2 cm y 320 × 3.8 cm. Precios de **≈$56 a ≈$118**, con paquetes de varias piezas. [ML MLM2004174899](https://www.mercadolibre.com.mx/5-tira-de-sellado-para-bano-y-ducha-cinta-para-5m-x-22cm/p/MLM2004174899), [ML MLM-2975990370](https://articulo.mercadolibre.com.mx/MLM-2975990370-cinta-selladora-autoadhesiva-para-inodoro-2-rollos-_JM), [Cinta sellado impermeable](https://listado.mercadolibre.com.mx/cinta-sellado-impermeable)
- **HECHO (referencia minorista):** MayoreoTotal vende la "Cinta Adhesiva Selladora Impermeable" a **$399**. [MayoreoTotal](https://www.mayoreototal.mx/products/cinta-adhesiva-selladora-impermeable)
- Amazon MX: **No disponible** (sin búsqueda). "+X vendidos" en ML: no capturado.

### Inferences
- **ESTIMACIÓN:** un paquete de cinta antiderrapante transparente de 5 m + 2 rollos selladores a $299 es viable si el costo combinado ronda $100–150. Ese costo es una **suposición sin fuente mayorista**.
- **HIPÓTESIS (ángulo México):** baños sin ventilación y con humedad producen moho en la junta de silicón de la tarja o la regadera, y la cinta es un arreglo "sin albañil". Las personas mayores o con niños tienen el riesgo de resbalar en regaderas de loseta. Un hueco de producto: la cinta "de silicón real" anti-moho frente al PVC que domina.
- **HIPÓTESIS (riesgo):** las quejas probables son de adhesivo que se despega con humedad constante (la propia guía de ML lo advierte). Devolución baja por el precio, pero riesgo de calificaciones malas.

### Gaps
- Mayorista nacional (Truper vende por distribuidores; no hay precio público): **No disponible**.
- Amazon y Google Trends: **No disponible**.
- Facebook Marketplace: **No disponible, requiere verificación manual.**

---

## 8. Ideas rechazadas (o de baja prioridad) y por qué

### Takeaway
Rechacé los productos voluminosos con precio ya fijado por grandes tiendas (spin mop, mop plano con cubeta), los de calificación pobre (limpiador magnético), los de ticket bajo con un referente fuerte de ferretería (destapacaños) y los que dejan margen casi nulo frente a precios minoristas (escoba barredora mágica).

### Cited Findings
- **Trapeador giratorio 360 con cubeta (spin mop): RECHAZADO por volumen y precios fijados.** Demanda probada: Magic Mop 360 con **+1000 vendidos** a $475/$451.25 [ML MLM25662214](https://www.mercadolibre.com.mx/trapeador-giratorio-magic-mop-360-microfibra-con-cubeta-exprimidor/p/MLM25662214); Wehogar con **+1000 vendidos** [ML MLM50578146](https://www.mercadolibre.com.mx/trapeador-giratorio-de-microfibra-mop-con-exprimidor-cubeta-color-morado/p/MLM50578146); Cuher con **+500** [ML MLM26797528](https://www.mercadolibre.com.mx/trapeador-spin-mop-giratorio-360-con-exprimidor-de-acero-inoxidable-y-mango-extensible-1-mopa-de-repuesto/p/MLM26797528); OEM HT-9010 con **3.6/5 (78)** a $396 [ML MLM20942158](https://www.mercadolibre.com.mx/trapeador-magico-exprimidor-auto-spin-mop-gira-360-valde-e-color-rojo/p/MLM20942158). Precios minoristas: **Walmart MYRVA $449** [Walmart](https://www.walmart.com.mx/ip/trapeador-giratorio-myrva-cubeta-magic-mop-360-con-exprimidor-de-acero-y-mop-de-repuesto/00750303416207), **Sanborns Omi $419** [Sanborns](https://www.sanborns.com.mx/producto/872597/trapeador-giratorio-360-omi-con-cubeta-y-mopa). MayoreoTotal lo vende a $599 y declara **peso de 1.5 kg y volumen de 12 L** [MayoreoTotal](https://www.mayoreototal.mx/products/trapeador-giratorio-de-360). Hay reseñas de **cubetas de plástico que se rompen** [ML MLM-827818825](https://articulo.mercadolibre.com.mx/MLM-827818825-trapeador-mop-microfibra-360-cubeta-sistema-autolimpieza-_JM).
- **Mop plano con cubeta de exprimido (doble compartimento): RECHAZADO por volumen.** Betterware y Magiclean cuestan ≈$570–$760 [Cubeta con exprimidor](https://listado.mercadolibre.com.mx/cubeta-con-exprimidor-de-trapeador); en Amazon, O-Cedar EasyWring y Vileda Easy Wring dominan [Amazon trapeador doméstico](https://www.amazon.com.mx/trapeador-dom%C3%A9stico/s?k=trapeador+dom%C3%A9stico).
- **Limpiador magnético de ventanas: RECHAZADO por calificaciones bajas.** El más vendido (doble imán + 2 repuestos) tiene **+500 vendidos con 3.8/5 a $87.72**; Slim Company **+100 vendidos con 3.1/5**; Wimu **+50 con 3.6/5**. Muchos anuncios tienen 1–3 vendidos [Limpiador magnético para ventanas](https://listado.mercadolibre.com.mx/limpiador-magnetico-para-ventanas), [ML MLM2015788169](https://www.mercadolibre.com.mx/limpiador-magnetico-para-ventanas-mango-grande-doble-cara/p/MLM2015788169). Hay proveedor (ELE-GATE, paquete de 2 a **1–9 $80 → 100+ $50**) [ELE-GATE HOG.227](https://www.ele-gate.com/producto/pack-2-limpiador-magnetico-doble-cara-para-ventanas-cristal/), pero el precio ancla (<$100) deja el ticket fuera del rango y la calificación baja anticipa devoluciones. Alternativa sin imán: "Kit de limpieza de ventanas con poste de extensión", **$190 → $160** [ELE-GATE HOG.184](https://www.ele-gate.com/producto/kit-de-herramientas-de-limpieza-de-ventanas-con-poste-de-extension/).
- **Destapacaños flexible / serpiente: RECHAZADO por ticket bajo y referente de ferretería.** El Truper de 25 pies cuesta **$127.49** (27 calificaciones) y el Pretul ≈$260. Un "plumbing snake" de 7 m tiene +100 vendidos y un Slim Company de 2 m +25 [Serpiente para destapar drenajes](https://listado.mercadolibre.com.mx/serpiente-para-destapar-drenajes), [Destapacaños 25 pies](https://listado.mercadolibre.com.mx/destapaca%C3%B1os-25-pies). Solo serviría como complemento en un paquete.
- **Rodillo quitapelusa reutilizable (solo): RECHAZADO como producto individual** porque el precio ancla es de $35–$111 con +1000 vendidos (ver sección 3). Se conserva como componente del kit anti-pelo.
- **Escoba barredora mágica manual: RECHAZADA por margen.** Ocupa el #2 en Más vendidos de Escobas en ML (sección 3), pero el costo de dropship en ELE-GATE ($170 por 1–9 pzas) es **igual o mayor** que el precio al público de MayoreoTotal ($169) [ELE-GATE HOG.03](https://www.ele-gate.com/producto/escoba-barredora-magica-aspiradora-manual-recogedor-basura/), [MayoreoTotal](https://www.mayoreototal.mx/products/escoba-magica).
- **Excluidos por los criterios:** químicos (p. ej. la caja de Drano Plus de 12 piezas en MayoreoTotal [MayoreoTotal Drano](https://www.mayoreototal.mx/products/caja-destapacanos-drano-plus-de-946-ml-con-12-piezas-sc-johnson)); quitapelusas eléctrico, aspiradoras e hidrolavadoras (electrónica, voluminosos); robots de barrido.

### Inferences
- **HIPÓTESIS:** el spin mop podría funcionar solo con proveedor local en CDMX y entrega en mano (sin paquetería nacional). Con dropshipping nacional, el volumen de 12 L lo vuelve inviable frente a $419–$449 en Walmart y Sanborns.

### Gaps
- Costo de envío por peso volumétrico del spin mop: no cotizado.

---

## 9. Semillas no evaluadas y proveedores generales (contexto)

### Takeaway
Varias semillas quedaron **sin evaluar** porque se agotó el presupuesto de búsqueda: bolsas de malla para lavadora, organizador de productos de limpieza, juego de puntas y brocas, cepillo para juntas o azulejo, paños de microfibra industriales, kit para colgar cuadros sin taladro y malla mosquitero magnética. Sobre plataformas de dropshipping nacionales: Dropi MX existe, pero su catálogo requiere registro; ELE-GATE es el único con precios públicos verificados.

### Cited Findings
- **HECHO:** Dropi México se presenta como plataforma que "te conecta con proveedores locales verificados y centraliza la logística con transportadoras". Para proveedores dice "Expón tus productos a más de 200 mil vendedores". El catálogo y los precios **requieren registro**. [Dropi MX](https://www.dropi.mx/) (redirige a dropi.co/mx)
- **HECHO (conflicto de fuentes):** Tiendanube describe una comisión fija del 5% en Dropi MX [Tiendanube](https://www.tiendanube.com/blog/dropshipping-nacional-con-dropi-mx/), mientras Andrey Business habla de una "comisión promedio del proveedor 15–30%" [Andrey Business](https://www.andreybusiness.com/blog/proveedores-dropshipping-mexico-directorio-operador-2026). Son incompatibles; verificar en la plataforma.
- **HECHO:** MayoreoTotal anuncia "más de 12,000 productos", con entrega en CDMX, Valle de México y Toluca y pago contra entrega. Sus precios publicados son de menudeo; solo mejora precio en compras de más de $50,000. [MayoreoTotal](https://www.mayoreototal.mx/), [Compra por mayoreo](https://www.mayoreototal.mx/pages/compra-por-mayoreo)
- **HECHO:** MayoreoTotal también vende "Mosquitero magnético" a $291 y "Toallas de microfibra Member's Mark 36 pzas" a $569 (menudeo). [MayoreoTotal mosquitero](https://www.mayoreototal.mx/products/mosquitero-magnetico), [MayoreoTotal microfibra](https://www.mayoreototal.mx/products/toallas-de-microfibra-members-mark-36-pzas-zk)
- **HECHO:** ELE-GATE tiene un "Cepillo Multiusos de Mango Largo 102 cm con Cabezal de Microfibra" a **$170 → $140**, con "Bodega: 500+" y medidas de 17×7.5×5.5 cm. [ELE-GATE HOG.184.5](https://www.ele-gate.com/producto/cepillo-multiusos-mango-largo-102-cm-microfibra/)
- **HECHO:** GLEZ Productos de Limpieza (jarciería mayoreo y menudeo, envío gratis desde $799) maneja sobre todo jarciería tradicional (lazos, mechudos, escobas de fibra, limpiavidrios por caja de 24–36). No tiene los productos "novedad" de este informe. [GLEZ](https://www.glez.mx/)
- **HECHO:** Nacional de Aseo (Puebla, desde 1994) cotiza por caja, docena o volumen. Ejemplo: cubeta Toscana de 15 L con exprimidor "desde $45.26 c/u + IVA"; también distribuye herramientas Truper. [Nacional de Aseo](https://nacionaldeaseo.com/)

### Inferences
- **HIPÓTESIS:** para tendedero retráctil, escoba de goma y spray mop, el siguiente paso es registrarse en Dropi MX o cotizar con importadores del Centro de CDMX, porque no hay precios públicos.

### Gaps
- Bolsas de malla para lavadora, organizador de limpieza, puntas y brocas, cepillo de juntas, microfibra industrial y kit para colgar cuadros sin taladro: **no evaluados** (presupuesto de búsqueda agotado). Quedan pendientes.

---

## 10. Tabla resumen y principales recomendaciones

### Takeaway
Las mejores combinaciones de demanda, abasto y margen son **(1) la regadera de alta presión con filtro**, **(2) el tendedero retráctil de pared** (con tarea pendiente de proveedor) y **(3) el kit de herramientas de 53 piezas con juego de destornilladores** (proveedor sólido, demanda moderada).

### Cited Findings
- Todas las cifras de la tabla vienen de las secciones 1–8, con sus URLs y la fecha de consulta 2026-10-22.

### Inferences
**Tabla resumen** (señales preliminares; "ML" = Mercado Libre; vendidos = acumulado; Trends = No disponible en todos por HTTP 429)

| # | Producto | Rango de precio en ML (MXN) | Evidencia ML | Evidencia Amazon MX | Trends | Proveedor y costo | Peso / fragilidad | Demanda | Crecimiento | Brecha competitiva | Margen | Facilidad de abasto |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Regadera alta presión con filtro | $395–$619 (básicas $72–80) | MÁS VENDIDO 4.6/390; 4.8/291; +100 vendidos a $619 | DOBEVI 4.3/895; VMASSTONE 4.4/159; queja "no aumentó presión" | No disp. | ELE-GATE $110 (1–9) → $85 (100+); existencias en CDMX; envío al cliente | 0.5 kg / baja | Alta | Media (sin dato) | Media | Alta (≈68% bruto) | Alta |
| 2 | Tendedero retráctil de pared | ≈$170–$1,000+ | 4.5/636; 4.8/237; #3 y #7 en Tendederos | 200+ y 50+ comprados el mes pasado; #4 y #10 en Tendederos | No disp. | **Sin mayorista con precio público**; menudeo MayoreoTotal $269–399; Home Depot $149 | ≈0.5–1.5 kg (no verif.) / baja | Alta | Media (estacional, HIPÓTESIS) | Media (cable débil, "sin perforación") | Media (sin dato) | Baja-media |
| 3 | Escoba de goma + kit anti-pelo | $187–$290 escoba; kit ≈$299 | MÁS VENDIDO 4.6/51; +100 vendidos; Escoba Pro 2en1 1° en Escobas 4.7/240 | 1,345 / 1,669 / 2,103 / 1,172 reseñas (4.2–4.5) | No disp. | Escoba: **No disp.**; guante ELE-GATE $25 | ≈0.6–1 kg, largo / baja | Alta | Media | Baja (Betterware, Practiclean) | Media | Baja |
| 4 | Trapeador con atomizador (spray mop) | $300–$550 (Betterware $600–660) | +1000 vendidos (2 publicaciones); MÁS VENDIDO 4.7/29 | VIOPY #4 subcat. 4.2/121; 4.3/261 con 100+ el mes pasado | No disp. | **No disp.** (MayoreoTotal $807 menudeo) | ≈1–1.5 kg, largo / baja | Alta | Media | Baja | Media | Baja |
| 5 | Kit de herramientas 53–100 pzas + destornilladores 30 en 1 | $540–$888 (100 pzas) | "Más vendido" 4.2/49 y 4.8/236 | No disp. | No disp. | ELE-GATE 53 pzas $160→$130; 100 pzas $490→$430; 30en1 $90→$60; bodega 100–500+ | 53 pzas ligero; 100 pzas >2 kg (HIPÓTESIS) / baja | Media | Media (regalo, HIPÓTESIS) | Baja-media | Alta (53 pzas ≈60%) | Alta |
| 6 | Cepillo eléctrico giratorio (**alerta electrónica**) | $129–$833+ | MÁS VENDIDO 29 calif.; pocos vendidos visibles | No disp. | No disp. | ELE-GATE $236→$192; 1.1 kg; bodega 100+ | 1.1 kg, 42 cm / media (batería) | Media-baja | Media | Media | Alta (≈57%) | Alta |
| 7 | Kit baño seguro (antiderrapante + selladora) | $56–$179 por cinta; kit ≈$249–349 | Truper transparente "entre más vendidas" | No disp. | No disp. | **No disp.** | <0.3 kg (HIPÓTESIS) / nula | Media | Media | Media (hueco: silicón real) | Media (sin dato) | Baja-media |

**Principales recomendaciones (ESTIMACIÓN e HIPÓTESIS):**
1. **Regadera de alta presión con filtro.** Es el único candidato con todos los eslabones verificados: demanda en ML (varias "MÁS VENDIDO" con 290–390 calificaciones) y en Amazon (895 reseñas), proveedor nacional con existencias en CDMX, precio escalonado ($85–110) y envío directo al cliente en 48 h, 0.5 kg, sin fragilidad. Encaja con dolores locales (tinaco, sarro; HIPÓTESIS). El riesgo principal es la promesa de "más presión": hay que comunicar bien y añadir cinta teflón y filtro extra para subir el ticket a $349–$449.
2. **Tendedero retráctil de pared.** Tiene la señal de demanda más robusta y reciente (636 opiniones en ML; "200+ comprados el mes pasado" en Amazon) y un ángulo urbano claro (departamentos, azotea, lluvias; HIPÓTESIS). La diferenciación posible está en cable de acero frente a cordón, que es la queja documentada, y en la versión "sin perforación". **Condición:** conseguir cotización mayorista (Dropi MX o importador del Centro de CDMX) con costo de $150 o menos para sostener $399–$449.
3. **Kit de herramientas de 53 piezas con juego de destornilladores 30 en 1 (paquete regalo $399–$449).** Tiene el abasto más sólido (cientos de unidades, CDMX, cuatro niveles de precio) y un margen bruto aproximado del 60%. La demanda está probada en ML pero la competencia es alta. Evitar o advertir el kit de 100 piezas por el voltímetro y el peso.
- Alternativa si se consigue proveedor: **kit anti-pelo de mascota** (escoba de goma + rodillo reutilizable + guante). La demanda en Amazon es la más grande del grupo (más de 1,000 reseñas en varias publicaciones), pero no hay costo mayorista verificado.

### Gaps
- Las señales de "crecimiento" son débiles en todos los candidatos porque Google Trends no estuvo disponible y no hubo acceso a Movers & Shakers. Las únicas señales recientes son las insignias mensuales de Amazon ("X+ comprados el mes pasado").
- Facebook Marketplace: **No disponible para ningún candidato, requiere verificación manual.** Hay que revisar, con sesión iniciada y en un radio de CDMX y Edomex: número de anuncios activos por término, rango de precios, proporción de vendedores con envío frente a entrega en punto, anuncios de catálogo (Betterware, etc.) y anuncios duplicados de revendedores. También confirmar que ninguna publicación choque con las Políticas de Comercio de Facebook. HIPÓTESIS: estos productos no son de categorías prohibidas, pero el cepillo con batería y el kit con voltímetro conviene revisarlos.
