# ECG Arrhythmia Classifier

Deep learning model that identifies the heart rhythm from a 12-lead ECG image.

## Classes
- SR: Sinus rhythm
- AF: Atrial fibrillation
- ST: Sinus tachycardia
- SB: Sinus bradycardia

## Data
[PTB-XL](https://physionet.org/content/ptb-xl/): real 12-lead ECG signals, which I converted into ECG images.
The dataset is not included in this repository.

## Model
- ResNet18 fine-tuned with PyTorch
- Built in Google Colab

## Results
- Test accuracy: ~89–91%
- AF recall: 91%
- AF precision: 91%

## Limitations
- Trained on images generated from signals, not photos of real ECG printouts
- Educational project, not for clinical use

## How to run
1. Open `ECG_Rhythm_Classifier_NEW` in Google Colab
2. Download PTB-XL using the link above
3. Run all cells

## Author
Mai Siton
