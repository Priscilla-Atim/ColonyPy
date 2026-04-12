# ColonyPy

**Automated fungal colony detection and classification for antifungal tolerance and heteroresistance, powered by StarDist deep learning**  
ColonyPy is a desktop application for automated fungal colony detection and classification from petri dish images. It uses a StarDist deep-learning model to segment colonies and classify them as **Tolerance** or **Heteroresistance** based on size relative to strain-matched control plates.

\---

## Download

Download the latest version for your operating system from the [Releases](../../releases) page.

|Platform|File|
|-|-|
|🪟 Windows|`ColonyPy\_Windows.exe`|
|🍎 macOS|`ColonyPy\_macOS.zip`|
|🐧 Linux|`ColonyPy\_Linux`|

\---

## ⚠️ Security Notice

ColonyPy is not commercially code-signed as it is an academic research tool. Your operating system may display a security warning when launching it for the first time. **This is expected, the software is safe to use.**

### Windows

1. Click **"More info"** on the SmartScreen warning
2. Click **"Run anyway"**

### macOS

1. Go to **System Settings → Privacy \& Security**
2. Scroll down and click **"Open Anyway"** next to ColonyPy

### Linux

You may need to make the file executable before running it:

```bash
chmod +x ColonyPy\_Linux
./ColonyPy\_Linux
```

\---

## User Manual

The full user manual is available here:  
👉 [**ColonyPy User Manual**](https://Priscilla-Atim.github.io/ColonyPy/USER_MANUAL.html)

The manual covers installation, workflow, the manual editor, output files, troubleshooting, and FAQs.

\---

## Features

* Automated colony detection using a StarDist deep-learning model
* Classification of colonies as **Tolerance** or **Heteroresistance**
* Strain-matched control plate calibration
* Manual editor for adding, removing, and reclassifying colonies
* Batch processing of multiple plates
* CSV and Excel output with replicate statistics
* Cross-platform: Windows, macOS, and Linux

\---

## System Requirements

||Minimum|
|-|-|
|RAM|8 GB (16 GB recommended for large batches)|
|Storage|500 MB free space|
|GPU|Optional — TensorFlow will use a supported GPU automatically if available|

> \*\*Note:\*\* TIFF images take longer to analyse due to their large file size, especially if your system RAM is running low. Converting images to PNG before analysis will improve performance.

\---

## Citation

If you use ColonyPy in your research, please cite:

> Atim, P. et al. (2026). \*ColonyPy: A deep-learning pipeline for automated fungal colony detection and classification of antifungal tolerance and heteroresistance.\* \[Journal name, DOI — coming soon]

\---

## Contact

For questions or issues, please open a [GitHub Issue](../../issues) or contact the Nielsen Laboratory at Virginia Tech University.

\---

*ColonyPy v1.0 · Nielsen Laboratory · Virginia Tech University*

