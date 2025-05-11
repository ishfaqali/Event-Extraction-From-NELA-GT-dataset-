# Event-Extraction-From-NELA-GT-dataset-
# Crisis Misinformation Analysis Framework

[![CI Status](https://github.com/ishfaqali/crisis-misinformation-analysis/actions/workflows/ci.yml/badge.svg)](https://github.com/yourusername/crisis-misinformation-analysis/actions)

A pipeline for identifying high-impact socio-political events from news datasets using:
- NELA-GT datasets (2015-2023)
- Temporal spike detection
- NLP content analysis
- Geospatial mapping

## Features
- Automated event detection from news spikes
- Multi-modal verification (text, images, social)
- Policy impact scoring system

## Quick Start
```bash
git clone https://github.com/yourusername/crisis-misinformation-analysis.git
cd crisis-misinformation-analysis
pip install -r scripts/requirements.txt

# Run full pipeline
python scripts/process_events.py --years 2015-2023 --output outputs/events.csv
