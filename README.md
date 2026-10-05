# satellite-change

Sentinel-2 imagery answering one local question over time: housing construction, tree canopy, rooftop solar, or flood extent.

## Phases

1. **Question and data:** pick the question and the area, get Sentinel-2 scenes, handle clouds.
2. **Baseline:** a simple index-based change map (e.g. vegetation index differences).
3. **Model:** labelled samples and a segmentation model.
4. **Showcase:** a map viewer and a write-up.

## Next questions

Bushfire burn scars and recovery, flood extent from Sentinel-1 radar, and an urban heat map from Landsat thermal bands (tracked as issues). Rooftop solar builds on [rooftop-segmenter](https://github.com/ahmedbaig/rooftop-segmenter).
