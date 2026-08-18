# Ghost Manifesto

Sito personale a pagina singola che presenta un manifesto filosofico in
dieci tesi sul rapporto tra tecnologia, attenzione e identità personale —
più una serie di pagine tema che approfondiscono argomenti specifici
(anonimato, crittografia, blockchain, software libero...) con strumenti
concreti, tutti open source.

**Sito live:** https://TUO-USERNAME.github.io/ghost-manifesto/

## Cos'è

Non è un trattato tecnico né un invito a rifiutare la tecnologia. È un
punto fermo: dieci tesi che usano la metafora della protezione
anti-malware — non "hacking del sé" (postura aggressiva) ma difesa di un
territorio conteso, l'attenzione umana, contesa tra il capitale
(piattaforme, algoritmi di engagement), il sé sociale/performativo, e il
sé creativo/profondo.

## Lingue

Il sito è in tre lingue — EN, FR, IT — selezionabili dal menu in alto.
La lingua scelta resta attiva mentre navighi tra le pagine, ma si azzera
alla chiusura della scheda: nessuna persistenza tra sessioni, per scelta.

## Privacy

Il sito non raccoglie né tratta alcun dato personale, non installa
cookie e non fa nessuna chiamata a servizi esterni (font self-hosted,
niente analytics, niente pixel di tracciamento). Nessuna cookie policy
necessaria, perché non c'è nulla da consentire.

## Struttura

```
├── index.html          ← home, con le dieci tesi
├── style.css
├── fonts/               ← font self-hosted
└── temi/                ← una pagina per ciascuna area tematica
```

## Contribuire

Segnalazioni, correzioni e proposte sono benvenute — apri una issue o
una pull request. Un paio di cose da tenere a mente per restare coerenti
con lo spirito del progetto:

- ogni testo va duplicato nelle tre lingue (EN, FR, IT) — niente
  contenuti presenti in una sola lingua
- nessuna chiamata a servizi esterni (niente CDN, niente font remoti,
  niente tracker): tutto va servito localmente
- nella sezione "Strumenti" di ogni pagina tema, solo software open
  source verificabile, non semplicemente gratuito

## Licenza

I contenuti di questo sito (testi, tesi, pagine tema) sono rilasciati con
licenza **[Creative Commons Attribution 4.0 International (CC BY
4.0)](LICENSE)**: chiunque può condividerli, riutilizzarli e adattarli,
anche per scopi commerciali, a patto di citare la fonte. Vedi il file
[LICENSE](LICENSE) per il testo completo.
