# MARINE

Marine web tools for weather and navigation, from Xaxero Marine Software. Each tool is a self-contained HTML page — no build step, no backend. Open directly in a browser or serve from any static web server; most tools work offline once loaded.

**For planning and training purposes only. Always navigate with official charts, publications, and notices to mariners.**

## Celestial navigation

| File | Description |
|---|---|
| `cnavj.html` | HO-229 Sight Reduction & Plotter: complete celestial navigation workbench with an integrated nautical almanac, HO-229 table simulator, star finder, and interactive plotting sheet. Compute celestial fixes instantly. |
| `cnavjDoc.html` | H.O. 229 Interactive Guide: step-by-step documentation for the sight-reduction tool, with charts and worked examples. |
| `ho229_info.html` | Landing/info page describing the HO-229 tool and its features. |
| `ephemeris.js` | Ephemeris/almanac data used by the celestial navigation tools. |

## Marine weather

| File | Description |
|---|---|
| `fax2026.html` | Xaxero Weather Fax 2026: radiofax-style weather chart browser (surface analysis, prognosis, wind/wave charts). |
| `faxnew.html` | Xaxero Matrix Weather v2.3: interactive Leaflet map with gridded weather overlays and D3 visualizations. |
| `tides.html` | Xaxero Marine Tides: tidal height and stream predictions. |

## Sea surface temperature (satellite oceanography)

| File | Description |
|---|---|
| `sst.html` | Selector page for the SST analysis tools. |
| `sst_viewer_repaired.html` | Full SST viewer: NOAA SST chart analysis with temperature probing and route profiling, aimed at tuna operations. |
| `sst_viewer_simple.html` | Lightweight SST viewer for the NOAA global contour chart. |

## Vessel documentation

| File | Description |
|---|---|
| `crewlist.html` | IMO Crew List Generator (FAL Form 5): fill in crew details and produce a compliant, printable arrival/departure crew list with built-in country codes. |
| `paxlist.html` | IMO Passenger List Generator (FAL Form 6): same idea for passenger manifests. |

## License

See `LICENSE`.
