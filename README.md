Python simulation of cellular respiration built in Jupyter Notebook,
modeling enzymatic reactions, metabolite pools, cofactor cycling and 
energy balance under different substrate conditions.

## What it simulates
- 10 glycolysis enzymes with dynamic metabolite pools
- 8 Krebs cycle enzymes with cofactor cycling
- Stoichiometric validation before running each pathway
- Energy balance summary per simulation run
- Substrate-level phosphorylation (ADP → ATP, GDP → GTP)
- Cofactor cycling (NAD+/NADH, FAD/FADH2, CoA)
- CO2 release at each decarboxylation step
- Inorganic phosphate (Pi) cycling

## How to use
Run `ciclo_krebs()` and input the number of molecules for each substrate.

## Energy output per glucose (theoretical)
| Product | Glycolysis | Krebs cycle |
|---------|-----------|-------------|
| NADH | 2 | 6 |
| FADH2 | 0 | 2 |
| ATP/GTP | 2 net | 2 |
| CO2 | 0 | 4 |

## Roadmap
✅ Complete 10-enzyme glycolysis simulation  
✅ Complete 8-enzyme Krebs cycle simulation  
✅ Interactive orchestrator for Krebs cycle  
✅ Stoichiometric validation  
✅ Energy balance summary  
🔄 Glycolysis orchestrator function  
⬜ Pyruvate dehydrogenase complex  
⬜ Electron transport chain + ATP synthase  
⬜ Malate-aspartate and glycerol-phosphate shuttles  
⬜ Anaerobic conditions and fermentation  
⬜ Full cellular respiration orchestrator  

## Author
Carlos - Biology student learning Python through metabolic modeling
