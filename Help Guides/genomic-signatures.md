Genomic signatures, sometimes expressed as a weighted sum of genes, are an algebra over genes, such as "ESR1 + 0.5\*ERBB2 - GRB7". Once a signature is entered, the value for each gene name for each sample are substituted and the algebraic expression is evaluated.



### To make a signature {#to-make-a-signature}

1. Open the Add column menu
2. Enter '=' and then your signature into the gene entry box
3. Select 'gene expression' as the dataset
4. Click 'Done'

### Important notes {#important-notes}

* There must be a space on both sides of the "+" and "-".
* If we can not find a gene that is part of the signature, the 'missing gene will be included as a zero in the expression calculation and the label will list the genes as missing.
* Genomic signatures currently only work for HUGO gene names and gene expression datasets that have only one value for a gene \(ie. it does not work for exon expression datasets or where there are multiple probes that map to one gene\).

# Example: TFAC30 Gene Signature {#example-tfac30-gene-signature}

Hess et.al. identified 30 genes whose gene expression profile is predictive of complete pathologic response to chemotherapy treatment in breast cancer.

### Gene signature {#gene-signature}

=E2F3 + MELK + RRM2 + BTG3 - CTNND2 - GAMT - METRN - ERBB4 - ZNF552 - CA12 - KDM4B - NKAIN1 - SCUBE2 - KIAA1467 - MAPT - FLJ10916 - BECN1 - RAMP1 - GFRA1 - IGFBP4 - FGFR1OP - MDM2 - KIF3A - AMFR - MED13L - BBS4

Here we can see that the predicted chemo response signature is high in the basal subtype and low in luminal subtype. Additionally, the signature is high for ER negative samples and low for ER positive samples.

[https://xenabrowser.net/?bookmark=2401ccb792e256d7397008b24af20565](https://xenabrowser.net/?bookmark=2401ccb792e256d7397008b24af20565)

### ![](/assets/genomicSignatures.png) {#citation}

### Citation {#citation}

[Hess KR, et. al. Pharmacogenomic predictor of sensitivity to preoperative chemotherapy with paclitaxel and fluorouracil, doxorubicin, and cyclophosphamide in breast cancer. J Clin Oncol. 2006 Sep 10;24\(26\):4236-44. Epub 2006 Aug 8.](http://www.ncbi.nlm.nih.gov/pubmed/16896004)

