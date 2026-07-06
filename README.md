# CATS: Camera Augmentation Training Strategy for Uncalibrated Stereo Matching in MIS

Official repository for the IPCAI 2026 paper:

> **Camera Augmentation: Enabling Uncalibrated Stereo Matching of Minimally-Invasive Surgery Images by Training from the Wealth of Public Synthetic Image Datasets**

## 🌐 Project Page

https://rasoul-sharifian.github.io/CATS/

## 📄 Paper

https://encov.ip.uca.fr/publications/pubfiles/2026_Sharifian_etal_IJCARS_stereo.pdf

## 📦 Pretrained Models

https://drive.google.com/drive/folders/1YyuhrBO1VO9-nXw5LveIqXgPI2wUnEzo

## Abstract

Accurate stereo matching in minimally invasive surgery (MIS) typically assumes well-calibrated stereo cameras. In practice, however, calibration may be unavailable or inaccurate due to manufacturing tolerances, maintenance, or camera replacement. We propose **Camera Augmentation Training Strategy (CATS)**, a geometry-aware training approach that enables existing stereo matching networks to remain effective even when camera calibration is unavailable. CATS models realistic variations in stereo laparoscope geometry through camera-based augmentations, allowing state-of-the-art stereo methods to generalize to uncalibrated surgical images without requiring camera poses or depth during training.

## How to Use

CATS is a training strategy built on top of existing stereo matching networks.

To use the pretrained CATS models:

1. Clone the original repository of the desired stereo matching method (e.g., RAFT-Stereo or IGEV++).
2. Download the corresponding CATS pretrained weights from the link above.
3. Replace the original pretrained weights with the CATS weights.
4. Follow the inference instructions provided in the original repository.

The original repositories are:

- **RAFT-Stereo:** https://github.com/princeton-vl/RAFT-Stereo
- **IGEV++:** https://github.com/gangweiX/IGEV-plusplus

## Citation

If you find this work useful, please cite:

```bibtex
      @article{sharifian2026camera,
        title={Camera augmentation: enabling uncalibrated stereo matching of minimally invasive surgery images by training from the wealth of public synthetic image datasets},
        author={Sharifian, Rasoul and Rabbani, Navid and Zhang, Yongcong and Bartoli, Adrien},
        journal={International Journal of Computer Assisted Radiology and Surgery},
        pages={to apear},
        year={2026},
        publisher={Springer}
      }
```

## License

Please refer to the repository license for the terms of use.