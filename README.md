# Növénybetegségek felismerése neurális hálóval

A projekt célja növényi levelek képeinek automatikus osztályozása különböző betegségek szerint neurális háló segítségével.

### Az adathalmaz

A projekthez a _[PlantVillage](https://www.kaggle.com/datasets/mohitsingh1804/plantvillage)_ adathalmaz lett használva, amely növényi levelek képeit tartalmazza különböző egészségi állapotokban.

Főbb jellemzők:
- Több mint 50000 kép (54305)
- 38 különböző osztály
- Több növényfaj és betegség kombinációja

A képek jellemzően laboratóriumi körülmények között készültek, homogén háttérrel, ami egyszerűbbé teszi a feladatot, de csökkentheti a valós alkalmazhatóságot.

A modellek és a hozzá tartozó fájlok a _models/<model_név>_ könyvtárakban találhatóak.

_A dokumentáció többi része megtalálható az **[aml.ipynb](aml.ipynb)** jupyter jegyzetfüzetben!_
