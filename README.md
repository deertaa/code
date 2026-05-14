# Multi-omics Analysis Pipelines

This repository contains reproducible analysis workflows for RNA-seq, ChIP-seq, and CUT&Tag data.

## 📁 File Structure
- `rna_seq.txt`: Complete RNA-seq pipeline (QC → alignment → quantification → differential expression → visualization)
- `chip_seq.txt`: ChIP-seq/CUT&Tag pipeline (QC → alignment → filtering → peak calling → annotation)
- `cut_tag.txt`: CUT&Tag-specific optimized pipeline

## 🧰 Software & Versions
- FastQC v0.11.9
- TrimGalore v0.6.7
- Bowtie2 v2.4.5 / STAR v2.7.10a
- SAMtools v1.15
- MACS2 v2.2.7.1
- DESeq2 v1.38.3 (R)
- clusterProfiler v4.6.2 (R)

## 📄 Citation
If you use these pipelines in your research, please cite this repository.
