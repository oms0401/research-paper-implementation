# Replication of Lempel-Ziv Compression for DNA Sequences

## Overview
This repository replicates a research paper focusing on **Lempel-Ziv Compression** applied to DNA sequences. The project successfully implements the compression algorithm and demonstrates its functionality on DNA data, particularly analyzing regions of varying compressibility.

---

## Key Highlights
1. **Lempel-Ziv Compression**:
   - A practical algorithm for analyzing data compressibility.
   - Identifies patterns and reduces redundancy by encoding unique substrings.
   - Used here to study the complexity of DNA sequences.

2. **Sliding Window Analysis**:
   - A window of **250 nucleotides** is analyzed at a time.
   - The window is shifted by **50 nucleotides** to provide overlapping segments.
   - This approach ensures detailed, localized complexity analysis along the sequence.

3. **Results Visualization**:
   - The complexity metric for each window is plotted, highlighting compressible (low complexity) and random (high complexity) regions.

---

## Results
### Example Graph for Compression Results
**Title:** "Compression Complexity Across DNA Sequence Regions"
- Low peaks indicate easily compressible, repetitive regions.
- High peaks represent random, complex regions.

![Compression Results Graph](https://github.com/oms0401/research-paper-implementation/blob/97983d4d0351201fab82d62fc969cc9b802d2adc/lz_complexity_dna_full.png)

---

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/oms0401/research-paper-implementation.git
   ```
2. Run the script to analyze your DNA sequence.
3. Visualize the results with the provided graphing functionality.

---

## About Lempel-Ziv Compression
Lempel-Ziv is a lossless data compression algorithm that identifies and encodes unique patterns in sequences. It is widely used for analyzing compressibility and has practical applications in genomics, where it helps identify patterns in DNA regions efficiently.

---

