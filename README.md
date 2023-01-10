# Use cancer Dataset to Undestand Machine Learning Models

Breast Cancer is a very good dataset which contains only numerical well-distributed data and it's a classical binary prediction dataset. The target variable is 'Diagnosis',  which says if the cancer is M = malignant or B = benign. 
I use this Dataset to research LIME and SHAP libraries (or methods).
After taking and reserching some patient's cells model and data scientist should be able not only predict, but also explain why it gives this prediction. 

LIME and SHAP are great tools, but not the only ones. Firstly, ML engineer can find out the most important features using model's attributes. For understanding model, it is also possible to use built-in Scikit-learn methods such as: permutation_importance or SelectKBest. And in this case they not only explain models, but significantly improve performance! And, finally, library InterpretML is a very good tool which not uses models as a black box and interpretes them from inside.
