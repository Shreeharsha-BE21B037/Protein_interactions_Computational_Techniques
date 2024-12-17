# Protein Interactions and QSAR Analysis  
### Computational Techniques for Protein Interaction Studies and QSAR-Based Drug Discovery  

---

## **Overview**  
This repository contains computational analyses focused on protein-protein interactions, quantitative structure-activity relationship (QSAR) studies, pharmacophore modeling, and docking simulations. The work involves exploring online tools, building predictive models, and identifying new drug candidates based on structure and binding affinity.  

---

## **Contents**  

1. **Protein Interaction Studies**  
   - **Protein Structures:**  
      - *PDB ID: 2BTF* - Crystalline Profilin-Beta-Actin Complex  
      - *PDB ID: 1A22* - Human Growth Hormone Receptor (HGH)  

   - **Tasks Performed:**  
     - **Binding Site Identification:**  
       - *Techniques:* Accessible Surface Area (ASA) and Distance-based methods  
     - **Binding Interaction Types:** Identified and categorized interactions  
     - **Interaction Network Construction:**  
       - Tools: STRING, PDB SUM, and RCSB PDB  
     - **Thermodynamic Equation Extraction**  
     - **Propensity Calculations:** Computed interaction propensities  
     - **Predicted Protein Complex Structures:** Using FASTA sequence data  

---

2. **2D-QSAR Study and Drug Discovery**  
   - **Study Overview:**  
     - Performed QSAR study on 10 FDA-approved HIV protease inhibitor drugs.  
     - Developed and validated a 2D-QSAR model using a **70:30 training-test split**.  

   - **Tools and Techniques:**  
     - **ADME Property Determination:**  
       - Tool: [SWISS ADME](https://www.swissadme.ch/)  
       - ADME properties analyzed for all drug candidates.  
     - **Pharmacophore Modeling:**  
       - Tool: BIOVIA Discovery Studio  
       - Constructed a pharmacophore model to identify key binding features.  
     - **New Drug Identification:**  
       - Database: [ZINC15](https://zinc15.docking.org/)  
       - Identified **15 new drugs** with similar pharmacophore features.  
       - Performed drug-likeness screening and candidate selection.  
     - **Molecular Docking:**  
       - Visualized and compared drug efficacy of the 15 new drug candidates against the 10 FDA-approved drugs.  

---

## **Tools and Resources**  
- **Online Databases:**  
   - [RCSB PDB](https://www.rcsb.org/)  
   - [STRING Database](https://string-db.org/)  
   - [PDB SUM](https://www.ebi.ac.uk/pdbsum/)  
   - [ZINC15](https://zinc15.docking.org/)  
   - [SWISS ADME](https://www.swissadme.ch/)  

- **Software:**  
   - BIOVIA Discovery Studio  
   - Molecular Docking Software (e.g., AutoDock, PyMOL, or Chimera)  

- **Methods Applied:**  
   - Accessible Surface Area (ASA)  
   - Distance-based Binding Site Detection  
   - QSAR Modeling  
   - Pharmacophore Screening  
   - ADME Analysis  
   - Molecular Docking  

---

## **Results**  

1. **Protein Interaction Analysis:**  
   - Identified binding sites and interaction networks for proteins *2BTF* and *1A22*.  
   - Extracted thermodynamic equations and validated interaction sites.  

2. **QSAR and Drug Discovery:**  
   - Developed a robust **2D-QSAR model** for HIV protease inhibitors.  
   - Screened and identified **15 new drug candidates** from ZINC15.  
   - Assessed ADME properties and drug-likeness filters for candidate selection.  
   - Docking results confirmed promising drug efficacy compared to FDA-approved inhibitors.  

---

## **Conclusion**  

This study demonstrates an integrative computational approach for protein interaction analysis and drug discovery. Using 2D-QSAR modeling, pharmacophore screening, and docking simulations, we successfully identified potential drug candidates for HIV protease inhibition.  

---

## **Future Scope**  
- Explore advanced 3D-QSAR modeling.  
- Perform molecular dynamics simulations for in-depth drug-protein interaction analysis.  
- Extend the pipeline to other target proteins and diseases.  

---

## **Keywords**  
Protein Interaction, QSAR, Pharmacophore, Molecular Docking, HIV Protease Inhibitors  

---  
