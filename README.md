# Invitación del baby shower de Kael

Invitación web interactiva: portada en arco con un osito, un sobre que se abre, una tarjeta que sale y se despliega, y debajo la fecha con cuenta regresiva, el lugar, la lista de regalos y música de caja de música.

- **Dirección pública:** https://alexab060101.github.io/baby-shower-kael/
- **Todo el diseño, las ilustraciones y la animación:** `index.html`
- **Tipografías:** carpeta `fuentes/` (incluidas para que cargue rápido y sin depender de nadie)
- **Imagen que enseña WhatsApp al compartir el enlace:** `og.jpg`
- **Fichero para guardar la fecha en el calendario:** `baby-shower-kael.ics`

## Datos que se pueden cambiar

Al principio de `index.html` hay tres datos:

| Dato | Para qué sirve | Si se deja vacío (`""`) |
|---|---|---|
| `ENLACE_LISTA_DE_REGALOS` | Botón «Nuestra lista de regalos» | — (ya tiene el enlace de Amazon) |
| `ENLACE_UBICACION` | Botón «Cómo llegar» (enlace de Google Maps) | No se muestra el botón |
| `TELEFONO_CONFIRMACION` | Sección «Confirma tu asistencia» por WhatsApp (con prefijo, sin espacios ni «+», p. ej. `34600111222`) | No se muestra la sección |

## Cómo cambiar un dato

1. Entra en https://github.com/Alexab060101/baby-shower-kael con la cuenta de GitHub.
2. Pulsa en el fichero `index.html`.
3. Pulsa el icono del lápiz (arriba a la derecha, «Edit this file»).
4. Casi al principio verás, por ejemplo:

   ```
   const ENLACE_UBICACION = "";
   ```

5. Escribe el dato **entre las comillas**. No borres las comillas ni el punto y coma.
6. Pulsa el botón verde **«Commit changes…»** y después otra vez **«Commit changes»**.
7. Espera uno o dos minutos y vuelve a abrir la dirección pública. Ya tendrá el cambio.

## Detalles que ya trae

- Si alguien vuelve a abrir el enlace, la invitación sale ya abierta para consultar los datos. Abajo del todo tiene «Volver a abrir el sobre» para repetir la animación.
- La música (la nana de Brahms, de dominio público) la genera el propio navegador: no hay ningún fichero de audio. Empieza al abrir el sobre y se para con el botón redondo de abajo a la derecha.
- Si el móvil tiene activado «reducir movimiento», la invitación aparece con un fundido suave en lugar de la animación.
- Los botones de Amazon, Google Maps y WhatsApp abren en una pestaña nueva, sin cerrar la invitación.
- «Guardar en mi calendario» abre Google Calendar en Android y el calendario del móvil en iPhone.
