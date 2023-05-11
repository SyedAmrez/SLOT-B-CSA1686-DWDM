1.   Evaluating Accuracy of the classifier in WEKA using “germen credit” dataset.      
•	Logistic regression     
•	Navie bayes algorithm     
•	J48 algorithm     

2. Implement using WEKA for the given Apply Apriori Algorithm for given database below Assume Min_sup=2  	      

TID	     Items    
1	      Bread, Peanuts, Milk, Fruit, Jam   
2	      Bread, Jam, Soda, Chips, Milk, Fruit    
3	      Steak, Jam, Soda, Chips, Bread   
4	      Jam, Soda, Peanuts, Milk, Fruit    
5	      Jam, Soda, Chips, Milk, Bread    
6	      Fruit, Soda, Chips, Milk   
7	      Fruit, Soda, Peanuts, Milk   
8	      Fruit, Peanuts, Cheese, Yogurt  

Created Arff file :      
@relation buying_components   
@attribute bread {TRUE,FALSE}    
@attribute peanuts {TRUE,FALSE}      
@attribute milk {TRUE,FALSE}     
@attribute fruit {TRUE,FALSE}    
@attribute jam {TRUE,FALSE}      
@attribute soda {TRUE,FALSE}     
@attribute chips {TRUE,FALSE}     
@attribute cheese {TRUE,FALSE}    
@attribute yougat {TRUE,FALSE}    
@attribute steak {TRUE,FALSE}     
@data        
TRUE,TRUE,TRUE,TRUE,TRUE,FALSE,FALSE,FALSE,FALSE,FALSE    
TRUE,FALSE,TRUE,TRUE,TRUE,TRUE,TRUE,FALSE,FALSE,FALSE      
TRUE,FALSE,FALSE,FALSE,TRUE,TRUE,TRUE,FALSE,FALSE,TRUE    
FALSE,TRUE,TRUE,TRUE,TRUE,TRUE,FALSE,FALSE,FALSE,FALSE    
TRUE,FALSE,TRUE,FALSE,TRUE,TRUE,TRUE,FALSE,FALSE,FALSE    
FALSE,FALSE,TRUE,TRUE,FALSE,TRUE,TRUE,FALSE,FALSE,FALSE     
FALSE,TRUE,TRUE,TRUE,FALSE,TRUE,FALSE,FALSE,FALSE,FALSE      
FALSE,,TRUE,FALSE,TRUE,FALSE,FALSE,FALSE,TRUE,TRUE,FALSE     

3. Implement using WEKA for the given Suppose a database has five transactions. Let min sup= 50%(2) and min con f = 80%.     
	Transactions		Items     
	T1		(M, O, N, K, E, Y)    
	T2		(D, O, N, K, E, Y)    
	T3 		(M, A, K, E)   
	T4		(M, U, C, K, Y)     
	T5		(C,O, O, K, I ,E)     
•	Find all frequent item sets using Apriori algorithm      
•	Also draw FP-Growth Tree     

Created Arff file:     
@relation temp     
@attribute M {TRUE,FALSE}    
@attribute O {TRUE,FALSE}    
@attribute N {TRUE,FALSE}    
@attribute K {TRUE,FALSE}    
@attribute E {TRUE,FALSE}    
@attribute Y {TRUE,FALSE}   
@attribute D {TRUE,FALSE}    
@attribute A {TRUE,FALSE}     
@attribute U {TRUE,FALSE}    
@attribute C {TRUE,FALSE}    
@attribute I {TRUE,FALSE}    
@data    
TRUE,TRUE,TRUE,TRUE,TRUE,TRUE,FALSE,FALSE,FALSE,FALSE,FALSE    
FALSE,TRUE,TRUE,TRUE,TRUE,TRUE,TRUE,FALSE,FALSE,FALSE,FALSE      
TRUE,FALSE,FALSE,TRUE,TRUE,FALSE,FALSE,TRUE,FALSE,FALSE,FALSE     

4. Prediction of Categorical Data using Decision Tree Algorithm through WEKA using any datasets.   
 a) Tree     
 b) Preprocess     
 c) Logistic     
