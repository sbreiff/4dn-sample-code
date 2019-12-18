# 4dn-sample-code

This repository contains sample code for working with 4DN data locally.

Our library dcicutils is required. This can be installed via pip with:

```console
pip install dcicutils
```

Use of a virtual environment is recommended.

----------

### Notebook Contents

**Downloading 4DN Contact Matrices.ipynb**

Iterates through 4DN biosources and for each biosource, looks for experiment sets from a list of assays,
and downloads contact matrices from those experiment sets if found.
