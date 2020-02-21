# rnaseq-snf2

This RNA-Seq workflow uses the R package [`DESeq2`](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-014-0550-8) to perform genel-level RNA-Seq analysis, starting from a counts matrix. This workflow does not include the upstream pre-processing steps (fastQ libraries QC, reads alignment, transcript quantification, etc.).

The original dataset is from a systematic study comparing various RNA-Seq tools, using RNA-Seq libraries prepared from yeast _snf2_ knock-out versus wildtype ([Gierlinski et al. 2015](https://academic.oup.com/bioinformatics/article/31/22/3625/240923) and [Schurch et al. 2016](https://rnajournal.cshlp.org/content/22/6/839.full?sid=bdf6f07f-7f72-413b-b0c5-e32579faecac)).

The dataset used in this tutorial is a pre-processed subset of the original study. The file is called `featCounts_genes.txt` and can be downloaded from the [RNA-seq Analysis Workshop Course Materials at Weill Cornell Medical College](https://chagall.med.cornell.edu/RNASEQcourse/). For convenience, the file is also available in the `/data` directory of this repo.