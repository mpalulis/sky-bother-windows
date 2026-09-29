# Sky Bother for Windows

A Windows adaptation of **Sky Bother**, the observing-session planner originally created for macOS by **WrendorWC**.

Plan observing sessions, browse deep-sky targets, and use your site and equipment settings to prepare for a night under the stars.

## Download

**[Download Sky Bother for Windows v0.1.0 — Pre-comet ZIP](https://github.com/mpalulis/sky-bother-windows/releases/download/v0.1.0/SkyBother-v0.1.0-Windows-PreComet-With-Guide.zip)**

[Release notes and checksum](https://github.com/mpalulis/sky-bother-windows/releases/tag/v0.1.0)

This is the preserved Windows version from before comet lookup was added. The comet edition, v0.2.0, is being revised and tested separately.

| Version | Edition | Comet lookup |
| --- | --- | --- |
| v0.1.0 | Preserved Windows baseline | Not included |
| v0.2.0 | Comet edition under development | Being revised and tested |

## User guide

Read the **[v0.1.0 Pre-comet User Guide](HOW-TO-USE-SkyBother-v0.1.0.md)**. The downloadable ZIP also includes an HTML guide you can open in your browser and print or save as PDF.

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



