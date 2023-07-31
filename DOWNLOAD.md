Dataset **Apple orchard field MOTS** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/X/H/kW/IMETab09TudO6UvFGIJNlHprTAnwD9PtqMn6uBnmrdZaF5ufxKDyX7WhI6L33tP5DWmH2F8rwIuBVggjcvvnObF1OSBTMj3tig18uj02nQcqMu3fGqRjZ4OIpyuo.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Apple orchard field MOTS', dst_path='~/dtools/datasets/Apple orchard field MOTS.tar')
```
The data in original format can be 🔗[downloaded here](https://zenodo.org/record/5939726/files/APPLE_MOTS.zip?download=1)