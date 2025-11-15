# eCAS-AI
AI Model for Fish Species Detection and Length Estimation 

# Abstract
Advances in deep learning have enabled real-time object detection in complex
environments. In this study, we present a mobile application based on YOLO designed for
real-time detection and estimation of the length of fish species in Lake Tanganyika. The
model was trained on a curated dataset of images capturing key commercial species under
varied environmental conditions: L. miodon, L. stappersii, and S. tanganicae. The evaluation
demonstrates high accuracy in species identification and precise length estimation, while
maintaining efficient performance suitable for mobile deployment. The model performed
strongly in all species, achieving high overall precision (0.968) and near perfect recall (0.998),
indicating that almost all fish were detected with very few false positives. Performance at
stricter thresholds (mAP@50–95 = 0.664) was lower, as expected for small, domain-specific
datasets, but still reflects acceptable localization accuracy. Species-specific results show that
L. miodon achieved perfect recall (1.0) and very high precision (0.98), making it the best-
performing species. L. stappersii was consistently detected with strong localization across
thresholds, confirming the robustness for larger fish. S. tanganicae had a very high recall
(0.99), but slightly lower precision (0.93) and the lowest localization accuracy (mAP@50–95
= 0.614), likely due to its smaller size, delicate body shape, or overlapping events in the data
set. The model length estimates showed a strong correlation with ground truth measurements
(R = 0.84) and low errors (RMSE = 0.54 cm), indicating reliable fish length predictions with
minimal deviations. These results highlight the potential of lightweight deep learning models
for resource-constrained applications and provide a framework for extending real-time object
detection to fisheries monitoring and other ecological domains.
# Keywords 
YOLO; Deep learning; Real-time object detection; Fish species identification;
Length estimation; Lake Tanganyika; Fisheries monitoring
# Dashboard
https://huggingface.co/spaces/mngosha/eCAS_Detector
