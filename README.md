# CS5803_IIT-Hyd_Natural-Language-Processing-NLP-
This contains Named Entity Recognition project I did as part of CS5803 - Natural Language Processing (NLP) coursework at IIT Hyd during Jan-April 2023

The datset was obtained from "SemEval 2023 Task 2: MultiCoNER II Multilingual Complex Named Entity Recognition" competition.(https://multiconer.github.io/dataset) 
We chose the English language out of the 11 languages options provided.

The tagset of MultiCoNER is a fine-grained tagset.

The fine to coarse level mapping of the tags are as follows:

Location (LOC) : Facility, OtherLOC, HumanSettlement, Station
Creative Work (CW) : VisualWork, MusicalWork, WrittenWork, ArtWork, Software
Group (GRP) : MusicalGRP, PublicCORP, PrivateCORP, AerospaceManufacturer, SportsGRP, CarManufacturer, ORG
Person (PER) : Scientist, Artist, Athlete, Politician, Cleric, SportsManager, OtherPER
Product (PROD) : Clothing, Vehicle, Food, Drink, OtherPROD
Medical (MED) : Medication/Vaccine, MedicalProcedure, AnatomicalStructure, Symptom, Disease

For English, there were	16,778	training data points, 871	 validation points, 249,980 test points.

We implemented two approaches : 

1. Conditional Random Field- , preprocessing , feature engineering & training from scratch
2. BERT base NER model -- fine tuning a huggingface model on your 67 NER Tags

The Codes will be uploaded post the release of Grades to avoid plagiarism.
