# raupjc-hw0
# Pitanje 1 :
U Bin/Debug  folder su dodani MyConsole.dll i MyConsole.pdb. 
Ako maknemo .dll class library projekta aplikacija se nemoze pokrenuti.
To se dogodi jer je on potreban za povezivanje sa class library projektom.
Trebamo poslati .exe i .dll datoteke.
# Pitanje 2 :
Konzolna aplikacija je koristila staru verziju class library asemblija.
Jer konzolna aplikacija referencira asemblij, a on nije promijenjen.
# Pitanje 3 :
Build proces je napravljen bez problema.
U package direktoriju se ponovno stvorio NodaTime direktorij.