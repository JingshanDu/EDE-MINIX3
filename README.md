# EDE-MINIX3
__Project goal__: Patching the [Equinox Desktop Environment](https://sourceforge.net/projects/ede/) (EDE, version 2.1) to work with [MINIX3](https://www.minix3.org/) (R3.4.0rc6).

Based on the most recent releases of the EDE and the EDELIB, version 2.1, from SourceForge. EDE is licensed under GPLv2, and EDELIB under LGPLv2. This project is therefore licensed under GPLv2.

MINIX has been a great research and educational OS for a very long time, but it has not been able to catch up with time. Development activities of both MINIX and EDE have halted around 2016-2017. EDE was [once ported to MINIX3 in 2007](https://blog.minix3.org/2007/01/10/equinox-desktop-available/), but getting more recent versions to work seems problematic. 

## Current status
### September 8, 2025
With the current code patches, both `edelib` and `ede` can be compiled and installed with `clang` and `jam` included in MINIX3 without errors. However, I am yet able to successfully `startede` as there are problems with `evoke`.