## Valittu Vapaan Lähdekoodin Ohjelmisto

### Ohjelma
- **Nimi:** Pi-Hole
- **Kuvaus:** Pi-Hole on Linux-pohjainen ohjelma, joka estää mainoksia ja Internet-seurantaa verkossa toimimalla DNS-"sinkkinä" ja valinnaisesti DHCP-palvelimena. Se on tarkoitettu käytettäväksi yksityisessä verkossa, eikä se vaadi asiakaspuolen ohjelmistoja.
- **Toimintaperiaate:** Pi-Hole vastaanottaa verkon laitteiden DNS-kyselyt ja vertaa niitä mustiin listoihin, jotka sisältävät tunnettuja mainos- ja seurantadomaineja. Jos kysytty domain löytyy mustalta listalta, Pi-Hole palauttaa tyhjän vastauksen tai oman IP-osoitteensa, jolloin mainos tai seuranta estyy. Jos domain ei löydy mustalta listalta, Pi-Hole välittää kyselyn ylöspäin määritellylle ylätason DNS-palvelimelle ja palauttaa sen vastauksen laitteelle
- **Käyttökohteet:** Pi-Holea käytetään yleisesti kotiverkoissa, pienissä yrityksissä ja kouluissa, jotka haluavat suojata laitteitaan ei-toivotulta sisällöltä, parantaa verkon suorituskykyä ja säästää kaistanleveyttä. Pi-Holea voidaan myös käyttää VPN:n kanssa, jolloin mainosten esto toimii myös mobiililaitteilla.

### Lisenssi
- **Lisenssi:** European Union Public License. Sallii ohjelmiston käytön, kopioinnin, muokkaamisen ja jakamisen ilmaiseksi.

### Projektin Aktiivisuus ja Ylläpito
- **Historia:** Pi-Hole-projekti alkoi vuonna 2014 Reddit-ketjusta, jossa keskusteltiin Raspberry Pi:n käyttämisestä mainosten estämiseen. Vuonna 2015 projekti sai oman verkkosivun ja GitHub-repositorion. Vuonna 2016 projekti sai ensimmäisen rahoituskampanjansa ja vuonna 2017 se sai EUPL-lisenssin. Vuonna 2018 projekti sai uuden Web-käyttöliittymän ja FTL-komponentin, joka paransi DNS-kyselyjen käsittelyä. Vuonna 2019 projekti sai uuden logon ja brändin sekä tuen IPv6:lle.
- **Aktiivisuus:** Projekti saa säännöllisesti päivityksiä ja korjauksia. Viimeisen päivitys (päivitys nr.100!!) on Toukokuun lopulta. Projektia on forkattu 2500 kertaa ja sillä on yli 43 tuhatta tähteä. Committeja on 5760.
- **Ylläpito:** Projektia ylläpitää vapaaehtoinen kehittäjien tiimi, joka koostuu tällä hetkellä kolmesta pääkehittäjästä ja muutamasta avustajasta. Projektia kehitetään täysin vapaa-ajalla.

### Osallistuminen Projektiin
- **Contribution Model:** Pi-Hole-projektiin voi osallistua monella tavalla, kuten raportoimalla ongelmia, ehdottamalla uusia ominaisuuksia, luomalla vetopyyntöjä tai lahjoittamalla rahaa.
- **Osallistumisen Menettelytavat:** Pi-Hole-projektiin voi osallistua GitHubin kautta, jossa on projektin lähdekoodi, dokumentaatio ja ongelmaraportit. Projektilla on myös oma verkkosivu, foorumi, Discord-kanava ja Reddit-yhteisö, joissa voi keskustella projektista ja saada tukea.

### Tekninen Toteutus
- **Kielet:** Bash, PHP, JavaScript, Python ja C
- **Protokollat:** DNS, DHCP, HTTP, HTTPS
- **Välineet:** Docker, Shell-skripti, SQLite, Lighttpd, dnsmasq

### Projekti Käyntiin
- **Asennus ja Käyttöönotto:** Pi-Hole-projektin saa toimimaan asentamalla sen tuetulle Linux-käyttöjärjestelmälle tai Docker-konttiin. Asennus on helppoa ja nopeaa käyttämällä automaattista asennusskriptiä2. Asennuksen jälkeen Pi-Hole voidaan konfiguroida Web-käyttöliittymän tai komentorivin kautta. Pi-Hole vaatii verkon laitteiden käyttävän sitä DNS-palvelimenaan, joten se pitää määrittää reitittimen tai laitteiden asetuksissa.

[Voitte täydentää tätä pohjaa valitsemanne ohjelmiston tiedoilla ja lisätä tarvittaessa lisää tietoja tai kuvia ohjelmistosta.]

*Generated using GPT-3.5*
