<p align="center">
  <img src="assets/icon.png" width="110" alt="Matlab Report Builder icon">
</p>

<h1 align="center">Matlab Report Builder</h1>

<p align="center">
  Turn a folder of MATLAB assignments into <b>one clean Word report</b>:<br>
  syntax-highlighted code, real output and readable figures, assignment by assignment.
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/badge/Download-latest%20release-2a9fd8?style=for-the-badge" alt="Download"></a>
  <a href="https://YOURUSERNAME.pythonanywhere.com/#buy"><img src="https://img.shields.io/badge/Get%20License-ffd43b?style=for-the-badge&labelColor=ffd43b&color=ffd43b&logoColor=16435f" alt="Get License"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-2a9fd8" alt="Windows 10/11">
  <img src="https://img.shields.io/badge/MATLAB-R2020a%2B-orange" alt="MATLAB R2020a+">
  <img src="https://img.shields.io/badge/Octave-supported-1f77b4" alt="Octave supported">
  <img src="https://img.shields.io/badge/Free%20trial-assignments%201–3-green" alt="Free trial">
</p>

<p align="center"><img src="docs/screenshot.png" width="560" alt="Matlab Report Builder screenshot"></p>

---

## Contents
[Features](#features) · [Download](#download) · [Quick start](#quick-start) · [Free trial vs full version](#free-trial-vs-full-version) · [Requirements](#requirements) · [Troubleshooting](#troubleshooting) · [FAQ](#faq) · [Support](#support)

## Features

- **Runs your code for you.** Uses MATLAB or free GNU Octave to run every `.m` file and captures the printed output and every figure.
- **Syntax highlighting.** Comments, keywords, strings and numbers are coloured like the MATLAB editor.
- **Readable figures.** Dark-themed plots are converted to a white background with dark, bold titles and labels, so they look good on paper.
- **Clean report structure.** Each assignment becomes **Assignment N → Code → Output**.
- **Editable Word file.** The result is a normal `.docx`, so add your own cover pages afterwards.
- **Private.** Everything runs on your computer. Your code is never uploaded anywhere.

## Download

Go to the **[Releases page](../../releases/latest)** and download one of:

| File | Best for |
|---|---|
| `MatlabReportBuilder-Setup-x.y.z.exe` | **Most people.** Normal installer with a Start-menu entry and uninstaller. No admin rights needed. |
| `MatlabReportBuilder-portable.zip` | No installation. Extract anywhere and run `MatlabReportBuilder.exe`. |

You don't need Python or anything else. Everything is bundled.

<details>
<summary><b>Windows says "Windows protected your PC"?</b></summary>

Windows SmartScreen shows this for new apps that aren't yet widely downloaded. Click **More info → Run anyway**.

Some antivirus programs may also flag newly released apps by mistake. If you'd like to be sure your download is genuine, compare its checksum with the one in the release notes (see below).
</details>

<details>
<summary><b>Verify your download (optional)</b></summary>

Open PowerShell in the folder with the file and run:

```powershell
Get-FileHash .\MatlabReportBuilder-Setup-1.0.0.exe -Algorithm SHA256
```

The result should match the SHA-256 listed in the release notes.
</details>

## Quick start

1. **Install** the app (or extract the portable zip) and open **Matlab Report Builder**.
2. Click **Browse** and choose the folder that contains your `ASSIGNMENT` folders:

   ```
   Matlab-and-R/
   ├─ ASSIGNMENT 1/
   │   ├─ A1Q1.m
   │   └─ A1Q2.m
   ├─ ASSIGNMENT 2/
   │   └─ A2Q1.m
   └─ ASSIGNMENT 3/
       └─ ...
   ```

   Folder names just need to contain `ASSIGNMENT` followed by a number. Other folders are ignored.
3. Pick how to get the output:
   - **Run with MATLAB** or **Run with Octave**: the app runs each script and captures output and figures.
   - **Don't run**: uses output files (`.txt`, `.png`, `.jpg`) already saved next to your `.m` files.
4. Leave **Make figures readable** ticked (recommended).
5. Click **GENERATE** and watch the progress bar and console log.
6. Your report, `MATLAB_Assignments.docx`, is saved **inside the folder you chose**. Click **Yes** to open it.

## Free trial vs full version

| | Free trial | Full version |
|---|:---:|:---:|
| Assignments 1–3 | ✔ | ✔ |
| Assignments 4 and up | — | ✔ |
| Run with MATLAB / Octave | ✔ | ✔ |
| Syntax highlighting & readable figures | ✔ | ✔ |
| Price | Free | One-time payment |

### Getting the full version

1. Click **Get License Key** in the app, or visit the [purchase page](https://YOURUSERNAME.pythonanywhere.com/#buy).
2. Pay by bKash and send your payment screenshot as described on that page.
3. You'll receive a license key by email or WhatsApp.
4. In the app click **Enter License Key**, paste the key and confirm. The full version is unlocked.

Your key is stored on your computer and checked offline each time the app starts. No account and no internet connection are needed. Updating or reinstalling the app keeps your license.

## Requirements

- Windows 10 or 11 (64-bit)
- **MATLAB** R2020a or newer, **or** free [GNU Octave](https://octave.org). Only needed if you want the app to *run* your code. It finds default installations automatically.
- Microsoft Word, or any program that opens `.docx` files

## Troubleshooting

| Problem | What to do |
|---|---|
| "Could not find MATLAB" | Install MATLAB or Octave, or choose **Don't run**. |
| It seems stuck on one file | Scripts that use `input()` or `pause` wait forever (the app stops them after 5 minutes). Remove those lines. |
| A script's output is empty | Lines ending with `;` print nothing, exactly as in MATLAB. |
| "That key is not valid" | Copy the **whole** key (it is long). Spaces and line breaks are fine. Contact support if it still fails. |
| Figures look different from MATLAB | Untick **Make figures readable** to keep MATLAB's original colours. |
| The report has only some assignments | The free trial covers assignments 1–3. Unlock the full version for the rest. |
| Reset the license on a PC | Delete `%APPDATA%\MatlabReportBuilder\license.key` and restart the app. |

## FAQ

**Do I need MATLAB?**
To run your scripts, yes: MATLAB or free Octave. Without either, use **Don't run** with output files you already saved.

**Does it change my files?**
No. It only reads your `.m` files and writes one new `MATLAB_Assignments.docx`.

**Can I use my key on another computer?**
Keys are for personal use. If you change computers, contact support.

**Does it work offline?**
Yes, completely.

**I updated the app. Do I need my key again?**
No. The license is stored separately from the app and survives updates and reinstalls.

## Support

- Found a bug or have a suggestion? [Open an issue](../../issues).
- Payment or key problems: email **aymanafjal09@gmail.com** or WhatsApp **+8801816844231**.

When reporting a problem, include your app version, what you clicked, and the text from the console log.

## Releases and changelog

See [CHANGELOG.md](CHANGELOG.md) and the [Releases page](../../releases).

---

<p align="center">
  © Your Name. All rights reserved. See <a href="LICENSE.txt">LICENSE.txt</a>.<br>
  This repository contains documentation and release downloads only.
</p>
