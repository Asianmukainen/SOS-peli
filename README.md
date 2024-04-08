-- SÄÄNNÖT --
Pelin alussa käyttäjältä kysytään neliöruudukko, jonka koko on vähintään 3x3 ja mielellään alle 10x10 jotta ruudukko pysyy suorana.
Pelaajat lisäävät vuorotellen joko "S"- tai "O"-kirjaimen mihin tahansa vapaana olevaan pisteeseen, jotka on merkitty "+" symbolilla. Pelaaja voi siis käyttää molempia kirjaimia täysin vapaavalintaisesti. 
Pelin tavoitteena on, että kumpikin pelaaja yrittää luoda peräkkäisen S-O-S yhdistelmän ruudukkoon joko vinottain, vaakasuunnassa tai pystysuunnassa, ja luoda niitä niin monta kuin pystyy. Vanhoja SOS:eja voidaan käyttää uusien luomiseen.
Pelaajan 1 luomat SOS:it värittyvät automaattisesti punaiseksi, kun taas pelaajan 2 siniseksi. 
Joka vuorolla, jommankumman pelaajan nimeä (pelaaja 1 tai pelaaja 2) kutsutaan, ja pyydetään antamaan kirjain, x ja y koordinaatti tässä järjestyksessä. Jokainen merkki tulee erottaa välilyönnillä. Siirto tehdään painamalla enter näppäintä.
Jos pelaaja onnistuu luomaan SOS:in, saa hän jatkaa vuoroaan kunnes uutta SOS:ia ei voida enää luoda hänen vuorollaan. Muutoin pelaajat tekevät siirtoja vuorotellen.
Peli jatkuu kunnes kunnes ruudukko on täytetty, ja voittaja on pelaaja, joka teki eniten S-O-S yhdistelmiä. Jos ruudukon täytyttyä SOS:ien määrä on sama, peli on tasapeli. 
Ohjelma pitää kirjaa SOS:ien määrästä pisteiden muodossa, ja ilmoittaa lopuksi kuinka monta pistettä kumpikin pelaaja sai.

-- HUOMIOITAVAA --
SOS yhdistelmien värimerkintä ei toimi sääntöjen mukaisesti, eikä pisteidenlasku enää toimi oikein ensimmäisen SOS:in jälkeen, vaan piste voi tulla vaikka uutta SOS:ia ei ole tehty.
