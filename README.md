#DEGOE: Differential Expression -> Gene Ontology Enrichment
v1.0 (2025)

DEGOE performs Gene Ontology enrichment analyses using differential expression
results from DESeq2 directly, without the need to manually create scores files.

This version works on Linux and Windows, but it requires external python modules
Future versions will include these modules as part of the package.

Tests:
  - Mann–Whitney U (MWU) enrichment (Non-thresholded test)
  - Fisher's exact test enrichment (Thresholded input)
  - (I may add GSEA, ORA, or other methods in the future)
