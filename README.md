# 🛰️ FSAR-Cap: A Large-Scale Fine-Grained SAR Image Captioning Dataset

## 📖 Introduction
> 📢 :** Our paper has been officially accepted by **IEEE Geoscience and Remote Sensing Letters (GRSL)**! The dataset and code are now publicly available.

Synthetic Aperture Radar (SAR) image captioning enables scene-level semantic understanding and plays a crucial role in applications such as military intelligence, disaster monitoring, and urban planning. However, its development is severely constrained by the scarcity of high-quality, large-scale datasets.

To bridge this gap, we proudly present **FSAR-Cap**—a large-scale, fine-grained SAR image captioning dataset comprising **14,480 images** and **72,400 image-text pairs**. Built upon the FAIR-CSAR detection dataset, FSAR-Cap is constructed through a rigorous **two-stage annotation strategy** that integrates:
1. **Hierarchical template-based representation**
2. **Manual verification and expert supplementation**
3. **Prompt standardization**

Compared to existing resources, FSAR-Cap offers richer fine-grained annotations, broader category coverage, and superior annotation quality. Benchmarking across multiple encoder-decoder architectures validates the effectiveness of our dataset, establishing a solid foundation for future research in SAR image captioning and intelligent image interpretation.

---

## 📊 Dataset Analysis and Visualization
To demonstrate the richness and diversity of FSAR-Cap, we conducted a comprehensive statistical analysis of the annotated data:

- **(a) Caption Length Distribution**: A frequency histogram of the caption length per image, reflecting the descriptive depth of the annotations.
- **(b) Core Vocabulary Word Cloud**: A word cloud of the primary annotation words in the dataset, highlighting the diverse semantic vocabulary covered.
- **(c) Data Distribution Radar Plot**: A radar plot illustrating the distribution of main categories and attributes within the FSAR-Cap dataset.

![Dataset Analysis](https://github.com/user-attachments/assets/11ecdb06-f505-4d75-a18e-f60682167b51)
*Figure 1: Statistical analysis of the FSAR-Cap dataset (including caption length frequency, core annotation word cloud, and category distribution radar plot).*

---

## 📥 Download and Access
You can download and use our dataset via the Science Data Bank:

🔗 **[📦 Click here to download the FSAR-Cap dataset](https://www.scidb.cn/en/detail?dataSetId=e4c17cc137e74878b46c03d8650ffa78&version=V1&code=o00118)**

---

## 💻 Baseline Models and Code References
To facilitate rapid development and benchmarking within the community, we highly recommend referring to the following outstanding open-source models in the field of remote sensing and SAR image captioning. Their official implementations serve as excellent starting points for building customized models for FSAR-Cap:

### 1. MLAT (Multilayer Aggregated Transformer)
- **Description**: An advanced remote sensing image captioning model that effectively addresses multi-scale problems, significantly improving sentence generation accuracy and diversity.
- **Paper**: *Remote-Sensing Image Captioning Based on Multilayer Aggregated Transformer*
- **Source Code**: [Chen-Yang-Liu/MLAT](https://github.com/Chen-Yang-Liu/MLAT)

### 2. HCNet (Hierarchical Feature Aggregation and Cross-Modal Feature Alignment)
- **Description**: A network specifically designed for remote sensing image captioning, which efficiently fuses visual and textual representations through hierarchical feature aggregation and cross-modal feature alignment.
- **Paper**: *HCNet: Hierarchical Feature Aggregation and Cross-Modal Feature Alignment for Remote Sensing Image Captioning* (IEEE TGRS, 2024)
- **Source Code**: [CVer-Yang/HCNet](https://github.com/CVer-Yang/HCNet)

---

## 🙏 Acknowledgements
We extend our sincere gratitude to:
- The creators of the **FAIR-CSAR** detection dataset, for providing a solid foundation for this work.
- The author teams of **MLAT** and **HCNet**, for their outstanding open-source contributions, which provided immense inspiration and convenience for our benchmarking.
- All domain experts and students who participated in the data annotation, manual verification, and supplementation processes.

---

## 📝 Citation
If you use the FSAR-Cap dataset in your research, please consider citing our work:

```bibtex
@article{zhang2026fsar,
  title={FSAR-Cap: A fine-grained two-stage annotated dataset for SAR image captioning},
  author={Zhang, Jinqi and Cong, Linhao and Zhuang, Di and Zhang, Lamei and Zou, Bin},
  journal={IEEE Geoscience and Remote Sensing Letters},
  year={2026},
  publisher={IEEE}
}
