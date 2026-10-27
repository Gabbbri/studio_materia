# Studio Materia

Sito statico HTML, CSS e JavaScript, senza dipendenze o build.

- `public/index.html`: testi e struttura.
- `public/style.css`: stile e layout responsive.
- `public/app.js`: interazioni.
- `public/assets/`: immagini WebP ottimizzate.
- `.github/workflows/pages.yml`: pubblicazione automatica su GitHub Pages a ogni push su main.

## Anteprima locale

```bash
python3 -m http.server 8000 --directory public
```

Aprire http://localhost:8000.

## Note

Nome, immagini illustrative e contatto dimostrativo della bozza. Nessun messaggio viene inviato dal modulo.

I file del sito corrispondono alla versione Sites approvata, commit `d6bdab3072f1ae24da3e03a9f7ac6f12eaf44d25`.
Non occorrono npm install o npm run build. I percorsi relativi supportano GitHub Pages nei repository di progetto.
