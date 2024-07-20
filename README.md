# Cap2Seg: Leveraging Caption Generation for Enhanced Segmentation of COVID-19 Medical Images

![Diagram](path-to-image)

## Requirements

The code is verified with Python 3.7 and PyTorch 1.13.1 Other dependencies are listed in `requirements.txt`.

## Datasets

Download images from [QaTa-COV19 Dataset]([link-to-coco](https://www.kaggle.com/datasets/aysendegerli/qatacov19-dataset)).
Download images from [MosMedData+ Dataset](https://www.kaggle.com/datasets/maedemaftouni/covid19-ct-scan-lesion-segmentation-dataset).

Data paths should be as follows:
.{YOUR_REFER_PATH}
├── Covid19
  ├── Train_Folder
  ├── Val_Folder
  └── Test_Folder
├── MosMedData+
  ├── Train_Folder
  ├── Val_Folder
  └── Test_Folder
