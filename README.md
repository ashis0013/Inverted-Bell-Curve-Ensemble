# Inverted-Bell-Curve-Ensemble
An ensemble of transfer learned model using a novel weighted average scheme using inverted bell curves. This is a research project published on Neural Computing and Applications, Springer. The paper is open access so you can read it online <a href="https://doi.org/10.1007/s00521-021-06737-6">here</a>.  If you find this useful consider us citing at
```
@article{paul2022inverted,
  title={Inverted bell-curve-based ensemble of deep learning models for detection of COVID-19 from chest X-rays},
  author={Paul, Ashis and Basu, Arpan and Mahmud, Mufti and Kaiser, M Shamim and Sarkar, Ram},
  journal={Neural Computing and Applications},
  pages={1--15},
  year={2022},
  publisher={Springer}
}
```

### Abstract
Novel Coronavirus 2019 disease or COVID-19 is a viral disease caused by severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2). The use of chest X-rays (CXRs) has become an important practice to assist in the diagnosis of COVID-19 as they can be used to detect the abnormalities developed in the infected patients’ lungs. With the fast spread of the disease, many researchers across the world are striving to use several deep learning-based systems to identify the COVID-19 from such CXR images. To this end, we propose an inverted bell-curve-based ensemble of deep learning models for the detection of COVID-19 from CXR images. We first use a selection of models pretrained on ImageNet dataset and use the concept of transfer learning to retrain them with CXR datasets. Then the trained models are combined with the proposed inverted bell curve weighted ensemble method, where the output of each classifier is assigned a weight, and the final prediction is done by performing a weighted average of those outputs. We evaluate the proposed method on two publicly available datasets: the COVID-19 Radiography Database and the IEEE COVID Chest X-ray Dataset. The accuracy, F1 score and the AUC ROC achieved by the proposed method are 99.66%, 99.75% and 99.99%, respectively, in the first dataset, and, 99.84%, 99.81% and 99.99%, respectively, in the other dataset. Experimental results ensure that the use of transfer learning-based models and their combination using the proposed ensemble method result in improved predictions of COVID-19 in CXRs.
