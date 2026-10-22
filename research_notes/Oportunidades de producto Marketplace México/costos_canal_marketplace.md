# Costos unitarios y reglas de canal: Facebook Marketplace + Messenger/WhatsApp + links de pago + dropshipping (México, oct-2026)

Fecha de consulta de todas las fuentes: **2026-10-22** (salvo que se indique otra cosa). Las fuentes publicadas antes del 2025-10-22 se marcan **[>12 meses]**. Etiquetas: **HECHO** (verificado y citado), **HECHO-secundario** (cifra citada por un tercero, no por el proveedor), **ANECDÓTICO** (blog, agencia o vendedor con posible conflicto de interés), **ESTIMACIÓN** (cálculo con insumos explícitos), **HIPÓTESIS** (supuesto sin fuente, para modelar). "No disponible" = no se encontró una cifra pública verificable.

Nota de método: varias páginas oficiales (Mercado Pago "costos", Openpay, centro de ayuda de Facebook) devolvieron 403/404 o no se pudieron leer con la herramienta de extracción. Cuando eso pasó, se usó la página oficial de producto o una fuente secundaria, y se marca así.

## 1. Costos de cobro en México (links de pago, pasarelas, SPEI, CoDi/DiMo, OXXO, MSI)

### Takeaway
Para un ticket de $250–$900 MXN, cobrar con link de pago o tarjeta cuesta en la práctica entre **~4.2% y ~6.4% del ticket ya con IVA** (Clip ~4.18% plano; Mercado Pago 3.49% + $4 + IVA ≈ 5.2% a $399 y 4.8% a $599; PayPal 3.95% + $4 + IVA ≈ 5.7% a $399). Todas las comisiones publicadas son **más IVA**. Los MSI suman entre +3.5% y +27% más IVA y no conviene ofrecerlos en este rango de precio. El efectivo en mano o el SPEI directo a la cuenta del vendedor no tienen comisión de procesador. Las tarifas exactas por banco para personas no quedaron verificadas.

### Cited Findings
**Mercado Pago (link de pago), HECHO, página oficial de producto:**
- Tarjeta de crédito, débito, saldo MP y transferencias SPEI: **3.49% al instante, 3.19% a 7 días, 2.95% a 30 días**. "A las comisiones se suma una tasa fija de $ 4.00 + IVA por venta." — [Mercado Pago, Link de pago](https://www.mercadopago.com.mx/herramientas-para-vender/link-de-pago) (consulta 2026-10-22)
- OXXO, transferencia y efectivo: la misma página da **dos tarifas que se contradicen**. La sección de precios dice "En hasta 3 días 3.49%" y la de preguntas frecuentes dice "3 días: 3.79% + $4.00" para depósitos en efectivo en OXXO, otras tiendas y bancos. — [Mercado Pago, Link de pago](https://www.mercadopago.com.mx/herramientas-para-vender/link-de-pago)
- MSI (sobretasa que se suma a la comisión base, todas + IVA): 3 MSI 4.69%; 6 MSI 7.69%; 9 MSI 11.19%; 12 MSI 12.89%; 18 MSI 19.39%; 24 MSI 27.29%. — [Mercado Pago, Link de pago](https://www.mercadopago.com.mx/herramientas-para-vender/link-de-pago)
- Algunas ventas, sobre todo de vendedores recién registrados, se liberan a 7 días y no al instante. — [Mercado Pago, Link de pago](https://www.mercadopago.com.mx/herramientas-para-vender/link-de-pago)
- IVA: la página oficial solo pone "+ IVA" explícitamente en la tasa fija. Un simulador de terceros aplica IVA del 16% sobre toda la comisión (porcentaje y fija), y en un cobro de $1,500 al instante calcula una comisión efectiva de 4.36%. HECHO-secundario. — [Atémpora, Comisiones Mercado Pago 2026](https://atempora.studio/blog/comisiones-mercado-pago-2026)
- La página oficial de "costo de recibir pagos" (mercadopago.com.mx/ayuda/costo-recibir-pagos-dinero_220) devolvió HTTP 403 y no se pudo verificar.

**Clip:**
- Comisión base **3.6% + IVA** por transacción, sin cuota fija; igual para crédito y débito. Fondos disponibles 24 h después del cobro; las ventas posteriores a las 20:00 se depositan al día siguiente. Sobretasa MSI (montos mayores a $300): 4.57% + IVA a 3 meses y hasta 27.17% + IVA a 24 meses. El artículo se contradice sobre el máximo (en otra sección dice 35.7% + IVA). La fuente no especifica tarifa distinta para el **link de pago**. — [Tiendanube, Comisiones de Clip 2026, act. 14/07/2026](https://www.tiendanube.com/mx/blog/clip)
- La ficha de la app de Clip en App Store indica "3.6% + IVA". HECHO-secundario (vía extracto de búsqueda). — [App Store, Clip](https://apps.apple.com/mx/app/clip/id771245360)
- clip.mx/precios devolvió 404, así que no se verificó la tarifa del link de pago directamente con Clip.

**Stripe México, HECHO (página oficial):**
- Tarjetas nacionales **3.6% + MXN 3.00** por transacción exitosa; tarjetas internacionales +0.5%; conversión de moneda +2%. "Todas las comisiones excluyen el IVA." — [Stripe MX, Precios](https://stripe.com/mx/pricing)
- Débitos bancarios, transferencias y otros métodos locales: 4% + MXN 3.00. SPEI no aparece nombrado y OXXO no aparece en la página principal. Meses sin intereses desde 5% a 3 meses. Payment Links sin costo adicional. **Disputa (contracargo): MXN 150.00**. Las comisiones originales no se devuelven en un reembolso. — [Stripe MX, Precios](https://stripe.com/mx/pricing)

**Conekta, HECHO (página oficial, plan PyMEs, todas + IVA):**
- Tarjeta **3.4% + $3.00**; Conekta Efectivo (OXXO y otros comercios) **2.6% + $3.00**, con comisión mínima de $5.40. Además, el cliente paga **$10–$13 MXN con IVA** en el comercio (sin cargo en Practicajas BBVA). SPEI **$12.50** por transacción. 3DS $1.50 + IVA. MSI por banco, por ejemplo "otros bancos" 3 MSI 3.5% y 12 MSI 12.0%. BNPL: Aplazo 4% + IVA. No publica una comisión específica para el link de pago. — [Conekta, Pricing](https://www.conekta.com/pricing)
- Monto mínimo por cobro $30 MXN; tope de pagos en OXXO $12,000 MXN. Los pagos con tarjeta se notifican al instante y los de OXXO/SPEI quedan pendientes hasta que se pagan. — [Tiendanube Ayuda, Conekta FAQ](https://ayuda.tiendanube.com/es_MX/conekta/preguntas-frecuentes-sobre-el-metodo-de-pago-conekta)

**PayPal México, HECHO (página oficial, "Última actualización: 13 de octubre de 2026"):**
- Tarifa estándar nacional **3.95% + $4.00 MXN**; tarifas comerciales por volumen desde 3.65% (ventas de $50,000–$249,999 MXN al mes) hasta 2.95% (más de $1 millón), con la misma tasa fija. "Todos los importes y porcentajes ... están sujetos a IVA." Pagos desde el extranjero +0.50%. — [PayPal MX, Comisiones](https://www.paypal.com/mx/webapps/mpp/merchant-fees)

**Openpay:** No disponible. openpay.mx/precios y openpay.mx/comisiones no mostraron contenido legible. Un directorio de terceros sin fecha cita "2.9% + $2.50 tarjetas y OXXO; $8 SPEI", pero no es confiable y se contradice con otras referencias. — [skills.sh, mexico-market (no confiable)](https://skills.sh/ivanovishado/agent-skills/mexico-market)

**SPEI, CoDi, DiMo:**
- SPEI es el sistema de Banxico para transferencias interbancarias inmediatas (creado en 2004) y CoDi (2019, QR) y DiMo (número celular) son sus iteraciones. Una nota de 2023 los describe como medios "seguros y gratuitos", y la adhesión de bancos a DiMo es voluntaria. **[>12 meses]** — [Expansión, 08/08/2023](https://expansion.mx/economia/2023/08/08/spei-codi-dimo-diferencias-banxico); [Veritas, SPEI-CoDi-DiMo](https://www.veritas.org.mx/Economia-y-finanzas/Fintech/SPEI-CoDi-DiMo-y-la-evolucion-de-los-pagos-digitales-en-Mexico)
- No se encontró una fuente vigente que confirme comisión $0 por SPEI en todos los bancos para cuentas de persona física. **No disponible** como dato universal.

**Depósito en efectivo en OXXO a cuenta bancaria del vendedor (alternativa "manual" a un link):**
- Cifras inconsistentes: $15 MXN por depósito a la mayoría de bancos y $12 a Spin by OXXO (blog 2026) frente a $10 (Rankia, sin fecha clara). HECHO-secundario y contradictorio. — [ARQ Finance](https://www.arqfinance.com/es-CO/blog/your-money/cuanto-cobra-oxxo-por-deposito); [Rankia](https://www.rankia.mx/blog/mejores-opiniones-mexico/3385957-depositos-oxxo-como-funcionan)

### Inferences
- **ESTIMACIÓN: comisión efectiva con IVA sobre toda la comisión** (fórmula: (tasa·P + fija)·1.16):

| Procesador | P=$250 | P=$399 | P=$599 | P=$900 |
|---|---|---|---|---|
| Mercado Pago link, al instante (3.49% + $4) | $14.76 (5.90%) | $20.79 (5.21%) | $28.89 (4.82%) | $41.08 (4.56%) |
| Mercado Pago, a 30 días (2.95% + $4) | $13.19 | $18.29 | $25.14 | $35.44 |
| Clip (3.6%, sin fija) | $10.44 (4.18%) | $16.66 (4.18%) | $25.01 (4.18%) | $37.58 (4.18%) |
| Stripe (3.6% + $3) | $13.92 (5.57%) | $20.14 (5.05%) | $28.49 (4.76%) | $41.06 (4.56%) |
| Conekta tarjeta (3.4% + $3) | $13.34 | $19.22 | $27.10 | $38.98 |
| Conekta efectivo/OXXO (2.6% + $3) | $11.02 | $15.51 | $21.55 | $30.62 |
| Conekta SPEI ($12.50) | $14.50 | $14.50 | $14.50 | $14.50 |
| PayPal estándar (3.95% + $4) | $16.09 (6.44%) | $22.92 (5.74%) | $32.09 (5.36%) | $45.88 (5.10%) |

- ESTIMACIÓN: por la tasa fija, en tickets bajos ($250–$399) Clip (sin fija) sale más barato que Mercado Pago o Stripe. En $900 se emparejan.
- HIPÓTESIS: el IVA de la comisión es acreditable solo si el vendedor está inscrito y recibe CFDI del procesador. Para un vendedor informal, el IVA es costo puro, y por eso se modela incluido.
- HIPÓTESIS: no ofrecer MSI en $250–$900. Con 3 MSI la comisión total llega a ~8–10% + IVA y destruye el margen.

### Gaps
- Tarifa oficial vigente del **link de pago de Clip** (clip.mx/precios: 404) y tabla oficial de Mercado Pago "costo de recibir pagos" (403).
- **Openpay**: sin tarifa pública legible.
- Comisión de **OXXO Pay vía Stripe**: no aparece en la página principal de precios.
- Confirmación de **SPEI/DiMo gratis por banco** para personas físicas en 2026.
- Si Mercado Pago cobra IVA sobre el porcentaje (la página oficial solo lo dice explícito para la tasa fija).

## 2. Costos de envío (local CDMX/Edomex y nacional), peso volumétrico y contra entrega

### Takeaway
Referencias públicas 2026 para **~1 kg nacional**: **~$96–$123 MXN** vía agregadores (Envia.com $95.99 en una ruta CDMX→Guanajuato; EnviaYa "desde" $103–$123 IVA incluido), **~$56–$161** vía Correos/Mexpost y **~$330–$420** vía FedEx/DHL al mostrador. Para **3 kg**, una calculadora de terceros da de $151 (Correos) a $423 (DHL). **Local mismo día CDMX/Edomex**: 99minutos "desde" ~$84 IVA incluido (ejemplo ilustrativo de $110 para 1.5 kg). El divisor volumétrico más citado es **5,000** (Mexpost usa 6,000). COD: 99minutos (Cash99) cobra **4% del valor declarado**; las demás paqueterías lo ofrecen por contrato, sin tarifa pública.

### Cited Findings
**Nacional (ejemplos con fecha y ruta):**
- Paquete de 1 kg, 35×21×13 cm, de CP 03810 (CDMX) a CP 37770 (San Miguel de Allende), agosto 2026: **Envia.com $95.99** (mejor resultado; transportista no nombrado); **Mexpost Estándar $161.07** IVA incluido (peso volumétrico 1.592 kg); **FedEx Nacional Económico $331.52**; FedEx Día Siguiente $394.13; **DHL $395.67** en tienda, $417.67 con recolección. Correos de México Paquetería Tradicional hasta 1 kg: **$56**. — [Tiendanube, Paquetería más barata, act. 21/08/2026](https://www.tiendanube.com/blog/cual-es-la-paqueteria-mas-barata-en-mexico/)
- EnviaYa (agregador), tarifas de ejemplo "para envíos de peso a un kilo o de tamaño estándar", IVA incluido: Económico Nacional desde **$103.22–$108**; Día Siguiente desde **$149–$158.41**; CDMX–Monterrey **$122.55**; CDMX–Guadalajara **$122.75**. Página sin fecha. — [EnviaYa, Precios](https://enviaya.com.mx/es/paqueterias/precios/)
- 3 kg (calculadora de terceros, versión v2026.1, abril 2026; dice basarse en "Tarifas públicas paqueterías México · IFT"; estimados): Correos de México **$151**; Paquetexpress **$223**; Redpack **$255**; Estafeta **$287**; FedEx **$400**; DHL Express **$423**. ESTIMACIÓN de terceros. — [CalculoSeguro, Calculadora costo de envío](https://calculoseguro.mx/calculadora-costo-envio-paquete)
- Dypaq: **$74.00 + IVA** hasta 1 kg, medidas máximas aprox. 20×20×15 cm (promoción, sin fecha). — [Dypaq](https://www.dypaq.com/promociones/nueva-tarifa-para-envios-1kg/)
- Estimaciones no verificadas para 1 kg: Mexpost $75–$90, Estafeta $145–$165. ANECDÓTICO. — [Cargomart 2026](https://cargomart.com.mx/envio-nacional-definicion-tiempos-costos/)
- **0.5 kg: No disponible**. Ninguna fuente pública dio tarifa específica para medio kilo.
- Estafeta publica un recargo por combustible entre el día 5 y el 10 de cada mes (aplica a guía y sobrepeso) y una reexpedición de $131.40. Fuente: espejo QA del sitio, posiblemente desactualizado. — [Estafeta (wwwqa)](https://wwwqa.estafeta.com/nacional)

**Local / mismo día CDMX-Edomex:**
- 99minutos (precios "desde", IVA incluido según la fuente): Same Day **~$83.90** (CDMX y Edomex; corte 13:30–14:00); Next Day **~$83.90**; Express (99 min, solo CDMX y zona metropolitana, tamaños XS/S/M) **~$96.80**; Nacional Sprint **~$89**. La fuente advierte que los costos reales pueden ser 50–200% mayores. Ejemplos ilustrativos: CDMX Express $145; CDMX Same Day $110 (1.5 kg); CDMX Sprint $95; Guadalajara Sprint $125; Sprint rural $165. Máximo 20 kg y 70 cm por lado. — [Cubbo, 99minutos pricing México 2026 (16-feb-2026)](https://www.cubbo.com/en/posts/99minutos-pricing-mexico-2026)
- Rango de $50–$150 MXN para mismo día o día siguiente en zonas metropolitanas. ANECDÓTICO (blog de dropshipping, verificado 21/05/2026). — [Andrey Business, 99minutos vs FedEx](https://www.andreybusiness.com/argentina/blog/99minutos-vs-fedex-mexico-dropshipping-2026)
- **DiDi Entrega Light**: precio mínimo **$29** en CDMX, distancia máxima 10 km, horario 9:00–19:00, valor máximo del objeto $2,000, en mochila de repartidor en moto o bici. Fuente sin fecha clara, probablemente **[>12 meses]**. — [Xataka México, DiDi Entrega Light](https://www.xataka.com.mx/automovil/entrega-light-nuevo-servicio-didi-mexico-barato-app-realizan-repartidores-didi-food-moto-bicicleta)
- **Uber Flash Ahorro** (variante más barata de Flash/Flash Moto, con espera mayor, para objetos que caben en mochila): la fuente no da montos. — [Xataka México, Uber Flash Ahorro](https://www.xataka.com.mx/aplicaciones/uber-te-puede-cobrar-enviarte-paquete-ciudad-mexico-condicion-ellos-deciden-cuando-pasar)
- **Lalamove, Rappi Favor, Uber Flash por 10 km**: **No disponible**. No hay tarifa pública por km para CDMX; solo se obtiene cotizando en cada app.

**Peso volumétrico:**
- Fórmula "(Largo × Ancho × Alto) ÷ 5000" (cm), usada como estándar para Estafeta, Paquetexpress y 99minutos. — [Base.com blog, 18/09/2026](https://base.com/es-MX/blog/?p=18541)
- Mexpost: "largo × ancho × alto ÷ 6000". — [Tiendanube, act. 21/08/2026](https://www.tiendanube.com/blog/cual-es-la-paqueteria-mas-barata-en-mexico/)
- Se cobra el mayor entre peso real y volumétrico; divisor 5,000 en CalculoSeguro. — [CalculoSeguro](https://calculoseguro.mx/calculadora-costo-envio-paquete)

**Contra entrega (COD):**
- 99minutos **Cash99**: disponible; comisión **4% del valor declarado**; liquidación en menos de 7 días hábiles. Seguro opcional del 4% del valor; sin seguro, la responsabilidad se limita a $2,500. Cancelación después de 5 minutos: $40 + IVA. — [Cubbo, 99minutos pricing 2026](https://www.cubbo.com/en/posts/99minutos-pricing-mexico-2026)
- En Estafeta, FedEx, DHL, Paquetexpress y J&T, el COD es un servicio **corporativo negociado por contrato** y no de mostrador. En J&T, cada paquete rechazado regresa con costo para el comerciante. ANECDÓTICO: la fuente es un proveedor de COD que promociona su servicio. — [Fufills, Paqueterías COD México](https://fufills.com/en/blog/3pl-fulfillment/paqueterias-pago-contra-entrega-mexico); [Fufills, J&T COD](https://fufills.com/en/blog/3pl-fulfillment/jt-express-mexico-pago-contra-entrega)
- Dropi (plataforma de dropshipping COD): comisión por pedido de **2–5% según país**; liquidación a la wallet 2–7 días hábiles después de la entrega. ANECDÓTICO (blog con enlace de afiliado, abr/may 2026). — [Andrey Business, Dropi devoluciones](https://www.andreybusiness.com/mexico/blog/dropi-contra-entrega-cobran-por-devoluciones-verdad)

### Inferences
- ESTIMACIÓN: con el divisor 5,000, una caja de 35×21×13 cm pesa 1.91 kg volumétricos, así que **se cobra como 2 kg aunque el producto pese 0.5 kg**. Para productos ligeros, la caja manda más que el peso.
- HIPÓTESIS: la tarifa de 0.5 kg en agregadores suele igualar la de 1 kg (peso mínimo cobrable). Para modelar, usar 0.5 kg = tarifa de 1 kg hasta tener una cotización.
- ESTIMACIÓN de rangos para modelar (1 kg nacional, pagado por el vendedor): bajo **$96** (Envia.com), base **$123** (EnviaYa CDMX–GDL), conservador **$161** (Mexpost estándar). Local CDMX/Edomex mismo día: bajo **$84**, base **$110**, conservador **$145** (99minutos).
- HIPÓTESIS: en un pedido rechazado bajo COD, el vendedor paga ida y regreso. Modelado como 0× (bajo), 0.5× (base) y 1.0× (conservador) el flete de ida.

### Gaps
- Tarifas oficiales publicadas por Skydropx, J&T Express México, Pakke, Redpack y Paquetexpress para 0.5/1/3 kg: todas requieren cotizador o cuenta. **No disponible**.
- Costo real de Uber Flash, DiDi Entrega, Lalamove y Rappi Favor para ~10 km en CDMX. **No disponible**.
- Comisión COD y cargo por devolución de Estafeta, J&T, Paquetexpress y DHL. **No disponible** (solo por contrato).
- Costo de devolución (flete de regreso) en 99minutos Cash99: no especificado en la fuente.

## 3. Publicidad pagada (Meta Ads) en México/LatAm: CPM, CPC, CTR, costo por conversación y cierre

### Takeaway
La única cifra específica de México encontrada es un **CPM mediano de Facebook para ecommerce de US$3.92** (Lebesgue, julio 2026). No existe benchmark público independiente de **costo por conversación** de Click-to-WhatsApp/Messenger en México, ni de tasa de cierre de conversación a venta. Esos insumos deben salir de pruebas propias y el modelo los trata como variables. Marketplace sí es una ubicación de anuncios de Meta.

### Cited Findings
- Facebook CPM, mediana ecommerce, en USD: **México $3.92** (índice 24 frente a EE. UU. = $16.08), Brasil $2.63, Colombia $2.00. Fuente original: Lebesgue (benchmark de 52 mercados), publicado el 27-jul-2026. No publica ventana de datos ni tamaño de muestra, y advierte que el orden entre mercados es más confiable que los valores absolutos. La misma página no trae CPC, CTR ni costo por mensaje para México o LatAm. — [Pace Ads, Meta Ads statistics 2026](https://paceads.com/research/meta-ads-statistics-2026)
- Benchmarks globales, no de México: DTC ecommerce, mediana de 15 marcas (jul-2025 a jun-2026): CPM $13.52, CPC $0.57, **CTR 2.68%**, ROAS 2.96, costo por compra $49.04. HECHO-secundario, muestra pequeña. — [TopGrowth Marketing, Meta Ads benchmarks](https://topgrowthmarketing.com/dtc-ecommerce-benchmarks/meta-ads-benchmarks/)
- "No existe un benchmark público independiente para anuncios Click-to-WhatsApp"; se recomienda comparar contra cuartiles de las propias campañas. — [Getkanal, CTWA benchmarks 2026](https://getkanal.com/blog/click-to-whatsapp-ads-benchmarks-2026)
- **WhatsApp Business Platform (API), HECHO oficial:** cobro **por mensaje** desde el 1-jul-2025, por categoría y país, por cada mensaje empresa→usuario entregado; los mensajes usuario→empresa no se cobran. Los anuncios Click-to-WhatsApp abren una **ventana gratuita (FEP) de hasta 7 días** (solo Android/iOS) en la que los mensajes son gratis. Ventana de atención de 24 h. Desde el **1-oct-2026**, Meta cobra los mensajes de servicio a partir del mensaje 1,001 del mes (los primeros 1,000 por número son gratis). **La tarifa de marketing para México sube desde el 1-oct-2026** (monto no mostrado en la página). — [Meta for Developers, WhatsApp pricing](https://developers.facebook.com/docs/whatsapp/pricing)
- Tarifas WhatsApp API en México (verificadas en ago-2026 por un proveedor): marketing **US$0.0305/mensaje**, utilidad US$0.0085/mensaje (gratis dentro de la ventana de 24 h). Pueden estar desactualizadas tras el aumento del 1-oct-2026. — [LeadSales, Precios WhatsApp API 2026](https://leadsales.io/blog/whatsapp-business-api-cuanto-cuesta/)
- **Marketplace como ubicación de anuncios:** los anuncios aparecen en la página de inicio de Marketplace y mientras se navega Marketplace en la app; los anuncios en resultados de búsqueda pueden aparecer junto a resultados de Facebook y Marketplace. Meta recomienda las ubicaciones automáticas (Advantage+). HECHO-secundario (vía extracto de búsqueda; el texto completo no se pudo leer). — [Meta Business Help, Ubicaciones de anuncios](https://www.facebook.com/business/help/407108559393196?id=369787570424415); [Meta Business Help, ubicaciones para video](https://www.facebook.com/business/help/360195617512041)

### Inferences
- ESTIMACIÓN (mezcla fuentes, usar con cautela): CPC ≈ CPM ÷ (1000 × CTR) = 3.92 ÷ (1000 × 0.0268) ≈ **US$0.15 por clic** si México tuviera el CTR mediano global de DTC. El CTR de México no está verificado.
- Fórmula para el costo de adquisición por pedido (A): **A = (CPM/1000) ÷ CTR ÷ r_conv ÷ r_cierre × TC**, donde r_conv es la tasa clic→conversación iniciada, r_cierre la tasa conversación→pedido y TC el tipo de cambio USD/MXN (usar el FIX de Banxico del día; no verificado en esta investigación). r_conv y r_cierre son **HIPÓTESIS** hasta tener datos propios.
- HIPÓTESIS operativa: usando la WhatsApp Business App (no la API) o Messenger, el costo por mensaje es $0 y el costo de la conversación se reduce al gasto en anuncios. Con la API, las conversaciones originadas en CTWA son gratis durante la ventana FEP.
- La publicación "boost" o promoción de anuncios individuales de Marketplace en México no quedó confirmada (ver Gaps). Lo confirmado es la **ubicación** Marketplace dentro de campañas de Ads Manager.

### Gaps
- **Costo por conversación (Messenger/WhatsApp) en México**: No disponible en fuentes públicas confiables.
- **Tasa de cierre conversación→venta**: no se encontró ni siquiera una fuente anecdótica específica de México. No disponible.
- CTR y CPC específicos de México en 2025–2026: No disponible.
- Disponibilidad en México de "promocionar publicación de Marketplace" (boost de listing): no confirmada con página oficial.
- Monto de la nueva tarifa de marketing de WhatsApp para México vigente desde 1-oct-2026.

## 4. Facebook Marketplace en México: checkout, envíos, comisiones y políticas de comercio

### Takeaway
En México, Marketplace funciona como **tablero de anuncios con trato directo**: no hay evidencia de checkout ni de envíos integrados (el envío con Facebook está documentado solo para EE. UU.). Por eso no hay comisión de Facebook por venta, y tampoco protección de compra ni retención fiscal. Las Políticas de Comercio prohíben 24 categorías (entre ellas animales) y declaran que **"Marketplace is intended for consumer-to-consumer sales"**. No se encontró una regla oficial explícita sobre dropshipping o artículos que el vendedor no tiene en su poder: es un riesgo de cumplimiento no resuelto.

### Cited Findings
- Las Políticas de Comercio enlistan **24 categorías prohibidas**: Adult Content...; Alcohol; Body Parts and Fluids; **Digital Media and Electronic Devices**; Discrimination; Documents, Currency and Financial Instruments; Gambling; Hazardous Goods and Materials; Human Exploitation and Sexual Services; Jobs; **Land, Animals, and Animal Products**; **Medical and Healthcare Products**; Misleading, Violent, or Hateful; **No Item for Sale**; Prescription Products, Drugs...; **Recalled Products**; Stolen Goods; Subscriptions and Digital Products; **Third-Party Infringement**; Tobacco...; **Used Cosmetics**; **Vehicle Parts and Accessories**; Weapons...; y Normas Comunitarias. — [Meta, Commerce Policies](https://www.facebook.com/policies_center/commerce)
- Animales: no se permite promover la compraventa de "animals or animal parts". Restringido (solo vendedores aprobados): boletos de eventos, tarjetas de regalo y **servicios de emparejamiento para adopción de mascotas**. Los servicios solo se pueden comerciar en WhatsApp Business o mediante Citas en Facebook/Instagram. — [Meta, Commerce Policies](https://www.facebook.com/policies_center/commerce)
- "Facebook Marketplace is intended for consumer-to-consumer sales." El incumplimiento puede llevar a eliminar publicaciones o a medidas sobre la cuenta, y las apelaciones van por las páginas de ayuda de Marketplace y Catálogo. La página no muestra fecha de actualización. — [Meta, Commerce Policies](https://www.facebook.com/policies_center/commerce)
- La política "Misleading, violent or hateful" prohíbe, entre otras cosas, contenido comercial "misleading, shocking, sensational", contenido que **"solicits ratings or reviews"**, contenido que genera autopercepción negativa para promover productos de salud, y contenido comercial **"that contains deceptive links"**. — [Meta, Commerce Policy: Misleading, violent or hateful](https://www.facebook.com/policies_center/commerce/misleading_violent_or_hateful)
- "No Item for Sale": se prohíbe contenido que no ofrezca un producto a la venta (noticias, humor). — [Meta, Commerce Policies](https://www.facebook.com/policies_center/commerce)
- En el lanzamiento en LatAm, Facebook no facilitaba ni el pago ni el envío: comprador y vendedor acuerdan los detalles por mensaje. **[>12 meses]** (dic-2016), sin fuente oficial más reciente para México. — [Meta Newsroom LatAm, 2016](https://about.fb.com/ltam/news/2016/12/pesentamos-mercado-compra-y-vende-articulos-en-tu-comunidad/)
- El envío en Marketplace es exclusivo de EE. UU. (requiere Facebook Payments con datos fiscales de EE. UU.); fuera de EE. UU. no hay guías prepagadas. HECHO-secundario. — [Crosslist Docs](https://docs.crosslist.com/getting-started/shipping-profiles/facebook); [HustleGotReal](https://hustlegotreal.com/faq/facebook-marketplace/facebook-marketplace-shipping-not-available-why-cant-i-offer-shipping/)
- Desde el 24-feb-2025 Marketplace dejó de vender guías prepagadas para publicaciones nuevas (EE. UU.). **[>12 meses]**. — [Value Added Resource](https://valueaddedresource.net/facebook-marketplace-ends-pre-paid-shipping)
- En EE. UU. las ventas con envío por checkout pagan ~10% (mínimo US$0.80). No aplica a México. — [Target Internet](https://www.targetinternet.com/what-is-facebook-marketplace/)
- Cuentas nuevas o con poca actividad: blogs reportan que son las más restringidas y que el acceso se habilita al generar confianza (foto real, actividad, sin logins desde otro país o proxy). El estado se revisa en Configuración > Marketplace > "Ver estado de la cuenta" y se puede solicitar revisión. ANECDÓTICO / baja calidad. — [DiCloak](https://dicloak.com/es/blog-detail/why-marketplace-isn-t-available-to-you-happens-and-how-to-fix-it-safely); [JustAnswer](https://www.justanswer.es/informatica-es/octra-facebook-marketplace-no-deja-ingresar-asistente-del.html)
- Un límite numérico de publicaciones para cuentas nuevas (p. ej. "5 artículos la primera semana") solo aparece en páginas SEO no confiables. **No verificado**.

### Inferences
- HIPÓTESIS: en México la comisión de Facebook por venta es **$0**, porque no hay checkout. A cambio, no hay protección de compra ni intermediación de pagos: el vendedor cobra con efectivo, SPEI o link de pago externo.
- HIPÓTESIS de riesgo de cumplimiento: operar dropshipping a escala de negocio en Marketplace choca con la declaración "intended for consumer-to-consumer sales". Publicar artículos sin inventario, con fotos de proveedor o con precios gancho puede caer en "misleading". Un link de pago externo es legítimo solo si no es "deceptive". La mitigación prudente es tener al menos una unidad en mano, usar fotos propias y describir con honestidad el tiempo de entrega.
- Categorías a vigilar por su cercanía con las prohibidas: accesorios de mascotas (permitidos solo si no involucran animales ni partes animales), dispositivos electrónicos de streaming o "desbloqueo" (Digital Media and Electronic Devices), productos de salud o bienestar con claims (Medical and Healthcare; Misleading), accesorios para auto (existe la categoría "Vehicle Parts and Accessories", cuyo alcance no se pudo leer) y cosméticos (Used Cosmetics). Validar cada SKU contra la subpágina correspondiente.
- Prácticas de validación del canal (HIPÓTESIS operativas, sin fuente cuantitativa): (1) medir mensajes por publicación por día y la tasa mensaje→cita→venta antes de pagar anuncios; (2) probar 1–2 publicaciones por SKU con unidad en mano antes de escalar; (3) evitar duplicados y automatizaciones de publicación (los blogs las señalan como disparadores de restricción); (4) registrar los rechazos de publicación y apelar desde el estado de la cuenta.

### Gaps
- Página oficial del Centro de Ayuda que confirme **para México** la ausencia de checkout y envíos (las URL de ayuda probadas dieron 404).
- Texto detallado de las subpáginas "Land, Animals, and Animal Products", "Digital Media and Electronic Devices", "Medical and Healthcare Products" y "Vehicle Parts and Accessories" (404 o no leídas). Falta confirmar por escrito que los **productos para mascotas** (no animales) están permitidos.
- Política oficial explícita sobre **dropshipping o artículos no en posesión**: no encontrada.
- **Límites numéricos** de publicaciones para cuentas nuevas: no verificados.

## 5. Comportamiento del comprador y fraude en Marketplace (México)

### Takeaway
Facebook concentra casi la mitad de los reportes de fraude en compraventa en línea atendidos por el Consejo Ciudadano de la CDMX (47.9% en ene–sep 2024, con electrónicos como la categoría principal). Profeco recomienda revisar al vendedor y entregar en lugares públicos. Por eso la **entrega en punto medio con pago contra revisión** y las señales de confianza (perfil antiguo, fotos reales) son normas de facto. El último dato público de AMVO sobre contra entrega es de **2024 (13% de uso)**; no se encontró el dato de 2026.

### Cited Findings
- Consejo Ciudadano CDMX, primeros nueve meses de 2024: **1,945 reportes** de fraude en compraventa en línea (+26%); **47.9% en Facebook**; 45% de los casos de hasta $10,000. Categorías en Facebook: electrónicos, electrodomésticos y pantallas 24.9%; "montaviajes" 15.5%; servicios 14.7%; vehículos 8.8%. Recomienda desconfiar de precios más de 20% por debajo del promedio. **[>12 meses]** — [Expansión, 08/10/2024](https://expansion.mx/finanzas-personales/2024/10/08/como-evitar-caer-fraudes-facebook)
- Un dato de 2022 ubicaba a Facebook en 65.5% de los reportes, Segunda Mano en 18.6% y Mercado Libre en 7.3%; otras fuentes dan cifras distintas. Los periodos y métodos no son comparables. **[>12 meses]** — [Chilango](https://www.chilango.com/noticias/reportajes/fraudes-en-sitios-de-compraventa/)
- Profeco recomienda verificar la antigüedad de la cuenta, la foto de perfil y las reseñas; revisar el producto en persona antes de pagar; **evitar transferencias a cuentas personales** y usar métodos con protección; comunicarse dentro de la plataforma; y **entregar en un lugar público**. **[>12 meses]** (19-ago-2024) — [El Cronista, Profeco](https://www.cronista.com/mexico/pc-celular/alerta-por-fraudes-profeco-publico-una-serie-de-recomendaciones-para-evitar-estafas-en-facebook-e-instagram/)
- Profeco y Facebook eliminaron **más de 7,000 perfiles** de ventas fraudulentas (contexto pandemia); se menciona la práctica de reunirse en un "punto medio". **[>12 meses]** (2021, act. 2023) — [ADN40](https://www.adn40.mx/mexico/facebook-tianguis-mva-especial)
- Fraude común contra **vendedores**: el comprador envía un comprobante de transferencia falso y pide el artículo antes de que se refleje el dinero. — [BBVA México, Estafas por Facebook](https://www.bbva.mx/personas/centro-de-ayuda/evitar-estafas-por-facebook.html)
- Condusef (2024) advierte riesgos en compras en Facebook, Mercado Libre, SHEIN y Amazon (robo de datos, suplantación, fraude con tarjeta), sin cifras específicas de Marketplace. **[>12 meses]** — [Genbeta, 09/05/2024](https://www.genbeta.com/a-fondo/condusef-alerta-mexico-comprar-shein-facebook-marketplace-amazon-puede-acabar-estafa)
- AMVO, Estudio de Venta Online 2024: formas de pago en ecommerce: débito 74%, crédito 57%, transferencia 20%, **efectivo contra entrega 13%**. **[>12 meses]** — [InformaBTL](https://www.informabtl.com/ecommerce-cuales-son-los-metodos-de-pago-favoritos-de-los-mexicanos-en-2024/)
- AMVO (Hot Sale 2026): los pagos son una palanca central del crecimiento y "el 80% de la población sin tarjeta de crédito" ha impulsado métodos de pago alternativos. — [DPL News](https://dplnews.com/?p=315249)
- Caso de feb-2026: detenida en Yucatán una mujer por fraude en compraventa de autos vía Marketplace. — [Por Esto, 11/02/2026](https://www.poresto.com/yucatan/sucesos/2026/2/11/mujer-estafaba-con-la-compraventa-de-autos-en-marketplace-de-facebook-asi-operaba.html)

### Inferences
- HIPÓTESIS: un vendedor nuevo y desconocido en Marketplace CDMX enfrentará una fuerte **resistencia a pagar por adelantado** con link o transferencia, porque Profeco aconseja justo lo contrario. Por eso la entrega en punto medio con pago en efectivo o SPEI verificado al momento, o el COD, serán los formatos con mayor conversión. Pagar por adelantado con link de pago probablemente convierte peor en frío. No hay datos cuantitativos.
- HIPÓTESIS: del lado del vendedor, el fraude principal es el comprobante SPEI falso. Conviene confirmar la recepción en la app bancaria antes de entregar.
- La preferencia por estaciones del Metro como punto de entrega es práctica conocida, pero **no se encontró una encuesta o estudio que la cuantifique**.

### Gaps
- AMVO **Estudio de Venta Online 2025/2026**: el porcentaje de contra entrega y la confianza en redes sociales no aparecieron en las fuentes accesibles.
- Alertas Condusef/Profeco **2025–2026** específicas de Marketplace: no encontradas.
- Un dato de "2,982 reportes de fraude compraventa vía Facebook hasta dic-2024" (Consejo Ciudadano) apareció en un extracto de búsqueda sin URL atribuible. No verificado.
- Prevalencia cuantitativa de entrega en estaciones del Metro y tasas de "plantón" (no-show) en punto medio: No disponible.

## 6. Obligaciones legales del consumidor y notas fiscales (ventas a distancia)

### Takeaway
La LFPC da al consumidor **5 días hábiles para revocar** las ventas "fuera del establecimiento, mediatas o indirectas" (art. 56): el proveedor reembolsa el precio y el consumidor paga flete y seguro del regreso. Toda garantía ofrecida dura **mínimo 90 días** (art. 77), y el comercio electrónico obliga a informar domicilio físico, teléfonos y costos totales (art. 76 Bis, reformado en dic-2025). En impuestos, la retención por plataformas digitales subió en 2026 a **2.5% ISR + 8% IVA** (persona física con RFC), pero **solo aplica cuando la plataforma intermedia y cobra**. Marketplace en México no cobra, por lo que no habría retención y el vendedor debe tributar por su cuenta. Esto último es una inferencia a confirmar con un contador.

### Cited Findings
- **LFPC art. 56** (Capítulo V, "De las ventas a domicilio o fuera del establecimiento mercantil, mediatas o indirectas", arts. 51–56): "El contrato se perfeccionará a los cinco días hábiles contados a partir de la entrega del bien"; durante ese lapso el consumidor puede revocar "sin responsabilidad alguna"; el proveedor devuelve el precio, y **"los costos de flete y seguro correrán a cargo del consumidor"**. La revocación se hace por aviso, entrega personal del bien, correo registrado u otro medio fehaciente. Reformas DOF 04-02-2004 y 11-01-2018. — [mLey, LFPC art. 56](https://mley.mx/LFPC/articulo/56/); [SDV, LFPC art. 56](https://sdv.com.mx/compendio/ley-federal-de-proteccion-al-consumidor/articulo-56/)
- **LFPC art. 77**: "la garantía no podrá ser inferior a noventa días contados a partir de la entrega del bien o la prestación del servicio." — [mLey, LFPC art. 77](https://mley.mx/LFPC/articulo/77/)
- **LFPC art. 76 Bis** (comercio electrónico): confidencialidad de datos; seguridad; informar **domicilio físico, teléfonos y medios de reclamación** antes de la transacción; no usar prácticas engañosas; informar "toda la información sobre los términos, condiciones, costos" y formas de pago; fracciones VI–IX (cargos recurrentes y cancelación) añadidas o reformadas en DOF **12-12-2025**. mLey indica que su texto está pendiente de cotejo con la fuente oficial. — [mLey, LFPC art. 76 Bis](https://mley.mx/LFPC/articulo/76%20Bis/)
- **Retención por plataformas 2026 (personas físicas)**: ISR **2.5%** (antes 1%) por enajenación de bienes; IVA **50% del trasladado (8% efectivo)**; sin RFC: ISR 20% e IVA 100%. Opción de pago definitivo con ingresos menores a **$300,000** anuales (sin declaraciones mensuales ni anuales, sin deducciones). — [Siigo, Régimen de plataformas digitales](https://www.siigo.com/mx/blog/obligaciones-fiscales/regimen-plataformas-digitales-sat-obligaciones/); [IDC Online, 17/04/2026](https://idconline.mx/fiscal-contable/2026/04/17/plataformas-digitales-2026-el-nuevo-alcance-fiscal-para-personas-morales)
- Nueve asociaciones (entre ellas AMVO y Canieti) pidieron reducir las retenciones a 2% de IVA y 1% de ISR para el Paquete Económico 2027. — [DPL News](https://dplnews.com/?p=328946)
- El SAT indica que **las plataformas que intermedian y cobran** las operaciones deben retener y enterar el ISR, calculado sobre el total del ingreso. Documento probablemente **[>12 meses]**. — [SAT, Preguntas generales esquema de intermediación](https://www.sat.gob.mx/minisitio/PlataformasTecnologicas/PlataformasTecnologicas_Intermediacion/documentos/PreguntasGenerales_esquema_intermediacion.pdf)
- RESICO y plataformas: la regla 3.13.4 de la RMISC 2022 establece que quien tribute por plataformas y además tenga ingresos por actividades empresariales no puede tributar en RESICO. **[>12 meses]**, verificar la RMF vigente. — [IDC Online, 2022](https://idconline.mx/fiscal-contable/2022/02/09/resico-e-ingresos-por-plataformas-pueden-combinarse)

### Inferences
- HIPÓTESIS (confirmar con contador): Marketplace México no intermedia el cobro, así que **no retiene ISR ni IVA**, a diferencia de Mercado Libre. El vendedor habitual realiza actividad empresarial y debe inscribirse (p. ej. RESICO o actividad empresarial), declarar y, si aplica, **trasladar IVA del 16%**. Para el margen, formalizarse implica que el ingreso neto es P/1.16: **$343.97** en lugar de $399 (−$55.03) y **$516.38** en lugar de $599 (−$82.62).
- HIPÓTESIS: tampoco está claro si cobrar por link de pago de Mercado Pago u otro procesador activa la retención de plataformas. Las fuentes no lo resuelven.
- ESTIMACIÓN de impacto legal en el modelo: el derecho de revocación de 5 días hábiles solo obliga a devolver el precio, porque el flete del regreso lo paga el consumidor. Aun así, la comisión de cobro original normalmente no se recupera (Stripe lo dice expresamente). Hay que reservar un % para devoluciones y garantía de 90 días.
- La **NOM-247-SE** no quedó verificada en esta sesión. Por conocimiento previo (no verificado), la NOM-247-SE-2021 regula información y contratos de **bienes inmuebles de casa habitación**, por lo que no aplicaría a esta venta de bienes muebles. Tratar como HIPÓTESIS.

### Gaps
- Texto oficial (DOF o Cámara de Diputados) de los arts. 56, 76 Bis y 77: solo se consultó la compilación mLey, que advierte cotejo pendiente.
- Tasas vigentes de RESICO para personas físicas y compatibilidad 2026 con ingresos por plataformas: no verificadas en esta sesión.
- Confirmación oficial de que Facebook/Meta **no** retiene en México.
- Si la NMX-COE-001-SCFI-2018 (comercio electrónico, voluntaria) u otra NOM aplica: no verificado.

## 7. Tasas de devolución o rechazo en dropshipping COD (México/LatAm)

### Takeaway
Solo hay fuentes **anecdóticas** (blogs de dropshipping con afiliación a Dropi o proveedores de COD): tasa de entrega efectiva de **70–85%** en zonas urbanas con confirmación previa por WhatsApp, devoluciones de **~20% como "estándar"**, y casos de 30% bajando a 15%. No hay datos oficiales ni de paqueterías.

### Cited Findings
- "Tasa de entrega típica en zonas urbanas: **70-85%** cuando hay confirmación previa por WhatsApp o IA de voz." Comisión Dropi 2–5% por pedido según país. ANECDÓTICO (afiliado a Dropi; publicado 07-abr-2026, act. 21-may-2026). — [Andrey Business, Dropi contra entrega](https://www.andreybusiness.com/mexico/blog/dropi-contra-entrega-cobran-por-devoluciones-verdad)
- En dropshipping contra entrega "un **20% de devoluciones** es un estándar"; tasa = devoluciones ÷ pedidos despachados × 100 (ejemplo: 30 de 200 = 15%); el flete promedio en México es ~**12% del precio de venta** como punto de partida. ANECDÓTICO (mismo autor). — [Andrey Business, devoluciones sanas COD](https://www.andreybusiness.com/mexico/blog/que-de-devoluciones-es-sano-en-una-tienda-de-dropshipping-contra-entrega); [Andrey Business, reducción de 30 a 15%](https://www.andreybusiness.com/mexico/blog/reduccion-de-devoluciones-de-30-a-15-con-este-sistema)
- Cada paquete COD rechazado regresa **con costo para el comerciante** (contratos J&T). ANECDÓTICO (proveedor de COD). — [Fufills, J&T COD](https://fufills.com/en/blog/3pl-fulfillment/jt-express-mexico-pago-contra-entrega)

### Inferences
- ESTIMACIÓN para modelar la tasa de entrega efectiva e: bajo-riesgo **85%**, base **80%**, conservador **70%** (rango anecdótico 70–85%).
- ESTIMACIÓN: con e = 70%, cada pedido entregado carga el costo de 0.43 pedidos fallidos (0.3/0.7). Con un flete de ida de $165 más regreso de $165 y empaque de $20, eso suma **$150 por pedido entregado**, que es el factor que más destruye margen en tickets de $399.
- HIPÓTESIS: la confirmación previa por WhatsApp (y, si el proveedor lo permite, un anticipo parcial) es la palanca principal para mover e de 70% a 85%.

### Gaps
- Tasas de rechazo COD publicadas por paqueterías (99minutos, J&T, Estafeta) o por estudios independientes: No disponible.
- Cobro exacto del flete de regreso en Dropi México o 99minutos Cash99: No disponible.

## 8. Síntesis: cost stack y plantilla de margen de contribución

### Takeaway
Con insumos citados y supuestos explícitos: el **escenario A (orgánico + punto medio)** deja el mayor margen, pero no es dropshipping puro (requiere unidad en mano). El **escenario B (orgánico + paquetería + link)** es viable en $599 y ajustado en $399 si el costo X supera ~$150. El **escenario C (ads + paquetería + COD)** a $399 **no es viable en el caso conservador ni antes de anuncios** (K ≈ $12), y a $599 solo tolera un costo por pedido de anuncios bajo. Hay que priorizar tickets de ~$599 o más para COD con anuncios.

### Cited Findings
**(a) Cost stack** (MXN por pedido salvo que se indique; IVA incluido en comisiones y fletes cuando la fuente lo indica)

| Componente | Bajo | Base | Conservador | Unidad | Etiqueta | Fuente |
|---|---|---|---|---|---|---|
| Comisión Facebook Marketplace (MX) | 0 | 0 | 0 | MXN/venta | HIPÓTESIS (sin checkout en MX) | [Commerce Policies](https://www.facebook.com/policies_center/commerce); [Meta 2016](https://about.fb.com/ltam/news/2016/12/pesentamos-mercado-compra-y-vende-articulos-en-tu-comunidad/) |
| Cobro: efectivo en mano / SPEI directo | 0 | 0 | 0 | MXN | HIPÓTESIS (gratuidad bancaria no verificada) | [Expansión 2023](https://expansion.mx/economia/2023/08/08/spei-codi-dimo-diferencias-banxico) |
| Cobro: link/tarjeta | Clip 3.6% + IVA (4.18%) | Mercado Pago 3.49% + $4 + IVA | PayPal 3.95% + $4 + IVA | % + fija | HECHO | [Tiendanube/Clip](https://www.tiendanube.com/mx/blog/clip); [MP](https://www.mercadopago.com.mx/herramientas-para-vender/link-de-pago); [PayPal](https://www.paypal.com/mx/webapps/mpp/merchant-fees) |
| Cobro: efectivo OXXO vía pasarela | Conekta 2.6% + $3 + IVA | MP 3.49% (+ $4) | MP 3.79% + $4 (FAQ) | % + fija | HECHO (MP se contradice) | [Conekta](https://www.conekta.com/pricing); [MP](https://www.mercadopago.com.mx/herramientas-para-vender/link-de-pago) |
| Sobretasa MSI (no recomendada) | 3.5% (Conekta 3 MSI) | 4.69% + IVA (MP 3 MSI) | 5% (Stripe 3 MSI) o más | % adicional | HECHO | [Conekta](https://www.conekta.com/pricing); [MP](https://www.mercadopago.com.mx/herramientas-para-vender/link-de-pago); [Stripe](https://stripe.com/mx/pricing) |
| Contracargo | 0 | — | 150 | MXN/disputa (Stripe) | HECHO | [Stripe](https://stripe.com/mx/pricing) |
| Envío nacional ~1 kg | 95.99 | 122.75 | 161.07 | MXN/envío | HECHO-secundario (cotizaciones publicadas 2026) | [Tiendanube](https://www.tiendanube.com/blog/cual-es-la-paqueteria-mas-barata-en-mexico/); [EnviaYa](https://enviaya.com.mx/es/paqueterias/precios/) |
| Envío nacional ~3 kg | 151 (Correos) | 223 (Paquetexpress) | 287 (Estafeta) | MXN/envío | ESTIMACIÓN de terceros | [CalculoSeguro](https://calculoseguro.mx/calculadora-costo-envio-paquete) |
| Envío 0.5 kg | = tarifa 1 kg | = tarifa 1 kg | = tarifa 1 kg | MXN | HIPÓTESIS / No disponible | — |
| Local mismo día CDMX/Edomex | 83.90 | 110 | 145 | MXN/envío | HECHO-secundario ("desde" e ilustrativos) | [Cubbo/99minutos](https://www.cubbo.com/en/posts/99minutos-pricing-mexico-2026) |
| App courier ~10 km (DiDi/Uber/Lalamove) | 29 (mínimo DiDi Light) | No disponible | No disponible | MXN | HECHO [>12 meses] / No disponible | [Xataka](https://www.xataka.com.mx/automovil/entrega-light-nuevo-servicio-didi-mexico-barato-app-realizan-repartidores-didi-food-moto-bicicleta) |
| Comisión COD | 2% | 4% | 5% | % del valor | HECHO-secundario (99minutos 4%) / ANECDÓTICO (Dropi 2–5%) | [Cubbo](https://www.cubbo.com/en/posts/99minutos-pricing-mexico-2026); [Andrey Business](https://www.andreybusiness.com/mexico/blog/dropi-contra-entrega-cobran-por-devoluciones-verdad) |
| Tasa de entrega efectiva COD (e) | 85% | 80% | 70% | % | ANECDÓTICO | [Andrey Business](https://www.andreybusiness.com/mexico/blog/dropi-contra-entrega-cobran-por-devoluciones-verdad) |
| Flete de regreso en rechazo COD | 0× | 0.5× | 1.0× | × flete de ida | HIPÓTESIS | [Fufills (costo al comerciante)](https://fufills.com/en/blog/3pl-fulfillment/jt-express-mexico-pago-contra-entrega) |
| Pérdida de producto en rechazo (L) | 0% | 0% | 10% de X | % | HIPÓTESIS | — |
| Empaque / cargo de preparación del proveedor (F) | 0 | 8–10 | 15–20 | MXN/pedido | HIPÓTESIS (No disponible) | — |
| Abastecimiento a vendedor (solo escenario A) | 0 | 22.30 (lote de 3 kg a $223 ÷ 10 u) | 83.90 (1 envío mismo día por unidad) | MXN/unidad | ESTIMACIÓN | [CalculoSeguro](https://calculoseguro.mx/calculadora-costo-envio-paquete); [Cubbo](https://www.cubbo.com/en/posts/99minutos-pricing-mexico-2026) |
| Traslado a punto medio incl. plantones | 0 | 23.53 ($20 ÷ 0.85) | 57.14 ($40 ÷ 0.70) | MXN/venta | HIPÓTESIS | — |
| Reserva devoluciones/garantía (LFPC 56/77) | 0–2% | 3–4% | 5–8% | % de P | HIPÓTESIS | [LFPC 56](https://mley.mx/LFPC/articulo/56/); [LFPC 77](https://mley.mx/LFPC/articulo/77/) |
| CPM Facebook México (ecommerce) | — | US$3.92 | — | USD/1000 impresiones | HECHO-secundario (Lebesgue jul-2026) | [Pace Ads](https://paceads.com/research/meta-ads-statistics-2026) |
| Costo por conversación CTWA/Messenger | No disponible | No disponible | No disponible | MXN | — | [Getkanal](https://getkanal.com/blog/click-to-whatsapp-ads-benchmarks-2026) |
| Mensajes WhatsApp API (si se usa) | 0 (ventana FEP de CTWA, hasta 7 días) | — | US$0.0305/msg marketing (ago-2026; subió el 1-oct-2026) | USD/mensaje | HECHO / HECHO-secundario | [Meta Dev](https://developers.facebook.com/docs/whatsapp/pricing); [LeadSales](https://leadsales.io/blog/whatsapp-business-api-cuanto-cuesta/) |
| IVA trasladado si el vendedor está formalizado | 0 (informal) | — | P − P/1.16 (−$55.03 a $399; −$82.62 a $599) | MXN | HIPÓTESIS fiscal | [Siigo](https://www.siigo.com/mx/blog/obligaciones-fiscales/regimen-plataformas-digitales-sat-obligaciones/) |
| Retención por plataforma (ISR 2.5% + IVA 8%) | 0 | 0 | 0 (no aplica si Marketplace no cobra) | % | HIPÓTESIS | [Siigo](https://www.siigo.com/mx/blog/obligaciones-fiscales/regimen-plataformas-digitales-sat-obligaciones/) |

### Inferences
**(b) Plantilla de margen de contribución (CM) por pedido.** X = costo del producto puesto por el proveedor. Todos los cálculos son ESTIMACIÓN con los insumos de la tabla (a). Supuestos: vendedor informal (sin trasladar IVA; si se formaliza, sustituir P por P/1.16) y flete absorbido por el vendedor (si el comprador lo paga aparte, sumarlo al ingreso).

**Escenario A: Marketplace orgánico + entrega en punto medio (CDMX/Edomex), pago en efectivo o SPEI** (requiere unidad en mano, así que no es dropshipping puro)

Fórmula: `CM_A = P − X − Cobro − C_abasto − T/(1−n) − F − r·P`
(Cobro = 0 en bajo y base; Mercado Pago en el conservador. T = traslado, n = tasa de plantón, r = reserva.)

| P | Nivel | Cobro | Abasto | Traslado | F | Reserva | **K = CM + X** | X máx. (CM = 0) | X para CM ≥ 20% P |
|---|---|---|---|---|---|---|---|---|---|
| 399 | Bajo | 0 | 0 | 0 | 0 | 0 | **399.00** | 399.00 | 319.20 |
| 399 | Base | 0 | 22.30 | 23.53 | 8 | 11.97 | **333.20** | 333.20 | 253.40 |
| 399 | Conservador | 20.79 | 83.90 | 57.14 | 15 | 19.95 | **202.21** | 202.21 | 122.41 |
| 599 | Bajo | 0 | 0 | 0 | 0 | 0 | **599.00** | 599.00 | 479.20 |
| 599 | Base | 0 | 22.30 | 23.53 | 8 | 17.97 | **527.20** | 527.20 | 407.40 |
| 599 | Conservador | 28.89 | 83.90 | 57.14 | 15 | 29.95 | **384.12** | 384.12 | 264.32 |

Ejemplos con CM = K − X: P = $399, conservador, X = $150 → CM = **$52.21 (13.1%)**. P = $599, conservador, X = $150 → CM = **$234.12 (39.1%)**.

**Escenario B: Marketplace orgánico + paquetería nacional (~1 kg) + link de pago anticipado**

Fórmula: `CM_B = P − X − (tasa·P + fija)·1.16 − S − F − r·P`
(Bajo: Clip y S = $95.99; base: Mercado Pago al instante y S = $122.75; conservador: PayPal y S = $161.07.)

| P | Nivel | Cobro | Envío S | F | Reserva r·P | **K** | X máx. | X para CM ≥ 20% P |
|---|---|---|---|---|---|---|---|---|
| 399 | Bajo | 16.66 | 95.99 | 0 | 7.98 (2%) | **278.37** | 278.37 | 198.57 |
| 399 | Base | 20.79 | 122.75 | 10 | 15.96 (4%) | **229.50** | 229.50 | 149.70 |
| 399 | Conservador | 22.92 | 161.07 | 20 | 31.92 (8%) | **163.09** | 163.09 | 83.29 |
| 599 | Bajo | 25.01 | 95.99 | 0 | 11.98 | **466.02** | 466.02 | 346.22 |
| 599 | Base | 28.89 | 122.75 | 10 | 23.96 | **413.40** | 413.40 | 293.60 |
| 599 | Conservador | 32.09 | 161.07 | 20 | 47.92 | **337.92** | 337.92 | 218.12 |

Ejemplos: P = $399, X = $150 → CM base $79.50 (19.9%) y conservador $13.09 (3.3%). P = $599, X = $150 → CM base $263.40 (44.0%) y conservador $187.92 (31.4%). Con paquete de 3 kg, sustituir S por $151/$223/$287.

**Escenario C: anuncios pagados (CTWA/Messenger) + paquetería + contra entrega (por pedido ENTREGADO)**

Fórmula:
`CM_C = P − c·P − S − F − r·P − ((1−e)/e)·(S + R + F) − X·(1 + ((1−e)/e)·L) − A/e`
donde c = comisión COD, S = flete de ida, R = flete de regreso (0/0.5/1.0 × S), e = tasa de entrega efectiva, L = pérdida de producto en rechazos y A = costo de anuncios por **pedido confirmado** (= CPM/1000 ÷ CTR ÷ r_conv ÷ r_cierre × TC; variable HIPÓTESIS).
Costo máximo tolerable de anuncios por pedido confirmado: `A_máx = e·(K − coefX·X)`.

| P | Nivel | COD c·P | S | F | Reserva | Costo de fallidos por entregado | e | coefX | **K (antes de anuncios)** |
|---|---|---|---|---|---|---|---|---|---|
| 399 | Bajo | 7.98 (2%) | 89.00 | 0 | 7.98 | 15.71 | 85% | 1.000 | **278.33** |
| 399 | Base | 15.96 (4%) | 122.75 | 10 | 15.96 | 48.53 | 80% | 1.000 | **185.80** |
| 399 | Conservador | 19.95 (5%) | 165.00 | 20 | 31.92 | 150.00 | 70% | 1.043 | **12.13** |
| 599 | Bajo | 11.98 | 89.00 | 0 | 11.98 | 15.71 | 85% | 1.000 | **470.33** |
| 599 | Base | 23.96 | 122.75 | 10 | 23.96 | 48.53 | 80% | 1.000 | **369.80** |
| 599 | Conservador | 29.95 | 165.00 | 20 | 47.92 | 150.00 | 70% | 1.043 | **186.13** |

CM después de anuncios por pedido entregado (A = costo por pedido confirmado, valores HIPÓTESIS):

| P | Nivel | X | CM antes de anuncios | A_máx (punto de equilibrio) | CM con A = $50 | CM con A = $100 | CM con A = $150 |
|---|---|---|---|---|---|---|---|
| 399 | Base | 100 | 85.80 | 68.64 | 23.30 | −39.20 | −101.70 |
| 399 | Base | 150 | 35.80 | 28.64 | −26.70 | −89.20 | −151.70 |
| 399 | Conservador | 100 | −92.16 | negativo | −163.58 | −235.01 | −306.44 |
| 599 | Base | 100 | 269.80 | 215.84 | 207.30 | 144.80 | 82.30 |
| 599 | Base | 150 | 219.80 | 175.84 | 157.30 | 94.80 | 32.30 |
| 599 | Base | 200 | 169.80 | 135.84 | 107.30 | 44.80 | −17.70 |
| 599 | Conservador | 100 | 81.84 | 57.29 | 10.42 | −61.01 | −132.44 |
| 599 | Conservador | 150 | 29.70 | 20.79 | −41.73 | −113.16 | −184.58 |

Lectura (ESTIMACIÓN):
- A $399 con COD y anuncios, el negocio solo funciona con producto muy barato (X ≤ ~$100), tasa de entrega de 80% o más y costo de anuncios por pedido menor a ~$69.
- A $599, con X ≈ $150 y caso base, se toleran hasta ~$176 de anuncios por pedido confirmado.
- La variable que más mueve el resultado es la tasa de entrega e (de 85% a 70%), seguida del flete de regreso.
- Formalizarse (IVA 16%) resta $55 a $399 y $83 a $599 de cada K anterior.

### Gaps
- Todos los valores de A (costo de anuncios por pedido), r_conv, r_cierre, F, el traslado a punto medio, la tasa de plantón y la reserva de devoluciones son **HIPÓTESIS**: deben reemplazarse con datos de una prueba piloto.
- El flete de 0.5 kg y las tarifas de apps de mensajería por 10 km deben cotizarse directamente (sin registro: cotizadores públicos de Envia.com o EnviaYa; con registro: Skydropx).
- El tipo de cambio USD/MXN para convertir el CPM no se verificó; usar el FIX de Banxico del día del cálculo.
