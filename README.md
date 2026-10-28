# Kaarditrenn

Kuiv trenn päris orienteerumiskaartidel: leppemärgid, kaardilugemine, reljeef, teevalik, mõõtkava, Eesti tippvõistluste (MM, EM, MK) kaardid, päris võistluste analüüs Livelox'is ja märkide joonistamine mälu järgi. Raskus kohandub vastuste järgi.

Ava: https://anderojandu.github.io/kaarditrenn/

## Kaardid

Kaardipilte selles hoidlas ei ole. Need laaditakse kasutamise ajal otse [EOL-i kaardiserverist](https://orienteerumine.ee/kaardid/), ja iga kaardi all on kirjas selle omanik.

Kaust `data/` sisaldab ainult harjutuste jaoks arvutatud andmeid: objektide asukohti, etappe ja läbitavuse ruudustikku. Need on tuletatud samade kaartide OCAD-failidest, mida EOL avalikult jagab.

| Kaart | Maakond | Omanik |
|---|---|---|
| Lutsu (EOL 2025042) | Põlvamaa | OK Põlva Kobras |
| Kärsa (EOL 2024007) | Põlvamaa | OK Põlva Kobras |
| Vooreküla-Vastse-Kuuste (EOL 2020042) | Põlvamaa | OK Põlva Kobras |
| Pullapää (EOL 2018078) | Läänemaa | OK Okas |
| Kudjape (EOL 2024018) | Saaremaa | Saaremaa OK |

### Tippvõistluste kaardid

Nende kaartide OCAD-faile EOL ei jaga. Failid `data/champ-*.json` sisaldavad ainult kaardipildi värvide järgi leitud punkte: ühtlase maastikutüübiga kohti ja kohaleidmise ülesannete asukohti. Värvituvastust on kontrollitud OCAD-failiga kaartidel.

| Kaart | Maakond | Võistlus | Autoriõigus |
|---|---|---|---|
| Rõuge (EOL 2017001) | Võrumaa | MM 2017, tavarada (4.07.2017) | Eesti Orienteerumisliit |
| Rõuge (EOL 2019072) | Võrumaa | MM 2017 tavaraja maastik, kaart värskendatud 2019 | Eesti Orienteerumisliit |
| Vitipalu (EOL 2017006) | Tartumaa | MM 2017, lühirada ja teatejooks (6.–7.07.2017) | Eesti Orienteerumisliit |
| Kirikuküla (EOL 2017072) | Valgamaa | MM 2017 lühiraja ja teatejooksu näidisvõistlus | MTÜ MM2017 |
| Voorepalu (Küka) (EOL 2017005) | Põlvamaa | MM 2017 katsevõistlus (mai 2017) | Orienteerumisklubi Põlva Kobras |
| Tartu (EOL 2017003) | Tartumaa | MM 2017, sprindi eel- ja finaalvõistlus (30.06.–1.07.2017) | Eesti Orienteerumisliit |
| Viljandi (EOL 2017002) | Viljandimaa | MM 2017, sprinditeade (2.07.2017) | Eesti Orienteerumisliit |
| Kääriku (EOL 2006001) | Valgamaa | EM 2006 ja MK 2006 | OK Ilves |
| Otepää- Vastsemõisa- Nüpli (EOL 2006002) | Valgamaa | EM 2006 ja MK 2006 | OK Ilves |
| Tehvandi-Apteekri (EOL 2006003) | Valgamaa | EM 2006 ja MK 2006 | OK Ilves |
| Haanja- Kurgjärve (EOL 2006008) | Võrumaa | EM 2006 ja MK 2006 | OK Võru, OK Ilves |
| Haanja- Tseamäe (EOL 2006009) | Võrumaa | EM 2006 ja MK 2006 | OK Võru, OK Ilves |
| Otepää Linnamägi (EOL 2006004) | Valgamaa | EM 2006 ja MK 2006, sprint | OK Ilves |
| Tartu Toomemägi (EOL 2006005) | Tartumaa | EM 2006 ja MK 2006, sprint | OK Ilves |
| Uniküla (EOL 2003035) | Tartumaa | Juunioride MM 2003 | OK Põlva Kobras |
| Intsikurmu (EOL 2003036) | Põlvamaa | Juunioride MM 2003 | OK Põlva Kobras |
| Küka (EOL 2003037) | Põlvamaa | Juunioride MM 2003 | OK Põlva Kobras |
| Sae (EOL 2022015) | Lääne-Virumaa | EM 2022 ametlik treeningvõistlus | Rakvere OK |

Kui kaardi omanik ei soovi, et tema kaarti siin kasutatakse, eemaldame selle.
