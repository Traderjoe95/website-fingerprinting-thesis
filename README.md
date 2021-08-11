# Website Fingerprinting (Master Thesis)

This repository is home to the Master Thesis of Johannes Leupold at TU Darmstadt.

The preliminary structure, together with projected page counts is listed below.

## Structure (24-27 p.)

### 1. Introduction (2 p.)

* The overall setting and relevance of WF research
* Motivation for considering Gaussian Padding

### 2. Background Material (4 - 5 p.)

#### 2.1. Theoretical Setting (2 p.)

* Packet Traces
* Threat Model
* Attacks (ML techniques)
* Countermeasures (deterministic padding, randomized padding, noise, morphing)

#### 2.2. Gaussian Padding (0.5 - 1 p.)

* The definition of gaussian padding

#### 2.3. Security Bound Estimation according to Cherubin (1 - 1.5 p)

* How are security bounds estimated? What is the rationale behind it?

#### 3. Prior Work (3 - 4 p.)

* Early Attacks (Liberatore & Levine, Herrmann et al.)
* More Sophisticated Attacks (Panchenko, Dyer)
* Modern Attacks (Wang et al., Panchenko et al., Hayes & Danezis)
* Morphing Defenses (Traffic Morphing, BuFLO, Tamaraw)
* Security Bound Estimation (Cherubin)

### 4. Experimental Methodology (5 - 6 p.)

#### 4.1. Trace Data (1 - 2 p.)

* The Liberatore dataset
* Poor quality of the Liberatore dataset
* Preprocessing steps to improve data quality

#### 4.2. Evaluating Attack Performance (2 p.)

* Pipeline structure
  * Dataset
  * Defense
  * Feature Set
  * Attack (Classifier)
* Parameterization

#### 4.3. Error Bound Estimation (2 p.)

* Pipeline structure
* Parameterization

### 5. Results (7 p.)

#### 5.1. Performance of Gaussian Padding

* Performance against multiple attacks (as compared to no defense)
* Performance compared with uniform padding, significant difference?

#### 5.2. Security Bounds for Uniform Padding and Gaussian Padding

* Lower classifier error bounds for both padding distributions wrt. some modern feature sets

### 6. Discussion (2 p.)

### 6. Conclusion (1 p.)
