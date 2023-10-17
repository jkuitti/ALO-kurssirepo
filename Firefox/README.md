## Firefox

### Ohjelma

- **Nimi:** \[Lisää ohjelman nimi\]
- **Kuvaus:** \[Lyhyt kuvaus ohjelmasta\]
- **Toimintaperiaate:** \[Kuvaile lyhyesti miten ohjelmisto toimii\]
- **Käyttökohteet:** \[Missä tilanteissa tai organisaatioissa ohjelmistoa yleisesti käytetään\]

### Lisenssi

- **Lisenssi:** \[Mainitse ohjelmiston käyttämä lisenssi\]

### Projektin Aktiivisuus ja Ylläpito

- **Historia:** \[Kuinka kauan projekti on ollut olemassa? Onko sillä ollut merkittäviä virstanpylväitä?\]
- **Aktiivisuus:** \[Kuinka usein projektissa tehdään päivityksiä ja korjauksia?\]
- **Ylläpito:** \[Kuka tai ketkä ylläpitävät projektia?\]

### Osallistuminen Projektiin

- **Contribution Model:** \[Miten projektiin voi osallistua? Onko olemassa tiettyjä rooleja tai vastuita?\]
- **Osallistumisen Menettelytavat:** \[Kuinka voit osallistua projektiin?\]
___
### Tekninen Toteutus
**Kielet:**
- Eniten käytetyt kielet ovat:  C++, JavaScript, HTML, C, Rust, Python, XML, Assembly
	- Vähän yli puolet koodista on C++ ja Javascriptiä

![Firefoxin koodin jakauma ohjelmointikielten perusteella](res/language_breakdown.png)
- Syyskuussa 2023 Firefoxin lähdekoodiin lisättiin yli 720,000 riviä Rust koodia. Tämä on suurin määrä koodia, mitä projektiin on lisätty yksittäisen kuukauden aikana koko sen historiassa.[^languages]
	![Satoja tuhansia rivejä Rust koodia lisättiin Firefoxin lähdekoodiin Syyskuussa 2023](res/loc_by_language.png)
	
**Protokollat:**
Selaimena Firefox käyttää useita erilaisia protokollia, joista muutamia tärkeimpiä tai mielenkiintoisimpia ovat:
- **HTTP/HTTPS** selaimen ja verkkosivujen väliseen kommunikointiin.[^http] [^https]
- **WebRTC protokollat**, kuten *ICE*, *STUN*, ja *TURN* mahdollistavat esimerkiksi video- ja äänipuhelut, sekä tiedostojen jakamisen suoraan selaimessa.[^webrtc]
- Googlen **safebrowsing** protokolla, joka varoittaa vaarallisista tai harhaanjohtavista verkkosivuista, sekä tiedostoista jotka sisältävät viiruksia.[^safebrowsing]

**Välineet:**
 - **Mercurial**. Lähdekoodin ja versionhallinta
 - **MDN Web Docs**. Dokumentaatiota web teknologioista ja Firefoxista.
 - **Developer tools**. Erilaisia selaimeen sisäänrakennettuja työkaluja, joilla on mahdollista analysoida, testata, ja debugata selaimen tai verkkosivujen eri ominaisuuksia.
___
### Projekti Käyntiin
**Windows:**<br> Mozillan omilta [sivuilta](https://www.mozilla.org/en-US/firefox/all/) saa helppokäyttöisen installerin, jolla selaimen asentaminen tapahtuu.

**Linux:**<br> Jakelusta riippuen Firefoxin asentaminen voi tapahtua usealla eri tavalla. Useimpien jakeluiden paketinhallintajärjestelmistä löytyy jonkilainen Firefox paketti. Jos Firefox ei kuitenkaan ole valitun jakelun omassa paketinhallintajärjestelmässä, voi sen asentaa esimerkiksi flatpack tai snap paketinhallintajärjestelmillä. Asennus tapahtuu seuraavasti esimerkiksi:
- Debian: `sudo apt install firefox-esr`
- Fedora: `sudo dnf install firefox`
- Snap: `sudo snap install firefox`
- Flatpak: `flatpak install flathub org.mozilla.firefox`

**Mac:**<br>Kuten Windowsilla, oikean version Firefoxin asennustyökalusta saa samalta [sivulta](https://www.mozilla.org/en-US/firefox/all/), joka automaattisesti tunnistaa, että käytät Mac laitetta ja tarjoaa sinulle sopivan paketin.

#### Kääntäminen lähdekoodista:
Mozilla tarjoaa ohjeet Firefoxin kääntämiseen lähdekoodista [Windowsilla](https://firefox-source-docs.mozilla.org/setup/windows_build.html), [Linuxilla](https://firefox-source-docs.mozilla.org/setup/linux_build.html), ja [Mac:illä](https://firefox-source-docs.mozilla.org/setup/macos_build.html). 

*Vaiheittaiset ohjeet jätetty suoraan kopioimatta tästä tilaa, ja lukijan mielenterveyttä säästääksi.*

[^languages]: [Open Hub - Mozilla Firefox](https://openhub.net/p/firefox/analyses/latest/languages_summary)
[^http]:[MDN Web Docs - HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP)
[^https]:[MDN Web Docs - HTTPS](https://developer.mozilla.org/en-US/docs/Glossary/HTTPS)
[^webrtc]:[MDN Web Docs - WebRTC](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API/Protocols)
[^safebrowsing]:[Support Mozilla - How does built-in Phishing and Malware Protection work?](https://support.mozilla.org/en-US/kb/how-does-phishing-and-malware-protection-work)

