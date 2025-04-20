---
title: "NyanSat's CPB and OBC Are Now Open-Source"
last_modified_at: 2025-03-18T17:09:53-07:00
categories:
  - Blog
tags:
  - OBC
  - Avionics
  - CPB
header:
    teaser: /assets/images/obc.jpg
---
The NyanSat team has released the full open-source design files for its Onboard Computer (OBC) and Combined Payload Board (CPB), coinciding with the team’s presentation at the 2025 CubeSat Developer Workshop at Cal Poly San Luis Obispo.

Derived from the open-source PyCubed platform, these updated boards are designed to simplify integration into more complex spacecraft. The designs emphasize ease of manufacturing and sourcing, with single-sided assembly, widely available components, and robust electrical design for space environments.

[NyanSat Obi Wan Komputer and Combined Payload Board](https://github.com/OakwoodEngineering/ObiWanKomputer) by [Oakwood Engineering](https://nyansat.org) is licensed under [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/?ref=chooser-v1)  <img width="18" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""> <img width="18" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""> <img width="18" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt="">

{% include figure popup=true image_path="/assets/images/cpbobc.png" alt="The CPB and OBC in integration testing." caption="Oakwood’s open-source CPB, and the OBC that is informally dubbed the \"Obi Wan Komputer.\"" %}

The CPB offers a versatile payload interface with multiple power and signal domains, while the OBC features a newly developed stacking protocol, increased radiation tolerance, and a novel watchdog and supervisor circuit for fault recovery. Both boards are six-layer, via-in-pad PCBs with power and signal planes for performance and reliability.

For documentation and schematics, visit our [GitHub repository](https://github.com/OakwoodEngineering/ObiWanKomputer).

