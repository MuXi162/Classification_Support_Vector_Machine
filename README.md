# Classification_Support_Vector_Machine

credit_card_data.txt -> The dataset <br>
Support_Vector_Machine_Classification.RMD -> The R-markdown containing the code <br>
Support_Vecotr_Machine_Classification.HTML -> The results that can be displayed in a web browser <br>

Using the support vector machine function ksvm contained in the R package kernlab, find a good classifier for this data. Show the equation of your classifier, and how well it classifies the data points in the full data set.  (This does not provide insight for test/validation data yet; we’ll cover that topic soon.)

Notes on ksvm <br>
•	You can use scaled=TRUE to get ksvm to scale the data as part of calculating a classifier.<br>
•	The term λ we used in the SVM lesson to trade off the two components of correctness and margin is called C in ksvm.  One of the challenges of this homework is to find a value of C that works well; for many values of C, almost all predictions will be “yes” or almost all predictions will be “no”. <br>
•	ksvm does not directly return the coefficients a0 and a1…am.  
