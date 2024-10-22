# COADAPTIVE BCI BASED ON BACKWARD OPTIMAL TRANSPORT FOR DOMAIN ADAPTATION
<p align="center">
<img src="Images/transport_samples.jpeg" width="600">
</p>
You will find here Python notebook demos ([Colab](https://colab.research.google.com) notebooks) that would show you how the backward formulation of optimal transport for domain adaptation ([BODTA](https://github.com/vpeterson/otda-mibci)) can be used to build MI-BCI co-adaptive systems, where adaptation from a new session to an old one can be adressed without classifier retraining while at the same time, the MI-BCI users skills can be measured in real-time.

Demos were made to show and reproduce the experiments performed in simulated data in "Towards subject-centered co-adaptive BCIs based on backward optimal transport", by Victoria Peterson, Catalina Galván, Valeria Spagnolo, Nicolás Nieto, Ruben D. Spies and Diego H. Milone. 

The demos use artificially generated data, following [PySimMIBCI](https://github.com/catalinamagalvan/PySimMIBCI) pipeline. The completed set of generated sessions can be found in [Zenodo](https://zenodo.org/records/13760210).

Three notebook examples are provided. The first two show that the following assumptions are held:

Backward adaptation based on the system knowledge is successful if 
A1) the provided EEG patterns are discriminative and aligned to the indicated mental task, and
A2) the source data, where the classifier is trained, define a discriminative space.

From where the following main hypothesis stands

H)	``In supervised online adaptation based on BOTDA, the associated cost of transporting a testing trial to match the calibration data distribution reflects the MI user self-regulation capability.''

#---- RUNNING THE NOTEBOOK --- 

Notebook are written to be easily run in Colab. In order to run the notebooks, you should follow these simple steps:

1. Make a copy of the used data folder into your Drive. Click [here](https://drive.google.com/drive/folders/1fk8wIGDzArMl61fpPCJElyEbVRXbQjpW?usp=drive_link) to download the folder.
2. In GitHub, go to a given notebook. Click the "Open in Colab" button on the top of the file.
3. Make a local copy of the notebook.
4. Run the notebook.


##### And you are ready. Happy coding!

