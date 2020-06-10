# RA-ILD-query
# RA-ILD Project Documentation

|Project|RA-ILD|
|-|-|
|Project Start Date  | 11/2019|
|Primary Investigator  | Bryant England, MD, PhD|
|Coordinator  | Brendan Cope, PharmD|

[[_TOC_]]

### i. [Project Outline](http://necares-dev.unmc.edu:8090/brendancope/ra-ild/-/blob/master/201911_england_ra-ild_research_plan.docx)
### 1. Research Question
## Research Question:
Can we build and utilize a computable phenotype for RA-ILD to build a patient cohort from the GPC dataset?

### Primary Outcome:
Patients who meet the criteria for RA-ILD based solely upon EHR data.

### 2. Inclusion Criteria
### Inclusion Criteria
- RA diagnosis code
- DMARD medication or lab for rheumatoid factor or anti-CCP to confirm the RA diagnosis code
- ILD diagnosis code
- lung function procedure to confirm the ILD diagnosis code

### 3. Exclusion Criteria

### SNOMED CT EXCLUSION CODES:
- [31541009](https://browser.ihtsdotools.org/?perspective=full&conceptId1=31541009&edition=MAIN/2020-03-09&release=&languages=en) | Sarcoidosis (disorder) |
  - Miliary lupoid of Boeck
  - Boeck's sarcoidosis
  - Benign lymphogranulomatosis of Schaumann
  - Darier-Roussy sarcoid
  - Boeck's sarcoid
  - Lupus pernio of Besnier
  - Besnier-Boeck-Schaumann syndrome
  - Sarcoidosis (disorder)
  - Sarcoidosis
- [89155008](https://browser.ihtsdotools.org/?perspective=full&conceptId1=89155008&edition=MAIN/2020-03-09&release=&languages=en) | Systemic sclerosis (disorder) |
  - Thibierge-Weissenbach syndrome
  - Systemic sclerosis (disorder)
  - Scleroderma syndrome
  - Systemic scleroderma
  - SS - Systemic sclerosis
  - Systemic sclerosis
- [26889001](https://browser.ihtsdotools.org/?perspective=full&conceptId1=26889001&edition=MAIN/2020-03-09&release=&languages=en) | Myositis (disorder) |
  - Myositis (disorder)
  - Myositis
  - Inflammation of skeletal muscle, not including inflammation of cardiac muscle
  - Muscle inflammation
  - Inflammatory myopathy
  - Inflammatory disorder of muscle
- [5564009](https://browser.ihtsdotools.org/?perspective=full&conceptId1=5564009&edition=MAIN/2020-03-09&release=&languages=en) | Systemic lupus erythematosus (disorder) |
  - Systemic lupus erythematosus
  - SLE - Systemic lupus erythematosus
  - Disseminated lupus erythematosus
  - Systemic lupus erythematosus (disorder)
- [37471005](https://browser.ihtsdotools.org/?perspective=full&conceptId1=37471005&edition=MAIN/2020-03-09&release=&languages=en) | Extrinsic allergic alveolitis (disorder) |
  - Bagpipe lung
  - Allergic alveolitis
  - EAA - Extrinsic allergic alveolitis
  - Allergic pneumonitis
  - Extrinsic allergic alveolitis (disorder)
  - Allergic interstitial pneumonitis
  - Extrinsic allergic bronchiolo-alveolitis
  - Extrinsic allergic alveolitis
  - Hypersensitivity pneumonia
  - Hypersensitivity pneumonitis
- [40122008](https://browser.ihtsdotools.org/?perspective=full&conceptId1=40122008&edition=MAIN/2020-03-09&release=&languages=en) | Pneumoconiosis (disorder) |
  - Pneumoconiosis (disorder)
  - Pneumoconiosis
  - PK - Pneumoconiosis
- [22607003](https://browser.ihtsdotools.org/?perspective=full&conceptId1=22607003&edition=MAIN/2020-03-09&release=&languages=en) | Asbestosis (disorder) |
  - Asbestos pneumoconiosis
  - Pulmonary asbestosis
  - Asbestosis
  - Asbestosis (disorder)
  - Amianthosis
- [84004001](https://browser.ihtsdotools.org/?perspective=full&conceptId1=84004001&edition=MAIN/2020-03-09&release=&languages=en) | Radiation pneumonitis (disorder) |
  - Radiation pneumonitis
  - Pulmonary radiation alveolitis
  - Radiation pneumonitis (disorder)

### 4. Rheumatoid Arthritis Codes
## Diagnosis Codes for RA

### ICD 10
- M05
- M06.0
- M06.8
- M06.9

### ICD 9
- 714.0
- 714.2
- 714.1
- 714.81

### SNOMED CT
- <b>69896004</b> | Rheumatoid arthritis (disorder) |
  - Chronic rheumatic arthritis
  - Rheumatic gout
  - Rheumatoid arthritis
  - Rheumatoid disease
  - RhA - Rheumatoid arthritis
  - RA - Rheumatoid arthritis
  - Atrophic arthritis
  - Proliferative arthritis
  - Rheumatoid arthritis (disorder)

### 5. DMARD Codes
## DMARD
### Medications, RXNORM TTY=IN
- 6851 -- methotrexate
- 27169 --	leflunomide
- 9524 -- Sulfasalazine
- 5521 -- Hydroxychloroquine
- 1256 --	Azathioprine
- 42316 --	Tacrolimus
- 3002 --	Cyclophosphamide
- 68149 --	mycophenolate mofetil
- 8640 -- Prednisone

### Biologics, RXNORM TTY=IN
- 214555 --	Etanercept
- 1357536 -- Tofacitinib

### Monoclonals Antibodies, RXNORM TTY=IN
- 327361 -- adalimumab
- 819300 -- golimumab
- 709271 -- certolizumab
- 1923319 -- sarilumab
- 121191 -- rituximab

### 6. Confirming Lab Codes
## Lab Procedures with long common names from <a href="https://loinc.org/">loinc.org</a>
- [11572-5](https://loinc.org/11572-5/) - Rheumatoid factor [Units/volume] in Serum or Plasma
- [33935-8](https://loinc.org/33935-8/)</b> - Cyclic citrullinated peptide IgG Ab [Units/volume] in Serum or Plasma
- [57093-7](https://loinc.org/57093-7/)</b> - Cyclic citrullinated peptide IgA+IgG Ab [Units/volume] in Serum or Plasma by Immunoassay
- [63375-0](https://loinc.org/63375-0/) - Cyclic citrullinated peptide IgA+IgG Ab [Presence] in Serum

### 7. Interstitial Lung Disease Codes
### [SNOMED CT](https://browser.ihtsdotools.org/?perspective=full&conceptId1=404684003&edition=MAIN/2020-03-09&release=&languages=en) INCLUSION CODES:
- [233703007](https://browser.ihtsdotools.org/?perspective=full&conceptId1=233703007&edition=MAIN/2020-03-09&release=&languages=en)  --  Interstitial lung disease (disorder)

### SNOMED CT EXCLUSION CODES:
- [31541009](https://browser.ihtsdotools.org/?perspective=full&conceptId1=31541009&edition=MAIN/2020-03-09&release=&languages=en) | Sarcoidosis (disorder) |
  - Miliary lupoid of Boeck
  - Boeck's sarcoidosis
  - Benign lymphogranulomatosis of Schaumann
  - Darier-Roussy sarcoid
  - Boeck's sarcoid
  - Lupus pernio of Besnier
  - Besnier-Boeck-Schaumann syndrome
  - Sarcoidosis (disorder)
  - Sarcoidosis
- [89155008](https://browser.ihtsdotools.org/?perspective=full&conceptId1=89155008&edition=MAIN/2020-03-09&release=&languages=en) | Systemic sclerosis (disorder) |
  - Thibierge-Weissenbach syndrome
  - Systemic sclerosis (disorder)
  - Scleroderma syndrome
  - Systemic scleroderma
  - SS - Systemic sclerosis
  - Systemic sclerosis
- [26889001](https://browser.ihtsdotools.org/?perspective=full&conceptId1=26889001&edition=MAIN/2020-03-09&release=&languages=en) | Myositis (disorder) |
  - Myositis (disorder)
  - Myositis
  - Inflammation of skeletal muscle, not including inflammation of cardiac muscle
  - Muscle inflammation
  - Inflammatory myopathy
  - Inflammatory disorder of muscle
- [5564009](https://browser.ihtsdotools.org/?perspective=full&conceptId1=5564009&edition=MAIN/2020-03-09&release=&languages=en) | Systemic lupus erythematosus (disorder) |
  - Systemic lupus erythematosus
  - SLE - Systemic lupus erythematosus
  - Disseminated lupus erythematosus
  - Systemic lupus erythematosus (disorder)
- [37471005](https://browser.ihtsdotools.org/?perspective=full&conceptId1=37471005&edition=MAIN/2020-03-09&release=&languages=en) | Extrinsic allergic alveolitis (disorder) |
  - Bagpipe lung
  - Allergic alveolitis
  - EAA - Extrinsic allergic alveolitis
  - Allergic pneumonitis
  - Extrinsic allergic alveolitis (disorder)
  - Allergic interstitial pneumonitis
  - Extrinsic allergic bronchiolo-alveolitis
  - Extrinsic allergic alveolitis
  - Hypersensitivity pneumonia
  - Hypersensitivity pneumonitis
- [40122008](https://browser.ihtsdotools.org/?perspective=full&conceptId1=40122008&edition=MAIN/2020-03-09&release=&languages=en) | Pneumoconiosis (disorder) |
  - Pneumoconiosis (disorder)
  - Pneumoconiosis
  - PK - Pneumoconiosis
- [22607003](https://browser.ihtsdotools.org/?perspective=full&conceptId1=22607003&edition=MAIN/2020-03-09&release=&languages=en) | Asbestosis (disorder) |
  - Asbestos pneumoconiosis
  - Pulmonary asbestosis
  - Asbestosis
  - Asbestosis (disorder)
  - Amianthosis
- [84004001](https://browser.ihtsdotools.org/?perspective=full&conceptId1=84004001&edition=MAIN/2020-03-09&release=&languages=en) | Radiation pneumonitis (disorder) |
  - Radiation pneumonitis
  - Pulmonary radiation alveolitis
  - Radiation pneumonitis (disorder)

### 8. Lung Procedure Codes
## Lung Procedure Codes

### CPT
- 94010: spirometry
- 94060: spirometry
- 32607: Thoracoscopy; with diagnostic biopsy(ies) of lung infiltrate(s) (eg, wedge, incisional), unilateral
- 71250: Computed tomography, thorax; without contrast materiaL
- 71260: Computed tomography, thorax; with contrast material(s)
- 71270: Computed tomography, thorax; without contrast material, followed by contrast material(s) and further sections

### ICD9CM
- 33.28 Open biopsy of lung
- 33.20 Thoracoscopic lung biopsy

---

####  LOINC Codes for procedures - not currently utilized by NMC

- LOINC codes for Forced Vital Capacity
  - 19871-3
  - 19872-1
  - 19873-9
  - 19925-7
  - 19926-5
  - 64027-6
  - 64029-2
  - 64592-9
  - 69970-2
  - 69982-7
  - 69984-3

- LOINC codes for FVC
  - 19871-3
  - 19872-1
  - 19873-9
  - 19925-7
  - 19926-5
  - 64592-9
  - 69970-2
  - 69982-7
  - 69984-3

- LOINC codes for DLCO
  - 19910-9
  - 19911-7
  - 19912-5
  - 19913-3
  - 19914-1
  - 19915-8
  - 19916-6
  - 19917-4
  - 19918-2
  - 69578-3

# Lab Work
