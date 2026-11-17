# Traductor (Translator Lite)

Traductor de voz muy simple, en los dos sentidos, para iPhone y iPad. Usa Soniox.
Solo hay que elegir los dos idiomas y tocar el micrófono.

© 2026 DS-Lab

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | La app completa |
| `manifest.webmanifest` | Permite instalarla en la pantalla de inicio |
| `icon-180.png`, `icon-192.png`, `icon-512.png` | Iconos |

**Estos archivos no contienen ninguna API key.** La clave se pone en cada dispositivo desde la pantalla de configuración oculta, y solo queda guardada en ese dispositivo.

## Publicar en GitHub Pages

1. Crea un repositorio **nuevo**, distinto del de Seminar Interpreter (por ejemplo `traductor`), y sube estos 6 archivos a la raíz.
2. Ve a **Settings → Pages**, elige la rama `main`, la carpeta `/ (root)` y pulsa **Save**.
3. La app quedará en `https://<tu-usuario>.github.io/traductor/`.

## Instalar en el iPhone o iPad de otra persona

1. Abre la dirección en **Safari**.
2. Toca **Compartir → Añadir a pantalla de inicio → Añadir**.
3. **Abre la app desde el icono nuevo** y configúrala ahí. No lo hagas desde Safari: iOS guarda los datos de la app instalada por separado.
4. **Mantén pulsado el título de arriba ("Traductor") durante 3 segundos.** Se abre la configuración:
   - Pega la clave de Soniox.
   - Escribe tu nombre (opcional). Si algo falla, la app dirá "Avisa a <nombre>".
   - Pulsa **Probar clave** y luego **Guardar**.
5. Elige los dos idiomas (por ejemplo Español ⇄ 日本語), toca el micrófono una vez y permite el acceso al micrófono.

Desde Safari también se puede abrir la configuración añadiendo `#setup` al final de la dirección.

## Uso

- **Botones de idioma (arriba):** eligen los dos idiomas. **⇄** los intercambia.
- **Micrófono (abajo):** un toque empieza y otro para. Mientras escucha, el botón se pone rojo y se ilumina con la voz.
- La app detecta cuál de los dos idiomas se habla y traduce al otro. Las frases en el primer idioma aparecen a la izquierda y las del segundo a la derecha. Arriba va la traducción en grande y debajo, en pequeño, lo que se dijo.
- Los textos de la app salen en el idioma del iPhone (español, japonés o inglés).
- Mientras traduce, la pantalla no se apaga (iOS 16.4 o posterior). Si se bloquea o se cambia de app, iOS corta el micrófono y hay que volver a tocarlo.

## Seguridad

- Usa para esta app una **clave de Soniox distinta** de la tuya habitual. Así, si hay un problema, la borras sin afectar a lo demás.
- Si un dispositivo se pierde, borra esa clave en la consola de Soniox y crea otra.
