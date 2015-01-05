sfx2sirsi-deletes
=================

Program to report deletions in SFX to Symphony.

Basic algorithm is: 
Extract *full* title-list from SFX (not just active UA titles).
Use the SFX API to check whether the title has active portfolios.
If not, report it to Jim to be removed from the catalogue. 
