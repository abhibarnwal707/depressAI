# Audio Features

This directory contains the methodology and implementation for extracting and analyzing audio features for depression prediction.

## Methodology

1. **Baseline Statistics**
    - Extracted features from audio clips labeled as not depression.
    - Calculated mean and standard deviation for each feature.
    - Established baseline statistics for each feature.

2. **New Audio Clip Analysis**
    - Extract features from new audio clips.
    - Compare extracted features with baseline statistics.
    - Identify deviations indicating abnormalities.

3. **Symptom Identification**
    - Deviations in feature values highlight abnormal symptoms.
    - Provides additional information about the client's personality.

## Files

- `audio_features.ipynb`: Notebook for extracting audio features.

## Impact

Helps in identifying specific depressive symptoms through audio analysis, complementing textual analysis for a holistic view of the client's mental state.
