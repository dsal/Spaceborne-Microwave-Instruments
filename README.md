# Spaceborne-Microwave-Instruments

***What HH, VV, HV, VH mean?***
H = Horizontal polarization
V = Vertical polarization
The notation is Tx-Rx (Transmit–Receive):
HH → Transmit H, Receive H
VV → Transmit V, Receive V
HV → Transmit H, Receive V
VH → Transmit V, Receive H
So, the radar can send a wave in a given polarization and record how the scattered wave comes back in the same or a different polarization.

***What the different channels tell us?***
HH (co-polarized): Sensitive to surface scattering (flat surfaces like calm water, bare soil).
Strong HH return → rough horizontal features.
VV (co-polarized): Sensitive to double-bounce scattering (like urban areas, buildings, tree trunks with ground).
HV or VH (cross-polarized): Sensitive to volume scattering (randomly oriented objects like vegetation canopies, ice structures).
Cross-pol usually weaker than co-pol.

***Differences or ratios***
Often, researchers don’t just look at the individual polarizations but also differences, ratios, or combinations:
VV – VH (or ratio VV/VH): Helps separate urban vs vegetation. Vegetation has strong VH due to volume scattering, so VV–VH is low in forests, but high in built-up areas.

HH – HV (or ratio HH/HV): Useful for distinguishing bare soil / water (strong HH, weak HV) from vegetation (higher HV).

***What kind of plots you usually see?***
The plots are usually intensity maps or scatter plots: Intensity maps (grayscale or RGB composites):
Each polarization (HH, VV, HV) is shown as an image. Bright = strong backscatter.

Pauli or Freeman–Durden decomposition plots: Combine different polarizations into RGB false-color images to highlight scattering mechanisms. Example: Red = double-bounce (VV–HH), Green = volume (HV), Blue = surface (HH+VV)
Scatter plots (e.g., VV vs VH power): Show clusters for different land cover types (urban, vegetation, water).
