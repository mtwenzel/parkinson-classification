# Parkinson SPECT classification
Classifying SPECT scans of Parkinson's Disease which are available from the [PPMI repository](https://www.ppmi-info.org/access-data-specimens/download-data/). You can open the notebook file in Goolge Colab directly from here:

[<img src="https://colab.research.google.com/assets/colab-badge.svg">](https://colab.research.google.com/github/mtwenzel/parkinson-classification/blob/master/PPMI-InceptionV3.ipynb)

Note that due to the Colab markup, the notebook does not properly display in GitHub.

## License
Licensed under [this](LICENSE) license.

## Details
This notebook shows how we performed the experiment to fine-tune the Inception V3 classifier to distinguish patients with and without signs of Parkinson's disease.

The notebook is optimized to work with Google Colab. It hides all code by default so that you can run it sequentially from top to bottom. If you want to see the implementation, just double-click into any cell, and it will open in a side-by-side view.

This code is part of the publication 
> Publication reference and [link](dummy-link-not-working-yet) to be inserted after publishing.

The data are a derivative of the DAT scans available from the [PPMI repository](https://www.ppmi-info.org/access-data-specimens/download-data/). They were processed to represent the central 5 slices of the putamen in one slice by averaging them. For details, please refer to the paper.

The data was then split randomly into a training and a validation set. As we tested the performance on an independant test set drawn from clinical routine which cannot be published, this notebook does not contain testing of the trained classifier.

The data as used in the publication can be downloaded here:

If you want to run the notebook from Google Colab, put the data into your Google Drive, and adapt the path below in the respective cell.

## Usage
It is adviced to copy the Colab notebook to your own Google Drive before connecting to a runtime an running the code, though it is not strictly required. Note, however, that if you don't copy it, any changes you make, and also all results, will be discarded when you close the notebook.

To run the Colab notebook, you need to download the data zip file, and unpack it into your Google Drive. Then, after running the cell that connects to your Google Drive, right click the folder "PPMI-classification" and copy the path. You will need to enter it in the subsequent cell, replacing the predefined location.

