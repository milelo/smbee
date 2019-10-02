---
layout: default
title: Populating the PCB
parent: Make a beehive
has_children: false
nav_order: 3
---
<!-- Adds class names: {: .no_toc .text-delta } -->

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
## 12V DC-DC converter

The DC-DC converter needs to be mounted flat (and optionally stuck) onto the PCB without a gap and soldered through-hole
to the PCB with the supplied header pins which should then be trimmed short.

Place a strip of double sided kapton tape on the back. Remove the clear backing tape.| ![DC-DC converter with kapton tape](assets/DC-DC-kapton.jpg){:width="150px"}
Insert the supplied header pins (inverted) through the module and PCB. **Ensure you stick the module on the side of the PCB with the J3 label** | ![](assets/DC-DC-presolder.jpg){:width="250px"}
Turn over, position the header (still inverted) and solder one pin, check alignment then solder the rest. | ![](assets/DC-DC-soldering1.jpg){:width="250px"}
Turn over the PCB again. With the small side-cutters snip off each pin with the plastic strip above the module. | ![](assets/DC-DC-solder2.jpg){:width="250px"}
Solder the module to the pins. | ![](assets/DC-DC-solder3.jpg){:width="200px"}

## Surface mount components

Apply the solder paste to the SMD pads and place the components. Ensure the diode is correctly oriented with its body line next to the D1 label. | ![](assets/paste-with-SMDs.jpg)
Ensure particularly D1 is well seated in the paste, it can be easily dislodged by the airflow. With the hot-air station, flow the paste with the airflow directed down on top of the components. | ![](assets/SMDs-soldered.jpg)

## Sprung contact pins

Some precautions need to be observed when soldering the pins:
* Check each of the receiving holes on the PCB to ensure the pins fit.
* Minimize the time the heat is applied to avoid deforming the internal springs in the pins.
* While soldering the pins ensure they aren't compressed. The springs can deform and set in the compressed position.
* It is more important to ensure the pins are fully inserted into the PCB during soldering so they sit at an equal height, this is more important than ensuring they are perpendicular to the PCB.

Requirement:
* A heated soldering iron with a tinned tip.
* A soldering iron tip cleaner, a damp sponge or brass wire.
* Solder wire to tin the tip.

Add a small amount of solder paste to the three of the contact-pin pads on the top of the PCB with the contact labels. | ![](assets/PCB-pins-paste.jpg)
Place the corresponding pins in the holes. Some of the paste will be pushed through the back of the hole. | ![](assets/PCB-pins-place.jpg)
Keeping the PCB in a position perpendicular to the surface so the pins are parallel to the surface, apply the tinned soldering iron tip to the back of the pads to melt the extruded paste, until a ring of melted solder appears between the pin and the PCB. | ![](assets/contact-pin-solder-ring.jpg){:width="250px"}
Apply the solder paste to the other three contact pads then reposition the PCB with the unpopulated contact pads on top and repeat the pin placement and soldering. | ![](assets/soldered-contact-pins.jpg)

## Header pins

To keep a low profile the header pins are soldered directly into the PCB without the plastic retaining strip.

With a small pair of pliers pull the header pins out of the retainer one by one. | ![](assets/removed-header-pins.jpg)
Insert all the pins fully into a USBASP ribbon cable IDC socket. You can use an IDC socket attached to the supplied ribbon cable or an old socket (shown). | ![](assets/pins-in-IDC-connector.jpg)
Insert the pins with the IDC connector into the **top side of the PCB on the same side as the contact pins**. Turn over, solder one of the pins and check the alignment and adjust if necessary. | ![](assets/header-pins-1-soldered.jpg)
Solder the rest of the pins. Keep the heat application time to a minimum to avoid melting the connector housing. | ![](assets/header-pins-all-soldered.jpg)
Unplug the IDC socket from the PCB to reveal the soldered pins. | ![](assets/header-pins-all-soldered-top.jpg)

## Switch

Press-fit the switch into the PCB on the same side as the contact pins. Turn the PCB over and solder its pins. | ![](assets/sw-soldered-top.jpg)

## Completed PCA

![PCA top](assets/PCA-top.jpg){:width="350px"} | ![PCA bottom](assets/PCA-bottom.jpg){:width="350px"}
