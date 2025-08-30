# ammonia-combustion-psr-nox-control-
A numerical study of ammonia combustion in a Perfectly Stirred Reactor (PSR) focusing on the effects of equivalence ratio and inlet temperature on pollutant emissions (NO, NO₂, N₂O, and unburned NH₃), with the aim of developing strategies for low-NOx combustion.


# Ammonia Combustion in PSR for NOx and Pollutant Control

## 📌 Overview

This repository contains a numerical study of **ammonia (NH₃) combustion** in a **Perfectly Stirred Reactor (PSR)**.
The study investigates the effect of **inlet temperature** and **equivalence ratio (ϕ)** on:

* Pollutant emissions (**NO, NO₂, N₂O**)
* Unburned ammonia (NH₃ slip)
* Combustion temperature trends

The long-term objective is to develop insights for a **low-emission, low-NOx ammonia combustor**.

---

## ⚙️ Method

* **Tool used:** ANSYS Chemkin-Pro (Aurora + Reactor Network)
* **Reactor model:** Perfectly Stirred Reactor (PSR)
* **Operating conditions:**

  * Pressure: 1 atm
  * Inlet temperature: 298 K, 600 K, 900 K
  * Equivalence ratio sweep: 0.6 → 1.3
  * Residence time: typically 0.01 s (varied in some cases)
* **Output species tracked:** NO, NO₂, N₂O, NH₃, O₂, H₂O, radicals (H, OH, HO₂)

---

## 📊 Results

The study produced trends for:

1. **Temperature vs ϕ** → maximum temperature observed near slightly rich conditions.
2. **NO, NO₂, N₂O vs ϕ** →

   * NO decreases with higher ϕ (fuel-rich).
   * NO₂ and N₂O levels also decrease, but with different magnitudes.
3. **Unburned NH₃ vs ϕ** → increases rapidly under rich conditions (ϕ > 1).
4. **Effect of inlet temperature (298 K → 900 K)** → higher Tin leads to higher peak combustion temperatures and alters pollutant distributions.

👉 (This section will be expanded with your actual plots and key takeaways once you upload the PPT.)

---

## 📈 Plots

All simulation results are summarized in the `plots/` folder and the presentation slides (`results_presentation.pptx`).

* φ vs Temperature
* φ vs Pollutant emissions (NO, NO₂, N₂O)
* φ vs NH₃ slip
* Comparison of different inlet temperatures

👉 Will embed graphs here once available.

---

## 🛠 Requirements

* ANSYS Chemkin-Pro (Aurora module)
* Python 3.x (optional, for post-processing)
* Excel (for quick CSV handling)

---

## 🚀 How to Use

1. Open the Chemkin input files (`input/`) in Aurora.
2. Run PSR simulations with the specified equivalence ratio sweep.
3. Export CSV outputs for pollutants and temperature.
4. Use Excel/Python scripts in `analysis/` to generate plots.

---

## 📚 Citation

If you use this work, please cite as:
**Dipendra K. Dewangan, “Parametric Study of Low-Emission Ammonia Combustion in PSR Reactors,” M.Tech Thesis, IIT Kanpur, 2025.**
