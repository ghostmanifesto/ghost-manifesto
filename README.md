# Ghost Manifesto

A personal single-page site presenting a philosophical manifesto in ten
theses on the relationship between technology, attention and personal
identity — plus a series of theme pages that dig into specific topics
(anonymity, encryption, blockchain, free software...) with concrete,
open-source tools.

**Live site:** https://ghostmanifesto.github.io/ghost-manifesto/

## What it is

It's not a technical treatise, nor an invitation to reject technology.
It's a stake in the ground: ten theses that use the anti-malware
protection metaphor — not "hacking the self" (an aggressive posture) but
defending a contested territory, human attention, fought over between
capital (platforms, engagement algorithms), the social/performative
self, and the deeper, creative self.

## Languages

The site is available in three languages — EN, FR, IT — selectable from
the top menu. The chosen language stays active while navigating between
pages, but resets when the tab is closed: no persistence across
sessions, by design.

## Privacy

The site collects and processes no personal data, sets no cookies, and
makes no calls to external services (self-hosted fonts, no analytics, no
tracking pixels). No cookie policy needed, because there's nothing to
consent to.

## Structure

```
├── index.html          ← home page, with the ten theses
├── style.css
├── fonts/               ← self-hosted fonts
└── temi/                ← one page per theme area
```

## Contributing

Reports, corrections and proposals are welcome — open an issue or a pull
request. A few things to keep in mind to stay consistent with the
project's spirit:

- every piece of text must be duplicated in all three languages (EN, FR,
  IT) — no content in a single language only
- no calls to external services (no CDNs, no remote fonts, no
  trackers): everything must be served locally
- in each theme page's "Tools" section, only verifiable open-source
  software, not merely free-of-charge software

## License

The content of this site (texts, theses, theme pages) is released under
a **[Creative Commons Attribution 4.0 International (CC BY
4.0)](LICENSE)** license: anyone can share, reuse and adapt it, even for
commercial purposes, as long as they credit the source. See the
[LICENSE](LICENSE) file for the full text.
