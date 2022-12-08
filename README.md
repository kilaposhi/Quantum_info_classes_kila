# Quantum Computing classes : Practical ⚛ 
  
---
In this repository you can find the jupyter notebooks I did for my university class about quantum computing.  
This class was a formal introduction to quantum computing. During the practical classes we learned how to use Jupyter notebook, qiskit and we tested our code on actual quantum computer of IBM. I implemented some famous quantum algorithm (Simon algorithm, Grover search...) and I wrote a rapport / commentary, it's all in french though.

Here is a preview of what you can find in this repo  

---
### The usual quantum gates and their matrix :

____
### Simon algorithm :
The [Simon problem](https://en.wikipedia.org/wiki/Simon%27s_problem) is one of the problem (with the Deutsch-Josza) that is solved more efficiently with a quantum algorithm than a classical one. It's purpose is to identify in one take the type of function of the oracle. The oracle being a blackbox function that can either be one-to-one or two-to-one. 

<p align="center"> Quantum circuit </p> 

![Quantum circuit of Simon Algorithm | 100](https://github.com/kilaposhi/IQ01_Kila/blob/main/images/Simon_circuit.png "Simon circuit")  
Result histogram          |     Verif result (counts)
:-------------------------:|:-------------------------:
![Histogram of the measures](https://github.com/kilaposhi/IQ01_Kila/blob/main/images/Simon_histo.png "Simon circuit") |  ![Verifying the result](https://github.com/kilaposhi/IQ01_Kila/blob/main/images/verif_simon.png "Simon circuit") 
