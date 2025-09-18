## wordSeg

A lightweight Chinese word segmentation algorithm based on PMI (Pointwise Mutual Information) and information entropy.

Main Script

newWordsFind.py

## Overview

This project implements a custom Chinese word segmentation algorithm without relying on any existing segmentation dictionaries.
The approach analyzes daily news corpora and automatically identifies new words.

## Key Features

PMI + Left/Right Entropy: Utilized to evaluate word boundaries and cohesion.

Dictionary-free: No pre-built segmentation lexicons are required.

Incremental vocabulary building:

Extracts candidate words from the corpus that meet statistical thresholds.

Compares them against an existing dictionary.

Adds unseen words to the dictionary automatically.

Unified handling of “new words” and “out-of-vocabulary (OOV) words”: Both are treated the same (not differentiated).
