# A Dataset of Images of Floating Rubbish on the Surface of the Water

An object detection dataset for floating rubbish on the water surface.

- **Version:** v1.0  
- **Release date:** 2025-06-21  
- **License:** CC BY 4.0  
- **Privacy / sensitive content:** None  
- **DOI:** https://doi.org/10.57967/hf/7674  
- **Hugging Face (official hosting):** https://huggingface.co/datasets/gonzz2026/A-dataset-of-images-of-floating-rubbish-on-the-surface-of-the-water  

> This GitHub repository provides documentation and citation information.  
> Please download the dataset from Hugging Face via the DOI link above.

---

## 1. Overview

- **Task:** Object detection
- **Image resolution:** 2048 × 2048  
- **Split (Train / Val / Test):** 1901 / 238 / 238  
- **Number of classes:** 11  

---

## 2. Class List (YOLO `class_id` starts from 0)

| class_id | class_name |
|---:|---|
| 0 | Glass |
| 1 | Styrofoam_Piece |
| 2 | Plastic_Buoy_China |
| 3 | Metal |
| 4 | Net |
| 5 | Rope |
| 6 | Plastic_Buoy |
| 7 | PET_Bottle |
| 8 | Styrofoam_Box |
| 9 | Plastic_ETC |
| 10 | Styrofoam_Buoy |

---

## 3. Annotation Format

This dataset provides bounding-box annotations in:
- **YOLO TXT**
- **XML** (Pascal VOC style)

## 4. Download

```bash
pip install -U huggingface_hub

huggingface-cli download \
  gonzz2026/A-dataset-of-images-of-floating-rubbish-on-the-surface-of-the-water \
  --repo-type dataset \
  --local-dir ./data

unzip "A-dataset-of-images-of-floating-rubbish-on-the-surface-of-the-water.zip" -d ./data
```

## License
This dataset is released under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

- Dataset: *A-dataset-of-images-of-floating-rubbish-on-the-surface-of-the-water*
- Author: gonzz2026
- URL: https://huggingface.co/datasets/gonzz2026/A-dataset-of-images-of-floating-rubbish-on-the-surface-of-the-water
- License: CC BY 4.0

## Citation
```bibtex
@misc{gonzz2026_floating_rubbish_2026,
  title        = {A Dataset of Images of Floating Rubbish on the Surface of the Water},
  author       = {gonzz2026},
  year         = {2026},
  howpublished = {Hugging Face Hub (dataset)},
  note         = {Version v1.0. License: CC BY 4.0},
  doi          = {10.57967/hf/7674},
  url          = {https://doi.org/10.57967/hf/7674}
}
```

For questions or issues, please open an issue in this GitHub repository.
