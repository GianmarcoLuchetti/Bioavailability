# Bioavailability

Bioavailability is one of the most important pharmacological parameters to be considered in the dis vilution process of a new drug. This parameter represents to us the percent of administered drug that we actually find in the bloodstream after the absorption process. Its evaluation therefore allows us to assess several aspects, such as the efficacy and safety of an administration.

This value is generally difficult to predict, as it is related to many variables, both chemical related to the molecule, but also related to physiological processes in the body and possible pathological changes in the tissues. This project is intended to be an example of how new technologies related to data science and machine learning can be used in the pharmaceutical development process, providing probabilistic predictions in order to reduce the time and cost of work.

## Dataset
In the work, data were used from two publications [1], [2] which represent the bioavailability of orally administered molecules. From these samples, molecular descriptors were calculated and used as features, and classes were assigned based on bioavailability ranges so that this was a classification problem:
- Class 0 --> bioavailability <= 35%;
- Class 1 --> bioavailability > 35% and <= 70%;
- Class 2 --> bioavailability > 70%;

The two datasets were eventually merged to increase the number of samples available for subsequent prediction steps, distinguishing between a training set and a test set.

## Bioavailability_prediction
In this notebook, some features of our dataset were first analyzed using data analysis techniques. Then an evaluation was made of the ability of some algorithms to predict bioavailability classes as a function of features.

## Reference
[1] Tingjun Hou, Junmei Wang, Wei Zhang, Xiaojie Xu, ADME evaluation in drug discovery. 6. If the oral bioavailability in human can be effectively predicted by simple molecular properties-based rules? Journal of Chemical Information and Modeling, 2007, 47, 460-463

[2] Min Wei, Xudong Zhang, Xiaolin Pan, Bo Wang, Changge Ji, Yifei Qi, and John Z.H. Zhang. HobPre: accurate prediction of human oral bioavailability for small molecules
