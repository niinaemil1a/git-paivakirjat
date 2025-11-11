# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Olen käyttänyt git versionhallintaa muutamalla kurssilla, mutta en ole syvällisesti ymmärtänyt sen käyttöä kun se on kursseilla ollut sivuosassa ja tämä kurssi on tähän mennessä selkeyttänyt gitin ideaa. Hankaluuksia oli saada tiedostot auki VS Codessa mutta googlaamalla löysin tähän ohjeet ja nyt saan tiedostot auki "code styles.css" komennolla.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git init | Luo uuden git repon |
| git status | tarkistaa statuksen/tilan |
| git add test.txt | lisää tiedoston seuraavaan talletukseen |
| git add . | Lisää kaikki muutokset |
| git commit -m "Ensimmäinen commit" | Tallettaa muutokset committiin |
| git mv hello.html index.html | Nimeä tiedosto uudelleen |
| git rm test.txt | Poista tiedosto versionhallinnasta |
| git log --stat | näyttää commit historian tiedot|
| git branch tyylit | Luo uuden haaran "tyylit" |
| git switch tyylit | Vaihtaa tyylit haaraan |
| git switch main | Vaihtaa main haaraan |
| git merge tyylit | Yhdistä tyylit-haara main-haaraan (tee main-haarasta) |
| git restore hello.html | Peruuttaa työtilassa tehdyt muutokset joita ei ole vielä tallennettu versionhallintaan |
| git revert| Peruuta edellinen commit|
| git clone "https:/xxxx.xxx.xxx/xx/xxx" | Kloonaa repositio |