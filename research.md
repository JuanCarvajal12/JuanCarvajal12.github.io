---
layout: default
title: Research
permalink: /research/
---

I study the environmental transformation of galaxies, with a focus on **gas-rich dwarf galaxies** entering the **Fornax Cluster** for the first time. I primarily use **VLT/MUSE** integral-field spectroscopy, Next Generation Fornax Survey imaging (Muñoz et al. 2015) and MeerKAT H I observations from Serra et al. 2023. Whenever additional data is available and informative, I also try to make sense of it in a single coherent picture.

I also have an active interest in **solar system science**.

---

## Dwarf galaxies in clusters: first infall, stripping, and tides

### Motivation
Cluster dwarf galaxies today are mostly gas-poor and quenched, but the transition phase (from gas-rich to gas-poor) is short and hard to catch. The Fornax Cluster is a great nearby laboratory for this, and deep H I observations reveal a population of gas-rich dwarfs, some likely undergoing environmental interaction.

Some questions that motivate my research are:
- How do **ram-pressure stripping** and **tidal interactions** jointly regulate gas content and star formation of dwarf galaxies entering clusters?
- Can we quantify the roles of gas-consumption vs. gas-removal by linking star-formation diagnostics to morphology and kinematics?
- How is the transformation modulated by stellar mass and gas mass?
- How does star formation enhancement in cluster dwarfs compare to dwarf-dwarf interaction-driven bursts?
- Can spatially resolved chemistry + kinematics reveal **starburst migration** and progressive depletion?

### Data & approach
My core dataset is based on **VLT/MUSE** observations. I built a custom pipeline that wraps the regular data reduction workflow with improvements in sky subtraction strategies by using external photometric data. We analyze the data products with full-spectrum fitting. Details on the procedure and full list of references may be found in Carvajal et al. (2026, submitted).

---

## Flagship case study: NGC 1427A (Fornax)

NGC 1427A is my main benchmark object to understand early transformation in a low-mass galaxy. The project combines a deep, spatially contiguous MUSE mosaic with ancillary data from the FUV to radio (including H I), to link stars, ionised gas, neutral gas, and dust.

**High-level result:** stars and gas are strongly decoupled, and the multi-phase constraints point to **ram-pressure stripping with a strong line-of-sight component**, plus an additional local perturbation consistent with a mild dwarf–dwarf fly-by.

**Status / link**
- Tidal pre-conditioning and ram-pressure stripping in NGC 1427A. Deep VLT/MUSE spectroscopy and FUV--to--radio observations trace a Fornax Cluster dwarf in transformation (submitted)
  - If not available on arxiv yet, feel free to reach out requesting a preprint.

### Figures (from Carvajal et al., submitted)

<figure style="margin:18px 0;">
  <img src="{{ '/assets/img/ngc1427a_fig2_rgb.png' | relative_url }}"
       alt="NGC 1427A: 8µm (dust), Hα, and FUV composite with H I contours"
       style="width:100%; max-width:900px; border-radius:12px; display:block;">
  <figcaption style="font-size:0.92rem; color:#555; margin-top:6px;">
    <strong>Fig. 2.</strong> Multi-wavelength view of NGC 1427A: Spitzer 8µm (dust), MUSE Hα, and GALEX FUV, with optical contours overlaid (u+g+i). A compact star-forming body sits within a more extended multi-phase component.
  </figcaption>
</figure>

<figure style="margin:18px 0;">
  <img src="{{ '/assets/img/ngc1427a_fig3_hi_optical.png' | relative_url }}"
       alt="NGC 1427A: MeerKAT H I contours over optical image"
       style="width:100%; max-width:900px; border-radius:12px; display:block;">
  <figcaption style="font-size:0.92rem; color:#555; margin-top:6px;">
    <strong>Fig. 3.</strong> MeerKAT H I column-density contours over the optical light. The asymmetric, extended H I morphology highlights ongoing environmental interaction.
  </figcaption>
</figure>

<figure style="margin:18px 0;">
  <img src="{{ '/assets/img/ngc1427a_fig10_cartoon.png' | relative_url }}"
       alt="Schematic interpretation of NGC 1427A transformation"
       style="width:100%; max-width:900px; border-radius:12px; display:block;">
  <figcaption style="font-size:0.92rem; color:#555; margin-top:6px;">
    <strong>Fig. 10.</strong> Schematic interpretation: a sequence from earlier pre-conditioning to the current stripping geometry, shown in projected and side views to emphasize the line-of-sight component.
  </figcaption>
</figure>


---

## Solar system science

I also like solar system science. My first paper (2023) focused on active asteroids in the context of Rubin-era science. More recently, I contributed to the 3I/ATLAS campaign, with the X-shooter spectroscopy data reduction and primary analysis. For details see the [Publications]({{ '/publications/' | relative_url }}).


<figure style="margin:18px 0;">
  <img src="{{ '/assets/img/UC_team_photo.jpg' | relative_url }}"
       alt="UC Chile solar system working group"
       style="width:100%; max-width:900px; border-radius:12px; display:block;">
  <figcaption style="font-size:0.92rem; color:#555; margin-top:6px;">
    From top left, clockwise, Baltasar Luco, Thomas Puzia, Juan Carvajal, Rohan Rahatgaonkar.
  </figcaption>
</figure>

