# Breast-cancer-detection-using-Multi-UNet
This project uses a multi-task U-Net-based model to perform both segmentation and classification on breast ultrasound images. The shared encoder extracts common features, with a decoder for lesion mask segmentation and a global pooling + dense layer for classifying cases into normal, benign, or malignant.

The model is trained using binary cross-entropy + Dice loss for segmentation and sparse categorical cross-entropy for classification. It achieves over 90% accuracy in classification and a Dice score above 0.80 for segmentation, showing strong performance in both tasks.
