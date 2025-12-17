# Healthcare Treatment Recommendation using IDP

This repository contains an IDP (Imperative Declarative Programming) knowledge base for recommending healthcare treatments based on patient data and clinical rules. It encodes medical domain knowledge as logical constraints and uses model expansion to suggest suitable treatments for given patient profiles. [^1]

## Features

- Encodes patient attributes such as symptoms, diagnoses, risk factors, and contraindications.
- Represents treatment options and eligibility criteria as logical rules.
- Uses the IDP system to compute consistent treatment recommendations.
- Includes example queries and results in `Results.txt`. [^1]

## Repository structure

- `HEALTHCARE TREATMENT RECOMMENDATION.idp` – main IDP theory, vocabulary, and structures defining patients and treatments. [^1]
- `Results.txt` – sample outputs showing recommended treatments for example input cases. [^1]

## Prerequisites

- IDP system (knowledge base solver) installed locally or access to an IDP web IDE.  
  See the official IDP documentation and downloads:  
  - IDP system: https://dtai.cs.kuleuven.be/krr/idp  
- A text editor or IDE capable of handling `.idp` files.

## How to run

1. Install or open the IDP system.
2. Clone this repository:
git clone https://github.com/NexusSin/healthcare-treatment-recommendation-using-idp.git   
cd healthcare-treatment-recommendation-using-idp
3. Open `HEALTHCARE TREATMENT RECOMMENDATION.idp` in the IDP environment.
4. Load the theory and structures, then execute model expansion (or the relevant procedure defined in the file) to compute recommended treatments.
5. Adjust patient data in the structure section and rerun to obtain recommendations for different cases.

## Customization

- Modify or extend the vocabulary to include additional symptoms, lab values, or comorbidities.
- Add new treatments with their eligibility and contraindication rules.
- Tune priority rules (if present) to reflect different clinical guidelines or risk attitudes.

## Results

Example runs and their corresponding treatment recommendations are documented in `Results.txt`. Use these examples as a template when defining your own patient cases and interpreting the solver output. [^1]

## License and citation

This repository does not include an explicit license at the time of writing; treat it as “all rights reserved” unless the owner adds a license file. If using this project in academic work, cite the GitHub repository:

> NexusSin, *Healthcare Treatment Recommendation using IDP*, GitHub repository,  
> https://github.com/NexusSin/healthcare-treatment-recommendation-using-idp

[^1]: Repository: https://github.com/NexusSin/healthcare-treatment-recommendation-using-idp
