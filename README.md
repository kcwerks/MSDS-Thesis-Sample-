# MSDS-Thesis-Sample-
Small sample of the work performed in my Master's thesis project for Data Science.

Nomenclature:

    CA2 - Contains notebooks that apply contrast-stretching to spectrograms (by a factor of two)

    GS - Contains notebooks that apply grayscale conversion to spectrograms

    GS_CA - Contains notebooks that apply grayscale conversion + contrast-stretching to spectrograms

    Original - Contains notebooks that do not utilize any image enhancement technique, simply the original spectrograms

    Ensemble - Contains notebooks that implement a model averaging ensemble

    NB1 - Initial preprocessing/EDA/generating Mel-spectrogram values for 1D CNN

    NB2 - 1D CNN on unaugmented training sets (RAVDESS)

    NB3 - Augmentations EDA/generating augmented Mel-spectrogram values for 1D CNN (RAVDESS)

    NB4 - 1D CNN on augmented training sets (RAVDESS)

    NB5 - Splits data for train and test, generates spectrograms and uploads to Google Drive

    NB6 - Implements feature extraction on unaugmented training sets 

    NB7 - Implements feature extraction on augmented training sets 

    NB8 - Implements fine-tuning on unaugmented training sets

    NB9 - Implements fine-tuning on augmented training sets

    NB10 - Model averaging ensembles

    TPU - Files suffixed with _TPU utilize a tensor processing unit

Notes:

    Jupyter Notebooks are currently configured to work with my personal Google Drive and Google Cloud Storage bucket. 

    If you wish to run the notebooks you will have to configure all of the path names to suit your file system, whether it be local or a Google Drive that is   mounted locally on Google Colab.

    If you wish to gain access to one of the trained models that have been saved, please contact me at kyle.p.calabro@gmail.com

    Notebooks utilizing a TPU are configured specifically to work with the TPUs available through Google Colab, if you wish to use another platform you will need to reconfigure for the specific platform
    
    It is possible to run the notebooks without the use of a TPU through the following process. Do not run the cell that initializes the TPU. Comment out the TPU strategy statements. This will allow you to utilize a CPU or GPU based runtime.
  
Datasets:

    Only the raw audio files are needed.

    RAVDESS is available at:
    https://zenodo.org/record/1188976#.Ybt5DhPMJbY

    CREMA-D is available at: 
    https://github.com/CheyneyComputerScience/CREMA-D
