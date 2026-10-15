# AI-Powered Medical Image Analysis — Educational Demo

A beginner-friendly Python project demonstrating grayscale image preparation, normalization, feature extraction, classification, evaluation, and visualization.

## Medical safety note
The default project creates **synthetic grayscale patterns**, not real X-rays, MRI scans, CT scans, or patient data. Labels are **Pattern A** and **Pattern B**, not diseases. This model is not clinically validated and must never be used to diagnose, rule out, or guide treatment for a medical condition.

## Workflow
1. Generate synthetic grayscale patterns.
2. Normalize pixels to 0–1.
3. Extract HOG (Histogram of Oriented Gradients) features.
4. Train a baseline Logistic Regression classifier.
5. Evaluate using accuracy, classification report, and confusion matrix.
6. Save a model, reports, sample images, and plots.

## Folder structure
```text
AI-Powered-Medical-Image-Analysis/
├── data/synthetic_samples/
├── src/medical_image_demo.py
├── models/
├── outputs/
├── images/
├── docs/PROJECT_NOTES.md
├── main.py
├── requirements.txt
└── README.md
```

## Run on Windows
```powershell
py -m venv .venv
.venv\Scripts\activate
python -m pip install --upgrade pip
pip install -r requirements.txt
python main.py
```

## Run on macOS/Linux
```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
python main.py
```

## Expected outputs
- `data/synthetic_samples/` — generated toy images
- `images/sample_preprocessed_images.png`
- `images/confusion_matrix.png`
- `images/class_distribution.png`
- `outputs/evaluation_report.json`
- `outputs/classification_report.txt`
- `outputs/confusion_matrix.csv`
- `models/synthetic_pattern_classifier.pkl`

Scores apply only to the synthetic toy dataset and are not medical-image performance claims.
## Future learning
For an advanced educational version, explore reputable public datasets and follow their license, privacy rules, and intended use. Do not publish patient-identifiable images. Using real clinical data requires careful validation and expert oversight; it does not automatically make a model a diagnostic tool.
<img width="1500" height="600" alt="sample_preprocessed_images" src="https://github.com/user-attachments/assets/4343722e-fcf5-4cb2-b9d3-504c898e58b1" />
<img width="825" height="675" alt="confusion_matrix" src="https://github.com/user-attachments/assets/eefba86d-3012-4333-aae4-83ce44b8ac23" />
<img width="1050" height="600" alt="class_distribution" src="https://github.com/user-attachments/assets/3318614f-11c6-4539-8c66-b6f311f2f23d" />


Github:https://github.com/yaseenkhaleel16-tech/AI-Powered-Medical-Image-Analysis
Linkedin: https://www.linkedin.com/in/yaseen-khaleel-6a535a432/
