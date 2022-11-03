## ADMET prediction using ML

This post is a step-by-step implementation of my approach to calculating the ADME(T) properties and it is meant for sharing, studying, and critiquing by fellow researchers who are new and interested in this topic. Most of the research paper that is implemented can be found in **ref** directory. 

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
*   [ ] **Stereo Centers**
*   [x] **Molar Refractivity**
*   [x] **tPSA**
*   [x] **LogP**
*   [ ] **pKa**
*   [ ] **LogS**
*   [ ] **LogD7.4**

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

*   [ ] **Caco-2 Permeability**
*   [ ] **MDCK Permeability**
*   [ ] **HIA**
*   [ ] **Pgp-substrate**
*   [ ] **Pgp-inhibitor**
*   [ ] **Oral Bioavailability**
*   [ ] **F20%**
*   [ ] **F30%**

---

### **Distribution:**

*   [ ] **BBB Penetration**
*   [ ] **PPB**
*   [ ] **VD**
*   [ ] **Fu**

---

### **Metabolism:**

*   [ ] **CYP450 inhibitor/substrate**
*   [ ] **1A2**
*   [ ] **2C9**
*   [ ] **2C19**
*   [ ] **2D6**
*   [ ] **3A4**

---

### **Excretion:**

*   [ ] **Half Life**
*   [ ] **CL**

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
*   [ ] **Hepatotoxicity**
*   [ ] **Eye Corrosion**
*   [ ] **Eye Irritation**
*   [ ] **Respiratory Toxicity**
*   [ ] **Bioconcentration Factor**
*   [ ] **hERG inhibition/blockers**
*   [ ] **IGC50**
*   [ ] **LC50FM**
*   [ ] **LC50DM**
*   [ ] **AR**
*   [ ] **AR-LBD**
*   [ ] **ER**
*   [ ] **ER-LBD**
*   [ ] **Aromatase**
*   [ ] **PPAR-Y**
*   [ ] **AhR**
*   [ ] **MMP**
*   [ ] **p53**
*   [ ] **ARE**
*   [ ] **HSE**
*   [ ] **ATAD5**

---