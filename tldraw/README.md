## Valittu Vapaan Lähdekoodin Ohjelmisto

### Ohjelma
- **Nimi:** TlDraw
- **Kuvaus:** tldraw on React-kirjasto, joka on suunniteltu luomaan valkotauluja.
- **Toimintaperiaate:**
  - tldraw'n avulla voi upottaa sovellukseen täysin varustellun ja laajennettavan valkotaulun käyttämällä <Tldraw> React-komponenttia.
  - Monen ihmisen samanaikaista yhteistyö käyttöä varten komponentin voi yhdistää yhteistyötaustajärjestelmään. Kuten esimerkiksi Yjs https://yjs.dev/#intro
  - Editor API:a voi käyttää muodostamaan, päivittämään ja poistamaan muotoja, hallitsemaan kameraa tai tekemään melkein mitä tahansa muuta.
  - tldraw:ia voi laajentaa omilla mukautetuilla muodoilla ja työkaluilla.
  - Valikoiden ja työkalurivien sisältöä voi muuttaa tai piilottaa käyttöliittymän ja korvata sen omalla
  - Jos haluaa mennä vielä syvemmälle, voi käyttää <TldrawEditor> komponenttia yksinkertaisempana moottorina ilman oletus tldraw-muotoja tai käyttöliittymää.
- **Käyttökohteet:**
  - Upottaa valkotauluja sovelluksiin.
  - Luoda yhteiskäyttöön valkotauluja yhdistämällä se yhteistyötaustajärjestelmiin, kuten Yjs.

### Lisenssi
- **Lisenssi:** Apache-2.0
    - **Sallii** kaupallisen käytön, muokkauksen, jakelun, patentoidun käytön ja yksityisen käytön
    - **Rajoittaa** tavaramerkin käyttöä, ei kanna vastuuta eikä anna takuita
    - **Velvoittaa** kopioimaan lisenssin ja tekijänoikeustiedot sekä ilmoittamaan muutoksista

### Projektin Aktiivisuus ja Ylläpito
- **Historia:** [Kuinka kauan projekti on ollut olemassa? Onko sillä ollut merkittäviä virstanpylväitä?]
- **Aktiivisuus:** [Kuinka usein projektissa tehdään päivityksiä ja korjauksia?]
- **Ylläpito:** [Kuka tai ketkä ylläpitävät projektia?]

### Osallistuminen Projektiin
- **Contribution Model:** 
    - Kuka tahansa saa osallistua projektiin, kunhan noudattaa alla esitettyjä osallistumisohjeita ja projektin [eettisiä ohjeita](https://github.com/tldraw/tldraw/blob/main/CODE_OF_CONDUCT.md). 
    - Virallista työnjakoa ei ole ilmoitettu, vaikka aktiivisimpien osallistujien commit-historioita tarkastelemalla voi huomata siiloutumista.
- **Osallistumisen Menettelytavat:** 
    1. Avaa uusi keskustelu (*issue*) korjausehdotuksestasi tai uudesta ominaisuudesta ja odota lupaa aloittaa sen työstäminen
    2. Forkkaa ja kloonaa repo itsellesi, luo oma kehitysbranch
    3. Tee sovittu muutos, käytä formatointiin Prettieriä
    4. Kirjoita järkevät testit muutoksillesi
    5. Aja `yarn build` ja `yarn test`, jos näissä molemmissa kaikki OK niin...
    6. Pushaa muutoksesi ja avaa pull request. Muista allekirjoittaa [osallistujan lisenssisopimus](https://tldraw.notion.site/Contributor-License-Agreement-4d529dd5e4b3438b90cdf2a2f9d7e7e6) pull requestin kommenttikentän kautta, muuten muutoksiasi ei voida mergetä.

### Tekninen Toteutus
- **Kielet:** [Mainitse käytetyt ohjelmointikielet]
- **Protokollat:** [Mainitse käytetyt protokollat]
- **Välineet:** [Mainitse tärkeimmät käytetyt työkalut ja resurssit]

### Projekti Käyntiin
- **Asennus ja Käyttöönotto:**

  Tldraw paketti on alfa-vaiheessa, mutta siitä on myös mahdollista asentaa Canary versio joka on aina ajantasalla main repositoryn kanssa.

  Uusimman alfa-version asentaminen
  1. Avaa komentorivi tai terminaali.
  2. Asenna @tldraw/tldraw -paketti käyttämällä @alpha-viitettä saadaksesi uusimman alfa-julkaisun:
      - Yarn-käyttäjille: ```yarn add @tldraw/tldraw@alpha```
      - NPM-käyttäjille: ```npm install @tldraw/tldraw@alpha```

  Kaikkein uusin versio (Canary version) Dokumentaatio canary.tldrav.dev
  1. Avaa komentorivi tai terminaali.
  2. Asenna @tldraw/tldraw -paketti käyttämällä @canary-viitettä saadaksesi uusimman kanarialinnun julkaisun:
      -  Yarn-käyttäjille: yarn add @tldraw/tldraw@canary
      -  NPM-käyttäjille: npm install @tldraw/tldraw@canary
    
  Asennuksen jälkeen voit alkaa käyttämään trdraw kirjastoa projektissasi.

  TLDraw komponenttia voi käyttää luomalla tiedoston:

``` javascript
import { Tldraw } from '@tldraw/tldraw'
import '@tldraw/tldraw/tldraw.css'

export default function () {
return (
    <div style={{ position: 'fixed', inset: 0 }}>
      <Tldraw />
    </div>
  )
}
```
