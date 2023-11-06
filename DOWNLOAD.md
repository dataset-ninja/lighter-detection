Dataset **Non-Metal Lighter Target Detection Under X-Ray** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/M/P/EP/TaNBEOnj3J0fUE2dn0QCuPBWUwV3ZrBVgMo6l4frLU5V0fBsMIN6ubkhAUsW69NKkkhtUTbWPimsCEenjItxSJMuYI0h9x8uc3x8efsbWPNQ7wWiuEd8NREhlroo.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Non-Metal Lighter Target Detection Under X-Ray', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/voler2333/lighter-detection-under-xray/download?datasetVersionNumber=1).