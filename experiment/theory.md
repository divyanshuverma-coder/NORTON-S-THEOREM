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
