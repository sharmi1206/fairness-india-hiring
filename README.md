# fairness-india-hiring
fairness constraint with Tensorflow Constrained Optimization in the context of staffing in Indian Schools

# Dataset
The dataset has been downloaded from https://www.researchconnections.org/icpsrweb/instructors/studies/36151 and has been analysed for School Staff (8). The same
can be done for Medical Staff (5).

# Jupyter Notebooks

* Fairness_m_Stochastic_Teaching_Staffs.ipynb - In this notebook, we explore the problem of classification with fairness on the [https://www.researchconnections.org/icpsrweb/instructors/studies/36151] (School Staffing -008 which can also be extended to Medical Staffing-005). We show how to set up a classification problem with data-dependent fairness constraints using the TensorFlow Constrained Optimization library and then subsequently train to optimize fairness.

* Fairness-Constraints-PRAUC-Teaching.ipynb - This notebook shows how to use the TF Constrained Optimization (TFCO) library to train a model to maximize the *Area Under the Precision-Recall Curve (PR-AUC)*, (ROC-AUC), (Precision at Recall) and (Recall at Precision). We'll show how to train the model both with (i) plain TensorFlow (in eager mode), and (ii) with a custom tf.Estimator.


* Recall-constraint-Teaching-Staffs.ipynb - In this notebook, we explore the problem of classification with fairness on the [https://www.researchconnections.org/icpsrweb/instructors/studies/36151] (School Staffing -008 that can be similarly extended to Medical Staffing-005). We show how to set up a classification problem with data-dependent fairness constraints using the TensorFlow Constrained Optimization library and then subsequently train to optimize fairness.
