---
title: "OSingle-cell transcriptional profiling reveals cellular diversity and intercommunication in the mouse heart"
date: 2021-07-29T06:09-05:00
#November 23, 2019 at 22:09 EST
excerpt: Kkelly et al., 2018, Cell Reports 22, 600–610
January 16, 2018 ª 2017 The Author(s).
https://doi.org/10.1016/j.celrep.2017.12.072
categories:
  - Daily Paper
---
## Introduction
Essentially they are using single-cell RNA sequencing on mice to understand gene expression of all cell types in the heart except for cardiomyocytes. In scRNA-seq, you isolate RNA from a single cell, use reverse transcription to convert it into complementary DNA, and then amplify that DNA either through the use of PCR or in vitro transcription. With that amplified DNA, you can then generate a sequencing library and sequence it. This method is advantageous because it can often reveal rare cell types in a population. However, one caveat is that it is impossible to gather 100% information on all RNA in each of the cells due to the very small amount present. Overall, though, these experiments allow us to understand the structure and function of the cardiac cell makeup. 

## Results
**Figure 1:** scRNA-Seq Analysis of Cardiac Non-myocytes Reveals Major Cardiac Cell Types
<ol type="a">
  <li>Shows the methodology of selecting cells for scRNA-seq. They reduce the percentage of endothelial cells to approx. 10% of total non-myocytes because they did not want to oversample endothelial cells (largest cardiac cell population and is mostly made of miscrovascular endothelial cells).
  </li>
  <li>Through dimensionality reducation and unsupervised cell clustering, 12 distinct cell clusters were revealed.
  | Endothelial cells | |
  | Fibroblasts | |
  | Granulocytes | |
  | Lymphocytes | |
  | Pericytes | |
  | Macrophages | |
  | Dendritic cell-like cells | |
  | Schwann cells | |
  | Smooth muscle cells | |</li>
  <li>Previously known markers of cell types and heatmaps of their corresponding cell type according to this group's results.</li>
  <li>Heatmap of 10 significant marker genes for each identified cell population. "Fibroblast are associated with extracellular matrix, leukocytes are associated with immune-regulatory terms, endothelial cells and smooth muscle cells are associated with vascular development/homeostasis terms, and Schwann cells are associated with neuro-regulatory terms."</li>
</ol>

**Figure 2:** Major Cardiac Cell Types Harbor Subpopulations that Reflect a Hierarchy of Transcriptional Diversity
<ol type="a">
    <li>Subclustering of populations shows differences within major cell types. They are taking the entire tSNE plot from Fig. 1B and classifying the cells as either lymphoid or myeloid, then subclustering those identified cells.</li>
    <li>Using the same tSNE plot from Fig. 1B, they display all subpopulations identified. Note that not all cell populations had identifiable subpopulations (e.g. endothelial cells, Schwann cells, smoooth muscle cells). This means that these popluations may be more homogeneous in a mature heart</li>
    <li>This shows gene expression gradients in cells identified from Fig. 2A. They are primarily macrophages and dentritic cell-like populations.</li>
    <li>Macrophages have a subpopulation of cells that are kind of a blend of both macrophages and fibroblasts. They show intermediate levels of expression in canonical fibrblast genes and high levels of expression in canonical macrophage/leukocyte genes."</li>
    <li>They want to confirm the existence of the previously mentioned macrophages, which they identify of "putative (i.e. assumed) fibrocytes." After staining, they first identify fibrocytes, and then GFP positive marks fibroblasts.</li>
    <li> Images of GFP+ cells that also have macrophage surface markers.</li>
    <li>Also detected less significant cell subsets with fibroblast-like gene signatures in other major cell populations, such as endothelial cells</li>
</ol>

**Figure 3:** Novel Strategies for Isolation of Cardiac Mural Cells and Glia
<ol type="a">
    <li>Specificcally looking at mural cells (vascular smooth muscle cells) and glia (non-neuronal cells in the CNS and PNS). Fig. 1B plot is modified to show these different types of cells, and the right part shows commonly use markers and new markers used to possibly identify these cell types.</li>
    <li>Staining in the CSPG4-GFP mouse hearts with GFP, IB4, and translecting for pericytes and smooth muscle cells. Why use IB4 if you are already using translecin?</li>
    <li>Three mouse models to detect fibroblasts and mural cells (itga7 and mefsk4 antibodies). What does pre-gated mean? They identify three populations of cells.</li>
    <li>Histograms showing the expression of R1, R2, and R3 in two different genotypes of mice in comparison to wild type. Main takeaway: cardiac fibroblasts (PDGFRalpha+ cells) can be identified and isolated using the mefsk4 and itga7 markers. Itga7 distinguishes mural cells from mefsk4low/int fibroblasts.</li>
    <li>MCAM separates mural cells from fibrblasts and marks Schwann cells. ENTPD1 identify smooth muscle cells, CD59a identify Schwan cells.</li>
    <li>This knowledge allowed them to identify and isolated smooth muscle cells, pericytes, and Schwann cells.</li>
</ol>

**Figure 4:** A Dense Network of Autocrine and Paracrine Signaling Udnerpins Cardiac Homeostasis
<ol type="a">
  <li>Map of intercellular communication</li>
  <li>Fibroblasts are the most "trophic," meaning that they stimulate the most activity</li>
  <li>Fibroblasts also signal the most for survival, as you can see the heatmap of cell types and important growth factors</li>
  <li>Fibroblasts and pericytes express csf1 and il34, respectively, which signal through sf1r and are essential factors for macrophage growth and survival</li>
  <li>Non-myocyte cultures show a lot of macrophages labeled with GFP</li>
  <li>zoomed in of Fig. 4E</li>
  <li>endothelial cells</li>
  <li>macropahges fail to grow when csf1r signaling is blocked. Main takeaway: fibroblasts are important for macrophage and endothelial cell growth (idk about endothelial cells though), but also other essential growth factors from non-fibroblasts are also important</li>
</ol>

**Figure 5:** Widespread Cell-Type-Specific Sexual Dimorphism in Cardiac Gene Expression
<ol type="a">
  <li>Separation of female and male cells</li>
  <li>Of the 396 genes upregged in female and 430 upregged in males, about 97% were under 2-fold ratio of sex:opposite sex. Median 1.17</li>
  <li>The differences in gene expression for which sex has more and how large the difference is largely depends on cell type</li>
  <li>Showcasing 27 genes that have different female/male gene expression between cell types. Male macrophages upregged genes that respond to foreign antigens. Female macrophages upregged responses to stress and electron transport chain
</ol>





## Introduction
BAG3 is a co-chaperone protein that is important for protein quality control (PQC), therefore maintaining proteostasis (proteo-stasis = protein equilibrium)[^1]. It does this through chaperone-assisted selective autophagy. However, "an amino acid exchange (P209L) in the HSPB8 binding site of the human co-chaperone BAG3 gives rise to severe childhood cardiomyopathy" (cardio-myo-pathy = heart muscle suffering/disease). P209L is a point mutation, but its precise location has not been discovered. There are three main types of cardiomyopathy: dilated, hypertrophic, and restrictive[^2].

| Dilated cardiomyopathy | LV is dilated (volume increases). Most frequent is in middle-aged men. Can be caused by coronary artery disease, heart attack, or poor genetics. |
| Hypertrophic cardiomyopathy | LV wall thickens (volume decreases). Condition extremely severe if during childhood. Can be linked to family history and some genetic mutations. |
| Restrictive cardiomyopathy | Heart muscle is stiff and less flexible. Any age but typically affects older people. Idiopathic (can happen for no apparent reason), or other diseases in the body that end up affecting the heart (e.g. amyloidosis). |

In this paper, the authors want to generate better replicates of the BAG3<sup>P209L</sup> mutation (and the subsequent phenotype) by using human transgenic mice. With these mouse models, we can better understand the mechanisms of BAG3<sup>P209L</sup>.

## Results
**Figure 1:** "Characterization of αMHC-BAG<sup>WT</sup> and αMHC-BAG<sup>P209L</sup> mice
<ol type="a">
  <li> </li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

## Discussion

## References
[^1]: https://www.frontiersin.org/articles/10.3389/fnmol.2017.00177/full
[^2]: https://www.mayoclinic.org/diseases-conditions/cardiomyopathy/symptoms-causes/syc-20370709
[^3]: 
[^4]: 
[^5]: 
[^6]: 
[^7]: 
[^8]: 
[^9]: 
[^10]: 