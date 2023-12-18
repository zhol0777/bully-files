# bully-files

Bully is a keyboard designed by paaradiso keyboard design and zhol. It combines low typing angle, a plateless build, and modest but dignified design sensibilities. Its 13.5u width layout is designed for maximum compatibility with base kits that are missing minimum 40% keyboard support (“3-key”). Bully has a 22.4mm EKH, 4.0 degree angle, and bezels measuring 8mm and 3mm. 

The case files are provided in the [./case](./case/) directory, and alternative tops for HHKB layout (1.25u blocker) and WKL (1.25u blocker) are provided in their respective directories. 

This ran in a private run and public run by Coffee Break Keyboards in Q1 2023 and fulfilling Q2 2023.


## Required components
* Daughterboard
  * It is designed for [C3 Unified Daughterboard](https://github.com/Unified-Daughterboard/UDB-C-Legacy), but an updated daughterboard that takes JST-SH cables is provided [here](https://github.com/Unified-Daughterboard/UDB-C-JSH).
* Tadpoles
  * bully's PCB is fit into the case not with screws, but 8 injection molded rubber inserts named "tadpoles", from Geonworks.
  * [Files, courtesy Geon](https://geon.works/pages/tadpole-files)
* Screws
  * All screws are M2. Screws for daughterboard are 4mm, case screws are 6-ish mm.
* JST cable
  * As sold, bully took a 50mm 4-pin JST-SH cable. These cables are wired 1:1. I had no issues with Adafruit Qwiic JST SH cables sourced from Mouser. If you use an alternative connector on your PCB and daughterboard, you will need to ensure those cables are also 1:1.
* PCB
  * PCB edge cuts and plate files are provided in the [./misc](./misc/) directory. An electro-capacitive (commonly known as Topre, or NIZ Plum) compatible PCB is provided by sporkus [here](https://github.com/sporkus/capybully_keyboard). An alternative PCB compatible with Cherry MX and Alps switches is provided by sporkus [here](https://github.com/sporkus/bully2040_keyboard).
* Case feet.
  * bully uses [SKUF feet](https://github.com/Zambumon/SKUF).
