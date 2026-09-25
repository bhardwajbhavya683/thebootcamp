Earth Observation: Solar Energy Prospector & Roof-Top Analysis

An end-to-end Computer Vision and Natural Language Processing pipeline designed to analyze urban satellite imagery; segment usable rooftop surface area; account for shading obstructions; and generate estimated annual solar energy production summaries.

Project Overview
Evaluating urban solar potential requires analyzing spatial data at scale. Manual inspection of rooftops is slow; unreliable; and difficult to standardize across large geographic zones.

This program combines OpenCV; NumPy; Pandas; and NLTK to automate the assessment pipeline:

Rooftop Detection: Pre-processes satellite frames using Gaussian blurring; Canny edge detection; and contour identification to isolate building boundaries.

Shadow Analysis: Masks low-intensity regions in the HSV color space to calculate shadow coverage across identified structures.

Regional Irradiance Mapping: Merges synthetic geographic metadata with detected spatial metrics to estimate solar yield; power output; and annual monetary savings.

NLP Summary Generation: Synthesizes spatial output into human-readable text summaries; tokenizing and filtering key terms via NLTK.