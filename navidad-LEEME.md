# navidad.m3u

Lista M3U con el contenido navideño de `tv mx pelis y series.m3u` (la original no se modificó).

## Qué es un M3U (IPTV)
Archivo de texto que empieza con `#EXTM3U`. Cada entrada son dos líneas: `#EXTINF:-1 tvg-id="" tvg-name="" tvg-logo="" group-title="",Título` (metadatos: nombre, logo, categoría) y debajo la URL del video. El reproductor IPTV solo lee la lista y reproduce cada URL; el video no vive en el archivo. `group-title` arma las carpetas y `tvg-logo` la carátula. Es texto plano, sin especificación formal; los atributos `tvg-*` son una convención de facto de IPTV.

## Contenido (149 entradas, sin duplicados)
- 🎄 Navidad - Películas: 55
- 🎅 Navidad - Infantil y Animación: 49
- 📺 Navidad - Series (por episodio): 21
- 🌐 Navidad - Título original (audio por verificar): 24

## Limitaciones
- Todas las URLs apuntan a un servidor IPTV de terceros (Xtream Codes, con usuario y clave en la URL). Si ese servicio cancela la cuenta o cambia IDs, los enlaces dejan de funcionar: no se puede garantizar que no caduquen.
- El audio en español no se pudo verificar; por eso los títulos en inglés van en su propia categoría.
- Los canales navideños gratuitos y legales (p. ej. Pluto TV) son temporales, de diciembre a enero.
