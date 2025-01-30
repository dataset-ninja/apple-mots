Dataset **Apple MOTS** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzE1NTlfQXBwbGUgTU9UUy9hcHBsZS1tb3RzLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogIm1FNnZtRXp4MUh0T29FL29IbDFTT05XYk5PalJiUVdtbHlVaWtmeWlIcDQ9In0=)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Apple MOTS', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://zenodo.org/record/5939726/files/APPLE_MOTS.zip?download=1).