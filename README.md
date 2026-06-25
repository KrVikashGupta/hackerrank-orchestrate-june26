# HackerRank Orchestrate – Multi-Modal Evidence Review

## Overview

This project was developed for the HackerRank Orchestrate Hackathon.

The system verifies damage claims by analyzing images, user claim conversations, claim history, and evidence requirements. It determines whether the submitted visual evidence supports, contradicts, or provides insufficient information for the claim.

## Supported Claim Objects

* Car
* Laptop
* Package

## Features

* Multi-modal evidence analysis
* Damage claim verification
* Image quality assessment
* Risk flag detection
* User history evaluation
* Evidence sufficiency validation
* Severity estimation
* Automated CSV output generation

## Dataset

The project processes the following files:

* `claims.csv`
* `sample_claims.csv`
* `user_history.csv`
* `evidence_requirements.csv`
* Image datasets located in `dataset/images/`

## Output Schema

The generated `output.csv` contains:

* evidence_standard_met
* evidence_standard_met_reason
* risk_flags
* issue_type
* object_part
* claim_status
* claim_status_justification
* supporting_image_ids
* valid_image
* severity

## Project Structure

```text
hackerrank-orchestrate-june26/
│
├── code/
│   ├── main.py
│   └── evaluation/
│       └── main.py
│
├── dataset/
│   ├── claims.csv
│   ├── sample_claims.csv
│   ├── user_history.csv
│   ├── evidence_requirements.csv
│   └── images/
│
├── output.csv
├── problem_statement.md
└── README.md
```

## Technologies Used

* Python
* Gemini API
* Pandas
* Pillow
* CSV Processing

## Evaluation

The system is evaluated using:

* Sample claim datasets
* Expected output comparison
* Evidence verification accuracy
* Risk assessment quality

## Hackathon

Built for HackerRank Orchestrate – June 2026.

## 📫 Contact

**Vikash Kumar Gupta**  
📍 Bokaro Steel City, Jharkhand  
✉️ [vikashkumargupta907@gmail.com](mailto:vikashkumargupta907@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/vikash1995) | [GitHub](https://github.com/KrVikashGupta)

---

⭐ If you find this project useful, please consider giving it a star to support the work!
