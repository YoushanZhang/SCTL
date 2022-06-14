# SCTL

This directory contains the code for paper [Separable Confident Transductive Learning for Dairy Cows Teat-End Condition Classification](https://www.mdpi.com/2076-2615/12/7/886), which is accepted by MDPI Animals.


If you have any questions, please email to yz945@cornell.edu
### Reference

If you find it is helpful, please cite it as:

`
Zhang, Youshan, Ian R. Porter, Matthias J. Wieland, and Parminder S. Basran. 2022. "Separable Confident Transductive Learning for Dairy Cows Teat-End Condition Classification" Animals 12, no. 7: 886. https://doi.org/10.3390/ani12070886.
`


Or in bibtex style:

```

@Article{ani12070886,
AUTHOR = {Zhang, Youshan and Porter, Ian R. and Wieland, Matthias J. and Basran, Parminder S.},
TITLE = {Separable Confident Transductive Learning for Dairy Cows Teat-End Condition Classification},
JOURNAL = {Animals},
VOLUME = {12},
YEAR = {2022},
NUMBER = {7},
ARTICLE-NUMBER = {886},
URL = {https://www.mdpi.com/2076-2615/12/7/886},
ISSN = {2076-2615},
DOI = {10.3390/ani12070886}
}

```

### Usage
1. Please unzip train_1.zip, train_2.zip, and test.zip. 
2. Combine train_1 (Score_1 and Score_2) and train_2 (Score 3 and Score 4) as the training dataset.
3. Train the model with the labeled training dataset and unlabeled test dataset

### Evluation
To avoid tuning the model based on the test dataset, we also provide an application to automatically evaluate the performance of your prediction.

1. You need to generate your prediction as a CSV file: [image_name, predicted labels]. We also uploaded a sample_results.csv for your reference.
2. In stall Cow_teat_classfication_accuracy.exe. You may need to install Matlab R2021b (9.11) MCR [here](https://www.mathworks.com/products/compiler/matlab-runtime.html)


<p align="center">
  <img src="./assts/cow_app.png" width="50%"> 
</p>
<p align="center">Cow Teat Classfication Accuracy software</p>

4. Run Cow_teat_classfication_accuracy software to get your prediction accuracy

   I) Click on 'Open CSV File' 
   
   II) Click on 'Calculate Accuracy'
   
   III) You will see the accuracy in the text area





