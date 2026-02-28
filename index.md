# Reverse Engineering the Dota 2 Patch Meta

Using 250,000 high-MMR matches, this project analyzes hero synergy, patch enablers, and counter-strategies in the current meta.

---

## 1. Dataset & Objective

- 250,000 matches
- Current patch
- High MMR only
- Goal: Identify statistically significant hero synergies and patch-defining heroes.

---

## 2. Are Heroes Balanced?

![Hero Winrate Distribution](images/hero_winrate.png)

Most heroes cluster around 50% winrate, indicating that major deviations are likely due to structural synergy rather than individual imbalance.

---

## 3. Quantifying Synergy

We define synergy using a Z-score:

Z = (Observed - Expected) / Standard Error

This adjusts for:
- Unequal sample sizes
- Baseline hero strength
- Random variance

---

## 4. Strongest Hero Synergies

![Top Synergies](images/top_synergy.png)

These combinations significantly outperform expectations even after statistical correction.

---

## 5. Patch Enablers

![Top Enablers](images/enablers.png)

Heroes like Razor and Drow Ranger consistently amplify teammate performance, suggesting they act as structural anchors in the patch.

---

## 6. Countering the Meta Anchor

![Razor Counters](images/razor_counters.png)

While Razor defines the patch, burst and lockdown heroes significantly suppress his winrate.

---

## 7. Conclusion

This analysis reveals:

- The patch favors structured scaling compositions.
- Certain heroes act as synergy anchors.
- Even dominant heroes have statistically reliable counters.

