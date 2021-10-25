# GroverPhysics

## Using Grover's Algorithm to solve problems in physics

### Overview: What is Grover's Algorithm?

According to Wikipedia, Grover's Algorithm "...a quantum algorithm for unstructured search that finds with high probability the unique input to a black box function that produces a particular output value..." One unique aspect of Grover's Algorithm is that it only takes order of square root of N evaluations to find the input with high probability. Broadly speaking, Grover's Algorithm is a search algorithm that can be used to find a specific input for a specific output in relatively few evaluations. 

More information and links to other resources are presented in GroverInfo.txt

Some useful links: https://en.wikipedia.org/wiki/Grover%27s_algorithm \\
                   https://qiskit.org/textbook/ch-algorithms/grover.html \\
                   https://quantum-computing.ibm.com/composer/docs/iqx/guide/grovers-algorithm \\
                   https://www.quantum-inspire.com/kbase/grover-algorithm/
                   
### Jupyter Notebook

GroverAlg.ipynb is our Grover's Algorithm Jupyter Notebook implementation that discusses and creates a one and three iteration amplifier. Here the background, implementation, and results of the circuit are discussed, as well as some potential further reading. Be sure to include your own API key in the IBMQ.save_account argument for this notebook to run correctly.

### Presentation

Included is Grover.ppt, a powerpoint presentation used in our video presentation titled Grover.vlc on Grover's Algorithm. This is the culmination of this project on Grover's Algorithm in which we go into more depth on the topic. The script for the video can be found in GroverScript.pdf.
