# X88H - Hybrid USB/JST

![](images/X88H-.bottom.svg)

![](images/X88H-.top.svg)

## License

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

This design may be freely produced, modified, and manufactured for private / low scale runs.

For larger scale runs (orders of over 50 units), please reach out to Nick (`nick[at]concreteflowers.com`), or Bachoo (`bachoobusiness[at]gmail.com`).

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Design Files / Libraries

The files were designed with [KiCAD 8.0.4](https://www.kicad.org/).

The [marbastlib](https://github.com/ebastler/marbastlib) MX switch symbol/footprint library is used for the project.

The 3D model for the PCB can be seen in the main folder under `X88H-3D-model.step`.

## Ordering from JLCPCB

1) Head to the [JLCPCB order page](https://cart.jlcpcb.com/quote).

2) Upload the `GERBER-X88H.zip` file in `jlcpcb/production_files/`.

3) Set the quantity of the PCBs you want made.

4) Set your desired PCB parameters. Here are some suggested parameters: (Everything else can be kept at their default)

- PCB Color: **Black**
- Surface Finish: **ENIG**
- Remove Order Number: **Yes**   

5) Enable the PCB Assembly option at the bottom, and set the following parameters:

- PCBA Type: **Standard**
- Assembly Side: **Both Sides**

6) Press `Confirm` at the bottom or `NEXT` on the right to get to the next page.

7) Click `NEXT` to get to the Bill of Materials tab.

8) Click `Add BOM File` and select the `BOM-X88H.csv` file in `jlcpcb/production_files/`.

9) Click `Add CPL File` and select the `CPL-X88H.csv` file in `jlcpcb/production_files/`. Click `Process BOM & CPL` to proceed.

10) You should be presented with a list of all the components and quantities needed. Double check there are no missing components. If there are, you will have to find substitute components for it. Click `NEXT` to proceed.

11) You should be presented with a view of the PCB and its components. Click `NEXT` to proceed.

12) You should see a breakdown of the price for the PCBs you want to order. Select `Keyboard - HS Code 847330` under `Office Appliance Accessories` for the Product Description.

13) Save to cart, and pay for it!

## Ordering from PCBWay

1) Head to the [PCBWay Quick Order page](https://www.pcbway.com/QuickOrderOnline.aspx)

2) Click the `Add Gerber file` button and add the `X88H.kicad_pcb.zip` file in the main folder. Don't worry about the broken preview.

3) Set the quantity of the PCBs you want made.

4) Set your desired PCB parameters. Here are some suggested parameters: (Everything else can be kept at their default)

- Solder mask: **Black**
- Surface finish: **Immersion gold (ENIG)**
- Remove product no.: **Yes (extra+$1.5)**

5) Enable the Assembly Service option at the bottom, and set the following parameters:

- Assembly side(s): **Both sides**
- Quantity: **as needed; same number as your PCBs?**
- Do you accept alternatives/substitutes made in China? **Yes**

6) Click Save to Cart. You will have to wait for your order to be reviewed before you can pay for it.
