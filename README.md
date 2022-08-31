# lcsc-kicad

KiCad library containting LCSC parts

## Adding Parts

A [`poetry`](https://python-poetry.org/) environment is provided containing [`easyeda2kicad`](https://pypi.org/project/easyeda2kicad/).

Add a part with
```
easyeda2kicad --full --overwrite --output ./lcsc --lcsc_id Cxxxxx
```