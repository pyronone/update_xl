# update_xl




> For when Excel is used as a database

This package simplifies the process of updating Excel “databases” - a
common use case for many organizations. Despite Excel not being a true
database management system, it is widely used as such due to its
accessibility and familiarity.

This package provides a set of features to make updating Excel data
effortless and reliable. Key features include:

1.  Update a subset of data in an Excel file without overwriting the
    rest of the information. The package handles blank cells in the
    update file, ensuring that existing data is not unintentionally
    erased.
2.  Comprehensive validation checks to ensure data integrity.
3.  Ability to append to, instead of overwrite, existing data such as
    existing notes in a comment column.
4.  Preserve existing notes and formatting.
5.  Creates a changelog showing exactly what was updated.

## Summarized Steps

1.  Create a workbook with two sheets containing the original data and
    the update data.
2.  Run `core.main`
3.  Paste result into original data file (either manually or w/ VBA)

A step-by-step example can be found in `03_example` in the
[documentation](https://pyronone.github.io/update_xl/example.html).

## Demo

<iframe src="https://drive.google.com/file/d/1m9J4fy5mR-3IRWTVV9TvjPGJ80dDkqh3/preview?vq=large" width="640" height="480" allow="fullscreen">
</iframe>
