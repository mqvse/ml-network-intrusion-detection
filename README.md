# ML Network Intrusion Detection

Comparing machine learning models for detecting anomalous network traffic on a public intrusion detection dataset.

**Status:** In progress (started Oct 2026)

## Approach
- Dataset: CIC-IDS2017 or UNSW-NB15 (not included, see Data below)
- Models: Random Forest, Isolation Forest
- Metrics: precision, recall, F1, false positive rate

## Data
Download the dataset from the original publisher and place it in `data/`. It is excluded from this repo.

## Roadmap
- [ ] Dataset downloaded and loaded
- [ ] Exploratory analysis
- [ ] Baseline model
- [ ] Model comparison
- [ ] Results and limitations written up

## Setup
```
pip install -r requirements.txt
```
