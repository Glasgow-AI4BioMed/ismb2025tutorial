# ISMB Tutorial 2025: Biomedical text mining for knowledge extraction

This repository provides the materials for a conference tutorial on biomedical information extraction. The resources are most easily viewed through the web page for this. It is accessible at: https://ai4biomed.org/ismb2025tutorial/

## Running on your own machine

While this tutorial is designed to be run through Colab, you could also run it locally on your own machine. You would need to install some pre-requisites as below. There are also some cells in the notebook which run terminal commands (prefixed by '!') which may need to be done manually. These include downloading and unzipping the dataset using the URL provided at the start of each notebook.

To install pre-requisites:
```
pip install -r requirements.txt
python -m spacy download en_core_web_sm # Install the English model for spaCy
```
