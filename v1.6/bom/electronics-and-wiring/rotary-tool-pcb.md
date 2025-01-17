---
title: "Rotary Tool PCB"
slug: "rotary-tool-pcb"
description: "This circuit board provides EMI filtering for the rotary tool motor as well as provisions to prevent a system voltage drop when the motor powers on."
cad: https://cad.onshape.com/documents/6626b842adca229e69544ad1/w/89ac2637f82d915f22c2bcd0/e/add47f53147452dd9a6a8ffc?renderMode=0&uiState=625506bb1ad350015b485f62
price: $15.00
quantity:
  standard: 1
  xl: 1
specs:
  motor connector: 3-pin JST XH receptacle
  pcb color: Matte black with gold ENIG
internal-specs:
  internal-part-name: Rotary Tool PCB
  rev: G
  cost: $3.90
---

{%
include callout.html
type="success"
title="Thank you Réstep"
content="The EMI filter circuit included in the Rotary Tool PCB is based on Chris Arntzen's openly licensed [Réstep EMI Filter add-on for older versions of FarmBot's vacuum pump](https://www.restep.eco/emi-filter).

Thank you Chris for lending your expertise in electronics design to the FarmBot community with this fantastic open-source contribution!"
%}

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|FWD/REV      |Assemble the PCB into a full Rotary Tool and test with a complete FarmBot.|Allows motor to be powered in forward and reverse at power/speed levels between 20% and 100%|N/A
|Load sense   |Assemble the PCB into a full Rotary Tool and test with a complete FarmBot.|PCB circuitry does not interfere with load sense readings or stall detection|N/A
|Color        |Inspect the color of the PCB.|Matte black|N/A
