# LAG-GC
LAG-GC is a Lagrangian guiding-center approach to resolving particle fluxes at GEO. LAG-GC models Earth's magnetosphere macroscopically using discrete protons that propagate according to BATSRUS MHD fields.

Make sure to adjust the datetime across all files to match your date of interest. Everything is currently set up to begin on December 31st, 2025 at 00:00 and end at 02:00 UTC. All the associated parameters are taken from that time as well. 

This includes the ephemeris of the GOES-18 satellite, the Kp index, the Dst index, and solar parameters. Each of these parameters is hardcoded and needs to be adjusted to match any new date not on December 31st, 2025, 00:00 to 02:00.
