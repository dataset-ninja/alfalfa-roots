Dataset **Alfalfa Roots** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/P/2/gk/zoBdA4v4KVT5XF4bMxGWkYdpT82IggREVg3vMjqK3wI5ocf9hXgm8niObWcOjwhjn31O7t1RnCjdRWwbOFPZ1hBrtW07O8vPiTaCRpx90KYbwR2j4r8ALh1omhr3.tar)

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
