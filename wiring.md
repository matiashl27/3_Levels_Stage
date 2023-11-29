# Mount the electronics

{{BOM}}

[M3x25mm cap head screw]: parts/mech/M3-25.md "{cat:mechanic}"
[M3 nut]: parts/mech/nuts.md "{cat:mechanic}"
[Raspberry Pi]: parts/elect/rpi-v4.md "{cat:electronic}"
[Pi HAT]: parts/elect/pi-hat.md "{cat:electronic, note:'This is a custom open-source board documented [here](https://github.com/wenzel-lab/open-microfluidics-workstation/)'}"
[Strobe Module]: parts/elect/strobe-module.md "{cat:electronic, note:'This is a custom open-source board documented [here](https://github.com/wenzel-lab/open-microfluidics-workstation/)'}"
[Strobe Cable]: parts/elect/strobe-cable.md "{cat:electronic, note:'This is a custom connector documented [here](https://github.com/wenzel-lab/open-microfluidics-workstation/)'}"
[Needle-nose plier]: parts/tools/pliers.md "{cat:tool}"
[2.5mm Ball-end Allen key]: parts/tools/2.5mmBallEndAllenKey.md "{cat:tool}"
[Spacer-S]: models/spacer-4mm.stl "{previewpage}"
[Spacer-M]: models/spacer-11mm.stl "{previewpage}"
[Nitrile gloves]: parts/consumables/gloves.md "{cat:consumable}"

These instructions assume you have the custom electronic components pre-assembled.

>! **Caution!** The electronic boards are static sensitive. Before touching them, touch a metal-earthed object. If you own one, consider wearing an anti-static strap.

## Connect the camera {pagestep}

* Use [nitrile gloves][Nitrile gloves]{Qty:2} to manipulate electronic components. 
* Insert the ribbon cable from the optics module into the camera port of the [Raspberry Pi]{qty:1}, ensuring the contacts are on the opposite side of the clasp. There are [detailed instructions on the Raspberry Pi website](https://projects.raspberrypi.org/en/projects/getting-started-with-picamera/2).

![](images/RPi_RibbonCable.jpg)

## Prepare the electronics {pagestep}

* Place the [strobe module][Strobe Module]{qty:1} over the [Pi HAT]{qty:1}.
* Mount the Pi HAT on the Raspberry Pi GPIO headers. There is a space to place the ribbon cable.

![](images/Pi-Hat_StrobeModule.jpg)
![](images/RPi_Pi-Hat.jpg)
![](images/RPi_Pi-Hat_1.jpg)

* Connect the 5-pin double row DuPont female connector of the [strobe cable][Strobe Cable]{qty:1} to the Pi HAT.

![](images/RPi_Pi-Hat_StrobeCable.jpg)
![](images/RPi_Pi-Hat_StrobeCable_1.jpg)

## Mount the boards {pagestep}

* Take four [M3x25mm cap head screws][M3x25mm cap head screw]{qty: 4} and insert them into each hole from the Pi hat and the Raspberry Pi. Use a [2.5mm Ball-end Allen key]{qty:1}.
* Use a [11mm spacer][Spacer-M](fromstep){qty: 2, cat:printedpart} in between the holes next to the power supply and USB connectors. A [needle-nose plier][Needle-nose plier]{qty:1} can be helpful to hold the spacer while you screw.

![](images/prepare-electronics.jpg)
![](images/prepare-electronics_1.jpg)
![](images/prepare-electronics_2.jpg)
![](images/prepare-electronics_3.jpg)

* Use a [4mm spacer][Spacer-S](fromstep){qty: 4, cat:printedpart} in between the electronic assembly and the bottom plate.
* Place the electronic assembly in the bottom plate and attach it to the surface using four [M3 nuts][M3 nut]{qty: 4}. A [needle-nose plier][Needle-nose plier] can be helpful to hold the nut.

![](images/mount_spacers.jpg)
![](images/mount_boards.jpg)
![](images/mount_boards_1.jpg)
![](images/mount_boards_2.jpg)
![](images/mount_boards_3.jpg)