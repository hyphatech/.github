# AGENTS.md

The front page of Hypha's GitHub organisation: GitHub shows
`profile/README.md` of the public repository `hyphatech/.github` on
`github.com/hyphatech`. This file is for anyone changing it, human or
agent.

## Layout

```
profile/README.md    the page: the banner, Hypha Stack, the site
profile/banner.jpg   the site's social card, public/og.jpg in hyphatech
```

A `CONTRIBUTING.md`, `SECURITY.md` or issue template at this repository's
root would become the default of every repository in the organisation that
has none of its own; there are none today.

## Rules that must hold

- **The page shows the open components and nothing else of Hypha.** It
  names each public library and what it provides, and no closed part of
  Hypha and no private project. Why: the page is the open core's front
  door, and anything it says of the rest is a promise it cannot link to.
  Symptom: a name in the README that no public repository of the
  organisation, nor the site, carries.
- **A library's row is its tagline, word for word.** Each row's
  description is the library's tagline in the registry,
  [[hypha-hq:repositories/map.md#the-registry]], and changes when that
  line does; its capability is the one it provides on hyphatech.io/stack.
  Why: a description told several ways is told wrong in all but one.
  Symptom: a row that differs from its library's README's second line.
- **The banner is the site's social card.** When the site's
  `public/og.jpg` changes, `profile/banner.jpg` is copied from it. Why:
  the tagline is set once, in the site's type.
