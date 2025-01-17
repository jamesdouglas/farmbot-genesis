---
title: "Camera Cable"
slug: "camera-cable"
description: "This cable connects the camera to the Raspberry Pi through the y-axis cable carrier."
cad: https://cad.onshape.com/documents/728fa8fdb342a040fe0ca4b5/w/0435033a7c78b02e71d0f721/e/3a0f0adaf57c0282d62a7445?configuration=default&renderMode=0&uiState=6255d38146b4a5023f0aac7b
variants: 2.6m|4.1m
price: $15.00|$20.00
quantity:
  standard: 1|0
  xl: 0|1
specs:
  length: 2.6m|4.1m
  cable: Shielded 28AWG/1p + 24AWG/2c<br><br>1p = 1 twisted pair (for data)<br>2c = 2 core (for power)
  connector 1: 4-pin female waterproof 90 degree connector
  connector 2: Right-angle USB Type A connector
  labels: CAM
internal-specs:
  internal-part-name: Camera Cable - 2.6m (Genesis)|Camera Cable - 4.1m (Genesis XL)
  rev: B|B
  cost: $5.70|$6.50
  notes: Cable must be shielded USB cable or there will be EMI issues.
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Length       |Measure the length of the cable using a measuring tape.|See BOM spec|+/- 20mm
|Diameter     |Measure the diameter of the cable using digital calipers.|5mm|+/- 0.5mm
|Cable        |Inspect the spec of the cable.|Shielded 28AWG/1p + 24AWG/2c<br><br>1p = 1 twisted pair (for data)<br>2c = 2 core (for power)|N/A
|Color        |Inspect the color of the cable.|Black|N/A
|Labels       |Inspect both ends for labels.|Should be labeled "CAM"|N/A
|Function     |Use the camera cable to connect a camera to a Raspberry Pi. Take a photo using the web app.|Image should be captured as expected|N/A
|90 degree connector|Connect the 90 degree connector to a camera and submerge into a cup of water. Take a photo using the web app.|The connector should make a waterproof connection, allowing an image to be captured as expected|N/A
|Electronics box fit|Connect the camera cable to the Raspberry Pi in a fully assembled electronics box.|Cable and connector should fit|N/A
