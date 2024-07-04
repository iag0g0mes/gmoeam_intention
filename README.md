# Interaction-aware Maneuver Intention Prediction using Gated Mixture-of-Experts Attention Mechanism

Created by Iago Pachêco Gomes at USP - ICMC, University of São Paulo - Institute of Mathematics and Computer Science

**(published in 26th IEEE International Conference on Intelligent Transportation Systems - ITSC 2023)**

**(we will finish to update the repository soon!! sorry for the delay!)**

## Introduction

This repository contains the implementation of the models proposed and evaluated in the article "Interaction-aware Maneuver Intention Prediction using Gated Mixture-of-Experts Attention Mechanism". 


## Abstract

This paper addresses the task of predicting the behavior of traffic participants, which involves complexities such as road geometry and agent interactions. To overcome these challenges, this paper presents a novel framework called AIMP (Attention-based Interaction-aware Maneuver Prediction). AIMP utilizes interaction graphs to extract intricate interaction features from traffic scenes. The framework incorporates a Gated Mixture-of-Experts Attention Mechanism, which combines information from road geometry, interaction patterns, and motion dynamics. This fusion process also considers prior maneuver intention estimations, enhancing both explainability and informativeness. Experimental results highlight a performance enhancement (approximately 2% ~ 9% of accuracy) of the proposed AIMP framework compared to alternative fusion methods.


## System Architecture

![Alt System Architecture](/images/model.png)

## License

Apache License 2.0

## Citation
``` 
@article{gomes2023gmoeam,
  title={Interaction-aware Maneuver Intention Prediction using Gated Mixture-of-Experts Attention Mechanism},
  author={Gomes, Iago Pach{\^e}co and Wolf, Cristiano Premebida, Denis Fernando},
  year={2023}
}
```

## Usage

### Requirements

- Python 3.8
- scikit-learn 0.23.2 (https://scikit-learn.org/stable/)
- TensorFlow 2.8.0

### Features

#### Dataset


### Training and Testing

#### Baseline


## Contact

If you find any bug or issue of the software, please contact 'iagogomes at usp dot br' or 'iago.pg00 at gmail dot com'


