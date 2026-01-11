# Model 2 Results

Three-stream CNN with pose estimation (Body + Context + Pose)

## Performance:

- **Test mAP:** 0.1669 (+2.83% over baseline)
- **Training Epochs:** 10
- **Parameters:** ~23.2M

## Files:

- `training_curves.png` - Training/validation loss and mAP curves
- `per_emotion_comparison.png` - Per-emotion Average Precision scores

## Top 5 Emotions:

1. Engagement: 0.6109 AP (+0.33%)
2. Confidence: 0.4123 AP (+3.02%)
3. Anticipation: 0.3912 AP (+0.95%)
4. Happiness: 0.3401 AP (+2.69%)
5. Esteem: 0.3287 AP (+2.37%)

## Innovation:

Explicit body pose modeling via MediaPipe (17 keypoints) provides geometric information complementary to appearance features.
