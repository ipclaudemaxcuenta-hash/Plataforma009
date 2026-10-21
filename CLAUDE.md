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

## Pantalla de resultado de búsqueda DNI (Prevención · Consulta Combo)
- **Versión final / a presentar a futuro:** `entregables/ipartner-prevencion-resultado-dni.html` (íconos actualizados de la home, Dock de la home e indicadores ×1/×2/×3).
- **Versión temporal (solo por ahora):** `entregables/ipartner-prevencion-resultado-dni-iconos-anteriores.html` (íconos anteriores, dock original, sin indicadores), porque los íconos del sistema aún no están actualizados.
