# Nuking Discord Server Bot/Nuke Bot
## Tehnyt Ossi ja Vili (Tietoturva)

Nopea ja ilmainen nuke botti


Olemme tehneet erittäin helppokäyttöisen botin

Python-versio 3.8.0 tai uudempi vaaditaan, jos aiot suorittaa tiedoston lähdekoodista.

[Kaikki 51 komentoa](manual.md)

```
[addRole] [addChannel] [autoNick] [addVoiceChannel] [autoStatus] 
[addEmoji] [addCategory] [banAll] [bans] [ban] [channelBomb] 
[categoryBomb] [config] [checkRolePermissions] [connect] [categories] 
[changeStatus] [channels] [deleteRole] [deleteChannel] 
[deleteVoiceChannel] [deleteCategory] [deleteCC] [deleteEmoji] 
[deleteAllRoles] [deleteAllChannels] [disableCommunityMode] 
[deleteAllEmojis] [deleteAllWebhooks] [emojis] [grantAllPerm] 
[help] [joinNuke] [kaboom] [leave] [leaveAll] [link] [moveRole] 
[members] [nuke] [off] [purge] [roles] [roleBomb] [roleTo] [servers] 
[serverIcon] [serverName] [unban] [voiceChannels] [webhook] 
```

# TÄRKEÄÄ:
* Emme ota mitään vastuuta kaikesta, mitä aiot tehdä tämän botin kanssa.
* Botin on silti noudatettava [palvelinrajoituksia](https://discordia.me/en/server-limits), koska ristiriidassa on nopeusrajoituksia. Näet paljon nopeusrajoituksia konsolissa, kun käytät joitain komentoja. (koska botti on liian nopea luodessaan tai poistaessaan.)
* Lisäksi, koska käytämme HTTP-pyyntöjä, toisin kuin muut nuke-botit, C-REAL-roskapostia luova kanava, rooli ja luokka (CRC) voi luoda yli 250 CRC:n rajan, joka vanhoilla nuking-botteilla on.


* Viesti niille koodausmestareille, jos näet jotain, mitä voimme parantaa koodissamme, voit tehdä vetopyynnön. Tämä auttaa meitä todella paljon. :)


## Miksi tietokoneeni sanoi, että se on vaarallinen tiedosto/sisältää viruksen?
* Aion tehdä itselleni selväksi - se ei ole virus.
* Ihmisille, jotka eivät luota julkaistuihin versioihin ja jotka eivät halua ladata pythonia, on toinenkin tapa käyttää bottia. Käytä https://repl.it/, luo tili, valitse "uusi repl" vasemmasta yläkulmasta, valitse python, klikkaa "luo repl", kopioi ja liitä [lähdekoodi] repliin ja napsauta yläreunassa olevaa Suorita-painiketta.

## Pääkäyttö (Lue `.config` komento alla ennen yhteydenottoa)


## Oppaat
### 2.4-asennus
* Suorita .exe tai .py
* Näet "Syötä tunnus" -viestin. Voit syöttää selfbot-tunnuksen tai normaalin bot-tunnuksen
* Seuraavaksi näet "Syötä käyttäjätunnus tai tunniste", sinun tulee kirjoittaa käyttäjätunnus tai tagi, jolla halusit komentaa bottia. Kaikki komentooikeudet myönnetään käyttäjälle, jolla on tähän antamasi tunnus tai tagi.
* Jos haluat tietää, mitä komentoja siellä on, suorita `.help'
* Jos haluat määrittää asetuksia, kuten after-komentoja tai webhook-roskapostikomentoja, sinun on käytettävä `.config-komentoa. Lisätietoja asetusten määrittämisestä on `.config`-komennossa.
* Jos sinulla on ongelmia, voit tehdä ongelman tällä github-sivulla.


## Ongelmia/ongelmia
* Jos kohtaat kaatumisen, ilmoita siitä [github-sivun] "ongelmiin"
* Jos botti ei vastaa mihinkään komentoihin, tarkista, onko konsoli korostus-/merkintätilassa. Jos se on korostus-/merkintätila, napsauta konsolia ja paina mitä tahansa näppäimistön näppäintä, niin se korjaantuu.
* Jos näet konsolissa joukon valkoisia virheitä, jotka sitten kaatuvat, se tarkoittaa, että se on 90 % virhe. Joten tee siitä uusi numero.


##Lue lisää uwuWhat'sThis.md tiedostosta
