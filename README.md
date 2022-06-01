# Fault-Classification
A machine learning model to detect and classify the fault in a power system using the Electrical Fault detection and classification dataset. 
#Context
The transmission line is the most crucial part of the power system. The requirement of power and its allegiance has grown up exponentially over the modern era, and the prominent role of a transmission line is to transmit electric power from the source area to the distribution network. The electrical power system consists of so many complex dynamic and interacting elements that are always prone to disturbance or an electrical fault.
High-capacity electrical generating power plants and the grid concept, i.e., synchronized electrical power plants and geographical d displaced grids, required fault detection and operation of protection equipment in minimum possible time to remain stable. The faults on electrical power system transmission lines are supposed to be first detected and classified correctly and should be cleared in the least possible time. The protection system used for a transmission line can also initiate the other relays to protect the power system from outages. An exemplary fault detection system provides a practical, reliable, fast, and secure way of a relaying operation. The application of pattern recognition technology could help discriminate against faulty and healthy electrical power systems. It also enables us to differentiate among three phases of a three-phase power system experiencing a fault.
The artificial neural networks (ANNs) are potent in identifying the faulty pattern and classification of fault by pattern recognition. An efficient and reliable protection method should perform more than satisfactorily under various system operating conditions and different electrical network parameters. As far as ANNs are considered, they exhibit excellent normalization and generalization capability, immunity to noise, robustness, and fault tolerance. Therefore, the declaration of fault made by the ANN-based fault detection method should not be affected seriously by variations in various power system parameters.
The various electrical transient system faults are modeled, simulated, and Various ANN-based algorithms are developed to recognize these faulty patterns. The performance of the proposed algorithm is evaluated by simulating the various types of fault and the results obtained are encouraging.

#Content
We have modeled a power system in MATLAB to simulate fault analysis. The power system consists of 4 generators of 11 × 10^3 V, each pair located at each end of the transmission line. Transformers are present in between to simulate and study the various faults at the midpoint of the transmission line.
power system
We simulate the circuit under normal conditions as well as under various fault conditions. We then collect and save the measured Line Voltages and Line Currents at the output side of the power system. We collected nearly 12000 data points, and then the data is labeled.

#Acknowledgements
We wouldn't be here without the help of others.
We want to extend our gratitude to the authors of this paper for helping us out in publishing this dataset.


