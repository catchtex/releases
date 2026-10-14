<p align="center">
  <img src="https://catchtex.com/assets/logo-256.png" width="96" alt="CatchTeX logo">
</p>

<h1 align="center">CatchTeX</h1>

<p align="center">
  <b>Snip tables, equations, plots and diagrams from PDFs. Get LaTeX that compiles.</b><br>
  Version 1.0 &middot; Fully offline &middot; Windows 10 and 11 &middot; Free edition forever
</p>

<p align="center">
  <a href="https://catchtex.com/download?ref=github"><b>Download from catchtex.com</b></a> &middot;
  <a href="https://catchtex.com/?ref=github">Website</a> &middot;
  <a href="https://catchtex.com/guides/">Guides</a> &middot;
  <a href="https://github.com/catchtex/releases/issues">Report a problem</a>
</p>

<p align="center">
  <img src="https://catchtex.com/media/snip-table.gif" width="760" alt="Snipping a block diagram and a table from a PDF in CatchTeX and getting TikZ and booktabs code">
</p>
<p align="center"><a href="https://catchtex.com/#demo">Watch the 45-second demo</a></p>

## What it does

Drag a box over part of a paper, in CatchTeX's own PDF viewer or anywhere on your screen (press
**S twice**), and get clean LaTeX you can paste into Overleaf:

| You snip | You get |
|---|---|
| a table | `booktabs` table with merged headers and maths in cells; doubtful cells highlighted |
| an equation | `amsmath`, your choice of environment, the paper's number kept as `\tag` |
| a plot | `pgfplots` with the measured data points, axes and legend |
| a block diagram | TikZ nodes and arrows |
| a reference list | BibTeX, optionally checked against Crossref, dblp, arXiv and OpenAlex |
| a paragraph | LaTeX text with maths and accents |

**Auto mode** recognises what you selected, so most of the time you just snip.

- **Exact from PDFs:** characters are read from the PDF's own text layer, not guessed from pixels.
- **Compiled before you copy:** a complete pdfLaTeX is built in; no TeX installation needed.
- **Private by design:** recognition runs fully offline. Your papers never leave your computer.

## Download

**Get the installer from [catchtex.com/download](https://catchtex.com/download?ref=github)**, or
from the [latest release](https://github.com/catchtex/releases/releases/latest) on this page.

| | |
|---|---|
| Version | 1.0.1 |
| File | `CatchTeX-Setup-1.0.1.exe` (238 MB) |
| SHA-256 | `ff8572da93dd79c2995ac9f6834ca4f25e818ca00e80654cebce05bf408ca90a` |
| System | Windows 10 or 11, 64-bit, about 750 MB disk space |
| Internet | Not needed (see below) |

Windows may show "Windows protected your PC" for a new installer: click **More info**, then
**Run anyway**. [Step-by-step help](https://catchtex.com/windows-warning).

To check the file, run this in PowerShell and compare it with the SHA-256 above:

```powershell
Get-FileHash .\CatchTeX-Setup-1.0.1.exe
```

This repository holds the installers, release notes and bug reports. The source code of CatchTeX
is not published here.

## Offline, and what goes online

CatchTeX 1.0 has no AI service and no cloud account. Everything is read on your computer. Only
two things use the internet:

- **Checking references** (Crossref, OpenAlex, dblp, arXiv, Semantic Scholar, Unpaywall): off
  until you allow it in *Settings â€º General â€º Internet*. Only the reference details are sent.
- **Activating Pro**: once per computer. Offline activation by e-mail is also possible.

## Editions

| | Free | Student | Pro | Lab pack |
|---|---|---|---|---|
| Price | $0 | $12 one-time | $29 one-time | $99 one-time |
| Snips | 10 a day | unlimited | unlimited | unlimited |
| Computers | any | 1 | 2 | 5 |
| Updates | all 1.x | all 1.x | all 1.x | all 1.x |

Students and researchers at the IITs and IISc get CatchTeX free for 6 months:
[catchtex.com/campus](https://catchtex.com/campus?ref=github). Departments and campuses: licences on request.

Paid licences come with a 14-day money-back guarantee, no questions asked.
[Buy a licence](https://catchtex.com/#pricing) &middot;
[Institute licences](https://catchtex.com/#institutes)


Mac or Linux? CatchTeX is Windows-only for now.
[Join the waitlist](https://catchtex.com/download#mac): sign-ups decide what comes next.

## What's new in 1.0

- Free edition and CatchTeX Pro (one-time licence).
- Fully offline: the optional AI assistant of the beta is removed.
- Reference checks ask before going online.
- Auto mode tells block diagrams apart from plots and node graphs more reliably.
- Clearer Settings window; screen snip by pressing **S** twice; simpler tray menu.

## Reporting a problem

Open an [issue](https://github.com/catchtex/releases/issues) or write to support@catchtex.com.
A screenshot of what you snipped and of the result helps most. Please do not attach confidential
documents.

---

CatchTeX is made by Mandla Labs, Mandla, India. &copy; 2026 Mandla Labs.
[Licence agreement](https://catchtex.com/eula) &middot; [Privacy](https://catchtex.com/privacy)
