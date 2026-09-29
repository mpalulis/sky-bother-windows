# Sky Bother for Windows

A Windows adaptation of **Sky Bother**, the observing-session planner originally created for macOS by **WrendorWC**.

Plan observing sessions, browse deep-sky targets, and use your site and equipment settings to prepare for a night under the stars.

## Download

**Latest: [Download v0.2.0 — Comet Edition ZIP](https://github.com/mpalulis/sky-bother-windows/releases/download/v0.2.0/SkyBother-v0.2.0-Windows-Comets.zip)**

[Version 0.2.0 release notes and checksum](https://github.com/mpalulis/sky-bother-windows/releases/tag/v0.2.0)

**Previous: [Download v0.1.0 — Pre-comet ZIP with guide](https://github.com/mpalulis/sky-bother-windows/releases/download/v0.1.0/SkyBother-v0.1.0-Windows-PreComet-With-Guide.zip)**

[Version 0.1.0 release notes](https://github.com/mpalulis/sky-bother-windows/releases/tag/v0.1.0)

| Version | Edition | Comet lookup |
| --- | --- | --- |
| v0.2.0 | Latest Windows release | JPL candidates, imaging filters, and coordinates |
| v0.1.0 | Preserved Windows baseline | Not included |

## User guides

- [v0.2.0 Comet Edition guide](HOW-TO-USE-SkyBother-v0.2.0.md)
- [v0.1.0 Pre-comet guide](HOW-TO-USE-SkyBother-v0.1.0.md)

Both downloads include an HTML guide for reading and printing.
## Screenshots — v0.2.0 Comet Edition

### Choose Comets in the planner
![v0.2.0 planner with the target-type menu showing Comets](v0.2.0-planner.png)
Choose **Comets** from the target-type menu to request night candidates for the selected site and observing night. The planner also retains its deep-sky targets, weather timeline, and equipment profiles.

### Open the comet catalog
![Settings menu with the Comets option](v0.2.0-settings.png)
Use **Settings → Comets** to browse or search the comet catalog directly, including when a known object is absent from the imaging shortlist.

### Inspect a selected comet
![Comet catalog with search, JPL refresh, and selected-object Horizons coordinates](v0.2.0-comet-catalog.png)
Search by name or designation, then select an entry to request its Horizons coordinates. Check the displayed observation time and coordinate frame. **Refresh from JPL** updates the catalog. Catalog membership alone does not establish that a comet is a practical observing target, and SBDB M1 is a model parameter rather than current apparent brightness.

### Night candidates and imaging filters
![Night candidates with estimated total magnitude limit and Include unknown brightness enabled](v0.2.0-night-candidates.png)
**Night candidates** are geometric opportunities returned by JPL. **Potential imaging targets** also pass the chosen total-magnitude filter. This example has **Include unknown brightness** enabled, so its large count includes objects whose total brightness is unknown; it is not a count of guaranteed telescope detections. Select an object for coordinates and observing guidance. Counts depend on the site, night, and filter settings.

## Screenshots — v0.1.0

### Main planner
![Main planner with night ratings, conditions timeline, and Eastern Veil target details](v0.1.0-planner.png)
Choose your site and equipment, compare nights on the left, and inspect the selected target on the right. This example is **cloud limited**: potential target windows do not mean clear weather is forecast.

### Target catalog
![Deep-sky target catalog with search, type filter, images, and IC 10 details](v0.1.0-catalog.png)
Browse the deep-sky catalog, search or filter by type, and select a target to see its coordinates, size, and planning information. Pictures are reference images, not a live telescope view.

### Sky View
![Sky View showing Eastern Veil and the time slider](v0.1.0-sky-view.png)
Move the time slider or press **Play** to preview the sky during the selected night. **Jump to best window** helps locate the preferred interval. The displayed time and status belong to the preview; check the planner's weather warnings separately.

### Equipment selector
![Equipment preset menu showing Seestar, Origin, Unistellar, Vaonis, DwarfLab, and camera options](v0.1.0-equipment.png)
Select the preset matching your setup, then check its values in **Settings → Equipment**. Equipment profiles support planning and framing; choosing one does not connect to or control the telescope.

## Install and run

1. Download the Windows ZIP from **Releases**.
2. Right-click it and choose **Extract All**.
3. Open the extracted `SkyBother` folder and run `SkyBother.exe`.
4. Keep the `Catalog` folder beside the executable; it contains the bundled target data and images.
5. Choose your observing site and equipment, then refresh the planner.

Internet access is needed for online features such as weather and place searches. Do not run the app directly from inside the ZIP.

## Update or return to an earlier version

Close Sky Bother before changing versions. Back up `%AppData%\SkyBother`, extract the desired release into a separate folder, and run that folder's executable. Update any shortcut to point to the new copy.

Different versions may share the same saved-settings folder. Keep your backup when switching between the pre-comet and comet editions.

## About version numbers

Windows releases use their own version sequence. The v0.1.0 package preserves the original pre-comet application; its embedded executable version may differ from the release label. It has not been rebuilt simply to change that metadata.

## Report a problem

Use this repository's **Issues** page. Include the release version, exact error message, what you were doing, and a screenshot where useful. Remove private site coordinates or other personal information before posting.

## Credits

**WrendorWC created the original Sky Bother for macOS.** This Windows adaptation is based on their work.

Original project: **[WrendorWC/sky-bother](https://github.com/WrendorWC/sky-bother)**

Please visit the original project for the macOS version. This repository distributes the Windows adaptation.

## License and attribution

Original copyright and license notices are preserved in [LICENSE](LICENSE). Catalog data and images have separate attribution and terms; see [CATALOG-LICENSE.md](CATALOG-LICENSE.md).





