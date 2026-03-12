# Automated Molecular Identify Disambiguator (AutoMID) 

AutoMID is a systematic, hierarchical schema of key metadata features of small molecules, in a comprehensive framework to better ensure the application of all FAIR (Findable, Accessible, Interoperable, Reusable) principles to manage scientific data.  This project focuses on addressing a critical issue of chemical ambiguity that arises when a single, non-systematic chemical identifier is linked to multiple systematic identifiers. In addition, the most widely used systematic representations have deficiencies, such as clear differentiation of an enantiomeric mixture, or an unknown configuration, or relative vs absolute configuration of two or more stereocenters.  Chemical structure ambiguity is not just a legacy problem in the context of historical data, but it remains a pervasive issue were errors propagate through public data sources while, in addition, new errors are introduced.  

This grant is managed by multiple principal investigators—each with a well-defined and complementary area of expertise. The Schürer group (University of Miami, PI Dr. Stephan Schürer) and Collaborative Drug Discovery (CDD, PI Dr. Barry Bunin).

## Project Purpose
In the era of AI-driven drug discovery, high-quality data is the primary bottleneck. AutoMID acts as a deterministic "chemical guardrail," ensuring that chemical entities utilized in biological assays are accurately represented and correctly disambiguated before downstream analysis.

## Key Methodology
Our approach leverages a structured transformation hierarchy:
- Standardization (S0 - S3): Canonicalization, desalting, and charge neutralization.
- Abstraction (S4 - S8): Progressive removal of structural complexity (tautomers, isotopes, stereochemistry, bond/atom connectivity) to uncover underlying structural identities and register errors.

## Dataset & Curation
This repository contains the logic and schema (SAME DB) used to analyze 2.4 million chemical records. The project serves as a longitudinal benchmark for assessing chemical data integrity within public aggregators like ChEMBL, Drug Central, and Probes and Drugs.

## Citation
If you use the AutoMID framework or logic in your research, please cite our manuscript:

## License
[Insert License, e.g., MIT License]
