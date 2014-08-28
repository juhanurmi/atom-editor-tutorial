# Atom - kehittynyt ohjelmointiympäristö

[Atom-editori][Atom] on yksinkertainen, helppokäyttöinen ja tehokas ohjelmointiympäristö.

Sillä on mahdollista koodata kaikilla kielillä ja automatisoida työtään. 

Useat paketit tarjoavat koodin validointia ja tyylin tarkastusta sekä tietysti syntaksivärityksen.

## Paketit

Atom-editoria on yksinkertaista laajentaa erilaisilla lisäosilla (paketit/packages).

Lisäosia voi kirjoitta itse tai asentaa pakettienhallinnasta.

Katso [tarjolla olevat lisäosat][Packages].

## Atom lähettää Google Analytic:lle tilastotietoja

### Metrics package

Automaattisesti mukana tuleva paketti, joka kerää dataa [Google Analytics][GA]:lle.

Seurannan voi ottaa pois päältä Metrics-paketin asetuksista.

#### Google Analytics:lle menevät tiedot

* ID, joka on [SHA-1][SHA1]-tiiviste tietokoneen [MAC address][MAC]-osoitteesta.
* Näytön resoluutio
* Atom-editorin versio
* Mitkä paneelit ovat auki
* Jokaisen ikkunan aukioloaika
* Ikkunoiden latausajat
* Atom-editorin käynnistämiseen kulunut aika

[Atom]: https://atom.io/
[Packages]: https://github.com/atom
[GA]: http://www.google.com/analytics
[MAC]: http://en.wikipedia.org/wiki/MAC_address
[SHA1]: http://en.wikipedia.org/wiki/SHA-1
