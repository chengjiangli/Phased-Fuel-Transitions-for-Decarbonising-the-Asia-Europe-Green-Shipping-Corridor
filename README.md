# Phased-Fuel-Transitions-for-Decarbonising-the-Asia-Europe-Green-Shipping-Corridor
This repository contains the supporting data and model details for the manuscript "Phased Fuel Transitions for Decarbonising the Asia-Europe Green Shipping Corridor". Contents: LCA input/output data, Vensim SD model files, and source data for all main and supplementary figures. 

## Repository Contents

| Folder / File | Description |
|---------------|-------------|
| `Mass_Flow_Inventory_Data/` | Life Cycle Inventory (LCI) datasets for 13 alternative marine fuels, including fossil, bio‑derived, and electro‑fuel pathways (methanol, LNG, hydrogen, ammonia, biodiesel). The folder also contains the 1,300 scenario assumptions derived from the full factorial combination of 4 vessel sizes, 3 operational speeds, fuel blend ratios (single‑fuel and dual‑fuel), and production‑route variants. |
| `SD_Model/` | System Dynamics model implemented in Vensim PLE. Contains the causal loop diagrams, and all necessary equations for simulating fuel transitions under IMO NZF and FuelEU Maritime policies. |
| `Source_Data_Figures/` | Raw numerical source data for all main figures and supplementary figures. Data are organised in Excel workbooks with separate worksheets per figure. |
| `Supplementary_Information/` | A complete PDF of the Supplementary Information containing extended methods, supplementary tables, and discussion. |

## Model and Data Overview
- **Life Cycle Assessment (LCA)** : Performed using GaBi. The life cycle senarios include >1,300 scenarios covering four vessel sizes, three operational speeds, dual‑fuel blend ratios, and regional electricity mixes.
- **System Dynamics (SD) Model** : Built in Vensim PLE. Simulates dynamic feedback among policy compliance costs, fuel prices, vessel adoption, and infrastructure investment from 2024 to 2050.

## Requirements
- Vensim
- Microsoft Excel or a CSV reader to view data files
- (Optional) GaBi for LCA calculations

## Citation
If you use the data or models from this repository, please cite the original manuscript:
> “Phased Fuel Transitions for Decarbonising the Asia‑Europe Green Shipping Corridor”.
---

*Last updated: April 2026*
