**Single-cell RNAseq Profiling of the Fallopian Tube**

CxG Collection: https://cellxgene.cziscience.com/collections/fc77d2ae-247d-44d7-aa24-3f4859254c2c

Group: Hammond


**Objective:** 
To explore the cellular heterogeneity of the healthy fallopian tube (FT) and its alterations in disease states, thereby informing potential therapeutic strategies for reproductive organ pathologies.

**Background:** 
- FT is pivotal for fertilization, compromised in infertility and ovarian cancer.
- Segments: Fimbriae (oocyte capture), Ampulla (fertilization & embryo development), Isthmus (sperm reservoir & embryo transport).
- CxG Explorer - Examining tissue
  - <img width="1792" alt="image" src="https://github.com/MaximilianLombardo/hamondCxGDemo/assets/25663501/22169568-5662-4d08-a754-cbf40da5238b">
- Augment knowledge of tissue with information from CellGuides
  - <img width="1792" alt="image" src="https://github.com/MaximilianLombardo/hamondCxGDemo/assets/25663501/b21e7048-452b-4f82-9109-b240a49816d4">



**Cellular Landscape of Healthy FT:** 

<img width="1792" alt="image" src="https://github.com/MaximilianLombardo/hamondCxGDemo/assets/25663501/b0431b64-c1ad-4942-9547-cd3d5442ea3b">


- Epithelial Cells: 
  - Ciliated cells (FOXJ1+/CAPS+): Movement of gametes and embryos.
    - We can visualize individual marker genes with CxG explorer
    - <img width="1792" alt="image" src="https://github.com/MaximilianLombardo/hamondCxGDemo/assets/25663501/e0022809-4b1e-43d5-931a-e84768ec3e77">
    - We also visualize multiple genes, or gene sets at the same time with the gene sets function:
      - <img width="1789" alt="image" src="https://github.com/MaximilianLombardo/hamondCxGDemo/assets/25663501/c2ec2ed8-8353-4263-9cdc-df15fb159ba5">
  - Secretory cells (PAX8+/KRT7+): Vital for fertilization and early embryo development.
    - <img width="1792" alt="image" src="https://github.com/MaximilianLombardo/hamondCxGDemo/assets/25663501/d82bf4e3-d1b8-45f9-af6d-65531f47a39d">
  - Peg cells (EPCAM+/CD44+/ITGA6+): Potential progenitor properties.
    - <img width="1792" alt="image" src="https://github.com/MaximilianLombardo/hamondCxGDemo/assets/25663501/a99e0730-4fd9-4139-86e8-8547031d89c0">
  - Basal cells: Suggested immune functions.
    - ...
- Stromal Cells: Diverse types including lymphocytes, macrophages, dendritic cells, mast cells, smooth muscle cells, fibroblasts, etc.
  - ...
 
Instead of visualizing markers of individual cell types in an individual dataset, we can visualize all of the cell types in the fallopian tube across the corpus with Gene Expression:
- Starting in gene expression and exploring the fallopian tube cellular composition (and representation in the corpus)
- <img width="1791" alt="image" src="https://github.com/MaximilianLombardo/hamondCxGDemo/assets/25663501/2fa6bdaf-3d72-4fc0-9f2b-68f6f062cb00">
- Visualize markers that were reported in the paper across 
- <img width="1792" alt="image" src="https://github.com/MaximilianLombardo/hamondCxGDemo/assets/25663501/4dcaf433-adf2-4deb-babf-6e417626097d">
- Get more information about a desired cell type (ciliated epithelial cells):
- <img width="1792" alt="image" src="https://github.com/MaximilianLombardo/hamondCxGDemo/assets/25663501/f6470b45-69aa-4da7-acff-d01cdab831a0">
- Discover additional markers via the CellGuides sidebar in gene expression:
- <img width="1792" alt="image" src="https://github.com/MaximilianLombardo/hamondCxGDemo/assets/25663501/fbb081dd-3f0f-4295-8e01-91e0544742d3">

**Disease States & Impact on FT:**
- Conditions influencing FT cell composition: hormonal fluctuations, menopause, ovarian cancer, surgeries (tubal ligation).
  - Hormonal changes impact ciliated cells.
  - Decrease in peg cells related to reduced ovarian cancer risk.
  - Tubal factor infertility tied to hydrosalpinx; standard treatment involves surgical removal followed by IVF.

**Methodology:**
- Utilized scRNA-seq on 53,376 cells from 9 FT specimens of 3 healthy subjects.

**Key Findings:**
- 12 major cell types identified: 4 ciliated epithelial subtypes and 6 non-ciliated secretory epithelial subtypes. Two potential progenitor cells aiding FT homeostasis.
- Differentiation trajectories revealed via RNA velocity; highlights multiple progenitor cells.
- Disease (Hydrosalpinx) Analysis: 
  - Altered cell proportions: decreased epithelial cells, increased fibroblasts and macrophages, reduced smooth muscle and endothelial cells.
  - Expression variations: cell growth, proliferation, cancer stem cells, EMT markers, inflammatory pathways.
  - Changes hint at elevated tumorigenesis risk in hydrosalpinx.

**Discussion & Implications:** 
- Refined cell atlas offers a deeper view of the FT's cellular diversity.
  - 10 epithelial subtypes identified, revealing greater functional nuances.
  - Several progenitor cell populations detected, including those undergoing epithelial-mesenchymal transition (EMT).
- Progenitor cells of interest: 
  - EMT-expressing progenitors, which may be crucial in counteracting oncogenic transformations. Specifically, the subset NSCE2-2 expresses PRRX1, a potential safeguard against tumorigenesis.
- Hormonal influences: Variations noted in cell types across menstrual phases and between pre- and post-menopausal women, implying hormonal modulation.

**Conclusion:** 
This study provides an intricate catalog of cell types, subtypes, and markers for a healthy human fallopian tube. Insights into hydrosalpinx reveal potential pathophysiology and alternatives to surgical treatments. The research deepens our understanding of FT's cellular heterogeneity, pivotal for studies on female reproductive health, hormonal modulation, and diseases like ovarian cancer. Future explorations should focus on the functional roles of identified progenitor cells and potential therapeutic interventions.

Cell Types and markers

- Secretory Epithelial Cells
  - General Function: These cells are primarily responsible for the production and secretion of various substances that nourish the ovum, sperm, or embryo as they travel through the fallopian tube. They also help in the creation of an environment conducive for fertilization.
  - Previously Described Markers: PAX8, OVGP1
- Ciliated Epithelial Cells
  - General Function: They have hair-like projections called cilia, which help in moving the ovum towards the uterus. This movement aids in transporting the egg from the ovary to the uterus and potentially moving sperm towards the egg.
  - Previously Described Markers: FOXJ1, DNAI1
- Smooth Muscle Cells
  - General Function: These cells make up the muscular layer of the fallopian tubes, aiding in the contraction and relaxation of the tubes. This helps in the movement of the egg, sperm, or embryo.
  - Previously Described Markers: ACTA2, MYH11
-  Stromal Cells
  - General Function: They provide structural support and are involved in the production of various factors that influence the function of the fallopian tube.
  - Previously Described Markers: VIM, DES
- Immune Cells (e.g., Macrophages)
  - General Function: They are involved in the immune response within the fallopian tube, ensuring a healthy environment by dealing with any potential pathogens.
  - Previously Described Markers: CD68, F4/80 (for macrophages)
- Endothelial Cells
  - General Function: They line the blood vessels in the fallopian tube, facilitating the exchange of nutrients and waste.
  - Previously Described Markers: CD31, VE-cadherin
