# Kuka robot
## Eivind og Dorde
Roboten heter **KR6 R700 sixx**.

Kontrolleren er en **KR C4 compact.**

Maskinens harddrive er "flashet" på en KUKA-USB James har.

For å finne databalder og andre Kuka resusser må du lage en konto på [Kuka Xpert](https://www.kuka.com/en-se/products/robotics-systems/software/cloud-software/kuka-xpert). [Her](https://xpert.kuka.com/ID/AR3605) er en gruppe med relevant informasjon om robotten.

På robotten skal vi ha et sikkerhetssystem med sikkerhets PLS-er. Eksempelvis kan vi bruke [denne](https://industrial.omron.no/no/products/cip-safety) eller [denne](https://www.beckhoff.com/BK9105/). Her styres alt over en ethernetkabel som skal inn i port X66 på kontrolleren.

I sammenheng med sikkerhet må vi innstallere [WorkVisual](https://kuka.sharefile.eu/share/view/s0977718741844ab8/fo93cf61-6254-4154-bafd-37665fe3ad5f) for å drive med safe operation. Du kan finne video tutorials for WorkVisual [her](https://kuka.sharefile.eu/share/view/s2ceab2ffc3a4ce48/fode320a-d018-49b4-a809-d53effa3f83d).

Robotten skal "sjekke seg selv" med jevne mellomrom. Dette må settes opp.
