# Student-Info
Matric : 270546

Name : SHARIFAH NURSAKINA EMALIN BT SYED MAHAZA

# Introduction

This is my first assignment that my lecterur give to me. In this assignment I have to a programming about calculation of car loan payment. So, in this assignment I have to calculate how much that we must pay in month. My lecterur give me the information like car price, down payment, loan period and interest rate. Using this information I have to compile this and make a simple formula to make the calculation. And before I start to make the coding calculation of car loan payment I have to write a pseudo code and flowchart. Pseudo code and flowchart are just my revision before write coding. In this assignment I have use looping. I hope this assignment can make easier to the user. 

# Pseudo code
Start

While 
	
	CarPrice < 30000 
	Output “Enter CarPrice”
	Input CarPrice 
	
While
	
	DownPayment < 0
	Output “Enter DownPayment”
	Input DownPayment
	
While 
	
	LoanPeriod < 5 or LoanPeriod > 9
	Output “Enter LoanPeriod”
	Input LoanPeriod
	
While 
	
	InterestRate < 3 or InterestRate > 7
	Output “Enter InterestRate”
	Input InterestRate
	
	
	TotalInterest = (CarPrice – DownPayment) * LoanPeriod * (InterestRate/100)
	MonthlyPayment = (CarPrice –DownPayment) + TotalInterest)/(LoanPeriod*12)
	Output MonthlyPayment
	
	Years =i+1
	Principal = MonthlyPayment * 12 * (Years)
	Interest = (CarPrice – DownPayment) * (InterestRate/100) * Years
	Balance = (MonthlyPayment * LoanPeriod * 12) – Principal
	
	Output Years, Principal, Interest, Balance
End 

# Flowchart
 






  

 
  
 
 
  
  
 




 
 
  
  
 





