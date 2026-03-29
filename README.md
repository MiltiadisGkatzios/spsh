# SHACL-SPARQL Functions Ontology

![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey)
[GitHub Pages](https://miltiadisgkatzios.github.io/shacl-sparql/)

This repository contains a **preliminary draft ontology** that formalizes **SPARQL 1.1 functions** as instances of `sh:SPARQLFunction` using **SHACL Advanced Features**.  

It provides machine-readable representations of SPARQL functions, mathematical operations, and symbols. Each function is uniquely instantiated and described with labels, definitions, and references from SPARQL 1.1.  

The ontology is intended to help users **standardize SPARQL queries within SHACL `sh:TripleRule` instances**, improving interoperability, reusability, and universality of SHACL-based rules.

---

## Status

- This is an **informal draft**; it has no official standing or normative authority.  
- The content may evolve over time and is provided for **documentation and reference purposes only**.  
- Examples illustrate potential approaches and are **not a mandatory specification**.  

---

## Repository Structure
shacl-sparql/ <-- root
├── index.html <-- ReSpec human-readable documentation
├── LICENSE <-- CC BY-NC 4.0 license file
├── README.md <-- this file
├── data/ <-- RDF/TTL files
  ├── shacl-sparql ontology.ttl <-- SHACL triple rules
  └── example-data.ttl 

## License

This repository is licensed under the Creative Commons Attribution–NonCommercial 4.0 International License (CC BY-NC 4.0).
You may copy, distribute, and adapt this work for non-commercial purposes, with proper attribution. Commercial use requires prior permission from the authors. See LICENSE
 for full details.

## Citation
If you use this repository in research or projects, please cite:
Miltiadis Gkatzios. (2026). SHACL-SPARQL Functions Ontology. 
https://miltiadisgkatzios.github.io/shacl-sparql/
