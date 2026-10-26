h0
x
en ole varma tiivistänkö oikeaa asiaa sillä tehtävänannon linkkaama artikkelin Niemi 2025: H4 Tehtävät, alkuvaiheet vaikuttavat jo tiivistelmältä ja viittaa muihin teksteihin. Alussa se kertoo Susanna Lehdon artikkelista, jossa käydään verkkopalvelun ostaminen ja asennus läpi. seuraavaksi kerrotaan Tero karvisen vuoden 2017 artikkelista First Steps on a New Virtual Private Server – an Example on DigitalOcean and Ubuntu 16.04 LTS, jossa käydään läpi mm. reiän teko tulimuuriin. 
Tämän jälkeen artikkeli kertoo pilvipalvelimen vuokraamisesta. Mainitaan että yhteydet ovat nopeampia jos palvelimen fyysinen sijainti on lähellä asiakkaita. Seuraavaksi artikkelissa kerrotaan pilvipalvelimelle tehdyistä alkutoimista. Kirjoittaja otti palvelimeen etäyhteyden käyttämällä komentoa ssh root@palvelien ip-osoite, tämän jälkeen kirjoittaja loi palvelimelle sudo käyttäjän ja mahdollisti sille kirjautumisen ssh:lla. viimeiseksi kirjoittaja asensi palvelimelle palomuurin ja sulki root tilin ja sinne ssh kirjautumisen.
artikkeli kertoo vielä web-palvelimen asennuksesta. kirjoittaja otti luomallaan sudokäyttäjällä ssh yhteyden pilvipalvelimeen, päivitti sen järjestelmät ja asensi apache2 tämän jälkeen kirjoittaja korvasi testisivun haluamalla sivullaan ja salli portin 80 läpipääsyn palomuurista.
myös artikkelin Partanen 2025: Harjoitus 5: Nimekäs: a kohta pitää tiivistää. tämä kertoo domain name palvelun käytöstä. Partanen kertoo miten hän osti domainnamen ja miten hän sai sen osoittamaan hänen palvelimeen namecheapin asetuksista.

a
tein vaihtoehtotehtävän
aloitin asentamalla virtuaalikoneelle debianin käyttämällä tero karvisen ohjetta Install Debian on Virtualbox - Updated 2024, loin myös sudo käyttäjän ja asensin palomuurin. seuraavaksi asensin apache2 komennolla sudo apt-get install apache2
