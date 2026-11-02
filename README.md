# Poraba občin

Platforma, ki iz javnih virov samodejno zajema plačila vseh 212 slovenskih občin (UJP TZIJZ), rezultate lokalnih volitev in demografske podatke ter jih poveže. Izračuna kazalnike, kot so poraba na prebivalca, koncentracija plačil in delež novih dobaviteljev po menjavi župana, in jih prikaže na interaktivnem zemljevidu občin.

Projekt pri predmetu Računalniške storitve v oblaku (UL FRI, 2026/27).

## Mikrostoritve

- **tzijz-ingest**: zajem plačil občin iz UJP TZIJZ
- **reference-ingest**: volitve, župani, registri podjetij, prebivalstvo
- **processing**: čiščenje podatkov in prepoznavanje dobaviteljev
- **analytics-api**: agregati in kazalniki za prikaz
- **UI**: spletna aplikacija z zemljevidom (React)