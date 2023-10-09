
## [EarTrumpet](https://github.com/File-New-Project/EarTrumpet)

### Ohjelma
- **Nimi:** EarTrumpet
- **Kuvaus:** Äänentoiston hallintaohjelma Windowsille. Parantaa oletusäänenvoimakkuusliukusäädintä lisäämällä samaan näkymään eri ohjelmien äänenvoimakkuuksien mikserin ja helpon tavan vaihtaa äänentoistolaitetta.

![Äänilaite, pää-äänenvoimakkuus ja mikseri](res/interface.png)
- **Toimintaperiaate:** EarTrumpetin käyttöliittymä on luotu [Windows Presentation Foundation](https://learn.microsoft.com/en-us/dotnet/desktop/wpf/overview/?view=netdesktop-7.0) -kirjastoa (WPF) käyttäen. Ohjelma näkyy Windowsin tehtäväpalkin oikeassa reunassa olevana äänenvoimakkuussymbolina (identtinen Windowsin oman kanssa), josta voi avata mm. äänimikserin ja ohjelman asetukset. EarTrumpet korvaa Windowsin oman äänentoistohallinnan käyttäen [Windows Multimedia Device API](https://learn.microsoft.com/en-us/windows/win32/api/_multimedia/):tä, mahdollistaen esimerkiksi yksittäisten ohjelmien äänilaitteiden vaihdon.[^toiminta]
- **Käyttökohteet:** Ohjelma on yleishyödyllinen, sillä lähes kaikkien tietokoneen käyttäjien täytyy muuttaa äänenvoimakkuutta joskus. Ohjelmasta voi olla erityisen paljon hyötyä sellaisessa toiminnassa, jossa äänilähdettä täytyy vaihtaa usein, tai käytettäessä kuulokkeita, joissa on korkea herkkyys (jolloin pää-äänenvoimakkuus pitää laittaa alhaiseksi ja hienosäätöä tehdä yksittäisten sovellusten säädöillä).

### Lisenssi
- **Lisenssi:** [Ohjelmisto on lisensoitu MIT-lisenssin alaisena.](https://github.com/File-New-Project/EarTrumpet/blob/master/LICENSE) MIT lisenssi on lyhyt ja yksinkertainen salliva lisenssi, jonka ehdoissa vaaditaan ainoastaan tekijänoikeus- ja lisenssi-ilmoitusten säilyttämistä. Lisensoituja teoksia, muutoksia ja laajempia teoksia voidaan jakaa eri ehdoilla ja ilman lähdekoodia.[^1]

### Projektin Aktiivisuus ja Ylläpito
- **Historia:** [Kuinka kauan projekti on ollut olemassa? Onko sillä ollut merkittäviä virstanpylväitä?] EarTrumpetin GitHub-repositorio luotiin heinäkuussa 2017. 29.9.2023 mennessä ohjelmalla on ollut 40 eri versiota, ja vuonna 2018 se siirtyi versiosta 1.x versioon 2.x.[^2] Tässä päivityksessä oli paljon uusia ominaisuuksia, ja projektin kehitys oli erityisen aktiivista.[^contributors]
- **Aktiivisuus:** Projektin aktiivisuus on vähentynyt vuoden 2019 jälkeen, mutta projektin dev-haaraan tehdään uusia muutoksia silloin tällöin[^dev], ja käyttäjien ongelmiin vastataan aktiivisesti. Ohjelmasta julkaistaan uusia versioita muutama vuodessa. Lisäksi vapaaehtoiset käyttäjät kääntävät ohjelman käyttöliittymää aktiivisesti eri kielille.[^kielet]
- **Ylläpito:** Projektin takana on kolmen hengen ryhmä [File-New-Project](https://github.com/File-New-Project), joka on tehnyt suurimman osan ohjelman kehityksestä ja ylläpidosta. Sen lisäksi koodia on kirjoittanut projektiin 24 muuta vapaaehtoista 29.9.2023 mennessä.[^contributors]

### Osallistuminen Projektiin
- **Contribution Model:** Projektissa ei taida olla varsinaisia rooleja tai vastuualueita osallistujille, vaan kaikki menettelevät saman kaavan mukaan. Projektiin voi osallistua issueilla tai pull requesteilla. Issuella osallistumiseen tulee bugien reportoinnin tapauksessa täyttää issue template. Mikäli asia koskee uusia ominaisuuksia tai kysymyksiä, siirtyy keskustelu projektin keskustelualueelle.[^3]  Pull requesteihin on toivottu menettelytapa. [^4]
- **Osallistumisen Menettelytavat:**

  Bugia reportoidessa pakollisia tietoja: 
  - Summary
  - Steps to reproduce
  - EarTrumpet version
  Valinnaisena:
  - Additional information

  Pull requesteilla osallistumisen toivotaan tapahtuvan seuraavan kaavan mukaan: 
  - Ensimmäiseksi, tulee etsiä tai tehdä uusi korjattava issue. 
  - Seuraava vaihe on ottaa yhteyttä projektin ylläpitotiimiin ja pyytää lupaa muutoksiin. 
  - Hyväksynnän jälkeen, tulee repositorio forkata ja tehdä siihen uusi branch "dev"-brachista, joka on nimetty tehtävien muutosten mukaan. 
  - Muutoksien jälkeen tulee tarkistaa muutoksien toimivuus buildaamalla projekti ja sen jälkeen puskea toimivat muutokset omaan forkkiin. 
  - Viimeinen vaihe on tehdä pull request juuriprojektin "dev"-branchiin.

### Tekninen Toteutus
- **Kielet:** [Mainitse käytetyt ohjelmointikielet]
- **Protokollat:** [Mainitse käytetyt protokollat]
- **Välineet:** [Mainitse tärkeimmät käytetyt työkalut ja resurssit]

### Projekti Käyntiin
- **Asennus ja Käyttöönotto:**
  -



[Voitte täydentää tätä pohjaa valitsemanne ohjelmiston tiedoilla ja lisätä tarvittaessa lisää tietoja tai kuvia ohjelmistosta.]

*Generated using ryhmätyö*

[^toiminta]: [EarTrumpet Technical Documentation](https://github.com/File-New-Project/EarTrumpet/blob/master/EarTrumpet/README.md)
[^1]: [choosealicense.com/licenses/mit](https://choosealicense.com/licenses/mit/)
[^2]: [CHANGELOG.md](https://github.com/File-New-Project/EarTrumpet/blame/master/CHANGELOG.md)
[^dev]: [Commits - dev-haara](https://github.com/File-New-Project/EarTrumpet/commits/dev)
[^kielet]: [EarTrumpet @ Crowdin](https://crowdin.com/project/eartrumpet)
[^contributors]: [EarTrumpet contributors](https://github.com/File-New-Project/EarTrumpet/graphs/contributors)
[^3]: [/issues/new/choose](https://github.com/File-New-Project/EarTrumpet/issues/new/choose)
[^4]: [CONTRIBUTING.md](https://github.com/File-New-Project/EarTrumpet/blob/master/CONTRIBUTING.md)
## [EarTrumpet](https://github.com/File-New-Project/EarTrumpet)

### Ohjelma
- **Nimi:** EarTrumpet
- **Kuvaus:** Äänentoiston hallintaohjelma Windowsille. Parantaa oletusäänenvoimakkuusliukusäädintä lisäämällä samaan näkymään eri ohjelmien äänenvoimakkuuksien mikserin ja helpon tavan vaihtaa äänentoistolaitetta.

![Äänilaite, pää-äänenvoimakkuus ja mikseri](res/interface.png)
- **Toimintaperiaate:** EarTrumpetin käyttöliittymä on luotu [Windows Presentation Foundation](https://learn.microsoft.com/en-us/dotnet/desktop/wpf/overview/?view=netdesktop-7.0) -kirjastoa (WPF) käyttäen. Ohjelma näkyy Windowsin tehtäväpalkin oikeassa reunassa olevana äänenvoimakkuussymbolina (identtinen Windowsin oman kanssa), josta voi avata mm. äänimikserin ja ohjelman asetukset. EarTrumpet korvaa Windowsin oman äänentoistohallinnan käyttäen [Windows Multimedia Device API](https://learn.microsoft.com/en-us/windows/win32/api/_multimedia/):tä, mahdollistaen esimerkiksi yksittäisten ohjelmien äänilaitteiden vaihdon.[^toiminta]
- **Käyttökohteet:** Ohjelma on yleishyödyllinen, sillä lähes kaikkien tietokoneen käyttäjien täytyy muuttaa äänenvoimakkuutta joskus. Ohjelmasta voi olla erityisen paljon hyötyä sellaisessa toiminnassa, jossa äänilähdettä täytyy vaihtaa usein, tai käytettäessä kuulokkeita, joissa on korkea herkkyys (jolloin pää-äänenvoimakkuus pitää laittaa alhaiseksi ja hienosäätöä tehdä yksittäisten sovellusten säädöillä).

### Lisenssi
- **Lisenssi:** [Ohjelmisto on lisensoitu MIT-lisenssin alaisena.](https://github.com/File-New-Project/EarTrumpet/blob/master/LICENSE) MIT lisenssi on lyhyt ja yksinkertainen salliva lisenssi, jonka ehdoissa vaaditaan ainoastaan tekijänoikeus- ja lisenssi-ilmoitusten säilyttämistä. Lisensoituja teoksia, muutoksia ja laajempia teoksia voidaan jakaa eri ehdoilla ja ilman lähdekoodia.[^1]

### Projektin Aktiivisuus ja Ylläpito
- **Historia:** [Kuinka kauan projekti on ollut olemassa? Onko sillä ollut merkittäviä virstanpylväitä?] EarTrumpetin GitHub-repositorio luotiin heinäkuussa 2017. 29.9.2023 mennessä ohjelmalla on ollut 40 eri versiota, ja vuonna 2018 se siirtyi versiosta 1.x versioon 2.x.[^2] Tässä päivityksessä oli paljon uusia ominaisuuksia, ja projektin kehitys oli erityisen aktiivista.[^contributors]
- **Aktiivisuus:** Projektin aktiivisuus on vähentynyt vuoden 2019 jälkeen, mutta projektin dev-haaraan tehdään uusia muutoksia silloin tällöin[^dev], ja käyttäjien ongelmiin vastataan aktiivisesti. Ohjelmasta julkaistaan uusia versioita muutama vuodessa. Lisäksi vapaaehtoiset käyttäjät kääntävät ohjelman käyttöliittymää aktiivisesti eri kielille.[^kielet]
- **Ylläpito:** Projektin takana on kolmen hengen ryhmä [File-New-Project](https://github.com/File-New-Project), joka on tehnyt suurimman osan ohjelman kehityksestä ja ylläpidosta. Sen lisäksi koodia on kirjoittanut projektiin 24 muuta vapaaehtoista 29.9.2023 mennessä.[^contributors]

### Osallistuminen Projektiin
- **Contribution Model:** Projektissa ei taida olla varsinaisia rooleja tai vastuualueita osallistujille, vaan kaikki menettelevät saman kaavan mukaan. Projektiin voi osallistua issueilla tai pull requesteilla. Issuella osallistumiseen tulee bugien reportoinnin tapauksessa täyttää issue template. Mikäli asia koskee uusia ominaisuuksia tai kysymyksiä, siirtyy keskustelu projektin keskustelualueelle.[^3]  Pull requesteihin on toivottu menettelytapa. [^4]
- **Osallistumisen Menettelytavat:**

  Bugia reportoidessa pakollisia tietoja: 
  - Summary
  - Steps to reproduce
  - EarTrumpet version
  Valinnaisena:
  - Additional information

  Pull requesteilla osallistumisen toivotaan tapahtuvan seuraavan kaavan mukaan: 
  - Ensimmäiseksi, tulee etsiä tai tehdä uusi korjattava issue. 
  - Seuraava vaihe on ottaa yhteyttä projektin ylläpitotiimiin ja pyytää lupaa muutoksiin. 
  - Hyväksynnän jälkeen, tulee repositorio forkata ja tehdä siihen uusi branch "dev"-brachista, joka on nimetty tehtävien muutosten mukaan. 
  - Muutoksien jälkeen tulee tarkistaa muutoksien toimivuus buildaamalla projekti ja sen jälkeen puskea toimivat muutokset omaan forkkiin. 
  - Viimeinen vaihe on tehdä pull request juuriprojektin "dev"-branchiin.

### Tekninen Toteutus
- **Kielet:**  
--C Sharp (C#)
-  **Protokollat:**
--  Windows Presentation Foundation (WPF)
--  Windows Multimedia Device API
-- Windows Storage tai rekisteri (Registry)
-- Bugsnag (virheraportointiin)
-- CircularBufferTraceListener
-- Windows Storage -luotettavuus (viitataan Windows.Storage.ApplicationData)
-- Platform Invoke (P/Invoke)
-- Platform Invoke (P/Invoke) -kääreet (wrappers)
--  Tyyppikirjasto (Type Library, TLB)
-- COM-liittymät (COM interfaces)
-- XAML (käytetään käyttöliittymän teemoittamiseen)
#### Välineet:
#### EarTrumpet.DataModel.AppInformation:
`AppInformationFactory` tuottaa `IAppInfo` -objektin prosessin tunnisteesta (PID). Tiedot (näytön nimi, kuvakkeen sijainti, taustaväri jne.) poistetaan ainutlaatuisesti työpöytä- ja modernista sovelluksesta.
#### EarTrumpet.DataModel.Audio
 - **IAudioDeviceManager:**
Hallitsee automaattisesti päivittyvää havainnollista kokoelmaa laitteista oletuslaitteella.
- **IAudioDevice:**
Kuvastaa äänilaitetta ja siihen liittyviä sovelluksia.
- **IAudioDeviceSession:**
Kuvastaa sovellusta, jolla on avoin äänisessio.
#### EarTrumpet.DataModel.Storage
Asetukset tallennetaan avain/arvo-tallennukseen, joka perustuu siihen, onko sovellus paketoitu vai ei (tukee Windows Storagea tai rekisteriä). `StorageFactory.GetSettings()` -toimintoa käytetään asetusten hakemiseen ja tallentamiseen.
####  EarTrumpet.DataModel
- **SystemSettings:** 
 Pääsee käsiksi käyttäjän mukautettuihin Windows-asetuksiin, jotka edustavat käyttäjän personointi-, saavutettavuus- ja globalisaatioasetuksia.
- **ProcessWatcherService:**
`ProcessWatcherService` käyttää taustasäiettä odottaakseen (käyttäen `WaitForMultipleObjects`) luetteloa prosessin kahvoista - prosesseista, joilla EarTrumpetilla on äänisessioita - ja odottaa niiden saamista signaalia. Tämä säie odottaa vain 5 sekuntia kerrallaan ja lähettää ilmoituksia lopetetuista prosesseista.

#### EarTrumpet.DataModel.WindowsAudio
Tarjoaa Windows-äänitoteutuksen `IAudioDeviceManager` ja siihen liittyvät rajapinnat.

#### EarTrumpet.Diagnosis

- **Bugsnag:**
Käyttää Bugsnagia virheiden raportointipalveluna. Turvalliset (TLS) yhteydet luodaan notify.bugsnag.comiin ilmoitushetkellä.

- **CircularBufferTraceListener:**
Sisältää pienen sisäisen lokiviestien puskurin, jotka näytetään vain käyttäjän pyynnöstä.

 - **ErrorReporter:**
Kapseloi Bugsnag-yhteyden ja hallitsee ilmoituksen lähettämiseen käytettyjä metatietoja.

- **LocalDataExporter:**
Muuntaa `IAudioDeviceManager` -datan merkkijonoksi vianmääritystarkoituksiin käyttäjän pyynnöstä.

- **SnapshotData:**
Sisältää metatietolomakkeet, jotka täytetään kaatumisilmoituksen yhteydessä tai käyttäjän pyynnöstä.

#### EarTrumpet.Extensibility
Sisältää tuen lisäosien lataamiseen. 
Lisäosien on toteutettava yksi `IAddonLifecycle` ulkoisen lisäosan kokoonpanossa.

#### EarTrumpet.Extensibility.Hosting
`AddonManager` käyttää `AddonResolver`ia lataamaan kaikki soveltuvat lisäosat `AddonHost`iin (`AddonManager.Host`), josta niihin voidaan käyttää suoraan.

####  EarTrumpet.Extensibility.Shared
Isännöi **vaadittuja** globaaleja tietoja.
- **ServiceBus:**
Käytetään lisäosien välistä viestintää varten. Lisäosa voi rekisteröityä `ApplicationLifecycleEvent.Startup`issa ja toinen voi noutaa palvelun `ApplicationLifecycleEvent.Startup2`issa.

#### EarTrumpet.Interop
Sisältää Platform Invoke (P/Invoke) -määrittelyt ja rajapinnat.

#### EarTrumpet.Interop.Helpers

Sisältää P/Invoke-kääreitä.

#### EarTrumpet.Interop.MMDeviceAPI

Sisältää ydinäänikommunikaation COM-rajapinnat ja määrittelyt, jotka on luotu `mmdevapi.idl`:stä. Tämä tehdään vieden se Tyypin kirjastoon (TLB), tuoden sen Visual Studioon ja kopioimalla sitten luodut artefaktit.

#### EarTrumpet.UI
##### EarTrumpet.UI.Helpers
- **ShellNotifyIcon:** 
`Shell_NotifyIcon` kutsutaan suoraan, koska `System.Windows.Forms.NotifyIcon` ei tue uutta `NOTIFICATIONDATAW` -rakennetta, joka sisältää `guidItem` -jäsenen. Tämä mahdollistaa Windows Shellin siirtää ilmoituksen kuvakkeen asetuksia, kun sovelluksen asennuskohde muuttuu.

#### EarTrumpet.UI.Themes

Sisältää WPF XAML -resursseja, joita käytetään käyttöliittymän asettamiseen vastaamaan Windows-tyylisen käyttöliittymän asetuksia.

EarTrumpet tukee kaikkia Windowsin teema-asetuksia:

-   Korkea kontrasti
-   Vaalea tai tumma teema (järjestelmän tai sovelluksen mukaan)
-   Korostusväri (käytetään vain tummassa teemassa)
-   Läpinäkyvyys (käytetään kaikissa paitsi korkeassa kontrastissa)
####  Build
EarTrumpet suuntautuu vain x86:lle. Jotkin P/Invoke -kutsut on päivitettävä, jos suuntaudutaan x64:lle tai muille alustoille.
- **Ennakkokääntämiskomentosarja: prebuild.ps1:**
Päivittää `AssemblyInfo.cs` (binääritiedoston versioinformaatio) ja paketin `AppxManifest.xml` pidetään synkronoituna. `Version.txt` on totuuden lähde versiolle.

#### Vianmääritys
EarTrumpetia voi vianmäärityksen kautta käyttää `EarTrumpet` -projektin kautta tai `EarTrumpet.Package` -projektin kautta, joka on hitaampi mutta mahdollistaa pakatun sovelluksen vianmäärityksen.

- **VSDebug -määritys:**

`VSDebug` -tila mahdollistaa seuraavat ominaisuudet verrattuna `Debug` -tilaan:
-   `TemporaryAppItemViewModel` on merkitty punaisella taustavärillä.
-    Vältä sovellustunnistuksen tarkistusta, joka aiheuttaa käsitellyn käynnistysvirheen.




### Projekti Käyntiin
- **Asennus ja Käyttöönotto:**
  --[*Microsoft Store*](https://www.microsoft.com/store/apps/9nblggh516xp)
  --[*Windows Package Manager Client*](https://github.com/microsoft/winget-cli) komennolla: `winget install File-New-Project.EarTrumpet` 
  --*Chocolatey* komennolla: `choco install eartrumpet`


*Generated using ryhmätyö*

[^toiminta]: [EarTrumpet Technical Documentation](https://github.com/File-New-Project/EarTrumpet/blob/master/EarTrumpet/README.md)
[^1]: [choosealicense.com/licenses/mit](https://choosealicense.com/licenses/mit/)
[^2]: [CHANGELOG.md](https://github.com/File-New-Project/EarTrumpet/blame/master/CHANGELOG.md)
[^dev]: [Commits - dev-haara](https://github.com/File-New-Project/EarTrumpet/commits/dev)
[^kielet]: [EarTrumpet @ Crowdin](https://crowdin.com/project/eartrumpet)
[^contributors]: [EarTrumpet contributors](https://github.com/File-New-Project/EarTrumpet/graphs/contributors)
[^3]: [/issues/new/choose](https://github.com/File-New-Project/EarTrumpet/issues/new/choose)
[^4]: [CONTRIBUTING.md](https://github.com/File-New-Project/EarTrumpet/blob/master/CONTRIBUTING.md)
