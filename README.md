# Roman Numeral Annotation Error Detection

This project tackles an Automated Error Detection (AED) task involving handwritten Roman numerals.

## Problem Statement

The dataset consists of grayscale images of handwritten Roman numerals, each labeled with its corresponding Roman string (e.g., "I", "II", "III", etc.). The images are represented as 2D Python lists of varying sizes, and each sample is associated with a `label` column indicating its Roman numeral.

The goal is to identify annotation errors in the dataset — cases where the provided label does not match the actual content of the image.

## Dataset Format

Each row in the dataset includes:

- `image`: a 2D list representing the grayscale image.
- `label`: a string containing the Roman numeral annotation for the image.

## Objective

Automatically detect potentially mislabeled images using machine learning techniques to flag samples where the predicted class does not align with the provided label.
