# MRP
The files here contain example code from my MRP. 

Exp4 uses a COVID-19 CT scan dataset, which can be found here: https://github.com/UCSD-AI4H/COVID-CT. Exp8 uses a mammography breast cancer mass dataset, which can be found here: https://wiki.cancerimagingarchive.net/display/Public/CBIS-DDSM. 

In both experiments the computer is trying to diagnose if the patient is healthy or not from the image. For the COVID-CT dataset, this is determining if COVID-19 is present in the lungs or not. For the mammography dataset, this is determining if the mass is benign or malignant. 

The experiments were run to compare transfer learning and self supervised learning for classification on medical imaging datasets.

The cancer data exploration file explores some of the cancer data used in the cancer experiments. It also extracts the image arrays from the DICOM files and organizes and prepares the data to be sent through a neural network.
