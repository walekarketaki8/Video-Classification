## Video Classification
**Aim** : Classify chunks of videos into respective classes.<br>

This project is implementation of the video classification method explained in [this](https://dzone.com/articles/video-analysis-to-detect-suspicious-activity-based) article.

1. Dataset Details:<br>
Collected dataset of videos. Created chunks of 15 frames(customizable) from videos. Divide those into train chunks and test chunks.

2. Video classification architecture(explained in the article):
![Network Architecture](video_classification_Architecture.png)<br>

3. Implementation Details:<br>
   1. Feature Extraction: We are using transfer learning technique to extract the features. We are extracting the result of the last pooling layer, which is a vector of 2,048 values (high-level feature map).
