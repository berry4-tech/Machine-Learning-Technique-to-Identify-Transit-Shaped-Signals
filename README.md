# 🪐 Machine Learning Technique to Identify Transit-Shaped Signals

> Detecting exoplanets by classifying transit-shaped signals in stellar light curve data using machine learning.

`Python` `Jupyter Notebook` `scikit-learn` `Astronomy`

---

## Table of Contents

- [Overview](#overview)
- [The Transit Method](#the-transit-method)
- [Approach](#approach)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Contributors](#contributors)

---

## Overview

Every exoplanet confirmed by NASA's Kepler and K2 missions was found the same way: by watching a star's brightness for years and looking for a tiny, periodic dip the signature of a planet passing in front of it. The catch is that space telescopes generate light curves for hundreds of thousands of stars, and most "dips" aren't planets at all they're eclipsing binaries, instrument noise, or stellar activity.

This project builds a machine learning classifier that separates genuine transit-shaped signals from these false positives, turning a problem that once required manual review by astronomers into something a trained model can screen at scale.

## The Transit Method

When a planet crosses in front of its star from our line of sight, the star's observed brightness drops by a small, measurable amount and then recovers — a signal that repeats on the planet's orbital period. The depth of the dip relates to the planet's size relative to its star, and the shape and duration relate to its orbital geometry. Distinguishing a real transit from noise or a false-positive signal (like a background eclipsing binary) is exactly the kind of pattern-classification problem machine learning is suited to.

## Approach

<!-- Fill in from the notebook — this is the core of the README, worth being specific:
- **Dataset**: which mission's data (Kepler KOI, K2, TESS?), how many light curves / samples, where it's sourced from
- **Preprocessing**: detrending, phase-folding, normalization, handling missing data
- **Features**: what was fed into the model (raw flux, extracted features like transit depth/duration, etc.)
- **Model(s)**: which algorithm(s) were tried and which performed best
- **Evaluation**: accuracy, precision/recall, F1, or AUC — and how the train/test split was done
- **Key finding**: the one sentence you'd tell a recruiter about what you learned or achieved
-->

## Tech Stack

`Python` `Jupyter Notebook` `scikit-learn`

<!-- Update with the actual libraries used (e.g. pandas, numpy, matplotlib, astropy, lightkurve) -->

## Getting Started

\`\`\`bash
git clone https://github.com/berry4-tech/Machine-Learning-Technique-to-Identify-Transit-Shaped-Signals.git
cd Machine-Learning-Technique-to-Identify-Transit-Shaped-Signals
pip install -r requirements.txt
jupyter notebook Exoplanets.ipynb
\`\`\`

<!-- Add a requirements.txt to the repo if one doesn't already exist, so this actually runs -->

## Contributors

- **Sriya KV**, Dayananda Sagar University
- **Pranav Bawgikar**, Dayananda Sagar University

---

⭐ If you find this useful, consider starring the repo!
