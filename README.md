# Solar Rooftop Analyzer

## Overview
An AI-powered tool to analyze rooftop solar potential using real satellite imagery.

## Features
- Detects rooftop area using Vision AI.
- Estimates solar installation potential.
- Calculates cost, ROI, payback period.
- Provides visual overlays and structured outputs.

## Installation
```bash
pip install -r requirements.txt
```

## Usage
```bash
streamlit run streamlit_app.py
```

## Modules
- `streamlit_app.py` - Main Streamlit app
- `rooftop_detector.py` - Handles roof detection
- `solar_estimator.py` - Estimates energy output
- `finance.py` - Computes financial metrics
- `utils.py` - Utility functions
