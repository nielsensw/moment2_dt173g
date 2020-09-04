# Moment 2
Moment 2 | DT173G | NodeJs &amp; Gulp


### Summering 
- vad automatiserings-processens syfte är.
  - Syftet med automatiseringen är att minska inladdningstiden och för att lättare kunna navigera när man ska göra ändringar i källkoden. Själva automatiseringen i sig är för att inte behöva göra det manuellt, vilket är tidskonsumerande.
- anger om vilka paket och verktyg du använt, och varför du valt just dessa.
  - Andända paket i uppgiften är: Gulp, gulp-browsersync, gulp-clean-css, gulp-concat, gulp-uglify, gulp-image.
- beskriv systemet du skapat, hur man startar upp det och de tasks som ingår.
  - Man kan starta upp webbplatsen genom att köra gulp från terminalen lokalt. När man gör det så skapas en publik mapp med kopia av källkodens index.html, js-filer i källkoden slås ihop och minimeras och läggs in i publika mappen, css-filer slås ihop och en minimerad version läggs in i publika mappen och bilder från src-mappen komprimeras och läggs in i den publika mappen. Ändras dessa nämnda filer så uppdateras de i den publika mappen. Resultatet av den publika mappen kan ses i webbfönstret, då detta vid start av gulp öppnas på localhost med livereload.
