<!-- All prose for this lab lives here. Write Markdown; write chemistry as inline $\ce{...}$
     (KaTeX + mhchem — correct subscripts, charges, arrows). Each "## " heading becomes a
     section card and a TOC entry (keep headings short, e.g. "1 · 3D structures").
     Interactive blocks are MOUNT POINTS filled by the engine from window.LAB:
       <div data-mount="viewers"></div>  <div data-mount="pathway"></div>
       <div data-mount="calculator"></div>  <div data-mount="references"></div>
     Styled blocks (.mech-grid / .callout / .safety / .dl-btn) are inline HTML here — use
     <strong>/<em> inside them (Markdown isn't processed inside raw HTML blocks), but $\ce{}$ still renders. -->

## A carbocation you can see

Most reactive carbocations are fleeting intermediates you never observe directly. The **trityl cation** is different: spreading its positive charge across three benzene rings makes it so stable that it survives in solution as a vivid yellow-to-orange species you can watch form and disappear.

**The reaction (an SN1 etherification):** concentrated sulfuric acid protonates the –OH of **triphenylmethanol** and pulls it off as water, leaving a resonance-stabilized trityl carbocation. Poured into cold **methanol**, that cation is trapped by the alcohol oxygen and — after losing a proton — becomes **triphenylmethyl methyl ether**. It is a clean textbook illustration of why carbocation stability governs $\ce{S_N1}$ chemistry.

## 1 · 3D structures

**Real geometries** from PubChem — drag to rotate, scroll to zoom. Compare the tetrahedral, three-ringed carbon of triphenylmethanol with the compact methanol that traps it, and see how the product trityl methyl ether simply swaps the alcohol –OH for a methyl ether. Turn on *Highlight O* to follow the single oxygen through the reaction.

<div data-mount="viewers"></div>

## 2 · Mechanism &amp; pathway

The ether-forming sequence is a **unimolecular nucleophilic substitution** ($\ce{S_N1}$): the alcohol ionizes first to a carbocation, and only then does the nucleophile (methanol) come in.

<div data-mount="pathway"></div>

<div class="mech-grid">
<article class="mech-step"><span class="step-num">1</span>
<h3>Protonate the –OH</h3>
<p>Concentrated $\ce{H2SO4}$ protonates the hydroxyl oxygen of <strong>triphenylmethanol</strong>, turning a poor leaving group (–OH) into an excellent one ($\ce{-OH2+}$, i.e. water).</p>
</article>
<article class="mech-step major-accent"><span class="step-num">2</span>
<h3>Lose water → trityl cation</h3>
<p>Water departs and the central carbon becomes a <strong>trityl carbocation</strong>. Because the charge is delocalized over three phenyl rings, the solution turns an intense <strong>yellow-orange</strong> — you are literally watching the carbocation form.</p>
</article>
<article class="mech-step minor-accent"><span class="step-num">3</span>
<h3>Methanol traps, then loses $\ce{H+}$</h3>
<p>Poured into cold <strong>methanol</strong>, the cation is attacked by the methanol oxygen. Loss of a proton gives the neutral <strong>methyl ether</strong>, and the color fades as the cation is consumed.</p>
</article>
</div>

<div class="callout info">
<h3>Why is the trityl cation so stable?</h3>
<p>A carbocation is stabilized by anything that spreads out its positive charge. In the <strong>trityl (triphenylmethyl) cation</strong> the empty p orbital on the central carbon is conjugated into <strong>three</strong> benzene rings at once, so the charge is delocalized across many carbons by resonance. That extensive delocalization is also why the cation absorbs visible light: the deep <strong>yellow-orange color</strong> you see when triphenylmethanol dissolves in sulfuric acid is the carbocation itself, and its fading as methanol is added is a direct readout that the trapping step has happened.</p>
</div>

| Property | Triphenylmethanol | Trityl methyl ether |
|---|---|---|
| Systematic (IUPAC) name | triphenylmethanol | [methoxy(diphenyl)methyl]benzene |
| Also known as | triphenylcarbinol | methoxytriphenylmethane |
| Formula | $\ce{C19H16O}$ | $\ce{C20H18O}$ |
| Molar mass (g/mol) | 260.33 | 274.36 |
| Role | starting material | product |
| PubChem CID | [6457](https://pubchem.ncbi.nlm.nih.gov/compound/6457) | [136388](https://pubchem.ncbi.nlm.nih.gov/compound/136388) |

Methanol (IUPAC *methanol*): $\ce{CH4O}$, 32.04 g/mol, the nucleophile and recrystallization solvent (PubChem CID 887). Concentrated sulfuric acid, $\ce{H2SO4}$ (98.08 g/mol, CID 1118), supplies the acid that removes the –OH as water.

## 3 · Procedure

The **microscale** procedure from Williamson &amp; Masters, *Macroscale and Microscale Organic Experiments* (7th ed., Cengage, p. 449). Always use your instructor's version and your lab's safety rules — this is a study aid, not a substitute for a supervised SOP.

<a class="dl-btn" href="docs/trityl-methyl-ether-lab-manual.pdf" target="_blank" rel="noopener">⬇ Download the full lab handout (PDF)</a>

| Reagent | Amount | Role |
|---|---|---|
| Triphenylmethanol | 50 mg (≈0.19 mmol) | substrate (the alcohol); limiting reagent |
| Concentrated sulfuric acid, $\ce{H2SO4}$ | 0.4–0.5 mL | ionizes the –OH to the trityl cation |
| Ice-cold methanol | 3 mL (+ extra for rinsing) | nucleophile; traps the cation |
| Distilled water | as needed | washes the crystals |

### Part A — Form the cation and the crude ether

1. Weigh **50 mg triphenylmethanol** into a **10 × 100 mm reaction tube**.
2. **Grind** the solid to a fine powder with a glass rod so it dissolves readily.
3. Add **0.4–0.5 mL concentrated $\ce{H2SO4}$** and stir until the solid is **fully dissolved**.
4. **Observe and record the color** — the intense yellow-orange is the resonance-stabilized trityl carbocation (see the mechanism above).
5. Place **3 mL ice-cold methanol** in a **second** tube.
6. With a **Pasteur pipette**, transfer the sulfuric-acid solution into the cold methanol.
7. **Rinse** the first tube with a little cold methanol and add it to the mixture.

### Part B — Crystallize and isolate

8. Let crystals form — **induce** crystallization by further **cooling**, adding a **seed crystal**, or **scratching** the tube wall at the air–liquid line.
9. Collect the crystals by **vacuum filtration on a Hirsch funnel fitted with a polyethylene frit**. **Do not** place filter paper on the frit — the strongly acidic solution would destroy it.
10. **Wash** the crystals thoroughly with **water**.
11. **Dry** by pressing the crystals between sheets of filter paper.

### Part C — Weigh and record the crude

12. **Weigh** the crude ether and calculate the **theoretical** and **percent yield** (calculator below).
13. **Reserve a sample** and record the **melting point** of the crude product.

### Part D — Recrystallize

14. **Recrystallize** the remaining material from **boiling methanol**.
15. **Collect and dry** the purified ether, then record its **melting point**.

<div class="safety"><strong>Safety:</strong> concentrated $\ce{H2SO4}$ is highly corrosive and causes severe burns; methanol is toxic and flammable — avoid inhalation, ingestion, and skin contact. Add the acid solution to the methanol as directed (not the reverse), and work in a <strong>fume hood</strong> or well-ventilated area with goggles and gloves. <strong>Cleaning up:</strong> dilute the filtrate with water, neutralize with sodium carbonate, and flush it down the drain (or follow your lab's waste rules).</div>

## 4 · Calculator

<div data-mount="calculator"></div>

## 5 · References

<div data-mount="references"></div>

Molecular data from [PubChem](https://pubchem.ncbi.nlm.nih.gov/compound/136388) (public domain) via PUG-REST — triphenylmethanol CID 6457, methanol CID 887, trityl methyl ether CID 136388. 3D rendering by [3Dmol.js](https://3dmol.csb.pitt.edu/); chemistry typeset with KaTeX + mhchem.
