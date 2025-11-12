# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

GitHubin web käyttöliittymän käyttö oli tuttua, push/pull perustoiminnoiltaa myös. Ongelmia tuli, kun aluksi paivakirja2.md olikin tyhjä tiedosto, eikä sisältänyt ohjeistusta tehtävään. Lopulta haara piti poistaa, hakea muutokset etäreposta ja avata uudestaan, seurasin kurssimateriaalin ohjeistusta.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git remote add origin <omaUrl> | Lisää etärepositio paikalliselle projektille |
| git push -u origin main | Pushaa main haara githubiin |
| git fetch origin | hakee muutokset etäreposta |
| git checkout origin/main | Tarkastelee etähaaraa |
| git merge origin/main | yhdistää muutokset main-haaraan |
| git branch -D paivakirja2 | poistaa paikallisen haaran joka ei seurannut etähaaraa |
| git remote -v | Tarkistaa etärepon listan |