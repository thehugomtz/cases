# Costos y disponibilidad con proveedores nacionales para la shortlist de 32 productos (corte: 2026-10-22)

Convenciones:
- **HECHO** = verificado en la página del proveedor. Todas las URL se consultaron el 2026-10-22.
- **ESTIMACIÓN** = cálculo con los insumos a la vista.
- **HIPÓTESIS** = no verificado.
- "1–9 / 10–49 / 50–99 / 100+" son los niveles de precio por mayoreo que publica ELE-GATE.
- Precios en MXN.
- **Nunca se extrapoló un costo**: si no se encontró, dice "No disponible".

## 1. ¿Qué proveedores nacionales con precio público se pudieron verificar y en qué condiciones (IVA, MOQ, envío, stock)?

### Takeaway
Solo **ELE-GATE** (CDMX) da a la vez un **costo de proveedor** (4 niveles de mayoreo desde 1 pieza), existencias por sucursal y envío directo al cliente final. **MayoreoTotal** y **Vianney** publican precios **al público**: sirven como techo o referencia de PVP, no como costo. Para los productos de negocios (NFC, placas QR, sellos, mandiles bordados, poly mailers con logo) no apareció ningún taller nacional con precio público por pieza. Todo se mueve por cotización.

### Cited Findings
**ELE-GATE**
- **Búsqueda.** HECHO: se corrieron **121 búsquedas** en su buscador (92 en una primera tanda y 29 en una segunda con términos amplios), con 2–4 variantes en español por producto.
- **Estructura de la ficha.** HECHO: cada ficha muestra:
  - "Precio por mayoreo" en 4 niveles (casi siempre 1–9 / 10–49 / 50–99 / 100+; en algunos SKU, 1–2 / 3–4 / 5–19 / 20+ o 1–4 / 5–9 / 10–19 / 20+);
  - un precio tachado;
  - "Existencias en" por ubicación: Bodega, U14 (Rep. de Uruguay 14), U19, Ejecentral32 y Ecommerce.
  - Ejemplo: [ELE-GATE HOG.311](https://www.ele-gate.com/producto/impermeable-de-2-piezas-con-visera-y-bandas-reflectivas/).
- **IVA.** HECHO: ninguna de las 27 fichas descargadas menciona "IVA" ni "impuesto", así que **no consta si el precio incluye IVA**. ELE-GATE emite CFDI 4.0 (dato ya documentado en `limpieza_herramientas.md` y `proveedores_nacionales.md`).
- **Peso y medidas.** HECHO: casi ninguna ficha publica peso ni dimensiones. Solo una de las revisadas: "Bolsas de Envío con Impresión Total 20x26", **0.6 kg; 23 × 9 × 8 cm** — [ELE-GATE BOLSA.ENVIO20X30P](https://www.ele-gate.com/producto/embalaje-inflable-rollo-de-bolsas-de-aire-40-x-30-cm/).
- **Modelo de dropshipping.** HECHO (en notas previas, misma fecha):
  - sin mínimo y sin costo de registro;
  - despacho en ≤48 h hábiles por J&T, iMile o Cainiao, con flete cotizado por destino (**no publicado**);
  - CFDI;
  - el paquete llega **con la marca ELE-GATE**.
  - Fuente: [ELE-GATE Dropshipping](https://www.ele-gate.com/dropshipping-ele-gate/).

**MayoreoTotal**
- HECHO: catálogo Shopify público con **3,904 productos** leídos vía `products.json` el 2026-10-22, todos con `updated_at` de 2026-10-22.
- Los títulos llevan sufijos de vendedor ("- DRO", "- BGP", "- ZK", "- SCG", "- KOZ"). "ZK" corresponde a productos Member's Mark (marca de Sam's).
- Muestra precio y un flag de disponible, **sin conteo de stock**.
- El campo de peso viene casi siempre en 0 o 1000 g (valor de relleno, no un peso real).
- Fuente: [MayoreoTotal catálogo](https://mayoreototal.mx/products.json).

**Vianney (fabricante textil mexicano)**
- HECHO: catálogo Shopify de **685 productos**. Publica precio al público por variante (tamaño) y disponibilidad, sin conteo de stock — [Vianney](https://vianney.com.mx/products.json).

**Cosmos.com.mx (directorio B2B)**
- HECHO: lista fabricantes de sellos, mandiles bordados, bolsas y bolsas térmicas. Casi todo es "Solicita cotización".
- Cuando hay precio, el sitio lo marca como orientativo: "* Los rangos de precio son orientativos" — [Cosmos: bolsa e-commerce (Bolsof)](https://www.cosmos.com.mx/producto/bolsa-para-e-commerce-m3bs/bolsa-para-e-commerce-con-cierre-g7p1e444d.html).

**Sitios bloqueados o sin resultado**
- HECHO:
  - uelectronics.com responde **403**;
  - vistaprint.com.mx **no resuelve DNS**;
  - mactronica.com.mx da error de túnel 502;
  - fancypets.mx no expone catálogo con precios (ver `mascotas.md`);
  - Mercado Libre no se consultó directo (anti-bot).

### Inferences
- ELE-GATE es la única fuente donde el "costo de proveedor" es en verdad un costo de reventa con niveles. Para el resto de la shortlist, el escritor solo tiene **precios al público de otros revendedores nacionales** (techo de precio).
- **ESTIMACIÓN (costo puesto en cliente):** precio ELE-GATE nivel 1–9 **+ flete no publicado**. El escritor debe tratar el flete como variable abierta o usar el rango de $80–$150 documentado en notas previas, que **no está verificado**.

### Gaps
- Si los precios de ELE-GATE incluyen IVA. No consta en las fichas, y aclararlo requiere preguntar o registrarse, cosa que el encargo prohíbe.
- Flete real de ELE-GATE a CDMX/Edomex por SKU.
- Peso real de casi todos los SKU.
- Si "Ecommerce" es el inventario que se usa para dropshipping.
- Si MayoreoTotal ("DRO") revende productos de Dropi. **HIPÓTESIS**, no verificada.

## 2. Mascotas (1–8): proveedor, precio por nivel, stock, MOQ, envío directo y specs

### Takeaway
Hay costo nacional verificado para **cama tipo iglú o casa para gato** ($145–$160 al nivel 1–9), **pechera antijalones con correa** ($50–$60) y alternativas de quitapelo (guante a $22). Del comedero solo hay platos de acero **no elevados**, y como cubreasiento solo un tapete acolchado para auto con 6 piezas en stock. **No disponible:** tapete atrapa-arena, protector anti-rasguños, pañales lavables y comedero elevado ajustable.

### Cited Findings
**1. Comedero elevado ajustable con 2 platos de acero**
- HECHO: en ELE-GATE, "comedero elevado" y "comedero ajustable" dan **0 resultados**. Los sustitutos más cercanos, **ninguno elevado ni ajustable**:
  - **"Platon para Mascotas de Acero Inoxidable Antideslizantes para Perros y Gatos Talla S"** (MAS.06.S). Juego de 2 platos de acero inoxidable con base antideslizante.
    - Precio: **1–9 $50; 10–49 $46; 50–99 $42; 100+ $38**.
    - Existencias: U19 83, U14 51, Ejecentral32 74, Ecommerce 41.
    - Fuente: [ELE-GATE MAS.06.S](https://www.ele-gate.com/producto/platon-para-mascotas-de-acero-inoxidable-antideslizantes-para-perros-y-gatos-talla-s/).
  - **"Tazón Redondo Antiderrapante De Acero Para Mascotas"** (MAS.06.M), 23 cm.
    - Precio: **1–9 $80; 10–49 $75; 50–99 $70; 100+ $65**.
    - Existencias: U19 91, U14 8, Ejecentral32 58, Ecommerce 46.
    - Bandera roja: la descripción es incoherente ("Cinturones y perlas en el agua").
    - Fuente: [ELE-GATE MAS.06.M](https://www.ele-gate.com/producto/cuenco-para-mascotas-comida-para-gatos-de-perro-de-acero-ino/).
  - **"Dispensador Doble Comedero Y Bebedero Para Mascotas"** (MAS.06.2).
    - Precio: **1–9 $155; 10–49 $145; 50–99 $135; 100+ $125**.
    - Existencias: quedan 28 (U19 2, Ejecentral32 26).
    - Bandera roja: la ficha no tiene descripción ni material.
    - Fuente: [ELE-GATE MAS.06.2](https://www.ele-gate.com/producto/dispensador-doble-comedero-y-bebedero-para-mascotas/).
  - **"Plato Doble De Alimentacion Para Mascota Dispensador De Agua"** (MAS.01.4).
    - Precio: **1–9 $80; 10–49 $70; 50–99 $65; 100+ $60**.
    - Existencias: quedan 15 (U14).
    - Sin descripción.
    - Fuente: [ELE-GATE MAS.01.4](https://www.ele-gate.com/producto/plato-doble-de-alimentacion-para-mascota-dispensador-de-agua/).

**2. Tapete atrapa-arena doble capa**
- HECHO: "tapete arenero" da **0 resultados** en ELE-GATE. "tapete arena", "arenero gato" y "tapete" solo devuelven arenero, tapetes de baño y tapetes refrescantes.
- Lo único relacionado es el "Arenero Plástico Para Gatos Con Pala" (MAS.11) a $100 en el listado — [ELE-GATE búsqueda](https://www.ele-gate.com/?s=tapete+arena&post_type=product).
- **No disponible.**

**3. Hamaca o cubreasiento trasero para perro**
- HECHO: "funda asiento mascota", "hamaca perro", "protector asiento mascota" y "asiento trasero" dan **0 resultados**.
- Lo más cercano es el **"Tapete para Perro Grande Impermeable Acolchonado y Resistente con Agarradera"** (MAS.38). Su descripción dice "Ideal para que el coche no se llene de pelos".
  - Precio: **1–9 $299; 10–49 $280; 50–99 $260; 100+ $240**.
  - Existencias: **solo 6** (Ecommerce).
  - La ficha no confirma anclajes a cabeceras ni formato hamaca.
  - Fuente: [ELE-GATE MAS.38](https://www.ele-gate.com/producto/tapete-para-perro-grande-impermeable-acolchonado-y-resistente-con-agarradera/).
- HECHO previo (en `auto_moto.md`): el vendedor "Mayoristas Mex" en ML a $143, sin escalas por volumen.

**4. Protector anti-rasguños para sofá**
- HECHO: "protector rasguños", "anti rasguños", "rasguños", "protector sofa" y "cinta gato" no devuelven cintas ni láminas.
- Solo aparecen rascadores (precio del listado): "Tablero Circular rascador" (MAS.104) $80, "Rascador Reversible de Cartón" (MAS.103) $60, "Tablero de Rascador Mágico" (MAS.102) $100 y "Almohadilla Rascadora" (MAS.101) $210 — [ELE-GATE búsqueda rascador](https://www.ele-gate.com/?s=rascador&post_type=product).
- **No disponible** como producto.

**5. Cama tipo cueva o saco para gato**
- HECHO: **"Cama Tipo Iglú para Gato"** (MAS.15).
  - Precio: **1–9 $145; 10–49 $135; 50–99 $125; 100+ $115**.
  - Existencias: Bodega 36, U19 43, U14 3, Ejecentral32 20, Ecommerce 46.
  - La ficha no da material, medidas ni peso.
  - Fuente: [ELE-GATE MAS.15](https://www.ele-gate.com/producto/cama-tipo-iglu-gato/).
- HECHO: **"Cama Tipo Casa para Gato o Perro Pequeño 41 × 41 × 23 cm"** (MAS.15.6).
  - Precio: **1–9 $160; 10–49 $150; 50–99 $140; 100+ $130**.
  - Existencias: Bodega 100+, U14 7, Ejecentral32 13, Ecommerce 56.
  - Material y peso no publicados.
  - Fuente: [ELE-GATE MAS.15.6](https://www.ele-gate.com/producto/cama-para-mascota-casa-cubierta-cerrada-interior/).
- HECHO (otro proveedor, al público): Vianney "Cama Mascota Gris" a $699–$899 (no es tipo cueva) — [Vianney](https://vianney.com.mx/products/accesorio-de-mascota-cama-mascota-gris).
- Saco térmico: **No disponible.**

**6. Pañales o calzones lavables para perro**
- HECHO: "pañal perro", "calzon perro", "pañales mascota" y "pañal" no tienen resultados relevantes en ELE-GATE.
- MayoreoTotal solo vende pañales de bebé y adulto — [MayoreoTotal](https://mayoreototal.mx/products.json).
- **No disponible.**

**7. Pechera antijalones con correa**
- HECHO: **"Conjunto De Arnés De Nailon Reflectante Y Correa Para Perros"** (MAS.04.20). Clip en el pecho "para evitar tirones" y otro en la espalda; acolchado y malla transpirable.
  - Precio: **1–9 $50; 10–49 $40; 50–99 $35; 100+ $30**.
  - Existencias: **solo 15** (U19).
  - Fuente: [ELE-GATE MAS.04.20](https://www.ele-gate.com/producto/conjunto-de-arnes-de-nailon-reflectante-y-correa-para-perros-comodidad-y-control-para-tus-paseos/).
- HECHO: **"Pechera Arnés Para Perro Mascota Ajustable"** (MAS.04). Poliéster acolchado, talla mediana; la correa no se menciona como incluida.
  - Precio: **1–9 $60; 10–49 $45; 50–99 $40; 100+ $35**.
  - Existencias: U14 100+, Ejecentral32 73.
  - Fuente: [ELE-GATE MAS.04](https://www.ele-gate.com/producto/pechera-arnes-para-perro-mascota-ajustable/).
- HECHO: **"Correa Resistente y Antitirones para Perros Medianos y Grandes"** (MAS.04.13).
  - Precio: **1–9 $35; 10–49 $28; 50–99 $25; 100+ $21**.
  - Existencias: U19 98, U14 100+, Ecommerce 9.
  - Bandera roja: el texto la llama "arnés" y "correa" a la vez.
  - Fuente: [ELE-GATE MAS.04.13](https://www.ele-gate.com/producto/correa-resistente-y-antitirones-para-perros-medianos-y-grandes-paseos-seguros-y-comodos/).
- HECHO: "Pechera con Bandas Reflectantes para Perros – Talla M" (MAS.04.21.M).
  - Precio: 1–9 $50 → 100+ $35.
  - Existencias: **solo 5**.
  - Fuente: [ELE-GATE MAS.04.21.M](https://www.ele-gate.com/producto/pechera-con-arnes-correa-y-bandas-reflectantes-para-perros-talla-m/).

**8. Rodillo o cepillo quitapelo reutilizable**
- HECHO: ELE-GATE no tiene rodillo quitapelo ("rodillo pelo", "rodillo mascota" y "rodillo" devuelven masajeadores).
- Alternativas en ELE-GATE:
  - **"Guante Antiestático Quita Pelo de Mascotas Reutilizable 20 × 15 cm"** (MAS.10.2).
    - Precio: **1–9 $22; 10–49 $20; 50–99 $18; 100+ $16**.
    - Existencias: Bodega 200+, U19 100+, U14 100+, Ejecentral32 200+, Ecommerce 68.
    - Medidas: **21 × 16 × 0.5 cm**.
    - Fuente: [ELE-GATE MAS.10.2](https://www.ele-gate.com/producto/guante-antiestatico-quita-pelo-de-mascotas-reutilizable-20-x-15-cm/).
  - "Cepillo autolimpiante para perros y gatos" (MAS.12).
    - Precio: **1–9 $70; 10–49 $60; 50–99 $55; 100+ $50**.
    - Existencias: Bodega 1000+.
    - Fuente: [ELE-GATE MAS.12](https://www.ele-gate.com/producto/cepillo-para-mascota-autolimpiante-aseo-limpieza-perros-gato/).
- HECHO (al público, con pago contra entrega): MayoreoTotal vende:
  - "RODILLO ADHESIVO PARA PELUSAS Y PELOS - DRO" **$199** (tachado $300);
  - "QUITA PELO MASCOTA LAVADORA - DRO" $99;
  - "GUANTE QUITA PELO MASCOTAS - DRO" $179.
  - Fuentes: [MayoreoTotal rodillo](https://mayoreototal.mx/products/rodillo-adhesivo-para-pelusas-y-pelos), [MayoreoTotal quita pelo lavadora](https://mayoreototal.mx/products/quita-pelo-mascota-lavadora).

### Inferences
- **ESTIMACIÓN (kit pechera + correa, nivel 1–9):** MAS.04 $60 + MAS.04.13 $35 = **$95**. Con MAS.04.20, que ya incluye correa, el costo es **$50**, pero solo hay 15 piezas.
- **ESTIMACIÓN (comparativo):** el guante ELE-GATE ($22) frente al guante de MayoreoTotal al público ($179) muestra que el sobreprecio de los revendedores nacionales es de ~8×. Sirve como techo de PVP, no como costo.
- **HIPÓTESIS:** el "Tapete para Perro Grande" (MAS.38) podría funcionar como cubreasiento, pero sin fotos de anclaje ni medidas no conviene anunciarlo como "hamaca". El stock de 6 lo vuelve frágil.

### Gaps
- Material, medidas y peso de las camas MAS.15 y MAS.15.6.
- Tallas de las pecheras, salvo la M.
- Proveedor nacional con costo para estos productos (búsquedas en ELE-GATE con 0 resultados, sin otra fuente con precio):
  - comedero elevado ajustable;
  - tapete atrapa-arena;
  - protector anti-rasguños;
  - pañal lavable;
  - saco térmico.

## 3. Hogar (9–16): proveedor, precio por nivel, stock, MOQ, envío directo y specs

### Takeaway
Hay costo verificado y stock profundo para **cajas apilables de zapatos** (6 piezas por $100–$210, con 500–1000+ en bodega). Hay costo parcial para **cajas plegables (set de 2, $70)** y un **organizador de 2 niveles** genérico ($150). Para burlete, bolsas al vacío, ganchos de terciopelo, protector de colchón y la base para garrafón solo existen **precios al público** (MayoreoTotal, Vianney) o nada.

### Cited Findings
**9. Guardapolvo bajo puerta o burlete**
- HECHO: "burlete" y "guardapolvo puerta" dan **0 resultados** en ELE-GATE.
- HECHO (al público, con pago contra entrega): MayoreoTotal "Guardapolvos Cubre Polvos De Puerta - DRO" a **$249**, disponible — [MayoreoTotal guardapolvos](https://mayoreototal.mx/products/guardapolvos-cubre-polvos-de-puerta).

**10. Bolsas al vacío para ropa con bomba**
- HECHO: ELE-GATE solo tiene bolsas de alimentos: "Paquete De 10 Bolsas Selladas Al Vacío… 30cm×20cm" (HOG.78.PP) a $15 en el listado, además de selladoras — [ELE-GATE búsqueda](https://www.ele-gate.com/?s=bolsas+al+vacio&post_type=product).
- HECHO (al público): MayoreoTotal "BOLSA DE SELLADO AL VACIO - DRO" **$149** (tachado $300). No especifica si es para ropa ni si incluye bomba — [MayoreoTotal bolsa vacío](https://mayoreototal.mx/products/bolsa-de-sellado-al-vacio).

**11. Ganchos de terciopelo (50 piezas)**
- HECHO: "ganchos terciopelo" y "terciopelo" no dan ganchos en ELE-GATE. Solo hay "Perchas para Ropa Ajustables… 10 PZS" (HOG.265.3) a $80 en el listado, que no son de terciopelo.
- HECHO (al público): MayoreoTotal vende:
  - "50 Ganchos Percha Para Ropa aterciopelad - DRO" **$399** (tachado $599);
  - "Ganchos de Terciopelo Member's Mark Gris 50 pzas - ZK" **$359**.
  - Fuentes: [MayoreoTotal 50 ganchos](https://mayoreototal.mx/products/50-ganchos-percha-para-ropa-aterciopelad), [MayoreoTotal Member's Mark](https://mayoreototal.mx/products/ganchos-de-terciopelo-members-mark-gris-50-pzas).

**12. Cajas apilables para zapatos (ELE-GATE)**
- HECHO: **"Cajas Organizadoras De Zapatos Apilables Almacenaje 6 piezas Model:S"** (HOG.124.Sx6), 31 × 20 × 12 cm.
  - Precio: **1–9 $100; 10–49 $90; 50–99 $80; 100+ $75**.
  - Existencias: **Bodega 1000+**, U19 6, U14 66, Ejecentral32 30, Ecommerce 200+.
  - Fuente: [ELE-GATE HOG.124.Sx6](https://www.ele-gate.com/producto/hog-124-cajas-organizadoras-de-zapatos-apilables-almacenaje-6-piezas-models/).
- HECHO: **"… 6 piezas Model:L"** (HOG.124.Lx6), 32 × 22.5 × 14 cm.
  - Precio: **1–9 $110; 10–49 $100; 50–99 $90; 100+ $80**.
  - Existencias: Bodega 1000+, U14 14, Ejecentral32 29, Ecommerce 98.
  - Fuente: [ELE-GATE HOG.124.Lx6](https://www.ele-gate.com/producto/cajas-organizadoras-de-zapatos-apilables-almacenaje-6-piezas-2/).
- HECHO: **"Kit de 6 piezas Cajas Organizadoras De Zapatos Apilables"** (HOG.125×6), 23 × 33 × 13 cm.
  - Precio: **1–9 $210; 10–49 $190; 50–99 $180; 100+ $170**.
  - Existencias: Bodega 500+, U14 25, Ejecentral32 31, Ecommerce 33.
  - Fuente: [ELE-GATE HOG.125x6](https://www.ele-gate.com/producto/cajas-organizadoras-de-zapatos-apilables-almacenaje-6-piezas/).
- HECHO: **"3 PZS Caja de Zapatos Apilable Transparente"** (HOG.224.L), plástico transparente, 17.5 × 26.5 × 33 cm.
  - Precio: **1–4 $260; 5–9 $250; 10–19 $240; 20+ $230**.
  - Existencias: Bodega 100+, U19 10, U14 27, Ejecentral32 3, Ecommerce 6.
  - Fuente: [ELE-GATE HOG.224.L](https://www.ele-gate.com/producto/3-pzs-caja-de-zapatos-apilable-transparente-tu-coleccion-en-orden/).
- Bandera roja: HOG.124 y HOG.125 comparten el mismo texto de descripción ("La puerta y los dos lados… transparentes"), así que no queda clara la diferencia física entre modelos. Ninguno publica peso.
- HECHO (al público): MayoreoTotal "20 piezas de caja zapatera organizador - DRO" **$949** — [MayoreoTotal](https://mayoreototal.mx/products/20-piezas-de-caja-zapatera-organizador).

**13. Cajas organizadoras de tela con tapa**
- HECHO: ELE-GATE **"Caja Organizadora Set de 2 Piezas Colapsable y con Colores Solidos"** (HOG.1026).
  - Precio: **1–9 $70; 10–49 $60; 50–99 $55; 100+ $50**.
  - Existencias: Ecommerce 71.
  - La descripción es genérica: **no indica tela, tapa ni medidas**.
  - Fuente: [ELE-GATE HOG.1026](https://www.ele-gate.com/producto/caja-organizadora-set-de-2-piezas-colapsable-y-con-colores-solidos/).
- HECHO (al público): Vianney "Caja Valladolid" (accesorio de clóset) a $105 — [Vianney](https://vianney.com.mx/products/accesorio-closet-caja-valladolid).

**14. Protector de colchón impermeable**
- HECHO: "protector colchon" da **0 resultados** en ELE-GATE.
- HECHO (fabricante nacional, precio al público): Vianney **"Protector De Colchón Impermeable"**.
  - Precio: **Individual $419; Matrimonial $449; Queen $569; King $669**.
  - Todas las tallas disponibles.
  - Fuente: [Vianney protector impermeable](https://vianney.com.mx/products/protector-de-colchon-impermeable).
- HECHO: Vianney "Protector de Colchón Básico Plus" ("tratamiento que repele líquidos", cubre colchones de hasta 40 cm) tiene los mismos precios por talla — [Vianney Básico Plus](https://vianney.com.mx/products/protector-de-colchon-basico-plus).

**15. Carrito o base inclinable para garrafón**
- HECHO: "garrafon", "base garrafon", "dispensador garrafon", "garrafa" y "carrito" solo devuelven bombas eléctricas de garrafón:
  - CON.58 $30;
  - CON.58.B $45;
  - CON.WL001 $70;
  - CON.124 $120.
  - Fuente: [ELE-GATE búsqueda garrafon](https://www.ele-gate.com/?s=garrafon&post_type=product).
- **No disponible.**

**16. Organizador bajo tarja de 2 niveles**
- HECHO: "bajo tarja" y "organizador fregadero" dan **0 resultados**. Lo más cercano es **"Organizador De Estante Smart Design"** (HOG.JL7079): "crea dos niveles de almacenamiento… gabinetes", pintura en polvo anticorrosión.
  - Precio: **1–2 $150; 3–4 $130; 5–19 $120; 20+ $110**.
  - Existencias: 38 (U19).
  - Medidas no publicadas, y no se anuncia como bajo tarja.
  - Fuente: [ELE-GATE HOG.JL7079](https://www.ele-gate.com/producto/organizador-de-estante-smart-design/).
- HECHO: "Organizador de Malla Metálica" (HOG.JL7076) es un especiero de 3 niveles de 28 × 25 × 11.9 cm, no apto para bajo tarja.
  - Precio: 1–9 $90 → 100+ $75.
  - Existencias: Bodega 500+.
  - Fuente: [ELE-GATE HOG.JL7076](https://www.ele-gate.com/producto/organizador-de-malla-metalica-para-almacenamiento-de-cocina/).

### Inferences
- **ESTIMACIÓN:** las cajas de zapatos son el producto de hogar con la cadena de abasto más sólida (costo de $100 por 6 piezas, es decir **≈$16.7 por caja**, y más de 1000 en bodega). Su volumen es alto, así que el flete puede pesar más que el producto. Falta el peso.
- Para burlete, ganchos, bolsas al vacío y tendedero (ver la sección 4), los precios de MayoreoTotal ($249–$399) sirven como **techo de PVP de la competencia nacional**, no como costo.

### Gaps
- Peso y volumen empacado de las cajas de zapatos.
- Si HOG.1026 es de tela y tiene tapa.
- Medidas de HOG.JL7079.
- Costo de proveedor para estos productos: burlete, bolsas al vacío para ropa, ganchos de terciopelo, protector de colchón y base para garrafón. **No disponible.**

## 4. Limpieza (17–20): proveedor, precio por nivel, stock y specs

### Takeaway
**Ninguno de los cuatro productos tiene costo de proveedor nacional verificado.** ELE-GATE no vende tendedero retráctil, escoba de silicón, spray mop ni cintas antiderrapantes o selladoras. Solo hay precios al público en MayoreoTotal.

### Cited Findings
**17. Tendedero retráctil de pared**
- HECHO: ELE-GATE "tendedero", "tendedero retractil" y "secador ropa" devuelven solo canastas para pinzas ($17) — [ELE-GATE búsqueda](https://www.ele-gate.com/?s=tendedero&post_type=product).
- HECHO (MayoreoTotal, precio al público):
  - "Tendedero Retractil, 2.8 m - DRO" **$269** (tachado $450);
  - "TENDEDERO DE ROPA RETRÁCTIL - DRO" $399 (tachado $599);
  - "TENDEDERO RETRACTIL DE 4 CUERDAS - DRO" $399.
  - Fuentes: [MayoreoTotal 2.8 m](https://mayoreototal.mx/products/tendedero-retractil-2-8-m), [MayoreoTotal 4 cuerdas](https://mayoreototal.mx/products/tendedero-retractil-de-4-cuerdas).

**18. Escoba de goma o silicón**
- HECHO: ELE-GATE "escoba silicon", "escoba goma" y "silicon" no la tienen. "escoba" devuelve aspiradoras y robots.
- HECHO (al público): MayoreoTotal "TRAPERO DE GOMA MOP - DRO" $349 (tachado $499). No se comprobó que sea la escoba de cerdas de silicón — [MayoreoTotal](https://mayoreototal.mx/products/trapero-de-goma-mop).
- **No disponible.**

**19. Trapeador con atomizador (spray mop)**
- HECHO: ELE-GATE "trapeador", "mop", "mop spray" y "trapeador giratorio" solo devuelven robots y aspiradoras.
- HECHO (al público): MayoreoTotal vende:
  - "TRAPEADOR SPRAY CON MICROFRIBRA - BGP" **$807**;
  - "Trapeador giratorio de 360° - DRO" $599.
  - Fuente: [MayoreoTotal spray](https://mayoreototal.mx/products/trapeador-spray-con-microfribra).

**20. Cinta antiderrapante y cinta selladora para tarja o baño**
- HECHO: ELE-GATE solo tiene:
  - "Cinta Nano Gel Transparente Doble Cara 3 m × 1 cm" (CINTA.02) a $13;
  - "… 5 m × 1 cm" (CINTA.03) a $21;
  - cinta de empaque.
  - No tiene cinta antiderrapante ni selladora — [ELE-GATE búsqueda cinta](https://www.ele-gate.com/?s=cinta&post_type=product).
- HECHO (al público): MayoreoTotal "Cinta Adhesiva Selladora Impermeable - DRO" **$399** — [MayoreoTotal](https://mayoreototal.mx/products/cinta-adhesiva-selladora-impermeable).
- MayoreoTotal también lista "TS antiderrapante - DRO" a $399, pero el título no deja claro qué producto es.

### Inferences
- **HIPÓTESIS:** los precios al público de MayoreoTotal en estos productos ($269–$807) sugieren que el PVP en Marketplace tiene margen si se encuentra un costo de mayoreo en importadoras del Centro. Sin ese costo, **no se puede calcular el margen**.

### Gaps
- Costo de proveedor nacional para los 4 productos: **No disponible**.
- Specs (longitud, material, peso) de los productos de MayoreoTotal: sus fichas JSON no traen peso real.

## 5. Auto/moto (21–25): proveedor, precio por nivel, stock y specs

### Takeaway
El **impermeable de 2 piezas** tiene costo verificado en ELE-GATE ($165 negro reflectivo y $185 fosforescente, con más de 200 en bodega). Para mochila térmica de repartidor, cubre puños y organizador de respaldo **no hay costo nacional**. El organizador de cajuela solo tiene precio al público (Vianney $269).

### Cited Findings
**21. Mochila térmica para repartidor**
- HECHO: ELE-GATE "mochila termica", "mochila repartidor", "bolsa termica", "hielera" y "termica" solo devuelven loncheras. La más cercana es "Lonchera Térmica 23 × 13 × 21 cm" (HOG.120) a $30, que **no es mochila de reparto** — [ELE-GATE búsqueda lonchera](https://www.ele-gate.com/?s=lonchera&post_type=product).
- HECHO (al público): MayoreoTotal "BOLSA TERMICA AISLANTE PLEGABLE - DRO" **$349**, sin medidas en la ficha — [MayoreoTotal](https://mayoreototal.mx/products/bolsa-termica-aislante-plegable).
- Directorio sin precio: un listado describe a "Miguel Petacas" (Centro CDMX) como fabricante de mochilas de reparto expandibles con precio de mayoreo, pero no publica cifras — [Directorio de Fábricas](https://www.directoriodefabricas.com/mexico/fabricas/mochilas_miguelpetacas.html). Llegó vía buscador y no se abrió.

**22. Traje o impermeable de 2 piezas para motociclista**
- HECHO: **"Impermeable de 2 Piezas con Visera y Bandas Reflectivas"** (HOG.311). Chaqueta con visera y pantalón, tela impermeable, botones de presión reforzados, negro con bandas reflectivas.
  - Precio: **1–9 $165; 10–49 $155; 50–99 $145; 100+ $135**.
  - Existencias: quedan 33 (U14 21, Ejecentral32 1, Ecommerce 11).
  - Fuente: [ELE-GATE HOG.311](https://www.ele-gate.com/producto/impermeable-de-2-piezas-con-visera-y-bandas-reflectivas/).
- HECHO: **"Impermeable de 2 Piezas con Visera Color Fosforescente"** (HOG.310).
  - Precio: **1–9 $185; 10–49 $175; 50–99 $165; 100+ $155**.
  - Existencias: **Bodega 200+**, U19 45, U14 73, Ejecentral32 17, Ecommerce 31.
  - Fuente: [ELE-GATE HOG.310](https://www.ele-gate.com/producto/impermeable-de-2-piezas-con-visera-color-fosforescente/).
- Bandera roja: ninguna de las dos fichas menciona **tallas** ni peso.
- HECHO (relacionado): "Cubierta Impermeable Para… Motocicleta" (HOG.160).
  - Precio: 1–9 $120 → 100+ $85.
  - Existencias: **solo 2**.
  - Fuente: [ELE-GATE HOG.160](https://www.ele-gate.com/producto/cubierta-impermeable-para-la-lluvia-para-motocicleta-o-moto/).

**23. Cubre puños o manoplas térmicas para moto**
- HECHO: "cubre puños", "manoplas", "guantes moto" y "manubrio" dan 0 resultados relevantes en ELE-GATE. MayoreoTotal no los tiene.
- **No disponible.**

**24. Organizador plegable para cajuela**
- HECHO: ELE-GATE "organizador cajuela" y "cajuela" no lo tienen.
- HECHO (fabricante o distribuidor nacional, precio al público): Vianney **"Organizador De Cajuela"** a **$269**, unitalla, "4 compartimentos expandibles, resistente y acabado impermeable… correas ajustables y soporte antideslizante", disponible — [Vianney](https://vianney.com.mx/products/organizador-multiusos-organizador-de-cajuela).
- HECHO previo (en `auto_moto.md`): kits en ML de 5 piezas a $900 ($180 c/u) y de 20 piezas a $3,200 ($160 c/u).

**25. Organizador de respaldo de asiento**
- HECHO: ELE-GATE no lo tiene. Lo único parecido es "Par de Rellenos de Espacio para Asiento de Coche con Organizador" (HOG.337), de cuero PU, que se coloca entre asiento y consola: **otro producto**.
  - Precio: 1–9 $40; 10–49 $36; 50–99 $33; 100+ $30.
  - Existencias: 25.
  - Fuente: [ELE-GATE HOG.337](https://www.ele-gate.com/producto/par-de-rellenos-de-espacio-para-asiento-de-coche-con-organizador-universal-para-auto-suv-y-camion-color-cafe/).
- **No disponible.**

### Inferences
- **ESTIMACIÓN:** el impermeable HOG.310 a $185 (1–9) tiene stock profundo para un pico estacional. El HOG.311 ($165) tiene solo 33 piezas. Hoy (22-oct) es fin de temporada de lluvias, así que el producto aplica para venta de abril a septiembre de 2027 o como remate (coincide con `auto_moto.md`).

### Gaps
- Tallas y peso de los impermeables de ELE-GATE.
- Costo nacional de mochila térmica, cubre puños, organizador de respaldo y organizador de cajuela. Del organizador de cajuela solo hay precio al público.

## 6. Negocios (26–30): proveedor, precio por nivel, mínimo y envío

### Takeaway
Para NFC y QR, placas QR, sellos y mandiles bordados **no se encontró ningún taller o proveedor nacional con precio público por pieza**: todos piden cotización. La excepción parcial son las **bolsas de envío**: ELE-GATE vende poly mailers lisos (100 piezas por $55) y bolsas "con impresión total" de diseño de stock. No se verificó impresión con el logo del cliente.

### Cited Findings
**26. Placa o tarjeta NFC + QR para reseñas, o tags NTAG213/215**
- HECHO: ELE-GATE "nfc" y "tarjeta nfc" solo devuelven escáneres y celulares.
- Steren redirige "nfc" a "3 tarjetas de bloqueo RFID/NFC" ($99, IVA incluido), que no son tags — [Steren](https://www.steren.com.mx/tarjeta-de-bloqueo-rfid-nfc.html).
- UNIT Electronics (uelectronics.com) responde 403, y 330ohms no muestra resultados.
- Las referencias que dio el buscador son **extranjeras** y quedan fuera de alcance: GoToTags (EE. UU.) a US$0.35–0.48 por tarjeta NTAG215 — [GoToTags](https://store.gototags.com/nfc-pvc-card-ntag215/).
- **No disponible.**

**27. Placa QR para cobros (acrílico o PVC)**
- HECHO: ELE-GATE "acrilico" y "qr" solo devuelven escáneres y lámparas. El buscador solo devolvió listados de Brasil.
- **No disponible.**

**28. Sello autoentintable personalizado**
- HECHO: Cosmos lista fabricantes con precio solo por cotización, entre ellos "Fábrica de Sellos de Goma Rino" (Av. Gustavo Baz 402 D, Tlalnepantla) — [Cosmos sellos](https://www.cosmos.com.mx/producto/sellos-de-goma-autoentintables-personalizados-de-uso-rudo-8rtl/).
- HECHO: Office Depot MX solo vende sellos **genéricos pre-entintados** ("Pagado", "Recibido"…), no personalizados, a $104.30–$111.75 (lista $149), marcados como "Agotado" — [Office Depot búsqueda](https://www.officedepot.com.mx/officedepot/en/search/?text=sello+autoentintable).
- Referencia **no verificada** (resumen del buscador sobre ML): sello Trodat personalizado de 7 × 2.5 cm a $414.90 y de 70 × 30 mm a $420 — [ML Trodat 4924](https://listado.mercadolibre.com.mx/sellos-trodat-4924).
- **No disponible** como costo verificado.

**29. Mandil o delantal con bordado o sublimado**
- HECHO: Cosmos lista proveedores de mandiles bordados (p. ej., Bordados Marún en CDMX, "menudeo y mayoreo"), sin precio publicado — [Cosmos mandil con logo](https://www.cosmos.com.mx/producto/mandil-3lwb/mandil-con-logo-3lwd/).
- HECHO (al público, **sin bordado**): Vianney "Mandil Ibiza" $219 (estampado) y "Mandil Kaki" $389 — [Vianney Mandil Ibiza](https://vianney.com.mx/products/mandil-ibiza).
- ELE-GATE: "mandil" y "delantal" dan **0 resultados**.
- **No disponible** con bordado.

**30. Bolsas de envío (poly mailers) impresas con logo**
- HECHO: ELE-GATE **"Bolsas PolyMailer para Envíos 20 x 30 cm, Paquete de 100"** (BOLSA.ENVIO20X30), polietileno blanco opaco con solapa adhesiva.
  - Precio: **1–9 $55; 10–49 $50; 50–99 $45; 100+ $40** por paquete de 100.
  - Existencias: U19 100+, Ecommerce 100+.
  - Fuente: [ELE-GATE BOLSA.ENVIO20X30](https://www.ele-gate.com/producto/paquete-de-100pzs-de-bolsas-sobre-polymailer-para-envios-de-paqueteria-de-20-x-30-cm/).
  - El listado también muestra 25 × 35 cm ×100 a $70, 35 × 55 cm ×100 a $150 y 50 × 60 cm ×100 a $220 — [ELE-GATE búsqueda](https://www.ele-gate.com/?s=bolsa+envio&post_type=product).
- HECHO: **"Bolsas de Envío con Impresión Total – Tamaño 26.5X33cm"** (BOLSA.ENVIO26.5X33). PE virgen de 13 micras por cara y solapa adhesiva; "Impresión a todo color… ideal para logotipo, marca o diseño personalizado".
  - Precio: **1–9 $160; 10–49 $150; 50–99 $140; 100+ $130**.
  - Existencias: Bodega 500+, Ecommerce 200+.
  - Fuente: [ELE-GATE BOLSA.ENVIO26.5X33](https://www.ele-gate.com/producto/bolsas-de-envio-con-impresion-total-tamano-26-5x33cm/).
- HECHO: versión 20 × 26 cm (BOLSA.ENVIO20X30P).
  - Precio: **1–9 $100; 10–49 $95; 50–99 $90; 100+ $85**.
  - Peso: 0.6 kg.
  - Existencias: Ecommerce 500+.
  - Fuente: [ELE-GATE BOLSA.ENVIO20X30P](https://www.ele-gate.com/producto/embalaje-inflable-rollo-de-bolsas-de-aire-40-x-30-cm/).
- Bandera roja: las fichas **no dicen cuántas bolsas trae cada paquete** ni ofrecen impresión del logo del cliente. "Impresión total" parece un diseño de stock (HIPÓTESIS).
- HECHO: Bolsof, fabricante mexicano listado en Cosmos, publica "Bolsa para e-commerce con cierre" a "$20 MXN*", con mínimo de venta "Ciento" e "Impresa de acuerdo a cantidad". El precio es orientativo y la ficha no aclara si es por pieza o por ciento — [Cosmos Bolsof](https://www.cosmos.com.mx/producto/bolsa-para-e-commerce-m3bs/bolsa-para-e-commerce-con-cierre-g7p1e444d.html).

### Inferences
- **ESTIMACIÓN:** el poly mailer liso de ELE-GATE cuesta **$0.55 por bolsa** ($55 ÷ 100) en el nivel 1–9. Es un insumo de empaque útil para todo el negocio, no un producto para revender.
- **HIPÓTESIS:** los productos 26–29 solo funcionan como servicio "bajo pedido con taller local". Su costo hay que cotizarlo por WhatsApp, lo que el encargo no permite. Ningún costo de estos cuatro debe entrar al cálculo de margen sin cotización.

### Gaps
- Costo nacional verificado de:
  - tags NFC;
  - placa NFC/QR;
  - placa QR acrílica;
  - sello personalizado;
  - mandil bordado;
  - poly mailer con logo del cliente (mínimo y precio por pieza).
- Piezas por paquete de las bolsas "con impresión total" de ELE-GATE.

## 7. Emergentes (31–32): proveedor y precio

### Takeaway
La **cortina blackout** solo tiene precio al público de un fabricante nacional (Vianney, $569–$669 por variante corta o larga). El **bidón plegable con llave** no tiene proveedor nacional con precio (**No disponible**), lo que confirma lo que ya decían las notas previas.

### Cited Findings
**31. Cortina blackout**
- HECHO: ELE-GATE "blackout" y "cortina termica" dan **0 resultados**.
- HECHO (Vianney, precio al público): **"Cortinas Blackout Catania"** en Beige, Celeste y Marino.
  - Precio: **CORTA $569; LARGA $669**.
  - "Cubren hasta el 90% de la luz", disponibles.
  - Fuente: [Vianney Catania Beige](https://vianney.com.mx/products/cortinas-blackout-catania-beige).
- HECHO: "Cortinas Blackout Ravenna Marfil" a $1,199 — [Vianney Ravenna](https://vianney.com.mx/products/cortinas-blackout-ravenna-marfil).
- Las fichas no dicen si el precio es por panel o por par, ni las medidas.

**32. Bidón o contenedor plegable de agua con llave (10–20 L)**
- HECHO: ELE-GATE "bidon", "bidon plegable", "contenedor plegable" y "garrafa" dan 0 resultados relevantes.
- Las búsquedas web solo devolvieron bidones **rígidos** industriales (Multiplastic, Veracruz, EXW, sin precio).
- **No disponible.**

### Inferences
- **HIPÓTESIS:** para la cortina, Vianney actúa como competidor o techo de PVP y no como proveedor dropship. No hay evidencia de un programa de mayoreo público.

### Gaps
- Si el precio de Vianney es por panel o por par, y las medidas.
- Proveedor nacional de bidón plegable.

## 8. Tabla consolidada de costos para calcular margen de contribución

### Takeaway
De 32 productos:
- **7 tienen costo de proveedor nacional con niveles, stock y envío directo verificados** (todos en ELE-GATE): #5, #7, #12, #13 (parcial), #16 (parcial), #22 y #30 (sin logo).
- **3 tienen solo un sustituto con costo en ELE-GATE**: #1 (platos de acero no elevados), #3 (tapete para auto, 6 piezas) y #8 (guante en vez de rodillo).
- **10 solo tienen precio al público** de revendedores o fabricantes nacionales: #9, #10, #11, #14, #17, #19, #20, #21, #24 y #31.
- **12 quedan como No disponible**: #2, #4, #6, #15, #18, #23, #25, #26, #27, #28, #29 y #32.
- Ningún precio de ELE-GATE indica si incluye IVA, y ninguno incluye flete.

### Cited Findings
Todas las URL se consultaron el 2026-10-22.
- **Leyenda de envío directo.** "Sí (dropship)" = programa de dropshipping de ELE-GATE; el paquete lleva la marca ELE-GATE y el flete no está publicado.
- **Leyenda de MOQ.** MOQ 1 = el primer nivel de precio empieza en 1 pieza.
- **Precio al público.** Los precios de MayoreoTotal y Vianney son de venta al público y **no son costo**.

| # | Producto | Proveedor 1 (precio por nivel; stock; MOQ; envío directo; URL) | Proveedor 2 | Peso | Observaciones |
|---|---|---|---|---|---|
| 1 | Comedero elevado ajustable 2 platos inox | **No disponible** (elevado). Sustituto ELE-GATE MAS.06.S, juego de 2 platos inox antideslizantes Talla S: 1–9 $50 / 10–49 $46 / 50–99 $42 / 100+ $38. Stock U19 83, U14 51, EC32 74, Ecom 41. MOQ 1. Sí (dropship). [URL](https://www.ele-gate.com/producto/platon-para-mascotas-de-acero-inoxidable-antideslizantes-para-perros-y-gatos-talla-s/) | ELE-GATE MAS.06.2, comedero y bebedero doble: $155 / $145 / $135 / $125. Stock 28. [URL](https://www.ele-gate.com/producto/dispensador-doble-comedero-y-bebedero-para-mascotas/) | No publicado | No es elevado ni ajustable. MAS.06.2 no tiene descripción ni material |
| 2 | Tapete atrapa-arena doble capa | **No disponible** | No disponible | — | ELE-GATE solo tiene arenero (MAS.11, $100) |
| 3 | Hamaca o cubreasiento de auto para perro | ELE-GATE MAS.38, "Tapete para Perro Grande Impermeable Acolchonado… con Agarradera" (para coche): $299 / $280 / $260 / $240. **Stock 6**. MOQ 1. Sí (dropship). [URL](https://www.ele-gate.com/producto/tapete-para-perro-grande-impermeable-acolchonado-y-resistente-con-agarradera/) | ML "Mayoristas Mex" $143 (en `auto_moto.md`; sin escalas) | No publicado | No confirma formato hamaca ni anclajes. Stock frágil |
| 4 | Protector anti-rasguños sofá (gato) | **No disponible** | No disponible | — | ELE-GATE solo tiene rascadores ($60–$210) |
| 5 | Cama tipo cueva o iglú para gato | ELE-GATE MAS.15, "Cama Tipo Iglú para Gato": 1–9 $145 / 10–49 $135 / 50–99 $125 / 100+ $115. Stock Bodega 36, U19 43, U14 3, EC32 20, Ecom 46. MOQ 1. Sí (dropship). [URL](https://www.ele-gate.com/producto/cama-tipo-iglu-gato/) | ELE-GATE MAS.15.6, "Cama Tipo Casa 41×41×23 cm": $160 / $150 / $140 / $130. Bodega 100+, Ecom 56. [URL](https://www.ele-gate.com/producto/cama-para-mascota-casa-cubierta-cerrada-interior/) | No publicado. Medidas 41×41×23 cm (MAS.15.6) | Material no publicado. Saco térmico: No disponible |
| 6 | Pañales o calzones lavables para perro | **No disponible** | No disponible | — | Ni ELE-GATE ni MayoreoTotal |
| 7 | Pechera antijalones con correa | ELE-GATE MAS.04.20, arnés reflectante con clip de pecho antitirones + correa: $50 / $40 / $35 / $30. **Stock 15**. MOQ 1. Sí (dropship). [URL](https://www.ele-gate.com/producto/conjunto-de-arnes-de-nailon-reflectante-y-correa-para-perros-comodidad-y-control-para-tus-paseos/) | ELE-GATE MAS.04, pechera poliéster acolchada (M): $60 / $45 / $40 / $35, U14 100+, EC32 73 ([URL](https://www.ele-gate.com/producto/pechera-arnes-para-perro-mascota-ajustable/)); + correa antitirones MAS.04.13: $35 / $28 / $25 / $21 ([URL](https://www.ele-gate.com/producto/correa-resistente-y-antitirones-para-perros-medianos-y-grandes-paseos-seguros-y-comodos/)) | No publicado | ESTIMACIÓN del kit MAS.04 + MAS.04.13 = $95 (1–9). Tallas no detalladas |
| 8 | Rodillo o cepillo quitapelo reutilizable | ELE-GATE MAS.10.2, guante antiestático reutilizable 20×15 cm: $22 / $20 / $18 / $16. Stock 200+ en varias sucursales. MOQ 1. Sí (dropship). [URL](https://www.ele-gate.com/producto/guante-antiestatico-quita-pelo-de-mascotas-reutilizable-20-x-15-cm/) | MayoreoTotal "Rodillo adhesivo para pelusas y pelos" **$199 al público** (pago contra entrega). [URL](https://mayoreototal.mx/products/rodillo-adhesivo-para-pelusas-y-pelos) | 21×16×0.5 cm (guante); peso no publicado | No hay rodillo reutilizable con costo. El guante es un sustituto |
| 9 | Guardapolvo o burlete de puerta | **No disponible** (costo) | MayoreoTotal "Guardapolvos Cubre Polvos De Puerta" **$249 al público**. [URL](https://mayoreototal.mx/products/guardapolvos-cubre-polvos-de-puerta) | No publicado | Solo techo de PVP |
| 10 | Bolsas al vacío para ropa + bomba (jumbo) | **No disponible** (costo) | MayoreoTotal "Bolsa de sellado al vacío" **$149 al público**; no especifica ropa ni bomba. [URL](https://mayoreototal.mx/products/bolsa-de-sellado-al-vacio) | No publicado | ELE-GATE solo tiene bolsas de alimentos |
| 11 | Ganchos de terciopelo (50) | **No disponible** (costo) | MayoreoTotal "50 Ganchos… aterciopelados" **$399** y Member's Mark 50 pzas **$359**, ambos al público. [URL](https://mayoreototal.mx/products/50-ganchos-percha-para-ropa-aterciopelad) | No publicado | Solo techo de PVP |
| 12 | Cajas apilables para zapatos | ELE-GATE HOG.124.Sx6, 6 pzs de 31×20×12 cm: $100 / $90 / $80 / $75. **Bodega 1000+**, Ecom 200+. MOQ 1. Sí (dropship). [URL](https://www.ele-gate.com/producto/hog-124-cajas-organizadoras-de-zapatos-apilables-almacenaje-6-piezas-models/) | ELE-GATE HOG.124.Lx6, 6 pzs de 32×22.5×14 cm: $110 / $100 / $90 / $80 ([URL](https://www.ele-gate.com/producto/cajas-organizadoras-de-zapatos-apilables-almacenaje-6-piezas-2/)); HOG.125×6: $210–$170; HOG.224.L, 3 pzs: $260–$230 | No publicado. Medidas por caja en la ficha | Mejor abasto del lote. Voluminoso, así que el flete puede pesar. Descripciones repetidas entre modelos |
| 13 | Cajas organizadoras de tela con tapa | ELE-GATE HOG.1026, "Caja Organizadora Set de 2 Piezas Colapsable": $70 / $60 / $55 / $50. Ecom 71. MOQ 1. Sí (dropship). [URL](https://www.ele-gate.com/producto/caja-organizadora-set-de-2-piezas-colapsable-y-con-colores-solidos/) | Vianney "Caja Valladolid" **$105 al público**. [URL](https://vianney.com.mx/products/accesorio-closet-caja-valladolid) | No publicado | No se confirma tela, tapa ni medidas |
| 14 | Protector de colchón impermeable | **No disponible** (costo) | Vianney "Protector De Colchón Impermeable", **al público**: Ind $419 / Mat $449 / Queen $569 / King $669. [URL](https://vianney.com.mx/products/protector-de-colchon-impermeable) | No publicado | Fabricante nacional, sin precio mayorista público |
| 15 | Carrito o base inclinable para garrafón 20 L | **No disponible** | No disponible | — | ELE-GATE solo tiene bombas eléctricas ($30–$120) |
| 16 | Organizador bajo tarja 2 niveles | ELE-GATE HOG.JL7079, "Organizador De Estante Smart Design" (2 niveles, gabinetes): 1–2 $150 / 3–4 $130 / 5–19 $120 / 20+ $110. Stock 38. MOQ 1. Sí (dropship). [URL](https://www.ele-gate.com/producto/organizador-de-estante-smart-design/) | No disponible | No publicado | No se anuncia como bajo tarja. Sin medidas |
| 17 | Tendedero retráctil de pared | **No disponible** (costo) | MayoreoTotal "Tendedero Retractil, 2.8 m" **$269 al público** (tachado $450); el de 4 cuerdas $399. [URL](https://mayoreototal.mx/products/tendedero-retractil-2-8-m) | No publicado | Solo techo de PVP |
| 18 | Escoba de goma o silicón | **No disponible** | MayoreoTotal "Trapero de goma mop" $349 al público (no confirmado como el mismo producto) | — | — |
| 19 | Trapeador con atomizador (spray mop) | **No disponible** (costo) | MayoreoTotal "Trapeador spray con microfibra" **$807 al público**. [URL](https://mayoreototal.mx/products/trapeador-spray-con-microfribra) | No publicado | Solo techo de PVP |
| 20 | Cinta antiderrapante y cinta selladora | **No disponible** (costo) | MayoreoTotal "Cinta Adhesiva Selladora Impermeable" **$399 al público**. [URL](https://mayoreototal.mx/products/cinta-adhesiva-selladora-impermeable) | No publicado | Cinta antiderrapante: No disponible |
| 21 | Mochila térmica para repartidor | **No disponible** (costo) | MayoreoTotal "Bolsa térmica aislante plegable" **$349 al público**. [URL](https://mayoreototal.mx/products/bolsa-termica-aislante-plegable) | No publicado | Fabricante en el Centro (Miguel Petacas) sin precio público |
| 22 | Impermeable de 2 piezas para moto | ELE-GATE HOG.310, fosforescente con visera y bandas reflectivas: 1–9 $185 / 10–49 $175 / 50–99 $165 / 100+ $155. **Bodega 200+**, U19 45, U14 73, Ecom 31. MOQ 1. Sí (dropship). [URL](https://www.ele-gate.com/producto/impermeable-de-2-piezas-con-visera-color-fosforescente/) | ELE-GATE HOG.311, negro reflectivo: $165 / $155 / $145 / $135. Stock 33. [URL](https://www.ele-gate.com/producto/impermeable-de-2-piezas-con-visera-y-bandas-reflectivas/) | No publicado | Sin tallas ni peso. Fuera de temporada de lluvias |
| 23 | Cubre puños o manoplas térmicas para moto | **No disponible** | No disponible | — | — |
| 24 | Organizador plegable para cajuela | **No disponible** (costo) | Vianney "Organizador De Cajuela" **$269 al público** (4 compartimentos expandibles, impermeable). [URL](https://vianney.com.mx/products/organizador-multiusos-organizador-de-cajuela) | No publicado | `auto_moto.md`: kits ML 5 pzs $900 ($180 c/u) |
| 25 | Organizador de respaldo de asiento | **No disponible** | ELE-GATE HOG.337, relleno de hueco con organizador (otro producto): $40 / $36 / $33 / $30. Stock 25 | — | No es organizador de respaldo |
| 26 | Placa NFC + QR para reseñas o tags NTAG | **No disponible** | No disponible | — | uelectronics 403. Solo referencias extranjeras (fuera de alcance) |
| 27 | Placa QR para cobros (acrílico o PVC) | **No disponible** | No disponible | — | Sin talleres con precio público |
| 28 | Sello autoentintable con logo | **No disponible** (solo por cotización: Sellos Rino, Tlalnepantla, en Cosmos) | Office Depot: solo sellos genéricos $104–$112, agotados | — | Referencia ML no verificada: ~$415–$420 al público |
| 29 | Mandil con bordado o sublimado | **No disponible** (cotización: Bordados Marún CDMX y otros, en Cosmos) | Vianney mandil **sin bordado** $219–$389 al público | — | — |
| 30 | Poly mailers impresos con logo | ELE-GATE BOLSA.ENVIO26.5X33, "con impresión total" (PE de 13 µm por cara): $160 / $150 / $140 / $130 por paquete. Bodega 500+. MOQ 1. Sí (dropship). [URL](https://www.ele-gate.com/producto/bolsas-de-envio-con-impresion-total-tamano-26-5x33cm/) | ELE-GATE poly mailer liso 20×30 ×100: $55 / $50 / $45 / $40 ([URL](https://www.ele-gate.com/producto/paquete-de-100pzs-de-bolsas-sobre-polymailer-para-envios-de-paqueteria-de-20-x-30-cm/)). Bolsof (Cosmos): "$20*" con mínimo de un ciento, orientativo | 0.6 kg (paquete 20×26) | **Sin impresión del logo del cliente verificada.** Piezas por paquete de las impresas no publicadas |
| 31 | Cortina blackout térmica | **No disponible** (costo) | Vianney "Cortinas Blackout Catania" **al público**: corta $569 / larga $669. [URL](https://vianney.com.mx/products/cortinas-blackout-catania-beige) | No publicado | No se dice si es panel o par |
| 32 | Bidón plegable con llave 10–20 L | **No disponible** | No disponible | — | Solo bidones rígidos industriales |

### Inferences
- **ESTIMACIÓN (margen de contribución):** el escritor debe calcular solo con las filas que tienen costo de ELE-GATE:
  - margen = PVP − costo nivel 1–9 − flete ELE-GATE (no publicado; usar escenario) − comisión o pasarela − empaque;
  - la entrega es gratis en FB Marketplace, sin comisión de Marketplace por venta local, según `costos_canal_marketplace.md`.
- **ESTIMACIÓN (vendedor que empieza):** los niveles 50–99 y 100+ bajan el costo entre 12 % y 42 % según el SKU. Por ejemplo, MAS.04 pasa de $60 a $35 y HOG.311 de $165 a $135. Esos niveles no aplican a un vendedor sin inventario, así que corresponde el **nivel 1–9**.
- **HIPÓTESIS:** las filas con solo "precio al público" (MayoreoTotal y Vianney) sirven para fijar el techo de PVP y la competencia nacional. Si se usaran como costo, el margen sería negativo o nulo.

### Gaps
- IVA incluido en ELE-GATE.
- Flete por SKU.
- Pesos.
- Tallas.
- Piezas por paquete de las bolsas impresas.
- Cotizaciones de los productos de negocios (#26–#29).
- Proveedores para los 13 productos "No disponible". El siguiente paso sería una visita o WhatsApp a importadoras del Centro CDMX y a la calle Río Frío, una zona de accesorios para mascotas, según [Chilango](https://www.chilango.com/agenda/otros/comprar-accesorios-perrhijos-gathijos/), que no se verificó. Esto queda fuera de este encargo, que no permite contactar proveedores.
