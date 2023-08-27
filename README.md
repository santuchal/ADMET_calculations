## ADMET prediction using ML

This post is a step-by-step implementation of my approach to calculating the ADME(T) properties and it is meant for sharing, studying, and critiquing by fellow researchers who are new and interested in this topic. Most of the research paper that is implemented can be found in **ref** directory. 

### NOTE

Note of the advanced machine learning module is upload in github and save as private repo.

* [x] marked is completed a long time ago. 

### **Physicochemical Properties:**

*   [x] **Molecular Weight**
*   [ ] **Volume**
*   [ ] **Density**
*   [x] **Heavy Atoms**
*   [x] **Aromatic Heavy Atoms**
*   [x] **Fraction Csp3**
*   [x] **Rotatable Bonds**
*   [x] **Hetro Atoms**
*   [x] **H-Bond Acceptors**
*   [x] **H-Bond Donors**
*   [x] **Ring Count**
*   [x] **Aromatic Ring Count**
*   [x] **Stereo Centers**
*   [x] **Molar Refractivity**
*   [x] **tPSA**
*   [x] **LogP**
*   [ ] **pKa**
*   [x] **LogS**
*   [x] **LogD7.4**

---

### **Medicinal Chemistry:**

*   [x] **QED**
*   [x] **SAscore**
*   [x] **NPScore**
*   [x] **Fsp3**
*   [x] [**Lipinski Violations**](https://en.wikipedia.org/wiki/Lipinski%27s_rule_of_five)
*   [ ] [**Pfizer Violations**](https://github.com/santuchal/adme_predection/blob/master/ref/hughes2008.pdf)
*   [ ] [**GSK Violations**](https://github.com/santuchal/adme_predection/blob/master/ref/gleeson2008.pdf)
*   [ ] [**Golden Triangle**](https://github.com/santuchal/adme_predection/blob/master/ref/johnson2009.pdf)
*   [x] [**Ghose Violations**](https://github.com/santuchal/adme_predection/blob/master/ref/ghose1999.pdf)
*   [x] [**Veber Violations**](https://github.com/santuchal/adme_predection/blob/master/ref/veber2002.pdf)
*   [x] [**Muegge Violations**](https://github.com/santuchal/adme_predection/blob/master/ref/muegge2001.pdf)
*   [x] [**Egan Violations**](https://github.com/santuchal/adme_predection/blob/master/ref/egan2000.pdf)
*   [x] [**PAINS Alerts**](https://en.wikipedia.org/wiki/Pan-assay_interference_compounds)
*   [x] **BRENK Alerts**
*   [ ] **ALARM NMR Rule**
*   [ ] **Chelator Rule**

---

### **Absorption:**

*   [x] **Caco-2 Permeability** Using RF and rdkit and chemdesc descriptor
*   [ ] **MDCK Permeability**
*   [x] **HIA** Using RF and MACCS Fingerprint
*   [x] **Pgp-substrate** Using RF and SVM with ECFP4, ECFP6, MACCS
*   [x] **Pgp-inhibitor** Using RF and SVM with ECFP4, ECFP6, MACCS
*   [ ] **Oral Bioavailability**
*   [x] **F20%** Using RF and MACCS Fingerprint
*   [x] **F30%** Using RF and MACCS Fingerprint

---

### **Distribution:**

*   [x] **BBB** Using SVM and ECFP6 with Morgan Fingerprint
*   [x] **PPB** Using RF and rdkit and chemdesc descriptor
*   [x] **VD** Using RF and rdkit and chemdesc descriptor

---

### **Metabolism:**

*   [ ] **CYP450 inhibitor/substrate**
*   [x] **1A2** Using RF and SVM with ECFP4, ECFP6, MorganFingerprint ( Different Accuracy, Precesion, FPR, Specifivity, ACC, F1 Score)
*   [x] **2C9**Using RF and SVM with ECFP4, ECFP6, MorganFingerprint ( Different Accuracy, Precesion, FPR, Specifivity, ACC, F1 Score)
*   [x] **2C19**Using RF and SVM with ECFP4, ECFP6, MorganFingerprint ( Different Accuracy, Precesion, FPR, Specifivity, ACC, F1 Score)
*   [x] **2D6**Using RF and SVM with ECFP4, ECFP6, MorganFingerprint ( Different Accuracy, Precesion, FPR, Specifivity, ACC, F1 Score)
*   [x] **3A4**Using RF and SVM with ECFP4, ECFP6, MorganFingerprint ( Different Accuracy, Precesion, FPR, Specifivity, ACC, F1 Score)

---

### **Excretion:**

*   [x] **Half Life(T1/2)** Using RF with descriptor(rdkit and chemdesc)
*   [x] **CL** Using RF with descriptor(rdkit and chemdesc)

---

### **Toxicity:**

*   [ ] **Rodent Acute Toxicity**
*   [ ] **Human Acute Toxicity**
*   [ ] **Genotoxic Carcinogenicity Rule**
*   [ ] **Carcinogenicity**
*   [ ] **Skin Sensitization Rule**
*   [ ] **Aquatic Toxicity Rule**
*   [ ] **NonBiodegradable Rule**
*   [ ] **Sure ChEMBL Rule**
*   [ ] **FAF-Drugs4 Rule**
*   [ ] **Ames Mutagenicity**
*   [x] **Hepatotoxicity** Using RF and descriptor
*   [ ] **Eye Corrosion**
*   [ ] **Eye Irritation**
*   [ ] **Respiratory Toxicity**
*   [ ] **Bioconcentration Factor**
*   [x] **hERG inhibition/blockers** Using Using RF and descriptor with MACCS
*   [ ] **IGC50**
*   [x] **LD50** Using RF 2D descriptor
*   [x] **AMES** Using RF and MACCS
*   [ ] **AR-LBD**
*   [x] **SkinSen** Using RF and MACCS
*   [ ] **ER-LBD**
*   [ ] **Aromatase**
*   [ ] **PPAR-Y**
*   [x] **DILI** Using RF and MACCS
*   [x] **FDAMDO** Using RF and ECFP4
*   [ ] **p53**
*   [ ] **ARE**
*   [ ] **HSE**
*   [ ] **ATAD5**

---