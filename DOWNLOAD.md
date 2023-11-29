Dataset **Alfalfa Roots** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://www.dropbox.com/scl/fi/amygfsqwii4wc3dct0kqd/alfalfa-roots-DatasetNinja.tar?rlkey=2t34bhhxo3tgcvaqenys41j9u&dl=1)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Alfalfa Roots', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be downloaded here:

- [Alfalfa_root_ML_color_photographs.zip](https://zenodo.org/record/5879779/files/Alfalfa_root_ML_color_photographs.zip?download=1)
- [Alfalfa_root_ML_segmented.zip](https://zenodo.org/record/5879779/files/Alfalfa_root_ML_segmented.zip?download=1)
