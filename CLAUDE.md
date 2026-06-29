# Sitio web Tangente — memoria del proyecto

Café · restaurante · bar. Comida de antojo elevada (smash burgers, pizza-burgers,
birria, brunch, mixología de autor) en espacios arquitectónicos restaurados.
Boutique, editorial, cálido pero sofisticado — NO cadena familiar.

Tono de voz: cálido, juguetón, guiños a "tangente" ("se salió por la tangente",
"sálte por la tangente y pruébalo"). Frase ancla:
> "La vida es como una tangente, que a veces se desvía para llevarte a lo inesperado…"

Texto de marca (Sobre Tangente):
> En Tangente, cada detalle importa. Nuestra prioridad es ofrecer alimentos de la más
> alta calidad y un servicio cálido que te haga sentir bienvenido desde el primer
> momento. Creemos que la buena comida nace del cuidado en cada ingrediente y del amor
> con el que se prepara, por eso cada platillo que llega a tu mesa está hecho con
> dedicación y con el corazón.

## Paleta (variables CSS ya definidas en Tangente.dc.html)
- --crudo  #F2EFEA (fondo dominante)   - --carbon   #1F1D1B (tipografía/logo)
- --oliva  #3A4332 (señalética)        - --dorado   #C99A3E (bebidas/acentos)
- --terracota #B5694A (birria/tocino)  - --azul-pastel #A9C9D9 (campañas)
- --rosa-polvo #E8C4C0 (campañas)
Acento dominante actual: --dorado.

## Tipografía
- Headers/logo: Jost (geométrico fino, sustituto de Century Gothic/Futura)
- Frases evocadoras superpuestas: Parisienne (script)
- Cuerpo: Mulish (sans limpia)
Logo: wordmark "TANGENTE" mayúsculas, tracking amplio, "A" como ángulo de tangente.

## Sucursales
- Tlaquepaque: Calle Progreso 30A, Centro, 45500 San Pedro Tlaquepaque, Jal.
- Acueducto (Zapopan): Av. Acueducto 4550, Lomas del Bosque, 45118 Zapopan, Jal.
- Dúo 24 (Zapopan): Dúo 24 New Living 4255, Av. Adolfo López Mateos Sur, Loma Bonita, 45086 Zapopan, Jal.
- León: Blvd. Juan Alonso de Torres Pte. 2105, Valle del Campestre, 37150 León de los Aldama, Gto.
- Virreyes: próxima apertura.
Instagram: @tangentegdl

## Diferenciadores
- Áreas infantiles con niñera fines de semana 9AM–2PM.
- Consumo cortesía a personas con síndrome de Down (Día Mundial del Síndrome de Down).
- Lealtad: "Cuponera Gastronómica Sé Parte" (con Mariscos Beto y Tacos Wicho).
- Transmisiones de eventos deportivos en vivo.
- Desayunos: 8:00 AM – 2:00 PM. Pizza-burgers (especiales): 2:00 PM al cierre.

## Estructura del sitio
- Entregable principal: `Tangente.dc.html` (Design Component).
- Construido: Hero (#hero) + Sobre Tangente (#sobre-tangente). Anchors libres
  #menu y #sucursales ya cableados en los CTAs para insertar secciones debajo.
- Tweaks del root: accent (dorado/terracota/oliva), scrimStrength, showScrollCue.

## Assets disponibles (fotos reales extraídas de los PDFs del menú)
- assets/hero-tangente.png  = food-pizzaburger-res (en uso en el hero)
- assets/food-pizzaburger-res.png   — corte de res estilo pizza-burger, tabla, luces cálidas
- assets/food-smashburger.png       — smash burger con queso, muro de ladrillo
- assets/food-pizzaburger-pollo.png — pizza-burger pollo/camarón, lámpara cálida
- image-slot.js — placeholders editables (arrastrar fotos reales del feed).

## Datos de menú
Texto completo de los 3 menús (Bebidas, Comida-Cena, Desayunos) con precios:
`data/menu-texto-completo.txt`. PDFs fuente en `uploads/` (copias sin acentos:
menu-bebidas.pdf, menu-comida.pdf, menu-desayunos.pdf).
Nota: el OCR de los PDFs tiene cabeceras corruptas (ej. "BIDAS"=BEBIDAS,
"TRAS"=ENTRADAS, "DTIDOS"=DESTILADOS); los precios/descripciones de platillos
están limpios.
