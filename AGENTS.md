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
  names each public library and what it provides, in the site's words,
  and no closed part of Hypha and no private project. Why: the page is
  the open core's front door, and anything it says of the rest is a
  promise it cannot link to. Symptom: a name in the README that no
  public repository of the organisation, nor the site, carries.
- **It says of a library only what the site says of it.** A library
  added, renamed or described anew on hyphatech.io/stack is changed here
  in the same breath. Why: two front pages that disagree make both look
  stale. Symptom: a row claiming something its card on the site's
  `/stack` page does not.
- **The banner is the site's social card.** When the site's
  `public/og.jpg` changes, `profile/banner.jpg` is copied from it. Why:
  the tagline is set once, in the site's type.

## Git

How work becomes a commit -- its format, where it happens, what is pushed
-- is [GIT.md](GIT.md), the same in every Hypha repository and changed in
all of them together, never in one. It is imported here, so it is read
with this file:

@GIT.md
