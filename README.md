[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/praghav444/AmeriFlux-Meeting-2025-FVS-Tutorial-Wetland/blob/main/AmeriFlux_Meeting2025_Tutorial.ipynb)
# AmeriFlux Meeting 2025 Tutorial – Water Flux Partitioning using Flux Variance Similarity (FVS) Theory in Wetland Settings

This tutorial introduces methods for **water flux partitioning** using the **Flux Variance Similarity (FVS)** theory, focusing on **wetland ecosystems**. It is designed for participants of the **AmeriFlux Meeting 2025** and includes a step-by-step demonstration using Python and Jupyter Notebook.

The tutorial notebook illustrates how to apply FVS-based approaches to partition evapotranspiration (ET) into **evaporation (E)** and **transpiration (T)** components from high frequency measurements of carbon and water eddy covariance fluxes.

---

## Background and Objective

Water flux partitioning helps separate ecosystem water fluxes (i.e., total evapotranspiration ET) into abiotic (evaporation; E) and biotic (transpiration; T) processes, improving understanding of water use efficiency, ecosystem productivity, and climate feedbacks.

This tutorial provides a hands-on introduction to:
- Theoretical foundation of FVS-based flux partitioning  
- Implementation of FVS in Python  
- Application to a AmeriFlux wetland site  
- Visualization and interpretation of results  

---

## 📚 References

Participants are encouraged to review the following key publications that form the theoretical and methodological foundation of this tutorial:

1. **Wagle, P., Raghav, P., Kumar, M., & Gunter, S. A. (2023).**  
   *Influence of water use efficiency parameterizations on flux variance similarity-based partitioning of evapotranspiration.*  
   *Agricultural and Forest Meteorology, 328, 109254.*  
   [https://doi.org/10.1016/j.agrformet.2022.109254](https://doi.org/10.1016/j.agrformet.2022.109254)

2. **Scanlon, T. M., Schmidt, D. F., & Skaggs, T. H. (2019).**  
   *Correlation-based flux partitioning of water vapor and carbon dioxide fluxes: Method simplification and estimation of canopy water use efficiency.*  
   *Agricultural and Forest Meteorology, 279, 107732.*  
   [https://doi.org/10.1016/j.agrformet.2019.107732](https://doi.org/10.1016/j.agrformet.2019.107732)

3. **Skaggs, T., Anderson, R., Alfieri, J., Scanlon, T., & Kustas, W. (2018).**  
   *Fluxpart: Open source software for partitioning carbon dioxide and water vapor fluxes.*  
   *Agricultural and Forest Meteorology, 253, 218–224.*  
   [https://doi.org/10.1016/j.agrformet.2018.02.019](https://doi.org/10.1016/j.agrformet.2018.02.019)

4. **Scanlon, T. M., & Sahu, P. (2008).**  
   *On the correlation structure of water vapor and carbon dioxide in the atmospheric surface layer: A basis for flux partitioning.*  
   *Water Resources Research, 44(10).*  
   [https://doi.org/10.1029/2008WR006932](https://doi.org/10.1029/2008WR006932)

---

## 🧑‍💻 How to Run This Tutorial

You can run the tutorial interactively on **Google Colab** — no installation needed.  
Simply click the link below:

👉[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/praghav444/AmeriFlux-Meeting-2025-FVS-Tutorial-Wetland/blob/main/AmeriFlux_Meeting2025_Tutorial.ipynb)

### Steps:
1. Click the link above to open the notebook in Colab.  
2. From the Colab menu, select **Runtime → Run all** to execute all cells sequentially.  
3. If prompted, allow Colab to install necessary Python packages.  
4. You may optionally **save a copy to your own Google Drive** to make personal edits.

---

## ⚙️ Local Setup (Optional)

If you prefer to run the notebook locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/praghav444/AmeriFlux-Meeting-2025-FVS-Tutorial-Wetland.git
   cd AmeriFlux-Meeting-2025-FVS-Tutorial-Wetland
