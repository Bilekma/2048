# 2048
## dokumentace
### uživatelská
hra 2048 vytvořená v pythonu s pomocí pygame, ovládaná šipkami

hra se hraje na poli 4x4 čtverců

šipky posunou všechny čtverce s mocninami dvojky k jedné straně, pokud se srazí dvě kostky se stejným číslem, spojí se v jednu, jejíž hodota bude součtem předešlých

po každém tahu se vytvoří nový čtverec s číslem 2 nebo 4

cílem hry je vytvořit čtverec s číslem 2048
### technická
hra běží v jednom souboru ve kterém se nachází:
1. určení rozměrů okna a barev, které bude hra využívat
2. inicializace proměnných
3. funkce, která umožňuje dělat jednotlivé tahy
4. funkce přidávající nové dílky do hry
5. vykreslující funkce
6. cyklus využívající funkce, zajišťující chod hry
