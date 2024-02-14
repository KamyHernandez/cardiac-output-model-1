# cardiac-output-model
This repository aims to model the prediction of cardiac output from acquired data from MIMIC-IV v.2 database. This mainly follows the Windkessel model developed and studied by several researchers who aimed to implement similar methods and variations of this thermodynamics theory for human blood flow. Cardiac output is crucial for determining the demands of tissue oxygen that meets human body’s heart demands, and it is often measured with Swan-Ganz catheters, which represents a risk in 10% of the cases for patients in clinical and ICU scenarios. The databases, contemplated in this research are compared in order to proceed with the most suitable implementation. These are as follows: The MIMIC II Clinical Database, MGH/MF Waveform Database and the Hemodynamics and Respiratory Pattern Dataset. The latter was selected for this work which contained 170 records with cardiac output values, which worked as ground truths for the prediction model. Therefore, algorithms such as XGBoost vector regression, decision trees, and random forest are implemented to forecast cardiac output based on the thermodilution theory in this research use case.

![image](https://github.com/kamilah2520/cardiac-output-model/assets/72052638/4fc16d72-290f-4889-9b30-b9e6d8ae8d27)
