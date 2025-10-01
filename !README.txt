Operational Guide – Foundations of Deep Learning Project
Authors: Chiara Genuardi and Giovanni Noè
Course: Foundations of Deep Learning – University of Milan-Bicocca

This guide provides the steps required to ensure reproducibility of the Foundations of Deep Learning Project developed by Chiara Genuardi and Giovanni Noè for the Foundations of Deep Learning course at the University of Milan-Bicocca.

Note: The project was developed on Google Colab using Google Drive as cloud storage. For this reason, we recommend uploading the entire project directory to MyDrive on Google Drive. This step is necessary if you wish to execute the code without modifying file paths for data loading and saving.

-------------------------------------------------------------------
Project Directory Structure

The project directory contains the following files and folders:

- download.zip – the EMO-DB dataset
- audio.zip – the audio files we recorded for testing
- Classification of Emotions using Emo-DB.pdf – the project report (not required, but included for completeness)
- FDL_project_presentation.pdf – the project presentation slides
- FDL_project_developement.ipynb – Jupyter notebook covering the full project pipeline (data acquisition to model evaluation)
- FDL_project_developement_with_saved_weights.ipynb – same as above, but models are not retrained (weights are loaded)
- FDL_project_test.ipynb – notebook for testing the final model on our custom audio files
- FDL_project_test_with_saved_weights.ipynb – same as above, but models are not retrained (weights are loaded)
- ModelsWeights/ – directory containing pretrained model weights
  - If compressed, unzip before use.
  - If provided as a link, place the folder in the same directory as the other project files.

-------------------------------------------------------------------
How to Reproduce the Project

Reproducing this project is straightforward:

1. Upload the project folder to MyDrive in Google Drive.
2. Unzip (or place) the ModelsWeights/ directory in the project folder.
3. Open the .ipynb notebooks in Google Colab.
4. Run the notebooks:
   - To reproduce the exact results described in the report and presentation, execute the _with_saved_weights versions.
   - These versions are also significantly faster since model training (fitting) is skipped.

