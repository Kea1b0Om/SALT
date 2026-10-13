# SALT: Symmetry-Augmented Level-Set Training for Radar Echo Extrapolation

Official repository for the paper

> **Learning Not to Average: Symmetry-Augmented Level-Set Training for Radar Echo Extrapolation**

SALT is a backbone-agnostic training framework for radar echo extrapolation. Instead of regressing reflectivity pointwise, it predicts nested exceedance probabilities at all warning thresholds (NLS Head) and reads warning regions from them without tuned parameters, and it tags each rotated or flipped training sample with its transform (OTSA) so that symmetry augmentation does not average the forecast over orientations.

## Status

The paper is currently under review. **Code, configurations and pretrained weights will be released here upon acceptance.**

## Citation

A BibTeX entry will be added once the paper is published.
