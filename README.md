[🇨🇳 中文文档 | Chinese README](./README.zh-CN.md)

# Image Processing for Remote Sensing Course


## 📚 Content
1. **Basics of Remote Sensing:** Key concepts, Sentinel-2 data download, structure, and band visualization.
2. **Image Enhancement & Filtering:** Enhancement techniques, 2D convolution, and histogram analysis for interpretation.
3. **Edge Detection & Classification:** Edge detection methods, land-cover mapping, and classification techniques.
4. **Vegetation Indices & Hyperspectral Pixel Classification:** Use of vegetation indices and hyperspectral analysis.
5. **CNNs for Remote Sensing:** Deep learning (e.g., ResNet18) for image and hyperspectral classification.
6. **Deep Representation Learning:** Techniques for remote sensing image retrieval.
7. **Hyperspectral Image Processing:** Advanced analysis and experiments on hyperspectral data.

## 🧪 Lab & Homework

### HW01: Sentinel-2 Data & Visualization
- **Goal:** Download and visualize Sentinel-2 satellite data, understand data structure, and access specific bands programmatically.
- **Skills:** Data acquisition, band extraction, visualization, SAFE format analysis.

### HW02: Multi-label Scene Classification with ResNet18
- **Goal:** Use ResNet18 for supervised multi-label classification of remote sensing images, exploring various data augmentation techniques.
- **Skills:** Deep learning, PyTorch, data augmentation, multi-label evaluation.

### Labs 01-07: Thematic Experiments
- **Lab01:** Sentinel-2 basics, Copernicus data access, band visualization.
- **Lab02-03:** Image enhancement, filtering, and edge detection.
- **Lab04-05:** Land-cover classification, vegetation indices, pixel-based analysis.
- **Lab06:** Deep learning for remote sensing, CNNs.
- **Lab07:** Hyperspectral image processing and advanced classification.

<div align="center">
  <img alt="Demo" src="./src/clf.png" style="width:80%; height:80%" />
</div>

---

## 🛠️ Environment
To export the environment:
```conda env export > environment.yml```
