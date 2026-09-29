# Catalog and Media Attribution

The application source is MIT licensed; see [LICENSE](LICENSE). The bundled data and images have separate terms:

- `Catalog/ExtendedCatalog.json` is derived from OpenNGC and is licensed CC BY-SA 4.0. The upstream project is https://github.com/mattiaverga/OpenNGC.
- `Catalog/TargetFacts.json` contains text from Wikipedia article summaries, licensed CC BY-SA 4.0. Its `sourceTitle` and `sourceURL` fields retain per-object attribution.
- `Catalog/Images/` contains Wikipedia images. Licenses vary by image; `Catalog/TargetImages.json` retains the corresponding article title and URL. The article's media/file page gives the individual license and required credit. The target detail view links to that source when it displays a photo.
- `Catalog/SkyThumbnails/` contains cutouts from the CDS HiPS survey `CDS/P/DSS2/color` (Digitized Sky Survey 2, color). `Catalog/SkyThumbnails.json` retains the per-target file mapping. The upstream project identifies these as DSS2 survey images and does not include an individual file license in the manifest; the survey attribution is shown in the target detail view.
- `Catalog/BuiltInCatalog.json` is mechanically translated from the curated catalog in Sky Bother's MIT-licensed source and keeps the source's designation, type, J2000 position, magnitude, size, and constellation fields.

The original upstream license notice is preserved in `LICENSE`; the original project is available at https://github.com/WrendorWC/sky-bother.
