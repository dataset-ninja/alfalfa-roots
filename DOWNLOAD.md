Dataset **Alfalfa Roots** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI0NTVfQWxmYWxmYSBSb290cy9hbGZhbGZhLXJvb3RzLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogInVKQXoxUStoMUNBeGNtRHUwR3NzRitld29ORVNHSXArcjhjeitieHJzU0E9In0=)

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
