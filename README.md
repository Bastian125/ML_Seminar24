# ML_Seminar24

Code and report of the Machine Learning Seminar for physicists at TU Dortmund in 2024.

---

Brain tumours are growths of cells in the brain that multiply abnormally. They can
be classified as benign (non-cancerous) or malignant (cancerous). The detection of
tumors especially malignant ones is crucial for doctors. Machine learning can be used
as a supplementary tool for medical diagnosis. Four machine learning models will be
trained on a labelled dataset of 3762 magnetic resonance imaging (MRI) scans with 13
tumour features derived from the images. The performances for training on the MRI
scan images and training on the tumour features will be compared to evaluate how much
performance is lost by skipping the feature derivation and directly taking the MRI scans
as input. The highest accuracy of 98.01 % for training on the features was achieved
by a Support Vector Machine (SVM), and the highest accuracy of 96.94 % for training
directly on the images was achieved by a Convolutional Neural Network (CNN). The
accuracy difference is notable, which is a sign of future areas of improvement that will
be discussed.

--

The **[dataset](https://www.kaggle.com/datasets/jakeshbohaju/brain-tumor)** was published by Jakesh Bohaju under the **[CC BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/)**. The coding was carried out in the 'Project.ipynb' jupyter notebook. The report can be read in the 'Report.pdf' file.
