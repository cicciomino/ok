# Stress Tester Generazione Infinita

Pagina web a file singolo che genera in continuo blocchi bianchi 3D con fisica semplice (gravità e rimbalzi) per mettere sotto stress il dispositivo e misurare gli FPS in tempo reale. Usa Three.js con rendering a istanze e Tailwind CSS.

## Uso

Apri `index.html` in un browser (serve la connessione internet per caricare Three.js e Tailwind da CDN), poi premi **Start**. Con lo slider scegli quanti blocchi al secondo generare, da 50 a 1.000. **Stop** mette in pausa la generazione, **Reset** rimuove tutti i blocchi. Trascina sull’area 3D per ruotare la camera.

Il limite è di 200.000 blocchi: raggiunto quello, la generazione si ferma.

## Pubblicazione con GitHub Pages

Il workflow in `.github/workflows/pages.yml` pubblica la pagina a ogni push su `main`. In **Settings > Pages** imposta **Source** su **GitHub Actions**.

## Crediti

Made with ❤️ by Giaco&Dario

## Licenza

MIT
