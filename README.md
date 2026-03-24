# Projecte Web Editorial EditoLine

> Web editorial responsive construïda des de zero amb HTML5 i CSS3 modern, sense JavaScript.  
> Enfocament *Mobile First* · CSS Grid + Flexbox · Tipografia fluida · Microinteraccions pures en CSS

---

## 📌 Encàrrec

Una editorial nova de llibres d'autors novells ens ha encarregat el desenvolupament de la seva web. La web s'ha construït des de zero amb HTML i CSS (sense JavaScript), seguint un enfocament _Mobile First_ i amb disseny completament responsive.

---

## 🔎 Investigació de mercat

### Competidors i referents

Durant la fase prèvia d'anàlisi de la competència i cerca d'inspiració, es van analitzar les webs de: [Blackie Books](https://blackiebooks.org/), [Anagrama](https://www.anagrama-ed.es/), [Alianza Editorial](https://www.alianzaeditorial.es/), [HarperCollins](https://www.harpercollins.com/), [Penguin Random House](https://www.penguinrandomhouse.com/), [Planeta de Libros](https://www.planetadelibros.com/), [Bloomsbury](https://www.bloomsbury.com/us/), [Faber & Faber](https://www.faber.co.uk/), [Cormorant Books](https://www.cormorantbooks.com/), [Quirk Books](https://www.quirkbooks.com/), [Claret](https://www.claret.cat/), [La Central](https://www.lacentral.com/), [Daunt Books](https://dauntbooks.co.uk/), [North Star Editions](https://northstareditions.com/flux/), [Uno Editorial](https://www.unoeditorial.com/), [Elsevier](https://www.elsevier.com/), [Second Story Press](https://secondstorypress.ca/), [London Review Bookshop](https://www.londonreviewbookshop.co.uk/), i diverses plantilles de temes editorials d'Envato Elements.

Consulta la carpeta `README/IDEES/` per a captures de pantalla d'algunes d'aquestes pàgines.

### Estudi de Branding de la marca {Edito}Line

S'ha definit una identitat visual pròpia per a {Edito}Line. Consulta la presentació completa de directrius de marca (logo, colors i tipografia) [aquí](https://docs.google.com/presentation/d/1QFD67kQfMXIyr037F_ZlGRVJmrv9sc8RBKmqBCDWRz0/edit?usp=sharing).

---

## 📋 Pàgines de la web

| Fitxer | Contingut |
|---|---|
| `inici.html` | Pàgina principal: hero, banner promocional, llibres destacats, gèneres, carrusel d'autors, esdeveniments i podcast |
| `llibres.html` | Catàleg complet de llibres, filtrat per gènere (ficció i no-ficció) |
| `autors.html` | Fitxes biogràfiques de tots els autors del catàleg |
| `editorial.html` | Història, missió, valors, procés editorial, equip i xifres clau |
| `contacte.html` | Formulari de contacte, mapa, informació de contacte i FAQ |

---

## 📂 Estructura del projecte

```
├── README.md  
├── README/                     ← Imatges del fitxer .md
│   └── IDEES/                  ← Captures d'inspiració
├── inici.html  
├── llibres.html  
├── autors.html  
├── editorial.html  
├── contacte.html  
├── css/
│   └── style.css 
└── assets/
    ├── audio/                  ← Podcast
    ├── imgs/
    │   ├── llibres/
    │   ├── autors/
    │   └── equip/
    └── videos/
```

---

## 🎯 Objectius del projecte

- Construir una web completament responsive seguint el principi _Mobile First_.
- Aplicar bones pràctiques d'estructura HTML semàntica.
- Utilitzar CSS modern per crear layouts complexos (Grid + Flexbox).
- Implementar microinteraccions i animacions visuals amb CSS pur.
- Mantenir un codi net, organitzat i reutilitzable mitjançant variables CSS.

---

## 🛠️ Tecnologies i eines utilitzades

**Llenguatges i estàndards**
- HTML5 semàntic (`<header>`, `<nav>`, `<main>`, `<footer>`, `<section>`, `<article>`, `<figure>`, `<figcaption>`, `<address>`, `<cite>`, `<abbr>`, `<blockquote>`, etc.)
- CSS3: Grid, Flexbox, `clamp()`, Scroll Snap, transicions, transformacions, `@keyframes`, variables CSS

**Eines de desenvolupament**
- [Validador W3C HTML](https://validator.w3.org/) i [CSS](https://css-validator.org/)
- Chrome DevTools + extensió [Mobile Simulator](https://chromewebstore.google.com/detail/mobile-simulator-responsi/ckejmhbmlajgoklhgbapkiccekfoccmk?pli=1)
- Extensió [Lighthouse](https://chromewebstore.google.com/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=es)
- [Google Fonts](https://fonts.google.com/) (Source Sans 3, Vollkorn, Roboto Slab) + Material Symbols + Font Awesome 6

**Disseny i recursos**
- [Canva](https://www.canva.com/) per les portades dels llibres
- [Perplexity](https://www.perplexity.ai/) (imatges d'autors) i [Gemini](https://gemini.google.com/) (imatges de l'equip)
- [Pexels](https://www.pexels.com/), [Unsplash](https://unsplash.com/), [Freepik](https://www.freepik.es/) per imatges i vídeos
- [Coolors](https://coolors.co/), [Color Hunt](https://colorhunt.co/), [ColorSpace](https://mycolor.space/) per paletes

**Àudio**
- [ChatGPT](https://chatgpt.com/) per crear el guió del podcast
- Gravadora del mòbil per l'enregistrament
- [Audacity](https://www.audacityteam.org/download/) per editar i afegir música d'entrada

**Tutorials de referència**
- [YouTube — Scroll Snap](https://www.youtube.com/watch?v=aEj6k-gi9-s)
- [YouTube — CSS Grid avançat](https://www.youtube.com/watch?v=JYfiaSKeYhE)
- [YouTube — Flexbox](https://www.youtube.com/watch?v=KD1Yo8a_Qis)
- [YouTube — Animacions CSS](https://www.youtube.com/watch?v=3Z780EOzIQs)

![Captura del Mobile Simulator](README/mobile-simulation.png)

---

## 📱 Responsive Design — Mobile First

El projecte es construeix des de la pantalla més petita i s'expandeix progressivament amb media queries:

| Breakpoint | Viewport | Comportament típic |
|---|---|---|
| Mobile (base) | < 768px | 1 columna, `flex-direction: column` |
| Tablet | ≥ 768px | 2 columnes per fila |
| Desktop | ≥ 1024px | 3–4 columnes, layouts complexos |

Alguns elements secundaris s'oculten en mòbil i tauleta per evitar scroll excessiu. Les unitats emprades són majoritàriament `rem` i `%`, i la tipografia s'ajusta automàticament amb `clamp()`.

---

## 🎨 Decisions tècniques rellevants

### Layout principal amb CSS Grid

El layout global (`header`, `main`, `footer`) s'ha resolt amb **CSS Grid** (`grid-template-rows: auto 1fr auto`), garantint que el footer sempre es manté al final de la pàgina i permetent una separació estructural neta i escalable.

### Flexbox per a seccions internes

Flexbox s'ha emprat en components unidimensionals: targetes de llibres, fitxes d'autors, seccions informatives i formularis. La combinació Grid (estructura global) + Flexbox (components interns) optimitza la distribució en tots els dispositius.

### Tipografia fluida amb `clamp()`

S'ha implementat `clamp()` a `h1`, `h2`, `h3` i al text base del `body`, aconseguint una tipografia adaptativa contínua sense salts bruscos entre breakpoints.

### Variables CSS per a coherència visual

Totes les tipografies, colors corporatius i tons neutres es gestionen des del `:root`, facilitant el manteniment i un possible rebranding futur.

### Microinteraccions i animacions

S'han implementat `:hover` i `:focus` en botons i enllaços, `transform` i `transition` per a feedback visual suau, i animacions amb `@keyframes` (efecte de batec al cor de Sant Valentí). Totes les interaccions són CSS pur, sense JavaScript.

![Exemple carrusel autors](README/carousel-autors.gif)
![Exemple efecte cor](README/gif-cor.gif)

### Carrusel horitzontal sense JavaScript

El carrusel d'autors s'ha resolt amb `overflow-x: auto`, `scroll-snap-type` i `scroll-snap-align`, permetent una navegació fluida nativa sense cap dependència de JavaScript.

### Navegació sticky

Inicialment plantetat com `position: fixed`, interferia amb el layout Grid. La solució adoptada va ser `position: sticky`, que manté la navegació visible sense trencar el flux estructural.

---

## ♿ Accessibilitat

- HTML semàntic amb jerarquia coherent d'encapçalaments.
- Textos alternatius (`alt`) descriptius en totes les imatges.
- Atribut `aria-current="page"` al nav de cada pàgina per indicar la pàgina activa.
- Atribut `title` a l'`<iframe>` del mapa de Google Maps.
- Estats `:focus` visibles per a navegació amb teclat.
- Contrast de color verificat (en procés de millora als botons i footer, vegeu apartat de millores).

---

## ⚠️ Reptes enfrontats

**1. CSS Grid al `header`**
El grid global no s'aplicava correctament. El problema era `position: fixed` al header, que el treia del flux del document. La solució va ser canviar a `position: sticky`.

<img src="README/image1.png" width="400" alt="Error grid header"><br>
<img src="README/image2.png" width="400" alt="Diagnòstic DevTools"><br>
<img src="README/image3.png" width="400" alt="Solució aplicada">

**2. Scroll Snap**
Calia ajustar acuradament `scroll-snap-type` i `scroll-snap-align` per evitar comportaments inesperats i desbordaments horitzontals.

**3. Tipografia fluida**
El càlcul dels valors de `clamp()` va requerir proves per trobar l'equilibri entre mides mínimes i màximes per a cada família tipogràfica i viewport.

**4. Gestió d'imatges pesades**
Les imatges sense optimitzar han tingut un impacte crític en el rendiment (vegeu apartat de millores). Problemes tècnics puntuals (USB defectuós, connexió) van dificultar el flux de treball.

<img src="README/image6.png" width="500" alt="Problema tècnic">

**5. CSS extens i complex**
Mantenir un sol fitxer CSS de ~3.000 línies coherent i organitzat ha requerit una nomenclatura clara i comentaris de secció.

---

## 📊 Validació i resultats Lighthouse

- HTML validat amb W3C ✔
- CSS validat amb W3C ✔

Les auditories s'han realitzat amb l'extensió Lighthouse de Chrome. Els resultats globals són positius, amb marge de millora en rendiment (imatges) i alguns elements d'accessibilitat de contrast.

### inici.html
<img src="README/inici-config.png" width="600" alt="Configuració Lighthouse inici">
<img src="README/inici-desktop-resultats.png" width="400" alt="Resultats desktop inici">
<img src="README/inici-mobile-resultats.png" width="400" alt="Resultats mobile inici">

### llibres.html
<img src="README/llibres-desktop-resultats.png" width="400" alt="Resultats desktop llibres">
<img src="README/llibres-mobile-resultats.png" width="400" alt="Resultats mobile llibres">

### autors.html
<img src="README/autors-desktop-resultats.png" width="400" alt="Resultats desktop autors">
<img src="README/autors-mobile-resultats.png" width="400" alt="Resultats mobile autors">

### editorial.html
<img src="README/editorial-desktop-resultats.png" width="400" alt="Resultats desktop editorial">
<img src="README/editorial-mobile-resultats.png" width="400" alt="Resultats mobile editorial">

### contacte.html
<img src="README/contacte-desktop-resultats.png" width="400" alt="Resultats desktop contacte">
<img src="README/contacte-mobile-resultats.png" width="400" alt="Resultats mobile contacte">

---

## 🔧 Millores detectades i com aplicar-les

### 🔴 Rendiment — Imatges (impacte crític, afecta totes les pàgines)

El problema principal del projecte són les imatges sense optimitzar:

- `dona-fulles.png` (Contacte): **25 MB** → representa el 97% del payload de la pàgina.
- `hero-image.jpg` (Inici): **9 MB** servida a 58×39 px, causant un LCP de ~178 s en mòbil.
- Fotos d'autors en PNG: ~1.2–1.5 MB cadascuna.
- Portades de llibres i imatges d'Editorial servides a dimensions molt superiors a les que es mostren.

**Solució:** Convertir totes les imatges a **WebP o AVIF**, implementar `srcset` i `sizes` per a imatges responsives, afegir sempre `width` i `height` a les etiquetes `<img>`, i usar `loading="lazy"` per a imatges fora del viewport inicial. Eina recomanada: [TinyPNG](https://tinypng.com/).

### 🔴 Rendiment — Recursos bloquejants (impacte alt en mòbil)

Google Fonts, el CDN de Font Awesome (`all.min.css`) i el propi `style.css` bloquegen el renderitzat inicial. En mòbil poden bloquejar més d'1 segon cadascun.

**Solució:** Extreure el CSS crític *inline* al `<head>`, carregar la resta de forma asíncrona, allotjar les fonts localment (*self-hosting*), i substituir Font Awesome per SVGs inline si només s'utilitzen unes poques icones.

### 🟠 Rendiment — CSS i servidor

`style.css` té ~14.8 KiB minificables i ~45.3 KiB de CSS no utilitzat; `all.min.css` afegeix ~16.9 KiB addicionals no usats. El servidor no aplica compressió.

**Solució:** Minificar el CSS amb `cssnano`, eliminar regles no usades amb `PurgeCSS`, i activar **gzip o Brotli** al servidor web.

### 🟠 Rendiment — Layout Shift (CLS)

Les fonts web de Google s'apliquen tard i causen desplaçaments visuals (CLS > 0.1 a Contacte i Autors).

**Solució:** Afegir `font-display: swap` a les declaracions `@font-face`, precarregar les fonts crítiques amb `<link rel="preload">`.

> **Nota:** Les Google Fonts ja inclouen `&display=swap` a la URL d'importació, cosa que millora parcialment aquest problema.

### 🟠 Accessibilitat — Contrast de colors

Múltiples elements no superen la ràtio de contrast mínima WCAG AA (4.5:1): botons, títols sobre fons de color, enllaços del footer, inputs i textos secundaris.

**Solució:** Revisar i ajustar els colors dels elements afectats fins a complir el contrast mínim. Eina recomanada: [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/).

---

## 🚀 Millores futures

- Implementació de funcionalitats amb JavaScript (menú hamburguesa funcional, filtratge real de llibres per gènere/autor).
- Formulari de contacte funcional amb backend.
- Mode fosc (`prefers-color-scheme`).
- Accessibilitat avançada (ARIA roles, live regions).
- Optimització d'imatges amb formats moderns (WebP/AVIF) i `srcset`.
- Desplegament en producció (GitHub Pages, Netlify o Vercel).
- Minificació del CSS i activació de compressió al servidor.

---

## 🔗 Demo

*(Pendent de desplegament — GitHub Pages / Netlify / Vercel)*

---

## 👩‍💻 Autoria

**Íngrid Palomino Pérez**  
Confecció i Publicació de Pàgines Web · Curs 2025–2026  
[CIFO La Violeta](https://cifolvioleta.cat/), Barcelona

---

## ⚖️ Copyright i llicència

© Febrer 2026 Íngrid Palomino Pérez. Tots els drets reservats.

El **codi font** (HTML i CSS) d'aquest projecte és obra original de l'autora, desenvolupat com a projecte acadèmic per al curs de *Confecció i Publicació de Pàgines Web* al CIFO La Violeta.

El **contingut editorial** (textos, noms d'autors fictícia, sinopsis de llibres, nom i marca {Edito}Line) és fictici i creat a efectes acadèmics.

Els **recursos multimèdia** (imatges, vídeos, àudio) provenen de fonts de lliure ús o han estat generats amb IA:
- Imatges de bancs lliures de drets: [Pexels](https://www.pexels.com/), [Unsplash](https://unsplash.com/), [Freepik](https://www.freepik.es/)
- Imatges d'autors generades amb [Perplexity](https://www.perplexity.ai/)
- Imatges d'equip generades amb [Gemini](https://gemini.google.com/)
- Portades dissenyades amb [Canva](https://www.canva.com/)

Queda **prohibida la reproducció, distribució o ús comercial** del codi sense el consentiment explícit de l'autora.

---

*Darrera revisió: Març 2026*  
*Aquest projecte forma part del curs "Confecció i Publicació de Pàgines Web", CIFO La Violeta, Barcelona.*