# Collision-Severity-Accidents
To predict the accident serverity with ML algos.

Accidents in traffic lead to associated fatalities and economic losses every year worldwide and thus is an area of primary concern to Society from loss prevention point of view. Modelling accident severity prediction and improving the model are critical to the effective performance of road traffic systems for improved safety. 

In accident severity modelling, the input vectors are the characteristics of the accident, such as driver behaviour and attributes of vehicle, highway and environment characteristics while the output vector is the corresponding class of accident severity.  

There are two main engineering approaches for dealing with traffic safety problems: 
the reactive approach and the proactive approach. The reactive approach, or retrofit approach, consists of making the necessary improvements to variable, for instance, taking necessary actions at idenetified hazardous sites in order to reduce collision frequency and severity at these sites. 
The proactive approach, on the other hand, includes a collision prevention approach, like, preventing a potential unsafe road conditions from occurring in the first place. 

We focus on proactive approach which involves prediction of accident severity and working backwards, the concerned entity implements appropriate preventive measures to improve road safety. By recognizing the key factors that influence accident severity, the solution may be of great utility to various Government Departments/Authorities like Police, R&B and Transport from public policy point of view. The results of analysis and modelling can be used by these Departments to take appropriate measures to reduce accident impact and thereby improve traffic safety. It is also useful to the Insurers in terms of reduced claims and better underwriting as well as rate making. 

Accuracy I got with:
1. Decision Tree_entropy : 90.46
2. XGBoost : 90.42
3. Logistic Regression : 89.92
4. Decision Tree_Gini : 89.88
5. Random Forest : 89.81
