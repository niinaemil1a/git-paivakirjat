# Oppimispäiväkirja: Git projektissa

__Mitä hyötyä voisi olla versionhallinnasta, jos kehität projektia yksin?__

Se auttaa seuraamaan projektin kehitystä, mahdollistaa palaamisen edelliseen versioon jos jokin menee pieleen. Muutosten kommentoinnin avulla pysyy kärryillä tehdyistä muutoksista.

__Mitä hyötyä voisi olla versionhallinnasta, jos projektissa on useita kehittäjiä?__

Versionhallinta mahdollistaa sen, että yksittäiset kehittäjät voivat kehittää itsenäisesti tahoillaan ja jakaa työtä haaroihin ilman että se vaikuttaa muiden työhön/olemassa olevaan, toimivaan koodiin. Versionhallinnan avulla muutokset voidaan yhdistää hallitusti. 

__Miten järjestäisit projektitiimin versionhallinnan 3-4 hengen ohjelmistoprojektikurssilla? Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.__

Versionhallintaa ylläpidetään github repositoriossa. Main -haara sisältää vain testatun ja hyväksytyn koodin. Develop -haara on yhteinen kehityshaara, johon tehtyjä muutoksia yhdistetään ennen päähaaraa. tehtyjä muutoksia kirjataan committeihin. Jokainen tekee oman ominaisuushaaran omalle kehitettävälle tehtävälle. Kun ominaisuus on testattu ja hyväksytty, tehdään pull request develop haaraan. Toinen tiimiläinen parkistaa pull requestin ennen yhdistämistä. Kun projekti on valmis, develop -haara yhdistetään main haaraa ja sovellus julkaistaan.

__Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?__

Opintojakso oli hyödyllinen ja auttoi ymmärtämään selkeästi versionhallintaa. Työmäärä oli sopiva. Harjoitus 6 oli hauska ja todella havainnollistava, kiitos. Materiaalit myös hyvin ajan tasalla.