# VISTA Engine (Vetting and Interferometric Spacial Transit Analyzer)
An automated exoplanet transit detection pipeline built in Python. Features adaptive stellar variability filtering, Box Least Squares (BLS) periodogram spectral sweeps and interactive multi-panel morphology models using Kepler and TESS space telescope telemetry

# VISTA Engine v5.4.2

A lightweight, exoplanet transit analysis engine built in Python. The application streams raw stellar photometry telemetry from NASA's MAST archive to locally process light curves, isolate signals from stellar noise and extract geometric planetary transit profiles.

# Features
* Stellar Variability Filter: Adaptive flattening window to isolate transit signals from active starspot rotations.
* BLS Periodogram Sweep: Box Least Squares algorithm spectral power analysis to detect exact orbital intervals.
* Morphology Sub-Models: Interactive folding maps, high-resolution micro-scale transit geometry fits, and flux probability density histograms.
* Precision Telemetry Metrics: Real-time local derivation of critical transit parameters, calculating physical planet radius, explicit transit duration in hours and statistical Signal-to-Noise Ratio (SNR) strength.
* Import and Export: The application features options to import and export planet data from .csv files and export .csv, .txt and images of the graphs.

# Installation
1. Python:
Make sure you have Python 3.10+ installed and added to your system's PATH.

2. Run this in your cmd:
pip install customtkinter lightkurve astropy astroquery matplotlib numpy

## Gallery & Performance Matrix

<table>
  <tr>
    <td align="center" width="50%"><b>TOI-1452 b (Primary Light Curve Matrix)</b></td>
    <td align="center" width="50%"><b>TOI-1452 b (Statistical Morphology)</b></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/Prathmaya/VISTA-Engine-v5.3.4/Assets/TOI-1452b(2).png" width="100%"></td>
    <td><img src="https://raw.githubusercontent.com/Prathmaya/VISTA-Engine-v5.3.4/Assets/TOI-1452b(1).png" width="100%"></td>
  </tr>

  <tr>
    <td align="center"><b>KEPLER-37 b (Primary Light Curve Matrix)</b></td>
    <td align="center"><b>KEPLER-37 b (Statistical Morphology)</b></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/Prathmaya/VISTA-Engine-v5.3.4/Assets/Kepler-37b(2).png" width="100%"></td>
    <td><img src="https://raw.githubusercontent.com/Prathmaya/VISTA-Engine-v5.3.4/Assets/Kepler-37b(1).png" width="100%"></td>
  </tr>

  <tr>
    <td align="center"><b>KEPLER-51 b (Primary Light Curve Matrix)</b></td>
    <td align="center"><b>KEPLER-51 b (Statistical Morphology)</b></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/Prathmaya/VISTA-Engine-v5.3.4/Assets/Kepler-51b(2).png" width="100%"></td>
    <td><img src="https://raw.githubusercontent.com/Prathmaya/VISTA-Engine-v5.3.4/Assets/Kepler-51b(1).png" width="100%"></td>
  </tr>
</table>
