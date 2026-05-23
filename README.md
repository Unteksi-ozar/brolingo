# Brolingo

**https://github.com/freshcakewtf/brolingo**

A satirical dictionary and survival guide for corporate buzzwords — modeled after Duolingo but for the language of business nonsense.

## What is this?

Brolingo documents the crimes committed against the English language in conference rooms, Slack channels, and all-hands meetings worldwide. Look up terms like *synergy*, *ideate*, *circle back*, and *paradigm shift* — and find out what they actually mean vs. what your manager thinks they mean.

## Features

- 38+ terms documented across 6 categories (Strategy, Tech, Meetings, Communication, Leadership, Finance)
- Severity ratings: Mild, Moderate, Severe, Critical
- Search, filter by category or severity, and sort
- "Also See" cross-references between related buzzwords
- Fully static — no backend, no tracking, no cookies

## Usage

Just open `index.html` in a browser. No build step, no dependencies, no npm install.

```
open index.html
```

Or serve it locally with any static file server:

```bash
npx serve .
# or
python3 -m http.server
```

## Adding Terms

All content lives in `terms.json`. Add a new entry following the existing schema:

```json
{
  "id": 39,
  "term": "Circle Back",
  "pronunciation": "SUR-kul bak",
  "part_of_speech": "verb phrase",
  "category": "Communication",
  "severity": "critical",
  "corporate_definition": "...",
  "real_definition": "...",
  "example": "...",
  "also_see": ["Alignment"],
  "brolingo_tip": "..."
}
```

**Categories:** `Strategy`, `Tech`, `Meetings`, `Communication`, `Leadership`, `Finance`
**Severity levels:** `mild`, `moderate`, `severe`, `critical`

## Contributing

PRs welcome at [github.com/freshcakewtf/brolingo](https://github.com/freshcakewtf/brolingo).

To suggest a term without a PR, [open an issue](https://github.com/freshcakewtf/brolingo/issues/new).

Add terms alphabetically within their category. Be funny.

## Disclaimer

100% satirical. No synergies were created in the making of this site. Built with genuine workplace trauma.
