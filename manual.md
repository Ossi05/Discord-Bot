

# Tunnettuja ongelmia

Selfbot - ei pysty havaitsemaan kaikkia palvelimen jäseniä. Hae jäsenet -komento lisätään 2.4:ssä tai uudemmassa, mukaan lukien massa-DM.

# Komennot asiakirja

Kaikki komennot eivät erota kirjainkoosta.

\[a] - pakollinen argumentti

{a} - valinnainen argumentti

\[a='1'] tai {a='1'} - a on oletuksena 1.

[a#Tämä on kommentti] tai {a#Tämä on kommentti}

\[] - väittelyä ei tarvita

# kuvausta kirjoitetaan pian...
### `addChannel`

* aliakset: "aCh", "aChannel".
* kuvaus: Lisää kanavan palvelimeen, johon olet yhteydessä.
* parametrit: \[nimi#Ei välilyöntejä sallittu] {category=Ei mitään#Välilyöntejä sallittu}

### `addRole`

* aliakset: "aRole", "aR".
* kuvaus: Lisää roolin palvelimeen, johon olet yhteydessä.
* params: \[roleName#Välilyönnit sallittu, mutta nimien ei voi päättyä numeroihin] {rolePermissions#Käytä roolilupien laskinta, joka löytyy builder.html:stä, ja laita se roolin nimi välilyönnillä erotettuna}

### `addEmoji`

* aliakset: "aEmoji", "aEm".
* kuvaus: Lisää emojin palvelimeen, johon olet yhteydessä.
* params: \[item#Voit käyttää linkkiä, discord mukautettuja hymiöitä tai tietokoneen tiedostopolkua] {nimi#Ei välilyöntejä; tämä vaaditaan vain, kun käytät linkkiä ensimmäisessä argssa}

### `addVoiceChannel`

* aliakset: "aVoiceChannel", "aVC".
* kuvaus: Lisää äänikanavan palvelimeen, johon olet yhteydessä.
* parametrit: \[nimi#Ei välilyöntejä] {category=Ei mitään#välilyönnit sallittu}

### `addCategory`

* aliakset: "aCat", "aCa".
* kuvaus: Lisää kategorian palvelimeen, johon olet yhteydessä.
* parametrit: \[nimi#välilyönnit sallittu]

### `kielto`

* aliakset: Ei komentoa * aliaksia tarjotaan.
* kuvaus: Panee jonkun palvelimeen, johon olet yhteydessä.
* parametrit: \[käyttäjä#Ping, tunnus tai pelkkä käyttäjänimi. Jos samoja käyttäjätunnuksia on kaksi tai useampia, komentosarja valitsee aina ensimmäisen]

### `kiellä kaikki`

* aliakset: Ei komentoa * aliaksia tarjotaan.
* kuvaus: estää kaikki mahdolliset yhdistetyllä palvelimella.
* parametrit: \[]

### `kiellot`

* aliakset: Ei komentoa * aliaksia tarjotaan.
* kuvaus: Näyttää kaikki kiellot palvelimella, johon olet yhteydessä.
* parametrit: {pageNumber=1}

### `poista porttikielto`

* aliakset: Ei komentoa * aliaksia tarjotaan.
* kuvaus: Poistaa porttikiellon palvelimelta.
* Perams: .unban @user#0000

### `channelBomb`

* aliakset: Ei komentoa * aliaksia tarjotaan.
* kuvaus: Tekee paljon satunnaisia ​​kanavia yhdistetylle palvelimelle.
* parametrit: \[numberOfBombs#Luottavien kanavien määrä] \[bombType#Se voi olla vain b64, an tai kiinteä]

### `kategoriapommi`

* aliakset: Ei komentoa * aliaksia tarjotaan.
* kuvaus: Tekee paljon satunnaisia ​​luokkia yhdistetyssä palvelimessa.
* parametrit: \[numberOfBombs#Luottavien luokkien määrä] \[bombType#Se voi olla vain b64, an tai kiinteä]

### `kanavat`

* aliakset: "tc", "textchannels", "textchannel", "channel"
* kuvaus: Näyttää kanavat, jotka ovat palvelimella, johon olet yhteydessä.
* parametrit: {pageNumber=1}

### `tarkista RolePermissions`

* aliakset: `check`, `crp`
* kuvaus: Tarkistaa kaikki roolit, jotka sinulla on.
* parametrit: \[käyttäjä#Ping, tunnus tai pelkkä käyttäjänimi. Jos samoja käyttäjätunnuksia on kaksi tai useampia, komentosarja valitsee aina ensimmäisen]

### "luokat".

* aliakset: "kissa", "luokka".
* kuvaus: Näyttää luokat, jotka ovat palvelimessa, johon olet yhteydessä.
* parametrit: {pageNumber=1}

### `tyhjennä`

* aliakset: `purge`
* kuvaus: Poistaa tietyn määrän viestejä kanavalta, jossa käytät tätä komentoa.
* params: {numberOfMessages=All#Jätä tämä tyhjäksi, jos haluat, että kanavan kaikki viestit poistetaan, mutta kanavan vakava poistaminen olisi paljon helpompaa}

### `muuta tilaa`

* aliakset: "cs".
* kuvaus: Muuttaa botin tilaa.
* parametrit: \[status#offline, invisible, dnd (tai do_not_disurb), online tai idle.]

### `automaattinen tila`

* aliakset: "as".
* kuvaus: Kytkee automaattisesti botin tilan päälle/pois päältä.
* parametrit: ei mitään

### `autonick`

* aliakset: "an".
* kuvaus: Muuttaa automaattisesti botin lempinimen.
* parametrit: ei mitään

### `yhdistä`

* aliakset: `con`
* kuvaus: yhdistää botin palvelimeen.
* parametrit: \{palvelin#tunnus tai palvelimen nimi ja unicode-käyttäjänimi on sallittu. Jos käytät tätä komentoa palvelimessa, johon haluat muodostaa yhteyden, sinun ei tarvitse laittaa argumenttia tähän, jos näin on}

### `deleteRole`

* aliakset: "dRole", "dR".
* kuvaus: Poistaa roolin palvelimelta, johon olet yhteydessä.
* parametrit: \[role#name tai id]

### `poista kanava`

* aliakset: "dChannel", "dCh".
* kuvaus: Poistaa kanavan palvelimelta, johon olet yhteydessä.
* parametrit: \[kanavan#nimi tai tunnus]

### `deleteVoiceChannel`

* aliakset: "dVC", "dVoiceChannel".
* kuvaus: Poistaa äänikanavan palvelimelta, johon olet yhteydessä.
* parametrit:

### `deleteCategory`

* aliakset: "dCat", "dCategory".
* kuvaus: Poistaa kategorian palvelimelta, johon olet yhteydessä.
* parametrit:

### `deleteCC`

* aliakset: "dCC".
* kuvaus: Poistaa kanavan, äänikanavan tai luokan palvelimelta, johon olet yhteydessä.
* parametrit: \[nimi#tai tunnus]

##

### `deleteEmoji`

* aliakset: `dEm`
* kuvaus: Poistaa emojin palvelimelta, johon olet yhteydessä.
* parametrit: \[emoji#nimi tai tunnus]

### `DisableCommunityMode`

* aliakset: "dCM", "dCommunityMode".
* kuvaus: Poistaa yhteisötilan käytöstä palvelimessa, johon olet yhteydessä.
* parametrit: Ei mitään

### `deleteAll Roles`

* aliakset: "dar", "dAllRoles".
* kuvaus: Poistaa kaikki roolit yhdistetystä palvelimesta.
* parametrit: \[]

### `poista kaikki kanavat`

* aliakset: "dac", "dAllChannels".
* kuvaus: Poistaa kaikki kanavat yhdistetystä palvelimesta.
* parametrit: \[]

### `deleteAllEmojis`

* aliakset: "dae", "dAllEmoji".
* kuvaus: Poistaa kaikki emojit yhdistetystä palvelimesta.
* parametrit: \[]

### `deleteAllWebhooks`

* aliakset: "daw", "dAllWebhooks".
* kuvaus: Poistaa akk webhookit yhdistetystä palvelimesta.
* parametrit: \[]

### "emojit".

* aliakset: Ei komentoa * aliaksia tarjotaan.
* kuvaus: Näyttää emojit, jotka ovat palvelimella, johon olet yhteydessä.
* parametrit: {pageNumber=1}

### `apua`

* aliakset: "h", "komennot".
* kuvaus: Näytä kaikki komennot. args: [Valinnainen: tyyppi: kaikki/nimet/komento: oletus=nimet] [Valinnainen: n: sivun n]
* params: {type=all#all/names/command vain leikkiä tällä. Sen pitäisi olla erittäin helppo ymmärtää.} {pageNumber=1#for type command}

### `joinNukeen`

* aliakset: `nukeOnJoin`, `join nuke`
* kuvaus: Nuke-komento suoritetaan seuraavassa palvelimessa, johon botti liittyy.
* parametrit: [boolean#True or false. Totta tarkoittaa, että kytke se päälle. Ja väärä tarkoittaa, että se sammutetaan]

### `kaboom`

* aliakset: Ei komentoa * aliaksia tarjotaan.
* kuvaus: Yhdistää kanavan Bomb, categoryBomb ja categoryBomb kaikki yhdeksi komennosta.
* parametrit: \[numberOfBombs#Luottavien kanavien, luokkien ja roolien määrä] \[bombType#Se voi olla vain b64, an tai kiinteä]

### `lähde`

* aliakset: Ei komentoa * aliaksia tarjotaan.
* kuvaus: Poistuu palvelimelta, jonka päätät poistua.
* parametrit: {palvelin#nimi tai tunnus. Jos arg-tiedostoa ei anneta, botti poistuu palvelimelta, johon se muodostaa yhteyden}

### `jätä kaikki`

* aliakset: Ei komentoa * aliaksia tarjotaan.
* kuvaus: Jättää kaikki palvelimet, joissa se on.
* parametrit: \[]

### `linkki`

* aliakset: `l`
* kuvaus: lähettää kutsukoodin bottiin.
* parametrit: \[]

### `moveRole`

* aliakset: "mRole", "mR".
* kuvaus: Siirtää annettua roolia hierarkiassa (jos sinulla on käyttöoikeudet) palvelimessa, johon olet yhteydessä.
* parametrit: \[rooli#nimi tai tunnus. Välilyönnit ovat sallittuja] \[sijainti#sijainti hierarkiassa. Viimeinen välilyönnillä erotettu argumentti lasketaan, ja sillä on sijainti]

### "ydin".

* aliakset: Ei komentoa * aliaksia tarjotaan.
* kuvaus: yhdistää banAll-, deleteAllChannels-, deleteAllEmojis-, deleteAllRoles-, deleteAllWebhooks-komennot yhdeksi suureksi komennot. Muuttaa myös yhdistettyjen palvelimien nimeä ja kuvaketta. Lisäksi se suorittaa komentoja "jälkeen" sisällä nukingin jälkeen.
* parametrit: {useAfter=True#True or false. Jos et halua suorittaa konfigurointitiedostoon kirjoittamiasi after-komentoja, voit asettaa tämän arvoon false}

### `pois`

* aliakset: "logout", "logoff", "shutdown", "stop"
* kuvaus: Sammuttaa botin.
* parametrit: \[]

### "roolipommi".

* aliakset: Ei komentoa * aliaksia tarjotaan.
* kuvaus: Tekee paljon satunnaisia ​​rooleja yhdistetyssä palvelimessa.
* parametrit: \[numberOfBombs#Luottavien roolien määrä] \[bombType#Se voi olla vain b64, an tai kiinteä]

### "roolit".

* aliakset: "ro", "rooli".
* kuvaus: Näyttää roolit, jotka ovat palvelimessa, johon olet yhteydessä.
* parametrit: {pageNumber=1}

### "rooli"

* aliakset: Ei komentoa * aliaksia tarjotaan.
* kuvaus: Antaa roolin jollekin yhdistetyssä palvelimessa.
* parametrit: \[käyttäjän#tunnus tai vain ping] \[rooli#nimi tai tunnus]

### `palvelinkuvake`

* aliakset: `si`, `changeServerIcon`
* kuvaus: Muuttaa palvelinkuvaketta yhdistetyssä palvelimessa.
* parametrit: \[item#Voit käyttää linkkiä, discord mukautettuja hymiöitä tai tietokoneen tiedostopolkua]

### `palvelimet`

* aliakset: "se", "palvelin".
* kuvaus: Näyttää palvelimet, joissa botti on.
* parametrit: {pageNumber=1}

### `palvelimenNimi`

* aliakset: `sn`, `changeServerName`
* kuvaus: Muuttaa palvelimen nimeä yhdistetyssä palvelimessa.
* parametrit: \[nimi#Unicode on sallittu]

### `poista porttikielto`

* aliakset: Ei komentoa * aliaksia tarjotaan.
* kuvaus: Poistaa porttikiellon palvelimelta, johon olet yhteydessä.
* parametrit: \[käyttäjän#nimi, tunnus tai ping]

### `äänikanavat`

* aliakset: "vc", "voicechannel".
* kuvaus: Näyttää äänikanavat, jotka ovat palvelimessa, johon olet yhteydessä.
* parametrit: {pageNumber=1}

### `webhook`

* aliakset: "webhooks", "wh".
* kuvaus: Luo, hyökkää, luettelee kaikki yhdistetyn palvelimen webhookit.
* parametrit: {pageNumber=1}
