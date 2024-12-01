# Quantum 3D Visual Grounding: A Step Towards Quantum-inspired AI-Visualization

This repository documents the Quantum3DVG framework, a novel integration of quantum computing and machine learning for 3D visual grounding tasks. By leveraging quantum neural networks (QNNs), this framework enhances the understanding of 3D environments through text-guided object detection and localization in RGB images.

---

## Overview

The Quantum3DVG model addresses limitations of classical 3D grounding methods by introducing quantum-inspired components, including:

- **Quantum Convolutional Neural Networks (QCNNs)**
- **Quantum Vision and Depth Encoders (QVDE, QD)**
- **Quantum Text-Guided Visual and Depth Adapters (QTGVA, QTGDA)**
- **Quantum Multi-Layer Perceptrons (QMLP)**

These components utilize quantum principles such as superposition and entanglement to enhance pattern recognition, even under high levels of occlusion and truncation.

---

## Key Features

1. **Advanced Quantum Framework**:
   - Integrates quantum gates and circuits for high-dimensional data processing.
   - Enables holistic representation of visual and depth features.

2. **Text-Guided Quantum Adaptation**:
   - Adapts visual and depth information based on textual descriptions using quantum text-guided adapters.

3. **Improved Efficiency**:
   - Reduces training time and computational costs compared to classical methods.

4. **Robust Object Detection**:
   - Handles occlusion and truncation effectively, ensuring accurate 3D bounding boxes.

---

## Methodology

The Quantum3DVG pipeline consists of:

1. **Quantum Encoding**:
   - Converts image patches and depth information into quantum states.

2. **Quantum Processing**:
   - Applies quantum attention mechanisms, deformable attention, and feed-forward networks.

3. **Quantum Grounding**:
   - Localizes objects in 3D scenes by combining visual and textual cues through QMLP.

---

## Dataset and Experiments

### Datasets:
- Utilized hybrid datasets from indoor and outdoor environments.
- Example datasets include **Quantum3DVG**, **ScanRefer**, and **REVERIE**.

### Results:
Quantum3DVG demonstrated superior accuracy in object detection and localization compared to classical models like Mono3DVG-TR.

| Metric                  | Quantum3DVG | Classical3DVG |
|-------------------------|-------------|---------------|
| Near Distance (ACC @0.25) | **68.23%**  | 64.74%        |
| Medium Distance (ACC @0.25)| **77.12%**  | 75.44%        |
| Far Distance (ACC @0.25)   | **46.87%**  | 45.07%        |

---

## Future Directions

- **Hardware Optimization**: Adaptation to near-term quantum devices.
- **Broader Applications**: Expanding use cases to autonomous driving and robotics.
- **Real-time Processing**: Development of low-latency systems for real-world deployment.

---

## Acknowledgments

This research was supported by the **University of Missouri-Columbia** and collaborators. Special thanks to dataset providers and tool developers for their contributions.

---
