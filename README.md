# Cirrow

A desktop clock with weather around its face, by [Good Tools](https://goodtools.ca).

**[Product page](https://goodtools.ca/tools/cirrow) · [Download the current beta](https://github.com/MadeByGoodTools/Cirrow-Updates/releases/tag/v0.1.0-beta)**

Cirrow includes seven clock designs, typeface choices, a live settings preview, animated location-based weather, and independent stopwatch and countdown windows. Desktop mode keeps the clock behind normal apps; Floating is an explicit option.

## Downloads

- **macOS:** Apple Silicon, macOS 14 or newer. Download the ZIP, extract it, and move Cirrow.app into Applications. Cirrow lives in the menu bar and has no Dock icon. This beta is locally ad-hoc signed and is not notarized.
- **Windows:** x64 portable EXE. This is an unsigned preview. Physical Windows desktop placement, multiple-display DPI, drag/resize, and location permission behavior are still awaiting device testing. In Desktop mode, an unverified desktop attachment keeps the clock hidden; Settings reports the issue. Floating and Window modes require an explicit selection.

Weather uses Open-Meteo current conditions, refreshed periodically. Mac location uses Core Location with permission; Windows first tries device location and can use a labelled approximate network-location fallback. Lookup coordinates are rounded to one decimal place. Manual weather scenes are previews.

The Mac edition uses native Apple Liquid Glass on macOS 26 and newer, with a material fallback on earlier systems. Windows uses its own glass treatment and Windows typography.

This repository hosts compiled beta downloads and release information. App implementation source is not published here. Cirrow does not distribute the original Flip Clock app's code, artwork, fonts, or audio.

[Installation help](https://goodtools.ca/first-time-install) · [Contact Good Tools](mailto:hello@goodtools.ca)
