---
Title: Om
Description: Information om tekniker använda på sidan
# hidden: true
---

## Om sidan
*(senast ändrad 2022-12-02)*

Här beskriver jag lite om vilka tekniker/principer som jag använder på sidan.

###Typografi
På denna webbplats har jag tillämpat följande typografiska principer:
- FOUT: Alla fonter (2 st) har backup-fonter, Faustina med serif för brödtext och Oswald med sans-serif för backup, detta görs m.h.a. font-display.
- Relativa enheter: fontstorlekarna har gjorts om för att utgå från relativa enheter.
- Har lagt till lite luft mellan stycken och rubriker för läsbarhetens skull: använde rekommenderade värden som riktlinje, men de känns en aning för stora, ska finslipa det lite vid tillfälle.
- Radlängder: Har tankarna på den klassiska 80-teckensraden, men det blir en del pysslande med beräkningar för att uppnå det, så inte där ännu (nej, går inte att uppnå med moderna fonter då de är olika, men har som riktmärke).

###SCSS/SASS
Har försökt använda några inbyggda delar i "språket" för att underlätta konstruktion av sidor.

- Använder variabler för färger och vissa text/fontrelaterade egenskaper.
- Använder nästlade selectors för att minska mängden kod där det har varit uppenbart lämpligt.
- Har hittat funktioner på nätet som ska underlätta vid ändring av storlek på skärm, tror de fungerar, men behöver experimentera lite mer.

###Responsivitet
Sidan har gjorts grundläggande responsiv, med två nivåer av storlekar:
- Vid 1024 pixlar eller mindre ändras bredden på main-delen (huvudtexten) så den tar upp lite mer yta.
- Vid 767 pixlar eller mindre ändras meny och header enligt den mall som medföljde temat "example".