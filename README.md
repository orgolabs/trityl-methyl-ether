<p align="center">
  <a href="https://github.com/orgolabs"><img src="https://orgolabs.github.io/shared/brand/orgolabs-wordmark.png" alt="orgolabs — organic chemistry labs" width="300"></a>
</p>

# Trityl Methyl Ether from Triphenylmethanol — an interactive, fact-checked explainer

> Part of **[orgolabs](https://github.com/orgolabs)** — interactive, fact-checked organic chemistry labs.
> **Live site:** https://orgolabs.github.io/trityl-methyl-ether/

Synthesis of **triphenylmethyl methyl ether** (trityl methyl ether) from **triphenylmethanol** via the resonance-stabilized **trityl carbocation** — a textbook **SN1**. It shows *how* and *why* the reaction works: real 3D structures (PubChem + [3Dmol.js](https://3dmol.csb.pitt.edu/)), the ionization/trapping mechanism, why the trityl cation is so stable (and so colored), the procedure, and a live yield calculator.

## The chemistry in one line

Concentrated sulfuric acid ionizes the alcohol to the trityl cation; methanol traps it:
`C₁₉H₁₆O —H₂SO₄, CH₃OH→ C₂₀H₁₈O` (+ H₂O).

## Run it locally

Open `index.html`, or serve with `python3 -m http.server`. The shared engine, styles, and 2D pathway images load from https://orgolabs.github.io/shared/.

## Credits & licensing

- Site content and code: **MIT License**.
- Molecular data: **PubChem**, U.S. National Library of Medicine — **public domain** (triphenylmethanol CID 6457, methanol CID 887, trityl methyl ether CID 136388).
- 3D rendering: **3Dmol.js** (Rego & Koes, *Bioinformatics* 2015) — **BSD-3-Clause**.

> Educational summary only — not a substitute for a supervised laboratory SOP. Concentrated sulfuric acid is highly corrosive; methanol is toxic and flammable.
