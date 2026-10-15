# Reglas del proyecto

## Skills de diseño (uso obligatorio y automático)
Skills instaladas en `.claude/skills/`, provenientes de:
- Apple Design: https://github.com/dickwu/apple-design-skill (`apple-design`)
- UX/UI Agent Skills: https://github.com/plugin87/ux-ui-agent-skills (`design-doctrine`, `design-screen`, `design-review`, `a11y-audit`, `apply-aesthetic`, `ux-writing`, etc.)
- UI UX Pro Max: https://github.com/nextlevelbuilder/ui-ux-pro-max-skill (`ui-ux-pro-max`, `design-system`, `ui-styling`, etc.)

1. Usar estas skills automáticamente en todo trabajo de diseño/UI/UX, sin que el usuario escriba /skill.
2. Al final de cada párrafo de respuesta, añadir una línea corta indicando cuál(es) de las 3 skills se usó para ese apartado, por ejemplo: `Skill: Apple Design (layout estilo iPadOS)`. Si no se usó ninguna, indicarlo.
3. Estilo objetivo: interfaz tipo iPad/iPadOS, fácil de usar y de calidad premium.
4. Entregables en HTML (luego pasan a Figma y otra persona los integra en la plataforma).

## Decisiones pendientes para la plataforma (después del login)
- Botón de cerrar ventanas estilo macOS ("semáforo": solo el círculo rojo, con la x al pasar el mouse). Se descartó en el login y se reserva para el interior de la plataforma.

## Verificación obligatoria antes de entregar cualquier pantalla
Medir en el navegador (lienzo 1920×1080, desde el borde visible de la pantalla) y no entregar si algo falla:
1. Márgenes exteriores iguales en los 4 lados (izquierda = derecha = arriba = abajo).
2. Espacios entre bloques iguales entre sí (borde → panel → íconos → borde).
3. Bordes alineados: encabezado, barra, grilla y Dock comparten bordes o centro; los widgets empiezan y terminan en las filas de íconos.
4. Mismo espacio entre todas las filas; nada se superpone (puntos, Dock, tarjetas) ni se corta (nombres de íconos).
5. Mirar la captura: textos legibles sobre el fondo y nada encima de objetos de la foto.
Reportar las medidas en la respuesta.
6. Medir bordes VISIBLES (la imagen del ícono, no su contenedor): barra de búsqueda y Dock empiezan y terminan exactamente en el borde de la primera y última columna de íconos.
7. La composición completa (saludo+widgets | barra+íconos+Dock) va centrada en el lienzo: margen izquierdo = derecho y superior = inferior. La barra comparte borde superior con el saludo y el Dock comparte borde inferior con el último widget.
