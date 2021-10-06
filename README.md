# Skin Disorder Detection

## Business Case for Skin Disease Detection

The six phenotypes of Erythmato-squamous Diseases (ESD) are the major challenge in dermatology. For instance, the psoriasis is the most common disease of ESD which approximately, 2 to 3% of population are affected. Due to overlapping between sign and symptom of ESD, differential diagnosis is very difficult. These diseases are frequently seen in the outpatient department of dermatology. All of ESD disease are same in terms of erythema and scaling, but when examine carefully some patient have the typical clinical feature of disease. Automatic detection of these group of disease could help physician for decision making.

The differential diagnosis of erythemato-squamous diseases (ESD) in dermatology is a difficult task because of the overlapping of their signs and symptoms. Automatic detection of ESD can be useful to support physicians in making decisions if the model gives comprehensible explanations and conclusions. Several approaches have been proposed to automatically diagnosis ESD, including artificial neural networks (ANN) and support vector machines (SVM). Although, these methods achieve high performance accuracy, they are not attractive for dermatologists because their models are not directly usable. Decision trees can be converted into a set of if-then rules, which makes them particularly suitable for rule-based systems. 

Area: Life

```
## Data Set Information:

The dermatology data set contains 366 samples and 34 attributes. Of 34 attributes, 12 are clinical features and 22 are histopathological features. From the data set features, age and family history are continuous and ranged between 0-1, respectively. Every other feature (clinical and histopathological) was given a degree in the range of 0 to 3 which, 0 indicates that the feature was not present, 3 indicates the largest amount possible, and 1, 2 indicate the relative intermediate values

This database contains 34 attributes, 33 of which are linear valued and one of them is nominal.

The dataset consists of information about 6 kinds of skin disorder. The details are as follows
 
- the family history feature has the value 1 if any of these diseases has been observed in the family, and 0 otherwise. 
 
- The age feature simply represents the age of the patient. 
 
- Every other feature (clinical and histopathological) was given a degree in the range of 0 to 3. 
 
- Here, 0 indicates that the feature was not present, 3 indicates the largest amount possible, and 1, 2 indicate the relative intermediate values. 

In the dataset constructed for this domain, the family history feature has the value 1 if any of these diseases has been observed in the family, and 0 otherwise. The age feature simply represents the age of the patient. Every other feature (clinical and histopathological) was given a degree in the range of 0 to 3. Here, 0 indicates that the feature was not present, 3 indicates the largest amount possible, and 1, 2 indicate the relative intermediate values.

## Attribute Information

### Clinical Attributes: (take values 0, 1, 2, 3, unless otherwise indicated)

- 1: erythema
- 2: scaling
- 3: definite borders
- 4: itching
- 5: koebner phenomenon
- 6: polygonal papules
- 7: follicular papules
- 8: oral mucosal involvement
- 9: knee and elbow involvement
- 10: scalp involvement
- 11: family history, (0 or 1)
- 34: Age (linear)

### Histopathological Attributes: (take values 0, 1, 2, 3)

Histopathology is the study of the signs of the disease using the microscopic examination of a biopsy or surgical specimen that is processed and fixed onto glass slides. To visualize different components of the tissue under a microscope, the sections are dyed with one or more stains.

- 12: melanin incontinence
- 13: eosinophils in the infiltrate
- 14: PNL infiltrate
- 15: fibrosis of the papillary dermis
- 16: exocytosis
- 17: acanthosis
- 18: hyperkeratosis
- 19: parakeratosis
- 20: clubbing of the rete ridges
- 21: elongation of the rete ridges
- 22: thinning of the suprapapillary epidermis
- 23: spongiform pustule
- 24: munro microabcess
- 25: focal hypergranulosis
- 26: disappearance of the granular layer
- 27: vacuolisation and damage of basal layer
- 28: spongiosis
- 29: saw-tooth appearance of retes
- 30: follicular horn plug
- 31: perifollicular parakeratosis
- 32: inflammatory monoluclear inflitrate
- 33: band-like infiltrate
```
