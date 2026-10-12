<p align="center">
  <a href="https://notes.davishiggins.com"><img src="assets/hero.svg" width="100%" alt="Curated Notes: a public notebook on data science, AI, building, and faith. Animated cover with the gold dh. mark and CURATED NOTES title beside a fanned stack of real note cards that lift in turn." /></a>
</p>

<h1 align="center">Curated Notes</h1>

<p align="center"><strong>My public notebook: long-form notes on data science, AI, building, and faith, designed to be read.</strong></p>

<p align="center">
  <a href="https://notes.davishiggins.com"><img src="assets/btn-open.svg" height="44" alt="Read the notes" /></a>&nbsp;
  <a href="https://davishiggins.com"><img src="assets/btn-dh.svg" height="44" alt="Davis Higgins" /></a>
</p>

<p align="center"><sub>Live · 19 published notes · Written, designed, and built by Davis Higgins</sub></p>

---

## See it in motion

<p align="center">
  <img src="assets/demo.gif" width="760" alt="Screen recording of notes.davishiggins.com: hovering the all-notes grid, opening 'Building Cade', and scrolling into the article as the reading-progress bar advances." />
</p>

<p align="center"><sub>Real capture of the live site: from the note grid into a published note. <a href="assets/demo.png">Static frame</a></sub></p>

## What it does

- **Notes worth finishing.** Each note is a full article with a serif reading face, a comfortable line length, a reading-progress bar, and links to the previous and next notes.
- **Easy to browse.** A featured row leads, then every note sits in a grid filterable by Projects, Data & AI, Business, and Personal, each card showing its date and read time.
- **Connected to the work.** Project notes link straight to the live product or case study they describe, so the writing and the building point at each other.

## Why I built it

I wanted a place to think in public that I own, rather than a feed. The notes record how my projects were made, what I'm learning in data and AI, and what I believe, organized and readable.

## What I built

- The site's design: a dark, gold-accented editorial look with Syne for display, DM Sans for interface text, and Lora for reading
- The publishing workflow behind every note
- The note grid, tag filter, featured row, reading progress, note-to-note navigation, and page transitions
- All 19 published notes

<details>
<summary><strong>How it's put together</strong></summary>

<br />

```mermaid
flowchart TB
    W[Notes I write] --> P[Publishing workflow]
    P --> G[Home: featured row<br/>and filterable grid]
    P --> N[A page for every note]
    G --> V[Fast static site]
    N --> V
```

| Decision | Why |
|---|---|
| **Writing comes first** | Publishing a note is as simple as writing it. There's no admin panel to maintain and every edit is versioned. |
| **Every note is pre-built** | Articles load instantly and are easy for search engines to read. |
| **Typography carries the reading** | Motion stays in the frame around the article and never animates the paragraphs someone is reading. |

</details>

## Screens

<table>
  <tr>
    <td width="62%"><img src="assets/screenshot-home.jpg" alt="Curated Notes homepage: CURATED NOTES in wide white and gold type, with Featured and All Notes buttons." /></td>
    <td rowspan="2" width="38%" align="center"><img src="assets/screenshot-mobile.jpg" width="300" alt="Curated Notes on a phone: tag filters and note cards with tags, read times, and dates." /></td>
  </tr>
  <tr>
    <td><img src="assets/screenshot-note.jpg" alt="The 'Building Cade' note: serif body text in a centered reading column with section headings." /></td>
  </tr>
</table>

<sub>Homepage · A published note · Tag filters and cards on mobile</sub>

## Technology

| Layer | Technology |
|---|---|
| Framework | Next.js, TypeScript |
| Content | MDX |
| Styling | Tailwind CSS |
| Motion | GSAP, Framer Motion, Lenis |
| Hosting | Vercel |

---

<p align="center">
  <a href="https://notes.davishiggins.com"><img src="assets/btn-open.svg" height="44" alt="Read the notes" /></a>&nbsp;
  <a href="https://github.com/DavisHiggins"><img src="assets/btn-more.svg" height="44" alt="More of my work" /></a>
</p>

<p align="center"><sub>© 2026 Davis Higgins. All rights reserved. Note content belongs to Davis Higgins.</sub></p>
