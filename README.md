# SDNET2018

## Overview

SDNET2018 is a task-specific package derived from SDNET2018.

- Task: classification
- Images: 56091
- Annotations: 56091
- Classes: 2 (cracked, non-cracked)
- Annotation format: image-level labels in class folders

This package consolidates the three structural surface subsets of SDNET2018—bridge decks (`bridge_deck` / `D`: 13,620 patches; 2,025 `cracked`, 11,595 `non-cracked`), pavements (`pavement` / `P`: 24,333 patches; 2,608 `cracked`, 21,725 `non-cracked`), and walls (`wall` / `W`: 18,138 patches; 3,851 `cracked`, 14,287 `non-cracked`). The 256x256 RGB patches (~60 mm x 60 mm each, crack widths 0.06–25 mm) were segmented from 230 full-resolution (4068x3456) images (54 bridge decks, 104 pavements, 72 walls) captured with a 16 MP Nikon digital RGB camera at a 500 mm working distance at Utah State University, Logan, Utah, USA.

Note: Table 1 of the *Data in Brief* article reports 21,726 uncracked pavement patches (56,092 total), whereas the released archive contains 21,725 uncracked pavement patches (56,091 total). Across the 56,091 files, there are 56,078 unique SHA-256 hashes (13 byte-identical `*_2.jpg` duplicate pairs in the `bridge_deck` subset).

## Source Dataset

- Name: SDNET2018
- Dataset DOI: 10.15142/T3TD19
- Dataset URL: https://digitalcommons.usu.edu/all_datasets/48/
- Article DOI: 10.1016/j.dib.2018.11.015
- Article title: SDNET2018: An annotated image dataset for non-contact concrete crack detection using deep convolutional neural networks

## Authors

- Sattar Dorafshan (Department of Civil and Environmental Engineering, Utah State University)
- Robert J. Thomas (Department of Civil and Environmental Engineering, Clarkson University)
- Marc Maguire (Department of Civil and Environmental Engineering, Utah State University)

## License

The source dataset is published under CC BY 4.0.

## Repository Links

- Package repo: https://github.com/large-road-damage-datalake/sdnet2018-classification
- Source dataset: https://digitalcommons.usu.edu/all_datasets/48/

## Package Contents

- METADATA.json
- stats/
- visualizations/
- ABSTRACT.md
- SUMMARY.md
- CITATION.bib
- CITATION.md
- DOWNLOAD.md
- LICENSE.md
