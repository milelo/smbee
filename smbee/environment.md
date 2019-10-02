---
layout: default
title: Environment
grand_parent: Make a bee
parent: Prerequisites
has_children: true
nav_order: 4
---

## Working surface

Although there is no use of naked flames the high temperatures involved with soldering can scorch, melt or even combust materials if the hot-air is directed at them for a prolonged period. You will need some sort of mat on top of most working surface materials to both protect them and help make the surface mount components easily visible. I use a large cream ceramic tile on my desk to solder on.

1. Surface for populating the PCB
  * Smooth - components won't be lost in the undulations.
  * Light coloured preferably white of cream - for good contrast.
  * The larger the better - it is easy to accidentally flick the components when handling them. so the larger the size of the working area the better.

1. Surface for heating the PCB
  * Heat resistant - it will scorch rather than melt or combust.
  * Insulating - it won't conduct the heat away from the PCB.
  * Sacrificial - it doesn't matter if it is damaged.

## Soldering fumes

I use and advise the use of lead-free solder that conforms to the
[RoHS](https://www.rohsguide.com/rohs-faq.htm){:target="rohs"} directive, not the traditional leaded solder still widely available particularly in the hobby community. Risks from the fumes of the heated solder flux should also be considered, the risks depend on the flux-type, your exposure and sensitivities.

The [HSE has some advise](http://www.hse.gov.uk/pubns/indg248.pdf){:target="HSE-flux"} for employees who solder using rosin flux (derived from tree resin), also referred to as colophony-based solder flux. Because of its low-toxicity, no-clean and electrical properties, this is likely the type you will be using. Rosin fluxes are primarily the type used in industry and the hobby community. Please check the heath and safety information for the product you use.

The exposure time to fumes when making a badge can be small, during the short time while you melt the solder paste. This is in contrast to manufacturing jobs where people have long or continuous exposure. Be aware of the risks and take appropriate preventative measures.

When using hot air to melt the solder paste it will tend to disperse the fumes away from you. The fumes from applying a soldering iron will tend to flow directly upwards because of the heat so avoid this area.

Beyond simply avoiding the fumes, if you want or need to take more preventative measures, particularly for extended soldering periods or in a confined or unventilated area, filter equipment is available:

* Wear a P3 rated mask, disposable versions are available fairly cheaply.
* Use a fan fitted with a filter - These are only effective if the fan is very close to the fume source or trail. In my experience they block the working light so to avoid having to move closer to the fumes to see you might also need a local light source.
* Professional soldering stations are available that suck up and filter the area around the tip but these are expensive.

## ESD (electrostatic discharge) protection & EMC (Electro-Magnetic compatibility)

**Not required**: the risk of damage to the components is acceptable, the SMBee is designed for its aesthetics, minimalism and ease of construction rather than being burdened with the complexities needed to satisfy the demands and constrains necessary for more robust commercial product like arduino boards.
 
The badge can be functionally affected by static charges. If you put the badge near an insulated surface that has accumulated a static charge, the charge will likely overcome the weak pull-up on the badge button and trigger a LED sequence. 

It is normal practice to protect against electrostatic charges when working with electronic components however for cost and simplicity in this case I think it is an acceptable risk. The main device susceptible is the microcontroller, this does have a degree of protection from internal ESD protection diodes. For simplicity, the bee-badge doesn't have any additional designed-in protection so the risks during construction probably don't add much to ESD exposure risk after completion although no testing has been performed.

Many electrical components can be damaged by electrostatic discharges that accumulate on insulated (from ground) surfaces, particularly synthetic materials. Even if components appear not to be immediately damaged after being subjected to a discharge they can fail prematurely. Professionals will always use electrostatic protection like foot-straps, earthed wrist-bands, working surfaces and tools. Components will always be supplied in conductive packaging to avoid harmful potential differences (voltage) across sensitive devices. It is also a consideration when designing a product; as part of verifying a design, prototypes will be subjected to low-current high-voltage discharges to ensure they don't fail (environmental conformance testing).
