# Cap2Seg: Leveraging Caption Generation for Enhanced Segmentation of COVID-19 Medical Images

![Diagram](path-to-image)

## Requirements

The code is verified with Python 3.7 and PyTorch 1.13.1 Other dependencies are listed in `requirements.txt`.

## Datasets
Download the datasets ([QaTa-COV19](https://www.kaggle.com/datasets/maedemaftouni/covid19-ct-scan-lesion-segmentation-dataset), [MosMedData+](https://www.kaggle.com/datasets/maedemaftouni/covid19-ct-scan-lesion-segmentation-dataset)), and then unzip them to your_dataset_dir.


Data paths should be as follows:

{your_dataset_dir}

├── Covid19
│ ├── Train_Folder
│ ├── Val_Folder
│ └── Test_Folder
├── MosMedData+
│ ├── Train_Folder
│ ├── Val_Folder
│ └── Test_Folder
