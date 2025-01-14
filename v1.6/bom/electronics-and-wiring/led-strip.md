---
title: "LED Strip"
slug: "led-strip"
description: "This LED strip is strung through the gantry's horizontal cable carrier supports so that you can light up your garden at night to show friends or for easy harvesting. Please note: this is not a grow light."
cad: https://cad.onshape.com/documents/728fa8fdb342a040fe0ca4b5/w/0435033a7c78b02e71d0f721/e/a4131c8f795e39a2eaf20dbf?configuration=default&renderMode=0&uiState=6255da6d46b4a5023f0ae2f1
variants: 1.5m|3m
price: $25.00|$50.00
quantity:
  standard: 1|0
  xl: 0|1
specs:
  light color: White 6000K
  strip length: 1.5m|3m
  lead length: 1m
  cable color: Black
  connector: Black 2-pin plug (<a href="https://www.molex.com/molex/products/datasheet.jsp?part=active/1510492206_CRIMP_HOUSINGS.xml">Molex Part 151049-2206</a>) (Rev A, prior to July 2022)<br>Black 2-pin plug (<a href="https://www.molex.com/molex/products/part-detail/crimp_housings/0050579402">Molex Part 50579402</a>) (Rev B, July 2022 and later)
internal-specs:
  internal-part-name: LED Strip - 24V, 1.5m (Genesis)|LED Strip - 24V, 3.0m (Genesis XL)
  rev: B|B
  cost: $6.60|$12.00
  notes: LED strip should NOT have an adhesive backing. Cut end must be dipped in silicon to seal.
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Connector    |Connect the LED strip to a Farmduino peripheral plug.|Part should connect as expected|N/A
|Cable color  |Inspect the color of the cable.|Black|N/A
|Cable length |Measure the length of the cable using a measuring tape.|1m|+/- 20mm
|LED color    |Turn on an LED strip and inspect the color of the light.|Cool white (6000K)|N/A
|LED strip length|Measure the length of the LED strip using a measuring tape.|See BOM spec|+/- 30mm
|LED strip cut end|Inspect the cut end of the LED strip.|Cut end should be sealed with silicon rubber|N/A
|Double-sided tape|Inspect the LED strip for double-sided tape.|The part should not have any tape or other adhesives along its length|N/A
