# Variant Analysis 

This project analyzes annotated SNP variants from a Harvard PGP individual to identify potentially functional mutations. Using tools such as PolyPhen-2, Grantham, and GERP scores, we assess the protein-level impact and link variants to phenotypes and population data.

## 🧪 Objectives

- Compare SNP annotation from `functionGVS` and `functionDBSNP`
- Analyze the predicted functional impact using:
  - **PolyPhen-2**
  - **Grantham Score**
  - **GERP Conservation Score**
- Select three functionally relevant variants (PRDM16, IL37, PNPLA1)
- Investigate clinical relevance, zygosity, and population allele frequency

## 📊 Tools & Databases Used

- PolyPhen-2
- SeattleSeq Genome Variation Server (GVS)
- dbSNP
- UniProt
- OMIM


## 🧬 Selected Variant Insights

### Variant 1: PRDM16 (rs2493292)
- Function: Energy metabolism, brown fat development
- Impact: Possibly damaging, linked to cardiomyopathy

### Variant 2: IL37 (rs3811046)
- Function: Anti-inflammatory cytokine
- Impact: Homozygous variant associated with IBD

### Variant 3: PNPLA1 (rs34598813)
- Function: Lipid metabolism, skin barrier
- Impact: Carrier of a known ichthyosis-linked variant

## 📁 File Structure

| Folder | Description |
|--------|-------------|
| `report/` | Final report in `.docx` and `.pdf` formats |
| `data/` | Annotated SNP dataset (if sharing is permitted) |


## 📚 References

1. Allam, G. et al. (2016). Association of IL-37 gene polymorphisms with susceptibility to tuberculosis in Saudi subjects. *Microbiol Immunol, 60*(11), 778–786. https://doi.org/10.1111/1348-0421.12444  
2. Ahmad, F. et al. (2021). PNPLA1 variants in ARCI. *Mol Syndromol, 12*(6), 351–361. https://doi.org/10.1159/000516943  
3. SeattleSeq: https://gvs.gs.washington.edu/SeattleSeqAnnotation/  
4. dbSNP: https://www.ncbi.nlm.nih.gov/snp/  
5. UniProt: https://www.uniprot.org/  
6. OMIM: https://www.omim.org/



## 👨‍💻 Author

**Uday Kiran Gogineni** – Clustering & Modeling Lead  
_M.S. in Bioinformatics_  
[LinkedIn](https://www.linkedin.com/in/udaykiran01)

