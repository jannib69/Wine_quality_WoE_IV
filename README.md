# Klasifikacija kakovosti vin z uporabo Bayesovih mrež

Ta projekt prikazuje klasifikacijo kakovosti vin (nizka / visoka) z uporabo **Bayesove mreže**, uresničene v okolju **GeNIe**. Podatki so bili pridobljeni iz UCI Machine Learning Repository in pripravljeni v Pythonu s pomočjo WoE / IV analize.

## Ključna spoznanja

- Spremenljivka **alcohol** ima največji vpliv na napoved kakovosti
- Dosežen AUC = **0.736**, kar kaže na dobro ločilno sposobnost modela
- Bayesove mreže omogočajo razložljivo napovedovanje in vizualizacijo odvisnosti

## Orodja

- Python (pandas, numpy)
- GeNIe Modeler 5.0 (https://www.bayesfusion.com/)
- UCI Wine Quality Dataset
