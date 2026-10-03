# Projectes

Portada estàtica per penjar projectes i compartir-los amb coneguts. Es serveix amb GitHub Pages.

## Afegir un projecte nou
1. Crea una carpeta amb el projecte (ha de tenir un `index.html`), per exemple `elmeuprojecte/`.
2. Afegeix una entrada a `projects.js` (títol, descripció, etiquetes, data).
3. `git add . && git commit -m "Afegeix elmeuprojecte" && git push`
4. Al cap d'un minut és a `https://coldon82.github.io/elmeuprojecte/`.

## Notes
- El repositori és públic (GitHub Pages gratuït ho exigeix). No hi pugis res que no vulguis que vegi tothom.
- Les pàgines porten `noindex` i hi ha un `robots.txt` perquè els cercadors no les indexin. No és cap protecció: qui tingui l'enllaç, ho veu.
- Només serveix per a contingut estàtic (HTML, JS, dades). Si algun dia necessites un backend, cal un altre servei.
