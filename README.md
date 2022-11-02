# A meta-analytical comparison of Naive Bayes and Random Forest for software defect prediction

[pre-print](https://www.researchgate.net/publication/350459831_A_meta-analytical_comparison_of_Naive_Bayes_and_Random_Forest_for_software_defect_prediction)

To use this repo, clone the repo, and run the jupyter notebook [Meta_analysis.ipynb](Meta_analysis.ipynb).

The notebook will load the data from the folder named _data_, containing a csv file. The properties of CSV file are as follows:
- Title: title of the paper
- Authors: Author names
- Year: year of publication
- Number_of_observations_for_NB: the number of experiments performed for Naive Bayes
- Number_of_observations_for_RF: the number of experiments performed for Random Forests
- Precision_NB_mean: mean value of precision for the Naive Bayes
- Precision_RF_mean: mean value of precision for the Random Forests
- Precision_NB_std: standard deviation value of precision for the Naive Bayes
- Precision_RF_std: standard deviation value of precision for the Random Forests
- Recall_NB_mean: mean value of F-measure for the Naive Bayes
- Recall_RF_mean: mean value of F-measure for the Random Forests
- Recall_NB_std: standard deviation value of F-measure for the Naive Bayes
- F-measure_RF_std: standard deviation value of F-measure for the Random Forests
- F_Measure_NB_mean: mean value of F-measure for the Naive Bayes
- F_Measure_RF_mean: mean value of F-measure for the Random Forests
- F_Measure_NB_std: standard deviation value of F-measure for the Naive Bayes
- F_Measure_RF_std: standard deviation value of F-measure for the Random Forests

After running all the cells the code will output the forest plots, and also it will save the forests plots in the folder named _forest_pdf_

PS: The code is written and tested on Google Colab, you can open the code in Colab by clicking the **Open In Colab** button and reproduce the results.
