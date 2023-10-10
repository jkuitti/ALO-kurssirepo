## Valittu Vapaan Lähdekoodin Ohjelmisto

### Ohjelma
- **Nimi:** TlDraw
- **Kuvaus:** tldraw on React-kirjasto, joka on suunniteltu luomaan valkotauluja.
- **Toimintaperiaate:**
  - tldraw'n avulla voit upottaa sovellukseesi täysin varustellun ja laajennettavan valkotaulun käyttämällä <Tldraw> React-komponenttia.
  - Monen ihmisen samanaikaista yhteistyö käyttöä varten voit yhdistää komponentin valitsemaasi yhteistyötaustajärjestelmään. Kuten esimerkiksi Yjs https://yjs.dev/#intro
  - Voit käyttää Editor API:a muodostamaan, päivittämään ja poistamaan muotoja, hallitsemaan kameraa tai tekemään melkein mitä tahansa muuta.
  - tldraw'n voi laajentaa omilla mukautetuilla muodoilla ja työkaluilla.
  - Voit muuttaa valikoiden ja työkalurivien sisältöä tai piilottaa käyttöliittymän ja korvata sen omallasi.
  - Jos haluat mennä vielä syvemmälle, voit käyttää <TldrawEditor> komponenttia yksinkertaisempana moottorina ilman oletus tldraw-muotoja tai käyttöliittymää.
- **Käyttökohteet:**
  - Upottaa valkotauluja sovelluksiin.
  - Luoda moninpelivalkotauluja yhdistämällä se yhteistyötaustajärjestelmiin, kuten Yjs.
  - Laajentaa ja mukauttaa valkotaulun toimintoja ja ulkoasua, kuten muotoja, työkaluja ja käyttöliittymää.
  - Korvata tldraw'n oletuskäyttöliittymä ja muodot omilla mukautetuilla ratkaisuilla.

### Lisenssi
- **Lisenssi:** [Mainitse ohjelmiston käyttämä lisenssi]

### Projektin Aktiivisuus ja Ylläpito
- **Historia:** [Kuinka kauan projekti on ollut olemassa? Onko sillä ollut merkittäviä virstanpylväitä?]
- **Aktiivisuus:** [Kuinka usein projektissa tehdään päivityksiä ja korjauksia?]
- **Ylläpito:** [Kuka tai ketkä ylläpitävät projektia?]

### Osallistuminen Projektiin
- **Contribution Model:** [Miten projektiin voi osallistua? Onko olemassa tiettyjä rooleja tai vastuita?]
- **Osallistumisen Menettelytavat:** [Kuinka voit osallistua projektiin?]

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
