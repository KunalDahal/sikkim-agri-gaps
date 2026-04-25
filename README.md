# Sikkim Agricultural Dataset — Research Project

A multi-source agricultural dataset covering **989 records** across 6 districts of Sikkim (1997–2022), built to support longitudinal research on organic farming, climate-yield interactions, and farm economics.

---

## Dataset

| Detail | Value |
|--------|-------|
| Records | 989 observations |
| Features | 14 columns (7 primary + 7 derived) |
| Temporal Span | 1997 – 2022 (26 years) |
| Districts | Gangtok, Geyzing, Mangan, Namchi, Pakyong, Soreng |
| Crops | 13 crop types (cereals, pulses, oilseeds, tubers) |

**Primary source:** [Dataful.in — Dataset 5612](https://dataful.in/datasets/5612/) (Directorate of Economics & Statistics, Govt. of Sikkim + ICAR)  
**Secondary sources:** CACP (costs & revenue), IMD (rainfall), Sikkim Organic Mission (organic phases)

---

## Project Status

- [x] **Dataset Gathering** — Primary data acquired from Dataful.in; secondary features sourced from CACP, IMD, and Sikkim Organic Mission
- [x] **Preprocessing** — 14-feature authenticated dataset compiled, validated, and exported as `final_dataset.csv` (see `dataset.ipynb`)
- [ ] **Topic 1** — Organic Transition and Crop-Specific Yield Divergence in Sikkim (1997–2022) ← *next*
- [ ] **Topic 2** — Profitability Threshold Analysis of Organic Farming Adoption
- [ ] **Topic 3** — Rainfall Variability, Drought Stress, and Crop Yield Sensitivity
- [ ] **Topic 4** — Spatio-Temporal Shifts in Crop Portfolio Under the Organic Mission
- [ ] **Topic 5** — Machine Learning-Based Crop Yield Prediction
- [ ] **Topic 6** — Input Efficiency: Subsistence Crops vs. Cash Crops

---

## Repository Structure

```
├── dataset.csv              # Raw primary data (7 features, Dataful.in)
├── final_dataset.csv        # Compiled 14-feature dataset (all sources merged)
├── dataset.ipynb            # Full pipeline: data acquisition → feature engineering → export
├── Data-Source.pdf          # Feature-level source documentation
├── Research-Topics.pdf      # Six research proposals with hypotheses & literature gaps
└── README.md
```

---

## Citation

**Primary:** Dataful.in. (2024). *Sikkim Agricultural Crop Data* (Dataset ID 5612). Directorate of Economics & Statistics, Government of Sikkim. https://dataful.in/datasets/5612/

**Compiled:** Research Documentation Unit. (2025). *Sikkim Agricultural Multi-Source Dataset 1997–2022* [CSV]. v1.0.