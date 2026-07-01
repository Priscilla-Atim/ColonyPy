# ColonyPy

**Automated fungal colony detection and classification for antifungal tolerance and heteroresistance, using StarDist deep learning**
ColonyPy is a desktop application for automated fungal colony detection and classification from petri dish images. It uses a StarDist deep-learning model to identify colonies and classify them as **Tolerance** or **Heteroresistance** based on size relative to the p25 (25th percentile) colony area of isolate-matched, no-drug control plates. Both **disk diffusion** and **agar dilution / population analysis profiling** workflows are supported.


## Download 

Download the latest version of ColonyPy for your operating system from the [Releases](../../releases) page.

|Platform|File|
|-|-|
|🪟 Windows|`ColonyPy_Windows.exe`|
|🍎 macOS|`ColonyPy_macOS.zip`|
|🐧 Linux|`ColonyPy_Linux.zip`|


## ⚠️ Security Notice

ColonyPy is not commercially code-signed as it is an academic research tool. Your operating system may display a security warning when launching it for the first time. **This is expected, the software is safe to use.**

### Windows

1. Click **"More info"** on the SmartScreen warning
2. Click **"Run anyway"**

### macOS

1. Go to **System Settings → Privacy \& Security**
2. Scroll down and click **"Open Anyway"** next to ColonyPy

### Linux

1. Right-click the downloaded file → **Properties → Permissions**
2. Check **"Allow executing file as program"**
3. Double-click to open, or right-click → Run as Program

> If you continue to experience issues bypassing the security warning, please open a [GitHub Issue](../../issues) or contact us directly and we will assist you.

>  **⏱ First-launch delay:** On the very first launch, ColonyPy may take **5–10 minutes** to start while it unpacks its bundled libraries. Subsequent launches are faster. This is normal behaviour for PyInstaller executables.


## User Manual

The full user manual is available here:  
👉 [**ColonyPy User Manual**](https://Priscilla-Atim.github.io/ColonyPy/USER_MANUAL.html)

The manual covers installation, workflow, the manual editor, output files, troubleshooting, and FAQs.


## Features

* Automated colony detection using a StarDist deep-learning model
* Two analysis workflows: disk diffusion and agar dilution / population analysis profiling
* Classification of colonies as **Tolerance** (below p25 control threshold) or **Heteroresistance** (at or above p25 control threshold)
* Strain-matched control plate calibration
* Manual editor for adding, removing, and reclassifying colonies
* Session saving and reloading (Tools → Load Editing Session)
* Settings save/load between sessions (File → Save Settings / Load Settings)
* CSV and Excel output with replicate statistics and coefficient-of-variation warnings
* Per-image annotated PDF visualisations
* Cross-platform: Windows, macOS, and Linux
* No Python installation, no internet connection, and no additional setup required. ColonyPy is fully self-contained executable


## System Requirements

||Minimum|
|-|-|
|RAM|8 GB (16 GB recommended for large batches)|
|Storage|500 MB free space|
|GPU|Optional TensorFlow will use a supported GPU automatically if available|

> **Note**: Windows is supported but has known compatibility limitations with machine learning frameworks. On Windows, a single image may take 3–5 minutes to analyse. If you are on Windows and need faster performance, the recommended solution is to set up Ubuntu via WSL (Windows Subsystem for Linux) and run the Linux version of ColonyPy, this restores the ~20 second per image speed.


## Sample Images

Two sample images are provided in the [`sample_images/`](sample_images/) folder for you to test ColonyPy before analysing your own data.

Please rename them following the file naming convention described in the [User Manual](https://Priscilla-Atim.github.io/ColonyPy/USER_MANUAL.html#naming) before importing
For example
- `KN99_rep1_FLC.jpg` for a test plate
- `KN99_C.jpg` for the matching control plate


## Citation

If you use ColonyPy in your research, please cite:

> Atim, P. et al. (2026). ColonyPy: A python-based image analysis pipeline to quantify tolerance and heteroresistance in _Cryptococcus neoformans_. \[Journal name, DOI coming soon]


## Contact

For questions or issues, please open a [GitHub Issue](../../issues) or contact apriscilla@vt.edu.


*ColonyPy v1.0 · Nielsen Laboratory · Virginia Tech University*
