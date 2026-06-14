# Root Segmentation in SubArctic Grasslands: RS_SAG

[![Python](https://img.shields.io/badge/Python-3.8+-blue)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.9+-red)](https://pytorch.org)
[![License](https://img.shields.io/badge/License-GPLv3-blue)](LICENSE)

Code for automatic root segmentation of images from BARTZ system, from subarctic grasslands, and further calculations of total root length (TRL) and total root area (TRA). 
The repository also includes the Label tool, which was used for labeling the training dataset.

![Segm example](triptych.png)
Segmentation example.

| File | Description |
|------|-------------|
| `RS_SAG_data_generation_loop.ipynb` | Execution of the whole pipeline, from loading to segmenting, to calculating TLR and TRA, to saving the results |
| `RS_SAG_results_summary-Copy1.ipynb` | Summary of different methods tried for calculations, including depth profile and test of the model |
| `Label tool/segment_BARTZ_images_tool.py` | PyQt5 GUI for manual root annotation |

### Citation

```bibtex
@misc{Baykalov2024scripts,
  Author = {Pavel Baykalov},
  Title = {Root Segmentation in SubArctic Grasslands: RS_SAG},
  Year = {2024},
  Publisher = {GitHub},
  Journal = {GitHub repository},
  Howpublished = {\url{https://https://github.com/dIcarusb/Root-segmentation_subArctic-Grassland-RS_SAG-/tree/main}}
}
```
