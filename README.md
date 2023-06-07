# DOMAIN ADAPTATION BASED ON OPTIMAL TRANSPORT FOR MI-BCI
<p align="center">
<img src="Images/OTDA_workflow.png" width="600">
</p>
You will find here Python notebook demos ([Colab](https://colab.research.google.com/) notebooks) that would show you how the backward formulation of optimal transport for domain adaptation ([BODTA](https://github.com/vpeterson)) can be used to improve movement decoding. 

The demos uses artificially generated data, following [PySimMIBCI](https://github.com/catalinamagalvan/PySimMIBCI) pipeline. This proyect is a follow up of our previous publicaction: "Transfer Learning based on Optimal Transport for Motor Imagery Brain-Computer Interfaces", by Victoria Peterson, Nicolás Nieto, Dominik Wyser, Olivier Lambercy, Roger Gassert, Diego H. Milone and Ruben D. Spies

Three notebook examples are provided, each one testing one of the following hypothesis:

H1) The task is performed correctly (no failed trials) regardless of ERD
H2) The EEG patterns provided by the user correspond to the mental task to be performed
H3) The calibration data, used to train the decoding model, contains discriminable ERD patterns
##### And you are ready. Happy coding!

