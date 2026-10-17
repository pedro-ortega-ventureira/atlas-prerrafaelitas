# Atlas de las mujeres prerrafaelitas

Mapa interactivo de una sola capa para acompañar un artículo en **Jot Down** sobre la exposición *Prerrafaelismo. Itinerarios femeninos (1850–1914)*.

## Estado
Prototipo editorial. Las ubicaciones incluidas son provisionales y están identificadas como tales. No publicar como atlas histórico definitivo sin verificar cada relación geográfica y las licencias de las imágenes.

## Tecnología
HTML, Leaflet, OpenStreetMap y GeoJSON, sin proceso de compilación.

## Editar
- `index.html`: interfaz del mapa.
- `lugares.geojson`: puntos y fichas. Cada punto admite `title`, `artist`, `year`, `description`, `location_note`, `image` y `source`.
- Para añadir imágenes, usar una URL estable con permiso de reutilización; indicar siempre la fuente y condiciones de uso.

## Publicación
En GitHub: Settings → Pages → Deploy from a branch → main → /(root). Esperar a que GitHub indique la URL publicada.

## Integración en WordPress
```html
<iframe src="https://pedro-ortega-ventureira.github.io/atlas-prerrafaelitas/" title="Atlas de las mujeres prerrafaelitas" style="width:100%;height:650px;border:0" loading="lazy" allowfullscreen></iframe>
```
Requiere que la configuración editorial de Jot Down permita iframes externos.
