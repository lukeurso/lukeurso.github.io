---
title: "Twelve years of meltwater on Petermann and C.H. Ostenfeld glaciers"
excerpt: "Mapping slush, supraglacial lakes, and rapid drainage events in northern Greenland with Google Earth Engine and Landsat imagery."
collection: portfolio
---

My master's thesis at Stockholm University maps twelve years of slush and supraglacial lakes on the Petermann and C.H. Ostenfeld glaciers in northern Greenland.

## What it does

Working in Google Earth Engine, I classify slush and ponded meltwater from Landsat 8 and 9 imagery using a Random Forest classifier adapted from Dell et al. (2022), and estimate lake volumes following Pope et al. (2016) and Moussavi et al. (2020). Custom slope- and cloud-shadow masks let me track surface water at roughly two-day intervals, fine enough to detect rapid lake drainage events as they happen. The result is a high-frequency, long-term record of meltwater area, elevation, volume, and drainage for both glaciers.

The thesis is supervised by Dr. Nina Kirchner and Dr. Abhay Prakash.

📄 **[Read the full thesis (PDF)](/files/urso_luke_msc_thesis.pdf)**

## Code and tools

All of the analysis code is open on GitHub:

- **[MSc_ThesisScripts](https://github.com/lukeurso/MSc_ThesisScripts)** — the Earth Engine and Python workflows used throughout the thesis.
- A public **drainage-event viewer** in the repo renders before-and-after Landsat composites of individual drainage events (running it requires a Google Earth Engine account).

Built with Google Earth Engine, Landsat 8/9, Python, and JavaScript.
