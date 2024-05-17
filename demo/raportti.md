# Raportti

Harjoitustyön aiheena on yksinkertainen työajankirjaussivusto.

## Responsiivisuus

Sivusto on responsiivinen ja näkyy oikein useimmilla laitteilla. Laitteen näytön leveys on oltava vähintään 360 pikseliä, jotta sivusto näkyy oikein. 
Sivuston käyttö on testattu 1920 x 1080 ja 1920 x 1200 näytöillä, Chromen developer toolsin responsiivisuus työkalulla, ja Samsung S20 puhelimella.

## Toimivuus selaimilla

Sivosto on testattu toimivaksi Chromella, Firefoxilla ja Edgellä.

## Rajapinnat

Sivusto hyödyntää Google Firebasen autentikointia ja Firestore tietokantaa. 

Aloitusnäkymän satunnainen koirafakta ja satunnainen koirakuva haetaan REST rajapinnoista. Koirafakta haetaan [Dog API](https://dogapi.dog/) palvelusta ja koirakuva haetaan [random.dog](random.dog) palvelusta.
Koirakuva palvelussa osa linkeistä on toimimattomia, jolloin kuvaa ei lataudu.

## Latautumisaika

Sivuston alkunäkymän latautumisessa kestää 1-2,5 sekuntia, riippuen satunnaisen koirakuvan suuruudesta. 
Kirjausnäkymän lataumisessa kestää keskimäärin 900 ms.
