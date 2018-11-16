# Agent-Based-Macro
Agent Based Macroeconomic model development. Programmed in Mathematica. 

Heterogeneous agent based models (ABMs) afford the development of robust microfoundations through the direct simulation of interactions between economic actors. The aim of this agent based model is to describe non-friction based shocks (i.e. shocks arising from changes in demand or changes in actor psychology) in the macrodynamics of an otherwise healthy economy.

## Version History
### Version 1.1.2.1
- The price of capital responds to demand (captured as the ratio of capital to labor - i.e. if labor subsitutes for capital than demand has fallen).

### Version 1.1.2
- Firms update prices of goods based on inventory levels
- Firms update their expectations of labor prices based on a moving average of previous wages
- Added more tracked metrics about the economy
- Fixed issue where bank balance sheets weren' t updating properly
- Fixed issue where reservation wages weren' t updating properly
- Fixed issue where cash holdings are going negative for households (due to improper MPC calculations)
- Allowed inventory to persist through time (ref : InventorySpoilage)
- Fixed issue where consumption loop wouldn' t work when firm inventory equals zero

### Version 1.0
Simple deterministic model with limited adjustment capability (reservation wage preference adjustment) and forced savings. Banking sector collects deposits but does not make loans. Consumers purchase to their fullest within the constraints set by their MPC. Model is globally unstable. 

