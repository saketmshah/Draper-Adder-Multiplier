The file QCCalc.ipynb implements a version of 
Draper's algorithm for quantum ancilla-free 
addition and multiplication mod 2^d on length 
n bitstrings. 

In particular, we implement a circuit QCalc which
on qubits acts as 

Q|x>_d|y>_d|z>_1|0>_d = |x>_d|y>_d|z>_1|x+y>_d 

when z = 0 and 

Q|x>_d|y>_d|z>_1|0>_d = |x>_d|y>_d|z>_1|x*y>_d 

when z = 1. Here the subscript denotes the
number of qubits in the ket. 

For additional details about the 
implementation, please read QCCalc doc.pdf. 