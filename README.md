# Mas Tulsà · Mapa interactiu

Mapa il·lustrat interactiu de Mas Tulsà, pensat per incrustar-se a Wix mitjançant un iframe.

Tot el mapa és un sol fitxer autònom (`index.html`) amb les il·lustracions incloses. Es pot publicar amb GitHub Pages o amb Netlify sense cap pas de compilació.

## Incrustar a Wix

Afegeix → Inserir codi → Inserir HTML → Codi:

```html
<iframe
  src="URL-DEL-MAPA"
  title="Mapa interactiu · Mas Tulsà"
  style="width:100%; height:100%; border:0; display:block;"
  loading="lazy"
  allow="fullscreen">
</iframe>
```

Alçada recomanada del requadre: ~950 px a escriptori, 900–1000 px a mòbil.
