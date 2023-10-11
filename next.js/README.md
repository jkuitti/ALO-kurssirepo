## Valittu Vapaan Lähdekoodin Ohjelmisto

### Ohjelma
- **Nimi:** next.js
- **Kuvaus:** Next.js on React-pohjainen web-ohjelmointiin tarkoitettu kirjasto.
- **Toimintaperiaate:** Kirjaston avulla pystyy kehittämään dynaamisia nettisivuja.
- **Käyttökohteet:** Next.js voi käyttää esimerkiksi tilanteissa, joissa halutaan tehdä sivuille hakukoneoptimointia. Lisäksi sitä voidaan käyttää, jos halutaan sivujen lataavan nopeasti.

### Lisenssi
- **Lisenssi:** MIT

### Projektin Aktiivisuus ja Ylläpito
- **Historia:** Projekti julkaistiin ensimmäisen kerran vuonna 2016. Tämän jälkeen sitä on kehitetty aktiivisesti.
- **Aktiivisuus:** Projektiin tehdään lähes päivittäin pieniä päivityksiä. Isommissa versiopäivityksissä voi olla väliä jopa vuosi.
- **Ylläpito:** Projektia ylläpitää yritys nimeltä Vercel.

### Osallistuminen Projektiin
- **Contribution Model:** [Miten projektiin voi osallistua? Onko olemassa tiettyjä rooleja tai vastuita?]
- **Osallistumisen Menettelytavat:** [Kuinka voit osallistua projektiin?]

### Tekninen Toteutus
- **Kielet:** JavaScript, TypeScript, Rust
- **Protokollat:** [Mainitse käytetyt protokollat]
- **Välineet:** [Mainitse tärkeimmät käytetyt työkalut ja resurssit]

### Projekti Käyntiin
- **Asennus ja Käyttöönotto:** [Kuinka valittu projekti saadaan toimimaan ja kuinka se käännetään lähdekoodista? Tarvittaessa lisää vaiheittaiset ohjeet.]

[Voitte täydentää tätä pohjaa valitsemanne ohjelmiston tiedoilla ja lisätä tarvittaessa lisää tietoja tai kuvia ohjelmistosta.]

### Developing

- The development branch is `canary`.
- All pull requests should be opened against `canary`.
- The changes on the `canary` branch are published to the `@canary` tag on npm regularly.

To develop locally:

1. Install the [GitHub CLI](https://github.com/cli/cli#installation).
1. Clone the Next.js repository (download only recent commits for faster clone):
   ```
   gh repo clone vercel/next.js -- --depth=3000 --branch canary --single-branch
   ```
1. Create a new branch:
   ```
   git checkout -b MY_BRANCH_NAME origin/canary
   ```
1. Enable pnpm:
   ```
   corepack enable pnpm
   ```
1. Install the dependencies with:
   ```
   pnpm install
   ```
1. Start developing and watch for code changes:
   ```
   pnpm dev
   ```
1. In a new terminal, run `pnpm types` to compile declaration files from
   TypeScript.
   _Note: You may need to repeat this step if your types get outdated._
1. When your changes are finished, commit them to the branch:
   ```
   git add .
   git commit -m "DESCRIBE_YOUR_CHANGES_HERE"
   ```
1. To open a pull request you can use the GitHub CLI which automatically forks and sets up a remote branch. Follow the prompts when running:
   ```
   gh pr create
   ```

For instructions on how to build a project with your local version of the CLI,

*Generated using GPT-3.5*
