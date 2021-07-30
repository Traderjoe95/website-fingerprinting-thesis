# Website Fingerprinting (Master Thesis)

This repository is home to the Master Thesis of Johannes Leupold at TU Darmstadt.

The preliminary structure, together with projected page counts is listed below.

## Structure (27-29 p.)

### 1. Introduction (2 p.)

* The overall setting and relevance of WF research

### 2. Website Fingerprinting and Defenses (6 - 7 p.)

#### 2.1. Theoretical Setting (2 p.)

* Packet Traces
* Threat Model
* Defenses (deterministic, randomized, morphing)

#### 2.2. Gaussian Padding (0.5 - 1 p.)

* The definition of gaussian padding, the reason to consider it in the WF setting

#### 2.3. Related Work (3.5 - 4 p.)

* Early Attacks (Liberatore & Levine, Herrmann et al.)
* More Sophisticated Attacks (Panchenko, Dyer)
* Modern Attacks (Wang et al., Panchenko et al., Hayes & Danezis)
* Morphing Defenses (Traffic Morphing, BuFLO, Tamaraw)
* Security Bound Estimation (Cherubin)

### 3. Experimental Methodology (5 - 6 p.)

#### 3.1. A Generic Framework (1.5- 2 p.)

* Why?
* Design choices and priorities
* Library choices (scikit-learn, ...)

#### 3.2. Dataset Quality (0.5 - 1 p.)

* Poor quality of the Liberatore dataset and measures taken to improve the used data

#### 3.3. The Evaluation Pipeline (1.5 p.)

* Pipeline structure
  * Dataset
  * Defense
  * Feature Set
  * Attack (Classifier)
* Parameterization

#### 3.4. Error Bound Estimation (1.5 p.)

### 4. Results (6 p.)

#### 4.1. Performance of Gaussian Padding

* Performance against multiple attacks (as compared to no defense)
* Performance compared with uniform padding, significant difference?

#### 4.2. Security Bounds for Uniform Padding and Gaussian Padding

* Lower classifier error bounds for both padding distributions wrt. some modern feature sets

### 5. Discussion (6 p.)

### 6. Conclusion (2 p.)
