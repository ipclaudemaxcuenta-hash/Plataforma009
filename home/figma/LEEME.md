# Home iPartner · paquete para Figma y desarrollo

## Contenido
- `index.html`: el home final (se adapta a 2560×1440, la medida del sistema). Todas las imágenes son archivos externos en `assets/`, ya no van dentro del HTML.
- `assets/fondos/`: los 4 fondos de tema (escritorio, fútbol, Tesla y Starbucks), en WebP y JPG de 2560×1440 y menos de 1 MB cada uno. Las miniaturas del selector de mood están en `assets/fondos/miniaturas/`.
- `assets/iconos/productos/`: los íconos de los productos (PNG transparente de 220 px, con su borde de color ya incluido).
- `assets/iconos/procesos/`: los íconos del Dock de Procesos (PNG de 200 px).
- `assets/iconos/acciones/`: Jaina, notificaciones, cohete, avión y Asíncrona (PNG de 160–200 px).

## Hoja de íconos
- `iconos.html`: todos los íconos sueltos en una sola página, ordenados por grupo y con su nombre y tamaño. Impórtala en Figma igual que el home.

## Pantallas con menús abiertos
- `index-menu-cohete.html`: el menú del cohete abierto (Admin, Actualizar datos, Cambiar password y Cerrar sesión).
- `index-menu-avion.html`: el menú del avión abierto (System, SLAM, Puntos IP, Eventos y Buzón de sugerencias).

Importa también estos dos archivos para tener los menús en Figma: en `index.html` los menús están cerrados.

## Importar en Figma
1. Instalar el plugin **html.to.design** en Figma.
2. Importar `index.html` junto con su carpeta `assets/`. También se puede subir la carpeta a cualquier hosting estático e importar la URL.
3. Elegir un ancho personalizado de **2560** (2560×1440, la medida del sistema). El home se escala solo y mantiene las proporciones.
4. Opciones: **Use Autolayout apagado**, Create styles & variables encendido y HTML layer names encendido; todo lo demás apagado.

## Temas
El tema se cambia con `body[data-tema]`:

| Valor | Fondo |
|---|---|
| `degradado` | Escritorio |
| `atardecer` | Fútbol |
| `confeti` | Tesla |
| `ondas` | Starbucks |

## Íconos
| Nombre en pantalla | Archivo |
|---|---|
| asincrona | `assets/iconos/acciones/asincrona.png` |
| avion | `assets/iconos/acciones/avion.png` |
| cohete | `assets/iconos/acciones/cohete.png` |
| jaina | `assets/iconos/acciones/jaina.png` |
| notificaciones | `assets/iconos/acciones/notificaciones.png` |
| Analytics | `assets/iconos/procesos/analytics.png` |
| Asíncrona | `assets/iconos/procesos/asincrona.png` |
| Dashboard | `assets/iconos/procesos/dashboard.png` |
| Diccionario Legal | `assets/iconos/procesos/diccionario-legal.png` |
| Historial | `assets/iconos/procesos/historial.png` |
| Home | `assets/iconos/procesos/home.png` |
| Monitoreo | `assets/iconos/procesos/monitoreo.png` |
| Procesos | `assets/iconos/procesos/procesos.png` |
| App Ipartner | `assets/iconos/productos/app-ipartner.png` |
| B2B | `assets/iconos/productos/b2b.png` |
| Black List | `assets/iconos/productos/black-list.png` |
| Busca Personas | `assets/iconos/productos/busca-personas.png` |
| Cese Laboral | `assets/iconos/productos/cese-laboral.png` |
| Clásico | `assets/iconos/productos/clasico-ia.png` |
| Clásico | `assets/iconos/productos/clasico.png` |
| Credit PN | `assets/iconos/productos/credit-pn.png` |
| Credit Pro | `assets/iconos/productos/credit-pro.png` |
| Extranjero | `assets/iconos/productos/extranjero.png` |
| Ficha ID | `assets/iconos/productos/ficha-id.png` |
| IA Plus | `assets/iconos/productos/ia-plus.png` |
| Icar | `assets/iconos/productos/icar.png` |
| Income Ultra | `assets/iconos/productos/income-ultra.png` |
| NFC | `assets/iconos/productos/nfc.png` |
| On Boarding | `assets/iconos/productos/on-boarding.png` |
| Podcast | `assets/iconos/productos/podcast.png` |
| Premium IA | `assets/iconos/productos/premium-ia.png` |
| Premium | `assets/iconos/productos/premium.png` |
| Referencia Laboral | `assets/iconos/productos/referencia-laboral.png` |
| Rep. Leg | `assets/iconos/productos/rep-leg.png` |
| RUC | `assets/iconos/productos/ruc.png` |
| Splaft | `assets/iconos/productos/splaft.png` |
| VIP | `assets/iconos/productos/vip-ia.png` |
| VIP | `assets/iconos/productos/vip.png` |
| Z. Básico Plus | `assets/iconos/productos/z-basico-plus.png` |
| Z. Básico | `assets/iconos/productos/z-basico.png` |
| Z. Premium | `assets/iconos/productos/z-premium.png` |
| Z. VIP | `assets/iconos/productos/z-vip.png` |
| ZETA | `assets/iconos/productos/zeta.png` |
