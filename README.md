# Project-SolderingStation

This is the project of Kobe Dieryck

## Intro
For this assignment, a soldering station was chosen. The project aimed to achieve a minimalist, small, and sleek design while maintaining a high level of power. The preferred connector for this project was the *Hirose RPC1* 6 pin connector, commonly found in JBC soldering stations. This choice allowed for easy swapping of the iron without the need for any modifications.


Furthermore, a single modification was made to the design by incorporating SMD (Surface-Mount Device) Components. This decision aimed to simplify the assembly process and achieve a more compact overall design.
The foundation of this project is based on the Elektor magazine release 507 (June 2021), which provides detailed instructions for constructing a soldering station. The design utilizes the *Atmega4809* microcontroller and a 2 x 12V transformer with a power rating of 60VA.


## Bill Of Materials

| Item             | Store      | Package          | Price/unit | Amount | Total price |
|------------------|------------|------------------|------------|--------|-------------|
| Resistors        |            |                  |            |        |             |
| 47 ohm           | lcsc       | 805              | € 0,0015   | 28     | € 0,0420    |
| 18 Kohm          | lcsc       | 805              | € 0,0010   | 3      | € 0,0030    |
| 1 Mohm           | lcsc       | 805              | € 0,0015   | 1      | € 0,0015    |
| 68 Kohm          | lcsc       | 805              | € 0,0016   | 1      | € 0,0016    |
| 5,6 Kohm         | lcsc       | 805              | € 0,0014   | 4      | € 0,0056    |
| 10 Kohm          | lcsc       | 805              | € 0,0010   | 6      | € 0,0060    |
| 100 ohm          | lcsc       | 805              | € 0,0018   | 3      | € 0,0054    |
| 10 Mohm          | lcsc       | 805              | € 0,0014   | 1      | € 0,0014    |
| 4,7 Kohm         | lcsc       | 805              | € 0,0015   | 6      | € 0,0090    |
| Inductors        |            |                  |            |        |             |
| L1               | lcsc       | 805              | € 0,1271   | 1      | € 0,1271    |
| L2               | Mouser     | 2545             | € 2,3000   | 1      | € 2,3000    |
| Capacitors       |            |                  |            |        |             |
| 4700 uF          | lcsc       | D25xL25mm plugin | € 0,8289   | 1      | € 0,8289    |
| 10 uF            | lcsc       | D4XL5,4          | € 0,0237   | 3      | € 0,0711    |
| 100 nF           | lcsc       | 805              | € 0,0023   | 6      | € 0,0138    |
| 100 uF           | lcsc       | SMD,D8xL10mm     | € 0,1362   | 2      | € 0,2724    |
| 10 nF            | lcsc       | 805              | € 0,0033   | 7      | € 0,0231    |
| Semiconductors   |            |                  |            |        |             |
| 1n4007           | lcsc       | SOD-123Fl        | € 0,0048   | 1      | € 0,0048    |
| Zener            | lcsc       | SOD-123Fl        | € 0,0127   | 1      | € 0,0127    |
| 1n14148          | lcsc       | SOD-123Fl        | € 0,0064   | 1      | € 0,0064    |
| Brug             | lcsc       | TTF              | € 0,3166   | 2      | € 0,6332    |
| BC847C           | lcsc       | SOT-23           | € 0,0146   | 3      | € 0,0438    |
| MOSFET-P 30v     | Mouser     | TO-263-3(DPAK)   | € 1,2900   | 1      | € 1,2900    |
| MOSFET-P 20V     | lcsc       | TO-252-2(DPAK)   | € 0,2785   | 1      | € 0,2785    |
| BC857C           | lcsc       | SOT-23           | € 0,0231   | 1      | € 0,0231    |
| DC/DC            | Mouser     | OKI78SR8         | € 7,0500   | 1      | € 7,0500    |
| MCP6002-E/MS     | Mouser     | MSOP-8           | € 0,4400   | 1      | € 0,4400    |
| Mircocontroller  | Mouser     | TQFP-48          | € 1,8200   | 1      | € 1,8200    |
| relay            | Mouser     | RT424005f        | € 5,3800   | 1      | € 5,3800    |
| encoder          | lcsc       | PEC11R4220F      | € 1,6500   | 1      | € 1,6500    |
| fuse             | Mouser     | 5x20mm           | € 0,4230   | 1      | € 0,4230    |
| PCB              |            |                  |            |        |             |
| soldeerbout      | JLCPCB     |                  | € 0,7280   | 1      | € 0,7280    |
| SMT stencil      | JLCPCB     |                  | € 6,3800   | 1      | € 6,3800    |
| Others           |            |                  |            |        |             |
| Extrudr PLA-NX2  | 3DJake     | 1kg              | € 25,9500  | 2      | € 51,9000   |
| Gray PMMA 3mm    | hornbach   | 500mm x 500mm    | € 13,0000  | 1      | € 13,0000   |
| screw terminal   | aliexpress | Pitch 5mm        | € 0,0880   | 4      | € 0,3520    |
| testpoints       | Mouser     | 3,5x1,78mm       | € 0,4230   | 2      | € 0,8460    |
| ac connector     | Mouser     |                  | € 2,3200   | 1      | € 2,3200    |
| hirose connector | Mouser     | 20x20mm          | € 2,9000   | 1      | € 2,9000    |
| VMA425           | Gotron     |                  | € 5,5100   | 1      | € 5,5100    |
| Shipping + tax   |            |                  |            |        |             |
| mouser           | mouser     |                  | € 58,7500  | 1      | € 58,7500   |
| lcsc             | lcsc       |                  | € 15,0200  | 1      | € 15,0200   |
| JLCPCB           | JLCPCB     |                  | € 45,5000  | 1      | € 45,5000   |
| Price total      |            |                  |            |        | € 225,97    |


