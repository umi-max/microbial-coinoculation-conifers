# Microbial Co-inoculation in Conifers — Interactive Research Guide

**Live site:** https://umi-max.github.io/microbial-coinoculation-conifers/

An interactive, single-page guide to microbial co-inoculation as a biological control strategy
against soil-borne fungal pathogens of conifers, and to the host transcriptomic responses that
accompany it.

## Contents

| Module | What it covers |
| --- | --- |
| 01 · Overview | Why conifer root and damping-off diseases outpace chemical control; scope of the evidence base |
| 02 · Concepts | Dual inoculation vs. multi-agent consortia, prophylactic timing, defence priming, six recurrent defence gene families, JA/ET vs. SA signalling |
| 03 · Efficacy explorer | Interactive model: vary pathosystem, inoculation design, prophylactic lead time and mechanism profile |
| 04 · Key terms | Eight flip cards with a mastery tracker |
| 05 · Pitfalls | Five common misconceptions, each paired with the evidence that corrects it |
| 06 · Quiz | Ten questions with instant feedback and explanations |

## Source material

All concepts, quantitative benchmarks, gene families and methodological critiques presented here are
drawn from:

> Awan, H. U. M., & Iqbal, M. *Microbial Co-inoculation for Biological Control of Forest Diseases in
> Conifers: A Systematic Review of Defence Mechanisms and Host Transcriptomic Responses.*
> A synthesis of 430 screened records and 20 primary studies (2005–2026). https://doi.org/10.1016/j.pmpp.2026.103432

Primary studies cited within the guide include Adomas et al. (2008), Arnerup et al. (2011, 2013),
Grönberg et al. (2009), Lehr et al. (2007, 2008), Moraga-Suazo et al. (2024), Otero et al. (2020),
Sun et al. (2011), Wang et al. (2022, 2025), Wen et al. (2021, 2025), Yu et al. (2024),
Yusypovych et al. (2025), Zamora-Ballesteros et al. (2025) and Zhang et al. (2011).

### How to read the Efficacy Explorer

The explorer is a **teaching model**, not a dataset. Its endpoints are anchored to figures reported
in the reviewed studies; intermediate slider positions interpolate between them. The exact published
values always appear in the "Closest Empirical Benchmark" box beneath the controls. Do not cite
interpolated numbers.

## Technical notes

- A single self-contained `index.html`: inline CSS and JavaScript, no build step and no package
  dependencies. Web fonts (Literata, Nunito Sans, Geist Mono) are loaded from Google Fonts.
- Quiz answers, flashcard mastery and simulator settings persist in the browser's `localStorage`,
  scoped to each visitor's own browser. If storage is unavailable (private browsing, blocked
  cookies), the page still works and simply does not remember progress.
- Responsive down to small screens, with `prefers-reduced-motion` respected.
- Published with GitHub Pages from the `main` branch, root folder.

## Updating the site

Commit a new `index.html` to `main`. GitHub Pages redeploys automatically, usually within a minute.

## Author

Hafiz U. M. Awan — doctoral researcher in forest pathology, University of Helsinki.
