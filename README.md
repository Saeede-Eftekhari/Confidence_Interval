# Confidence Interval Lab · MGSC 3005 · Week 8

An interactive, step-by-step page where students:

1. Start from what is unknown (μ, σ, the population) and what they will compute (x̄, s, n)
2. Draw one random sample of GMAT scores and compute x̄ and s in Excel
3. Learn the CI formula and notation for a known σ (slide 20: x̄ ± z_{α/2} σ/√n, with σ = 86.80)
4. Build their own confidence interval in Excel (NORM.S.INV, σ/SQRT(n), CONFIDENCE.NORM) and check their answers
5. Interpret it with the class sentence frame
6. See the true μ revealed and check whether their interval caught it
7. Simulate 100+ intervals to see what "95% confident" means, and count the hits in Excel with COUNTIF
8. Answer summary questions

It uses the same simulated pool of 2,637 GMAT scores (μ = 520.78, σ = 86.80) as the Sampling page.

## Publish on GitHub Pages

1. Create a new public repository, for example `ConfidenceInterval`.
2. Upload `index.html` (and this README) to the repository root.
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose branch `main` and folder `/ (root)`, then **Save**.
4. After a minute the page is live at `https://saeede-eftekhari.github.io/ConfidenceInterval/`.

The page is a single file with no external libraries, so it also works offline: students can download `index.html` and open it in any browser.

## Using the real GMAT scores

To use the real 2,637 scores instead of the simulated pool, paste them into the `REAL_SCORES` array near the top of the `<script>` section, for example `const REAL_SCORES = [530, 450, 600, ...];`.
