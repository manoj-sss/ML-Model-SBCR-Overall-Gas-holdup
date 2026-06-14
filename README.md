# ML-Model-SBCR-Overall-Gas-holdup
## Repository Overview

This repository contains five machine learning models, each featuring a dedicated graphical user interface (GUI). Every model is organized into its own separate folder.

### Folder Structure

Each model folder contains the following components:

* **Main GUI File:** The primary script you execute to launch the interface.
* **Trained Model:** The saved parameters that load directly into the GUI.
* **Training Limits:** The boundary data file required by the GUI for proper operation.
* **Test Data:** A sample dataset provided to verify that the code functions correctly.

### Large File Availability

Please note that the **EXT** and **AdaBoost** files exceed 25 MB in size. Due to these size constraints, these files are not included in this repository but are available upon request.

### Instructions for Running the Code

To use a model, open its specific folder and execute the main GUI file. You must keep the trained model file and the training limits file in the same directory as the main GUI file for the application to load configurations and weights successfully. Once launched, you can upload the provided test data file directly through the interface to verify the code performance.
