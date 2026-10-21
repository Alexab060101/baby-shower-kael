# Invitación del baby shower de Kael

Invitación web interactiva: un sobre que se abre, una tarjeta que sale y se despliega, y la lista de regalos de Amazon al final.

- **Dirección pública:** https://alexab060101.github.io/baby-shower-kael/
- **Todo el diseño y la animación:** `index.html`
- **Tipografías:** carpeta `fuentes/` (incluidas para que cargue rápido y sin depender de nadie)
- **Imagen que enseña WhatsApp al compartir el enlace:** `og.jpg`

## Cambiar el enlace de la lista de regalos

1. Entra en https://github.com/Alexab060101/baby-shower-kael con la cuenta de GitHub.
2. Pulsa en el fichero `index.html`.
3. Pulsa el icono del lápiz (arriba a la derecha, «Edit this file»).
4. Casi al principio verás este bloque:

   ```
   const ENLACE_LISTA_DE_REGALOS = "https://www.amazon.es/...";
   ```

5. Cambia **solo** lo que hay entre las comillas por el enlace nuevo. No borres las comillas ni el punto y coma.
6. Pulsa el botón verde **«Commit changes…»** y después otra vez **«Commit changes»**.
7. Espera uno o dos minutos y vuelve a abrir la dirección pública. Ya tendrá el enlace nuevo.

Cualquier otro cambio de texto se hace igual: se edita `index.html`, se guarda con «Commit changes» y la web se actualiza sola en uno o dos minutos.

## Detalles que ya trae

- Si alguien vuelve a abrir el enlace, la invitación sale ya abierta para consultar los datos. Abajo tiene «Volver a abrir el sobre» para repetir la animación.
- Si el móvil tiene activado «reducir movimiento», la invitación aparece con un fundido suave en lugar de la animación.
- El botón de la lista de regalos abre Amazon en una pestaña nueva, sin cerrar la invitación.
