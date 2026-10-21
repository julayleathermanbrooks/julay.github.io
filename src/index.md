---
title: Basicpage template
author: Julay Leatherman-Brooks
shortbio: Master's student in Computer Science at Portland State University
description-meta: Master's student in Computer Science at Portland State University 
og-url: https://julay.github.io
location: Biot, France
email: julay.brooks@eurecom.fr
clickable-email: true
picture: close.jpeg
picture-round: true
side-by-side: true
disable-dark-mode: true
pronouns: they/she
# og-picture: https://basicpage.github.io/img/profile.png
orcid: 0009-0005-5957-6981
# dblp: https://dblp.org/
# scholar: https://scholar.google.com/
# hal: https://hal.science/
# mastodon: https://lipn.info
github: julayleathermanbrooks
# gitlab: gitlab
# bitbucket: bitbucket.com
# bluesky: https://bsky.app/
linkedin: https://www.linkedin.com/julayleathermanbrooks
footer: >-
  Based on the
  [basicpage template](https://github.com/basicpage/basicpage.github.io),
  made to be easy to use! 🎓
---

I'm a master's student at Portland State University, advised 
by [Andrew Tolmach](https://web.cecs.pdx.edu/~apt/). I'm also currently a research intern at EURECOM, under the supervision 
of [Lesly-Ann Daniel](https://leslyann-daniel.fr/). 

Previously, I was a research intern at MPI-SP, under the supervision 
of [Cătălin Hrițcu](https://catalin-hritcu.github.io/).

# Publications

This template provide JSON or Yaml parsers to handle data representing
publications to put them in the nice following shape.

## Conference papers

``` json {.paper}
"title": "Towards automatic academic pages 2",
"authors": "Templato Urnehm, U. N. Owen, Wan Morotter",
"venue": "Principles of Awesomeness (PAW)",
"year": "2024",
"url": "https://basicpage.github.io"
```

``` json {.paper}
"title": "Towards automatic academic pages",
"authors": "Templato Urnehm, U. N. Owen",
"awards": "Automatic Award",
"venue": "Principles of Awesomeness (PAW)",
"year": "2023",
"url": "https://basicpage.github.io",
"files": [
  { "text": "Paper", "type": "pdf", "src": "foo.pdf" },
  { "text": "Bibtex", "type": "bib", "src": "foo.bib" },
  { "text": "Formalisation", "type": "code", "src": "foo.v" }
]
```

## Journal papers

``` yaml {.paper}
title: Yet another yaml parser 3
authors: Templato Urnehm
awards:
  - Yet another "Yet another" award
  - Never-ending Work Award
venue: Proceedings of Nihilism
year: 2029
url: https://basicpage.github.io
files:
  - text: Paper
    type: pdf
    scr: foo.pdf
  - text: Bibtex
    type: bib
    src: foo.bib
```

``` yaml {.papers}
papers:
  - title: Yet another yaml parser 2
    authors: Templato Urnehm
    venue: Proceedings of Nihilism
    year: 2027
    files:
      - text: Paper
        type: pdf
        scr: foo.pdf
      - text: Bibtex
        type: bib
        src: foo.bib
  - title: Yet another yaml parser
    authors: Templato Urnehm
    awards: Yet another "Yet another" award
    venue: Proceedings of Nihilism
    year: 2025
    files:
      - text: Paper
        type: pdf
        scr: foo.pdf
      - text: Bibtex
        type: bib
        src: foo.bib
      - text: Some link
        type: link
        src: fake.link.xyz
      - text: Repo
        type: git
        src: github.com
```

``` json {.paper}
"title": "How to tame your wagon",
"authors": "Templato Urnehm",
"venue": "Journal of Automatic Rejection (JAR)",
"year": "2022"
```

## Drafts

``` json {.paper}
"title": "TBD",
"authors": "TBD",
"awards": [
  "Best Draft Award",
  "Test-of-time Award for works which just never leave the draft stage"
],
"files": [
  { "text": "🐱 video", "type": "video", "src": "foo.mov" },
  { "text": "Poem", "type": "txt", "src": "foo.txt" },
  { "text": "My picture", "type": "img", "src": "img/profile.png" },
  { "text": "💣", "type": "zip", "src": "foo.zip" },
  { "text": "Slides", "type": "slides", "src": "foo.key" },
  { "text": "Some random file", "src": "foo.rand" }
]
```

## Talks

``` json {.papers}
{
  "title": "Talk 1",
  "authors": "Templato Urnehm",
  "venue": "My room"
},
{
  "title": "Secret talk",
  "authors": "Templato Urnehm",
  "year": "1990"
},
{
  "title": "Talk 3",
  "authors": "Templato Urnehm",
  "venue": "Don't remember…",
  "year": "???"
}
```

# Education

Write whatever you want here.

# Teaching

Write whatever you want here.

# Community service

Write whatever you want here.
