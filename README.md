# About 
This is a supplement repository to our paper "Population Group 2.0: Bringing the UMLS Semantic Network up to speed"

Authors: N Khatwani, J Geller

Conference: Medical Informatics Europe 2025 "Intelligent health systems – From technology to data and knowledge" 

https://mie2025.efmi.org/programme

--------------------------------------
# Population Group 2.0

### Abstract
The Unified Medical Language System (UMLS) Metathesaurus is
arguably the most comprehensive repository of biomedical terminologies. The
UMLS Semantic Network in orders of magnitude is smaller than the Metathesaurus
and contains 127 Semantic Types. One of those is “Population Group” – a Semantic
Type that encompasses concepts related to various demographics and social groups.
However, with the evolution of societal dynamics, the current classifications seem
to have become insufficient for distinctively capturing the semantics of the
contemporary societal structures. In this paper, we propose a re-evaluation and
expansion of the “Population Group” Semantic Type to better accommodate these
societal realities. With the introduction of the suggested new Semantic Types, we
aim to facilitate more precise healthcare data management, research, and policy
making.

### Index

### UMLS Semantic Network (Current Hierarchy)
```
Entity
├── Physical Object
│   ├── Organism
│   │   ├── Plant
│   │   │   └── Alga
│   │   ├── Fungus
│   │   ├── Virus
│   │   ├── Rickettsia or Chlamydia
│   │   ├── Bacterium
│   │   ├── Animal
│   │   │   ├── Invertebrate
│   │   │   └── Vertebrate
│   │   │       ├── Amphibian
│   │   │       ├── Bird
│   │   │       ├── Fish
│   │   │       ├── Reptile
│   │   │       └── Mammal
│   │   │           └── Human
│   │   └── Archaeon
│   ├── Anatomical Structure
│   │   ├── Embryonic Structure
│   │   ├── Fully Formed Anatomical Structure
│   │   │   ├── Body Part, Organ, or Organ Component
│   │   │   ├── Tissue
│   │   │   ├── Cell
│   │   │   ├── Cell Component
│   │   │   └── Gene or Genome
│   │   └── Anatomical Abnormality
│   │       ├── Congenital Abnormality
│   │       └── Acquired Abnormality
│   ├── Manufactured Object
│   │   ├── Medical Device
│   │   │   └── Drug Delivery Device
│   │   ├── Research Device
│   │   └── Clinical Drug
│   └── Substance
│       ├── Body Substance
│       ├── Chemical
│       │   ├── Chemical Viewed Structurally
│       │   │   ├── Organic Chemical
│       │   │   │   ├── Nucleic Acid, Nucleoside, or Nucleotide
│       │   │   │   ├── Organophosphorus Compound
│       │   │   │   ├── Amino Acid, Peptide, or Protein
│       │   │   │   ├── Carbohydrate
│       │   │   │   └── Lipid
│       │   │   │       ├── Steroid
│       │   │   │       └── Eicosanoid
│       │   │   ├── Element, Ion, or Isotope
│       │   │   └── Inorganic Chemical
│       │   └── Chemical Viewed Functionally
│       │       ├── Pharmacologic Substance
│       │       │   └── Antibiotic
│       │       ├── Biomedical or Dental Material
│       │       ├── Biologically Active Substance
│       │       │   ├── Neuroreactive Substance or Biogenic Amine
│       │       │   ├── Hormone
│       │       │   ├── Enzyme
│       │       │   ├── Vitamin
│       │       │   ├── Immunologic Factor
│       │       │   └── Receptor
│       │       ├── Indicator, Reagent, or Diagnostic Aid
│       │       └── Hazardous or Poisonous Substance
│       └── Food
├── Conceptual Entity
│   ├── Organism Attribute
│   │   └── Clinical Attribute
│   ├── Finding
│   │   ├── Laboratory or Test Result
│   │   └── Sign or Symptom
│   ├── Idea or Concept
│   │   ├── Temporal Concept
│   │   ├── Qualitative Concept
│   │   ├── Quantitative Concept
│   │   ├── Spatial Concept
│   │   │   ├── Body Location or Region
│   │   │   ├── Body Space or Junction
│   │   │   ├── Geographic Area
│   │   │   └── Molecular Sequence
│   │   │       ├── Nucleotide Sequence
│   │   │       ├── Amino Acid Sequence
│   │   │       └── Carbohydrate Sequence
│   │   └── Functional Concept
│   │       └── Body System
│   ├── Occupation or Discipline
│   │   └── Biomedical Occupation or Discipline
│   ├── Organization
│   │   ├── Health Care Related Organization
│   │   ├── Professional Society
│   │   └── Self-help or Relief Organization
│   ├── Group
│   │   ├── Professional or Occupational Group
│   │   ├── Population Group
│   │   ├── Family Group
│   │   ├── Age Group
│   │   └── Patient or Disabled Group
│   ├── Group Attribute
│   ├── Intellectual Product
│   │   ├── Regulation or Law
│   │   └── Classification
│   └── Language
└── Event
    ├── Activity
    │   ├── Behavior
    │   │   ├── Social Behavior
    │   │   └── Individual Behavior
    │   ├── Daily or Recreational Activity
    │   ├── Occupational Activity
    │   │   ├── Health Care Activity
    │   │   │   ├── Laboratory Procedure
    │   │   │   ├── Diagnostic Procedure
    │   │   │   └── Therapeutic or Preventive Procedure
    │   │   ├── Research Activity
    │   │   │   └── Molecular Biology Research Technique
    │   │   ├── Governmental or Regulatory Activity
    │   │   └── Educational Activity
    │   └── Machine Activity
    └── Phenomenon or Process
        ├── Injury or Poisoning
        ├── Human-caused Phenomenon or Process
        │   └── Environmental Effect of Humans
        └── Natural Phenomenon or Process
            ├── Biologic Function
            │   ├── Physiologic Function
            │   │   ├── Organism Function
            │   │   │   └── Mental Process
            │   │   ├── Organ or Tissue Function
            │   │   ├── Cell Function
            │   │   └── Molecular Function
            │   │       └── Genetic Function
            │   └── Pathologic Function
            │       ├── Disease or Syndrome
            │       │   ├── Mental or Behavioral Dysfunction
            │       │   └── Neoplastic Process
            │       ├── Cell or Molecular Dysfunction
            │       └── Experimental Model of Disease
```
            
### UMLS Semantic Network (After Population Group 2.0)


### Results
![Population Group 2.0](https://github.com/narenkhatwani/population-group-2.0/blob/main/img/tree.png?raw=true)

### Conclusion
