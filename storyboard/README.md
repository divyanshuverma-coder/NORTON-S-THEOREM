## Storyboard (Round 2)

Experiment 1:To Verify Norton's Theorem in DC Circuit.

### 1. Story Outline:

 The basic idea of this experiment is to solve the value of load current in complex electric circuit
     using Norton's Theorem. This experiment will consists of DC supply, resistor, ammeter and voltmeter.
	 This experiment will also give an idea about Norton's equivalent resistance (R<sub>N</sub>) and Norton's equivalent 
	 current (I<sub>N</sub>). Based on the information of R<sub>N</sub> and I<sub>N</sub>, the value of  load current (I<sub>L</sub>) will be calculated 
		using Norton's equivalent circuit.
### 2. Story:
In electrical engineering , the most important parameter is to calculate the value of electric current
     in the load. It is easy to calculate current in simple electric circuit by using KVL and KCL. However, it is very 
	 difficult to calculate current in complex electric circuit using KVL/KCL. It refer's, suitable theorem
	 or technique is required to address this issue.<br> Norton's theorem is one of the best suitable option to 
	 calculate  current in complex electric current.<br><br>
	 Norton's Theorem  states that " Any active linear bilateral complex network can be converted into a
     single current source equivalent in which Norton's  equivalent current (I<sub>N</sub>) is connected in parallel 
	 with parallel combination of Norton's equivalent resistance (R<sub>N</sub>) and load resistance (R<sub>L</sub>)."The Norton's equivalent circuit  of any complex circuit can be converted  into single current source 
     equivalent as shown in figure 1.</br>
     ![A test image](https://github.com/divyanshuverma-coder/NORTON-S-THEOREM/blob/master/storyboard/circuit%202.jpg)
     <p align="center">Figure 1</p>
   Norton's equivalent circuit <br> In order to make Norton's equivalent circuit, it is essential to understand the  calculation of Norton's
			  equivalent resistance ( R<sub>N</sub> ) and Norton's equivalent current ( I<sub>N</sub> ). Stepwise calculation of ( R<sub>N</sub> ) and ( I<sub>N</sub> ) are as follows :<br><br> 
			  Steps for Norton's Equivalent Resistance ( R<sub>N</sub> ) <br>
			  1. Open the terminals of load.<br>
			  2. Short circuit the voltage source and open circuit the current source. <br>
			  3. calculate the equivalent resistance from the open end load terminals. This will be Norton's 
			     equivalent resistance ( R<sub>N</sub> ).<br><br>
			Steps for Norton's Equivalent Current ( I<sub>N</sub> ) <br>
			  1. Short circuit the load terminals.<br>
			  2. calculate this short circuit current. This will be Norton's equivalent current (I<sub>N</sub>).<br><br>
			  Steps for Load current ( I<sub>L</sub> ) <br>
			  1. Construct Norton's equivalent circuit by connecting R<sub>N</sub>, I<sub>N</sub> and R<sub>L</sub> are in parallel
Figure<br>
![A test image](https://github.com/divyanshuverma-coder/NORTON-S-THEOREM/blob/master/storyboard/circuit%202.jpg)
			   <p align="center">Figure 1.1</p>
			  2. Calculate load current by current division rule:
			  <br>
			  <p align="center">
  I<sub>L</sub> = R<sub>N</sub>/(R<sub>N</sub>+R<sub>L</sub>)I<sub>N</sub>
</p>
			  <br><br>
			  Further load current can also be calculated by using KCL/KVL. Finally load current 
		obtained by Norton's Theorem will be compared with KCL/KVL.<br>

#### 2.1 Set the Visual Stage Description:
 On screen, there is button namely 'start simulator' button. Before this button, question of the task will be displayed. Then one MCQ which is having various electrical components. Further there are options displaying on the screen where student will select the correct option. Then other window will appear name as result window where Norton's equivalent circuit will display and two blank boxes for R<sub>N</sub> and I<sub>N</sub> values are inserted by the student. At the bottom side of the screen, 'submit' button is placed. When student will click on this button, result window will appear. In this window, two blank boxes for I<sub>L</sub> and percentage error will be shown where student will submit the value of I<sub>L</sub> and percentage error in these boxes. At the bottom of this window, 'calculate I<sub>N</sub>' button and'calculate error' button is placed. where student will click on these buttons,the correct value of I<sub>L</sub> and percentage error will display in the result window.


#### 2.2 Set User Objectives & Goals:<br>
1. This experiment provides the principle of Norton's Theorem in DC circuits.<br>
2. This experiment also give the information of circuit components ( Resistance, Ammeter, Voltmeter).<br>
3. Based on the experiment, user can also calculate Norton's equivalent resistance, Norton's equivalent current and load current.<br>
4. User can also understand the calculation of percentage error.<br>

#### 2.3 Set the Pathway Activities:
1. Click on start button.<br>
2. Click on simulator button.<br>
3. Complete the task by answering the questions.<br>
4. Identify the circuit and select correct option accordingly.<br>
5. Insert the values of circuit components.<br>
6. Student will calculate the value of R<sub>N</sub> and I<sub>N</sub> manually and insert into the given boxes.<br>
7. Result window will appear to insure whether the nature of R<sub>N</sub> and I<sub>N</sub> is correct or not.<br>
8. Further the Norton's equivalent circuit will display on the window.<br>
9. Student will click on 'submit' button.<br>
10. The result window having blank boxes of I<sub>L</sub> and percentage error will appear.<br>
11. Student will click on 'calculate I<sub>L</sub>' button and 'calculate percentage error' button.<br>
12. The correct value of I<sub>L</sub> and percentage error will display on the result window.<br>

#### 2.4 Set Challenges and Questions/Complexity/Variations in Questions:
Q.1 The algebraic sum of all current meeting at node is zero.This statement is___ .<br>
Q.2 The algebraic sum of all voltages in closed circuit is zero. This statement is __ .<br>
Q.3 Identify the symbol of resistor____,ammeter___, voltmeter_____ .<br>
Q.4 Calculate equivalent resistance of the given circuit---------<br>
![A test image](https://github.com/divyanshuverma-coder/NORTON-S-THEOREM/blob/master/storyboard/circuit%203.jpg)
 <p align="center">Figure 2.1</p>
Q.5 Calculte current in the 9 ohm resistance.------------<br>
<img src="https://github.com/divyanshuverma-coder/NORTON-S-THEOREM/blob/master/storyboard/circuit%204.jpg">
 <p align="center">Figure 2.2</p>
 If the calculated value of R<sub>N</sub> and I<sub>N</sub> is wrong then hint will appear.<br>

#### 2.5 Allow Pitfalls:
No pitfalls allow.

#### 2.6 Conclusion:
Student will get marks based on the assessment questions.


#### 2.7 Equations and Formulas:

1. Formula for Norton's Equivalent Resistance. <br>  <p align="center">
  R<sub>N</sub> = R<sub>1</sub>R<sub>2</sub>/R<sub>1</sub>+R<sub>2</sub><br>
</p>
    Where R<sub>1</sub> and R<sub>2</sub> are given resistance.<br>
 2. Formula for Norton's Equivalent Current <br> <p align="center">
	I<sub>N</sub> = V/R<sub>1</sub><br>
	Where V is value of supply voltage.<br>
</p>
3. Formula For load current (I<sub>L<sub>1</sub></sub>) using Norton's Theorem <br> For Norton,<br> <p align="center">
  I<sub>L<sub>1</sub></sub> = (R<sub>N</sub>/R<sub>N</sub>+R<sub>L</sub>)I<sub>N</sub><br>
	Where R<sub>N</sub> = Norton's Equivalent Resistance.<br>
            R<sub>L</sub> = Load Resistance.<br>
            I<sub>N</sub> = Norton's Equivalent Current.<br>
</p>
 4. Formula for load current using KCL/KVL <br> For KCL/KVL,<br> <p align="center">
 I<sub>L<sub>2</sub></sub> = (V.R<sub>2</sub>)/(R<sub>1</sub>.R<sub>2</sub>+R<sub>1</sub>.R<sub>L</sub>+R<sub>2</sub>.R<sub>L</sub>)
	</p><br>
 5. Formula for percentage error  <p align="center">
  Percentage Error =  {(|I<sub>L<sub>2</sub></sub>| -|I<sub>L<sub>1</sub></sub>|)/(|I<sub>L<sub>2</sub></sub>|)}*100<br>
</p>
