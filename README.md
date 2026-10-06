# PERSIST-On analysis

Analysis code for Tak and Hsu et al., "Stable activation of endogenous genes by harnessing endogenous
transcription factors" (Nature Communications)

`PERSIST_On_screen_analysis.ipynb` covers the pooled screening analysis: assigning amplicon reads
to designed motif variants, computing enrichment scores from the cell-sorting and ChIP readouts at
the *IL2RA*, *HER2* and *EPCAM* promoters, the sorting-versus-ChIP correlations, and the *in
cellula* position weight matrices rendered as sequence logos.

Run under Python 3.7 with logomaker, pandas, numpy, scipy, matplotlib, seaborn and plotnine.

The notebook reads per-experiment CSV tables that are not included here. The underlying reads are
in the NCBI Sequence Read Archive under BioProject PRJNA881771, and the per-variant read counts
and enrichment scores are in the paper's Source Data file.
