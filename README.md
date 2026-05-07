# Relay Computer
A relay computer that adds or subtracts two 4-bit numbers made for a Capstone project

## How to use
Power the computer with a 5V through the barrel jack on the top-right.

There are nine switches on the bottom left&mdash;these are the inputs.
The four on the top are the A3-A0 inputs, and the four on the bottom are the B3-B0 inputs.

On the the switch on the middle-right is the additon-subtraction selector.
Switch it up to add the two numbers, and down to subtract them.

## Bill of materials
Here is the BOM (bill of materials) for one of the computer, with links.
Prices are included (shipping not included) but always subject to change.

| Item | Variant | Quantity | Link | Price |
| :-: | :-: | :-: | :-: | :-: |
| Relays *(100x)* | SRD-05VDC-SLC | 20 | [AliExpress](https://www.aliexpress.us/item/3256805988664644.html) | $19.27 |
| Diodes *(100x)* | 1N4007 | 28 | [Amazon](https://www.amazon.com/dp/B0FC2CQF24) | $5.99 |
| LEDs | *red, 5mm* | 33 | | |
| Switches *(10x)* | MTS-102 | 9 | [Amazon](https://www.amazon.com/dp/B0799HC3VY) | $7.99 |
| Barrel Jack | *5.5mm OD* | 1 | | |
| Resistors | 220&ohm; | 33 | | |
| PCB *(5x)* | | 1 | *see [how to order](#how-to-order)* | $15.80 |
| **Total** | | **125** | | **$49.05** |

## How to order
Head to [JLCPCB](https://cart.jlcpcb.com/quote?stencilLayer=2&stencilWidth=140&stencilLength=210&plateType=1) and upload the gerber file at [`production.zip`](https://github.com/tinkerer9/relay-computer/raw/refs/heads/main/production.zip).

Use the default options for customizing your order.
Use this table for reference:

| Option | Selection |
| :-: | :-: |
| Base Material | FR-4 |
| Layers | 2 |
| Dimensions | 210 * 140 mm |
| PCB Qty | *you choose* |
| Product Type | Industrial/Consumer electronics |
| PCB Thickness | 1.6mm |
| PCB Color | *you choose* |

Select a build time and add the PCB to your cart.

For my order, the 5 PCBs costed **$15.80** and the shipping costed **&approx;$30**, plus tarrifs.
I ended up paying **&approx;$50**.
These prices are subject to change.

## Questions
For any questions about this project, feel free to create a [new issue](https://github.com/tinkerer9/relay-computer/issues/new) on this repository.
