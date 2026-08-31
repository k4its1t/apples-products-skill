# Apple’s Products Skills

Two Codex skills for creating original product-marketing headlines with concise, product-led language, human benefits, clear rhythm, and restrained wordplay.

- `apples-products` creates English headlines.
- `apples-products-zh` creates Simplified Chinese headlines localized for Mainland China.

The reference corpora cover current Apple product-page patterns, recent iPhone, iPad, Mac, and AirPods generations, and selected retired products. They are used for style analysis and collision checking rather than as a phrase bank.

## Install

Clone the repository, then copy either or both skill directories into your Codex skills directory:

```bash
git clone https://github.com/k4its1t/apples-products-skill.git
cp -R apples-products-skill/apples-products ~/.codex/skills/
cp -R apples-products-skill/apples-products-zh ~/.codex/skills/
```

## Use

Invoke the English skill with `$apples-products` and the Chinese skill with `$apples-products-zh`. Both skills can also be selected automatically when the request matches their descriptions.

## Corpus scope

- English: 115 current, recent-generation, and historical product records.
- Simplified Chinese: 96 current, recent-generation, and historical product records.
- Recent-generation layer: 41 paired records across iPhone, iPad, Mac, and AirPods from 2019–2025.

Each source is linked to an official Apple page. Product claims, specifications, availability, and superlatives are time-sensitive and must be reverified before commercial use.

## Disclaimer

This is an independent writing tool and is not affiliated with, endorsed by, or published by Apple Inc. Apple product names and quoted source headlines belong to their respective owners. Generated copy must not be presented as official Apple copy or closely reproduce the reference wording.
