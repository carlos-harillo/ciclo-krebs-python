# Krebs Cycle Simulation 🧬

A Python simulation of the Krebs cycle (citric acid cycle) built in 
Jupyter Notebook, modeling enzymatic reactions, metabolite pools, 
cofactor cycling and energy balance under different substrate conditions.

## What it simulates
- 8 enzymatic reactions as individual Python functions
- Dynamic metabolite pools as lists (Acetil-CoA, OAA, citrate, etc.)
- Cofactor cycling (NAD+/NADH, FAD/FADH2, CoA)
- CO2 release at each decarboxylation step
- Substrate-level phosphorylation (GDP → GTP)
- Stoichiometric validation before running the cycle
- Full energy balance per simulation run

## How to use
Run `ciclo_krebs()` and input the number of molecules for each substrate:
- Acetil-CoA (carbon source)
- Oxaloacetate (catalytic, regenerated each turn)
- NAD+ (minimum 3x Acetil-CoA)
- FAD, H2O, GDP (minimum 1x Acetil-CoA each)

## Energy output per turn
| Product | Amount |
|---------|--------|
| NADH | 3 |
| FADH2 | 1 |
| GTP | 1 |
| CO2 | 2 |

## Roadmap
✅ Complete 8-enzyme Krebs cycle simulation  
✅ Interactive orchestrator function with user inputs  
✅ Stoichiometric validation  
✅ Energy balance summary  
🔄 Glycolysis integration  
⬜ Pyruvate dehydrogenase complex  
⬜ Electron transport chain + ATP synthase  
⬜ Malate-aspartate and glycerol-phosphate shuttles  
⬜ Anaerobic conditions and fermentation  
⬜ Full cellular respiration orchestrator  

## Author
Carlos - Biology student learning Python through metabolic modeling
