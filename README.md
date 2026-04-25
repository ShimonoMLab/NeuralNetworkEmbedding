# NeuralNetworkEmbedding

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.xxxxxxxx.svg)](https://doi.org/10.5281/zenodo.xxxxxxxx)

## Neural Network Embedding of Functional Microconnectome

This repository provides code for reproducing and extending the analyses associated with:

**Shirakami, A., Hase, T., Yamaguchi, Y., & Shimono, M. (2025). _Neural network embedding of functional microconnectome_. Network Neuroscience, 9(1), 159–180. https://doi.org/10.1162/netn_a_00424**

## Overview

Neural Network Embedding (NNE) is a framework for compressing functional microconnectome matrices using a deep autoencoder and interpreting the compressed features through network metrics.

The method is designed to extract lower-dimensional representations of neuronal functional connectivity and then evaluate how these learned features relate to conventional and newly introduced network measures, including indirect-adjacent degree and neighbor hub ratio.

## Key Concepts

- Neural network embedding
- Functional microconnectome
- Deep autoencoder
- Network compression
- Network metrics
- Centrality
- Indirect-adjacent degree
- Neighbor hub ratio
- Microconnectome topology
- Neural population connectivity
- Computational neuroscience
- Network neuroscience

## Main Scripts

`deep_autoencoder.py` trains deep autoencoder models.

Usage:

```bash
python deep_autoencoder.py [depth of layers] [number of middle layer nodes]
```

Example:

```bash
python deep_autoencoder.py 3 5
```

`Network_analysis.py` calculates the new network metrics introduced in the paper as well as representative network metrics.

Usage:

```bash
python Network_analysis.py [directory for dataset]
```

Example:

```bash
python Network_analysis.py 180731001
```

## Citation

If you use this repository in any way that contributes to a publication, preprint, thesis, presentation, software tool, benchmark comparison, dataset analysis, or derivative codebase, please cite the peer-reviewed article below.

Please cite the paper if you:

- use the original code
- modify or extend the code
- reuse part of the code in another project
- use the dataset structure or preprocessing procedure
- use the autoencoder-based network embedding framework
- use the network-metric analysis procedure
- build upon the idea of interpreting compressed microconnectome features using network metrics
- use this work as a reference for neural network embedding, functional microconnectome analysis, or network neuroscience

### Peer-reviewed article

For the scientific method, results, and interpretation, please cite:

**Shirakami, A., Hase, T., Yamaguchi, Y., & Shimono, M. (2025). _Neural network embedding of functional microconnectome_. Network Neuroscience, 9(1), 159–180. https://doi.org/10.1162/netn_a_00424**

### Archived software release

The GitHub repository has been archived on Zenodo:

**Shimono, M. (2026). _NeuralNetworkEmbedding: Code for neural network embedding of functional microconnectome_. Zenodo. https://doi.org/10.5281/zenodo.19763280

Please cite the peer-reviewed article for the scientific method, results, and interpretation, and cite the Zenodo DOI when referring specifically to this archived software release.

## Suggested Citation Sentence

This repository implements neural network embedding code for compressing functional microconnectome matrices with a deep autoencoder and interpreting the learned features using network metrics.

## Contact

For questions about the code, data format, or reproduction procedure, please contact the corresponding author listed in the associated paper.
