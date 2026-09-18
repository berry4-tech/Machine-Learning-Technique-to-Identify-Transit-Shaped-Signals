# 🪐 Machine Learning Technique to Identify Transit-Shaped Signals

> Detecting exoplanets by classifying transit-shaped signals in stellar light curve data using machine learning.

`Python` `Jupyter Notebook` `scikit-learn` `Astronomy`

---

## Table of Contents

- [Overview](#overview)
- [The Transit Method](#the-transit-method)
- [Tech Stack](#tech-stack)
- [Contributors](#contributors)

---

## Overview

Every exoplanet confirmed by NASA's Kepler and K2 missions was found the same way: by watching a star's brightness for years and looking for a tiny, periodic dip the signature of a planet passing in front of it. The catch is that space telescopes generate light curves for hundreds of thousands of stars, and most "dips" aren't planets at all they're eclipsing binaries, instrument noise, or stellar activity.

This project builds a machine learning classifier that separates genuine transit-shaped signals from these false positives, turning a problem that once required manual review by astronomers into something a trained model can screen at scale.

## The Transit Method

When a planet crosses in front of its star from our line of sight, the star's observed brightness drops by a small, measurable amount and then recovers — a signal that repeats on the planet's orbital period. The depth of the dip relates to the planet's size relative to its star, and the shape and duration relate to its orbital geometry. Distinguishing a real transit from noise or a false-positive signal (like a background eclipsing binary) is exactly the kind of pattern-classification problem machine learning is suited to.

## Tech Stack

`Python` `Jupyter Notebook` `scikit-learn`

## Contributors

- **Sriya KV**, Dayananda Sagar University
- **Pranav Bawgikar**, Dayananda Sagar University

---

⭐ If you find this useful, consider starring the repo!
