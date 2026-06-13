# Research Scope

## Objective

Study internal representations, representation stability, latent shifts, and failure modes only after the main reliable-spatiotemporal-forecasting MVP creates a concrete diagnostic question.

This repository is not a generic XAI demo.

Representation analysis is used to test hypotheses, not decorate reports.

Diagnostic methods must be connected to falsifiable questions.

The repository must not start from a preconceived claim that reconstruction improves representations.

Prediction-reconstruction is a candidate intervention, not an assumed solution.

It activates only when the flagship MVP exposes a concrete reliability failure.

## Initial Questions

* Which layers become unstable first under structured corruption?
* How should latent shift be measured?
* How do prediction-only and prediction-reconstruction models differ internally?
* Are representation changes associated with calibration failures?
* Are representation changes associated with ranking or allocation failures?

## Planned Diagnostic Candidates

* layer-wise activation statistics
* PCA
* SVD
* cosine similarity
* CKA or comparable representation-similarity method
* embedding-drift visualization
* failure-case comparison
* intervention test

All methods are Candidate.

No diagnostic method has been implemented.

## Boundaries

* no modules
* no notebooks
* no diagnostic implementation
* no claimed findings
* no standalone representation project before the main MVP creates an integration target

## Expected Outputs

* concrete representation-level hypothesis
* integration map to Reliable-AI-Research-Lab
* diagnostic protocol
* limitation log
* advisor-ready evidence only after MVP results exist
