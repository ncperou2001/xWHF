# xWHF
---

## Directories
- **/primary** - Extimated whiff rate for pitches deemed 'Primary Fastballs'.
- **/secondary** - Extimated whiff rate for all other pitches.

## Files
- **/maj_agg.csv** - Extimated whiff rate for pitches thrown in MLB (2020-)
- **/min_agg.csv** - Extimated whiff rate for pitches thrown in MiLB (A:2021, AAA:2022)

## Columns
- **LVL** - League level pitches were thrown at (MLB,AAA,A)
- **NAME** -Pitcher Name
- **ID** - MLB Pitcher ID
- **HAND** - Pitcher Hand
- **TYPE** - MLB Pitch Type
- **YEAR** - YEAR
- **P** - Pitches Thrown
- **RV/100** - Pitcher Run Value per 100 Pitches ('+' == good)
- **VELO** - Average pitch velocity in sample (mph)
- **XR,EXT,ZR** - Average release position in 3 dimensions (horizontal,extension,vertical)
- **HM,VM,TM,VD** - Average pitch movement (inches). (horizontal, vertical, total, vertical drop (with gravity))
- **RATE** - Spin rate in RPM
- **SSH** - Horizontal Seam-Shifted Wake 
- **SSV** - Vertical Seam-Shifted Wake 
- **sWHF** - Expected whiff rate against same handed hitters (20-80 scale)
- **oWHF** - Expected whiff rate against opposite handed hitters
---