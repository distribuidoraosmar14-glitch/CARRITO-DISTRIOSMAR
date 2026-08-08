# Cómo actualizar el carrito (Distribuidora Osmar)

Guía rápida para cuando Claude te pase una versión nueva del carrito (por ejemplo, después de pedir un cambio de diseño o corregir algo).

## Lo que vas a recibir

Un archivo ZIP (`carrito-distriosmar.zip`) con estos 4 elementos adentro:
- `index.html`
- carpeta `images`
- carpeta `icons`
- `manifest.json`

## Paso a paso para actualizar

**1. Descomprimir el ZIP nuevo**
Guardalo en tu compu y descomprimilo (clic derecho → "Extraer todo" en Windows).

**2. Abrir la carpeta del repositorio**
Abrí **GitHub Desktop** → arriba, menú **"Repository"** → **"Show in Explorer"** (Windows) o **"Show in Finder"** (Mac).
Se abre la carpeta de tu proyecto en la compu.

**3. Reemplazar los archivos viejos**
Adentro de esa carpeta vas a ver `index.html`, `images`, `icons` y `manifest.json` de la versión anterior.

- Borrá esos 4 elementos.
- **No toques** `README.md` ni `.gitattributes` — esos quedan siempre igual, no son parte del carrito.

Copiá y pegá ahí adentro los 4 elementos nuevos que descomprimiste en el paso 1.

**4. Subir los cambios**
Volvé a la ventana de **GitHub Desktop**:
1. Del lado izquierdo vas a ver la lista de archivos que cambiaron.
2. Abajo, en el cuadro "Summary", escribí una frase corta describiendo el cambio (ej: `"nuevos precios"`, `"cambio de diseño"`).
3. Tocá el botón azul **"Commit to main"** (o **"Commit X files to main"**).
4. Arriba va a aparecer el botón **"Push origin"** — tocalo. Ahí se sube todo a internet.

**5. Confirmar que se ve bien**
Esperá 1-2 minutos y entrá a tu link:

`https://tu-usuario.github.io/carrito-distriosmar/`

Si en la compu no ves el cambio, apretá **Ctrl + F5** para forzar que recargue todo de cero (es un tema de caché del navegador, no de que algo esté mal).

---

## Tu link del carrito
`https://tu-usuario.github.io/carrito-distriosmar/`

## Recordatorios importantes
- Los **precios y productos** se actualizan solos desde tu Google Sheets — no hace falta subir nada para eso, solo para cambios de diseño o funcionamiento del carrito.
- Las **fotos nuevas** se cargan pegando el link de Google Drive en la columna oculta **E (LINK_FOTO)** de la planilla — tampoco requiere subir nada acá.
- Si le cambiás el **nombre a una pestaña** de la planilla, avisale a Claude para actualizar el carrito (si no, esa categoría deja de aparecer).
