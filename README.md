# Running

These notebooks are set up to run in a pipenv environment. Run with:

```
pipenv run jupyter lab
```

A browser window should pop up, and then run `amp-scz-prep.ipynb` before running `amp-scz.ipynb`.

## Changes to make

Download the "QC" sheet from the "U24 MRI QC" spreadsheet as ODS. Set the `MANUAL_QC_EXPORT`
variable in the first document. Also update `MRIQC_PATH` to be the location of the MRIQC results.
