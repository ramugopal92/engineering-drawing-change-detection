# Engineering Drawing Change Detection

An AI-assisted drawing checker prototype for detecting changes between old and new engineering drawings using image alignment, ROI-based comparison, OCR extraction, and engineering token analysis.

## Overview

Engineering teams often spend significant time manually comparing drawing revisions to identify changes in views, notes, labels, and other document elements. This project presents a prototype system that automates part of that process using computer vision and OCR-based comparison techniques.

The system was developed as an experimental workflow to support engineering drawing review and change detection.

## Key Features

- Drawing alignment before comparison
- Global pixel-based difference analysis
- ROI-based localized comparison
- OCR extraction from notes block
- Token normalization and comparison
- Change classification
- Evaluation using precision, recall, accuracy, and confusion matrix

## Core Techniques

1. Image alignment
2. Pixel difference detection
3. ROI template matching
4. OCR text extraction
5. Engineering token comparison
6. Similarity scoring
7. PASS / CHANGE classification

## Workflow

1. Load old and new drawing files
2. Align drawings
3. Apply ROI templates
4. Measure ROI-wise pixel change
5. Run OCR on selected text regions
6. Normalize extracted text
7. Compare tokens and labels
8. Generate final engineering change summary
9. Evaluate performance using metrics

## Example Output Areas

- Section view change detection
- Front face / side view comparison
- Notes block OCR difference
- ROI-based classification report
- Confusion matrix and evaluation charts

## Evaluation Metrics

The prototype was evaluated using:

- Precision
- Recall
- Accuracy
- ROI classification accuracy
- Confusion matrix analysis
- Token detection performance

## Limitations

- OCR performance depends on drawing clarity
- Small symbol-level changes may require stronger detection logic
- ROI templates are currently predefined
- Performance may vary with scan quality and layout variation

## Future Improvements

- automatic dimension detection
- weld symbol detection
- dynamic ROI generation
- better engineering OCR pipeline
- change severity classification
- integration with CAD/PDM workflows

## Author

**Ramu Gopal**  
Founder, **The Tech Thinker**  
Senior Mechanical Design Engineer | CAD Automation | Engineering AI Workflows

## Related Articles

- The Tech Thinker article: [https://thetechthinker.com/engineering-drawing-change-detection/]
- Medium article: [https://medium.com/@TheTechThinker/engineering-drawing-change-detection-using-computer-vision-15b5fb9d8c6e]

## Disclaimer

This repository is a research and portfolio prototype intended for educational and technical demonstration purposes.
