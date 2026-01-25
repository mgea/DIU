# Vibe Design - Plantabaja

Qué es: https://www.visily.ai/vibe-designing/ 


CASO: 
* Plantabaja https://plantabaja.club/
* Figma Make https://gong-attic-81664024.figma.site
* v 1.0 25/01/2026 

 

## Diseño de web usando Figma Make 

* Simular web existente (layout) con imágenes originales.
* Incuir/mejorar elementos de diseño (cards, navegación)
* Modificar estilo  visual (fonts, iconos, ...) 
* Duración total 45min+ 


Pasos: 

### 1  Website genérica 

```
Create a concert pub website offering live free anf paid music. It contains an agenda of concerts with artist, date coments and buy tickets, also it has a blog. The name is PlantaBaja
```

* Uso de inglés
* Formato sugerido, sólo el nombre. 

I'll create a concert pub website for **PlantaBaja** with a **concert agenda, ticketing system, and blog**. Let me build this with a modern, vibrant design that captures the energy of live music.

I've created a complete concert pub website for PlantaBaja featuring a modern, vibrant design with a **dark theme** and orange accents. The site includes a **hero section** highlighting live music, a **full concert agenda** with artist details, dates, and ticketing (both free and paid concerts), individual concert detail pages with comment functionality, and a comprehensive blog section with multiple posts about music culture and venue insights.

The website is **fully responsive** and includes navigation between all sections, ticket purchasing interface, and interactive features like commenting on concerts. While this currently uses mock data for demonstration, Supabase could significantly enhance the experience by providing real-time data persistence for concert listings, blog posts, user comments, and ticket purchases - allowing you to manage content dynamically and store user interactions securely.

Would you like me to help you connect to Supabase to add backend functionality for storing concerts, blog posts, comments, and ticket purchases?

### 2  Logotipo 

```
Cambiar por un logotipo usando letras Pb en blanco estilo futurista
```

I'll replace the Music icon with a futuristic "Pb" logo in white letters.

Perfecto! He cambiado el logotipo del ícono de música a las letras "Pb" en blanco con un estilo futurista. El diseño incluye:

- Letras "Pb" en blanco con tipografía monoespaciada (estilo tecnológico)
- Fondo con degradado oscuro
- Borde blanco de 2px
- Esquinas redondeadas
- Efecto de escala al pasar el cursor

El logotipo mantiene el mismo comportamiento interactivo y se integra perfectamente con el diseño existente de PlantaBaja.

```
use this image as inspiration
```

Perfecto! Voy a actualizar el logotipo usando la imagen de inspiración que proporcionaste.

¡Listo! He actualizado el **logotipo con un estilo futurista** más sofisticado inspirado en tu imagen:

**Características del nuevo logo "Pb":**

- Fondo negro sólido con borde blanco de 2px
- Efecto de brillo neón naranja alrededor de las letras (text-shadow)
- Degradado sutil de naranja a púrpura en el fondo
- Tipografía sans-serif bold y compacta
- Espaciado ajustado entre letras para un look más moderno
- Efecto de escala al pasar el cursor

El diseño captura la estética futurista y tecnológica manteniendo la identidad visual de PlantaBaja.

```
Use this logo
```


Perfecto! Voy a r**eemplazar el logotipo con la imagen** que proporcionaste.

¡Perfecto! He actualizado el logotipo para usar tu imagen. Ahora el logo de PlantaBaja se muestra con la imagen que proporcionaste, manteniendo el efecto de escala al pasar el cursor para una experiencia interactiva.

### 3  Cambiar contenido (imgs y texto)

```
cambiar blog por Noticias
```


Perfecto! Voy a cambiar "Blog" por "Noticias" en la navegación.

¡Listo! He cambiado "Blog" por "Noticias" en el botón de navegación. Ahora el menú muestra "Noticias" en lugar de "Blog".

```
cambia imagen de fondo del hero section por la seleccionada
```

I'll update the **hero section to use your selected background image**. Let me first check the current structure of the App.tsx file.

Perfect! I've successfully updated the hero section to use your selected background image. The vibrant purple and orange interior photo of PlantaBaja will now be displayed as the background, which perfectly matches the venue's aesthetic and the site's color scheme. The dark overlay gradient is maintained to ensure the text remains readable while showcasing your venue's atmosphere.

### 4  Cards

<img src="https://plantabaja.club/wp-content/uploads/2026/01/IMG_2539.jpeg" height="150"> <img src="https://plantabaja.club/wp-content/uploads/2025/12/cartel-COUNTRY-GIRL.jpeg" height="150">

```
Cambia tres primeras cards por estas imágenes
```


I'll update the **first three concert cards** to use your custom event images. Let me first check the Agenda component to see where the concert data is stored.

Perfect! I've successfully updated the first three concert cards with your custom PlantaBaja event images. The cards now feature Patín Piti (DJ Session), HINDS + CARMENCORE (Indie Rock concert), and Country Girl (DJ Session), each with their authentic event posters. The dates and times have been updated to match the information shown in the images, and all remaining concerts are preserved in the agenda.

```
Cambia las 3 siguientes cards de concert agenda por las imagenes con informacion seleccionadas
```


I'll update the **next three concert cards** with your selected event images and information.

Perfect! I've successfully updated the next three concert cards with your custom event images. The concert agenda now features:

- **La Juan Román** (Feb 6) - Cumbia Nazarí (FREE)
- **Halusk & Piko present DJ Buenagente** (Feb 13, midnight) - Electronic/DJ Set with the playful tagline "No aceptamos peticiones, sólo quejas!"
- **Santiago Motorizado** (Feb 19) - Indie Rock from his European 2023 Granada tour

All six events now showcase authentic PlantaBaja event posters with updated dates, times, genres, and pricing information.

### 5  Tipografía

```
cambiar font de Hero header "Plantabaja Your underground music hub" por esta fuente https://www.dafont.com/es/nasalization.font
```

I can't directly download font files from external URLs. To use the Nasalization font, you'll need to provide the font file itself.

However, I can help you in two ways:

**Option 1:** If you have the Nasalization font file (.ttf, .woff, or .woff2), you can share it with me and I'll integrate it into the project.

**Option 2:** I can suggest a similar futuristic/tech-style font that's readily available. Nasalization has a modern, geometric, tech-inspired look. Some similar alternatives include:

- **Orbitron** - A geometric sans-serif with a futuristic feel
- **Rajdhani** - Bold and modern with similar geometric qualities
- **Saira Condensed** - Clean and tech-inspired

Would you like me to:

1. Wait for you to provide the Nasalization font file, or
2. Implement one of these similar alternative fonts for the hero section?

Let me know your preference!

```
usa orbitron
```


I'll update the Hero section to use the Orbitron font. Let me first check the current styles setup:

Perfect! I've successfully updated the Hero section to use the Orbitron font. The "PlantaBaja" main heading and "Your Underground Music Hub" tagline now use the modern, futuristic Orbitron typeface, which gives the hero section a tech-inspired, underground music venue aesthetic that matches the vibe of PlantaBaja.

### 6  Footer

```
Cambiar footer "© 2026 PlantaBaja. All rights reserved. Live music, live moments." por "CCBY mgea using Figma Make v1.0 2026"
```


I'll update the footer text for you. Let me first check the current Footer component:

Perfect! I've updated the footer text to "CCBY mgea using Figma Make v1.0 2026" as requested. The footer now displays your custom attribution text with the Creative Commons BY license notation.

### 7 Noticias: card


```
Primera card de noticias es esta imagen, el texto es XII CONCURSO DE BANDAS Y ARTISTAS GRANADINOS “ EMERGENTES 2025”
```

Voy a actualizar la primera tarjeta de noticias con la imagen y el texto del concurso. Primero déjame ver el componente de Blog:

Perfecto! He actualizado la primera tarjeta de noticias con la imagen del XII Concurso de Bandas y Artistas Granadinos Emergentes 2025. La tarjeta ahora muestra el cartel oficial del concurso con toda la información sobre las inscripciones hasta el 08/03/25, y la categoría ha sido cambiada a "Concursos" para reflejar el tipo de contenido.


### 8 Icono 

Dificultades para generar imágenes 

* ``cambiar icono de hero section por una guitarra electrica tocada por un hombre con forma de granada`` 

* ``reemplaza por una silueta de guitarra electrica en tono naranja/negro con pequeño efecto de movimiento``

* ``cambiar logo por esta imagen``


### 9 Pendiente 

* sección de Cómo llegar (mapa)
* Comprender e integrar submenu de eventos de tipo: Conciertos - Clubs - DJs





<br> 

<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/png/by-nc-sa.png"  width="75" > Miguel Gea, updated: 25/1/2026




