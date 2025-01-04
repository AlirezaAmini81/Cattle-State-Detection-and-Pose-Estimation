# Cattle State Detection and Pose Estimation

## Overview
This repository provides two main functionalities using a fine-tuned YOLOv8 model trained with PyTorch and a custom dataset:

1. **Cattle State Detection**
   - Detect and classify cattle states (e.g., feeding, standing) in real-time from images and videos.
   - Enables accurate tracking and count analysis, supporting improved livestock management.

2. **Pose Estimation**
   - Detect cattle body keypoints and measure distances between them.
   - Analyze motion for enhanced livestock monitoring and care.

## Project Structure
The repository includes the following files:

- **`cattle_state_detection.ipynb`**:
  - Implements the YOLOv8 model for detecting and classifying cattle states.
  - Processes images and videos to generate real-time insights.

- **`Pose_Estimation.ipynb`**:
  - Implements pose estimation by detecting key body points using YOLOv8.
  - Measures inter-point distances for motion analysis and visualization.


## Example Outputs
### Cattle State Detection
- Example output for state detection:
  ![Detection Example](path-to-detection-sample.gif)

### Pose Estimation
- Example output for pose estimation:
  ![Pose Estimation Example](path-to-pose-sample.gif)

## Demonstration Videos
Explore the functionalities through demonstration videos:

- [Cattle State Detection Video](videos/conf_index_output.mp4)
- [Pose Estimation Video](link-to-pose-estimation-video)

## Applications
- **Livestock Monitoring**: Enhance farm management by analyzing cattle states and motions.
- **Behavior Analysis**: Gain insights into activity patterns for improved welfare.
- **Motion Studies**: Leverage pose estimation for detailed motion tracking and health analysis.

## Future Enhancements
- Add multi-class activity recognition for cattle.
- Incorporate live streaming for real-time monitoring.
- Extend capabilities to detect and analyze other livestock species.

## Acknowledgments
Special thanks to the PyTorch and YOLOv8 communities for their invaluable resources and support.

---

Feel free to contribute or raise issues. For questions, contact the repository maintainer.

