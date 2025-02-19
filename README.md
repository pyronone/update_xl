# update_xl


<!-- ... -->

> For when Excel is used as a database

Despite not being best practice, many organizations/teams continue to
use Excel as a (pseudo) database due to its accessibility and
familiarity. This package simplifies the process of updating such
“databases”, providing a set of features to make data updates effortless
and reliable.

**Key features**

1.  Only needing to provide data that needs to be updated. Blank cells
    in the update file are automatically filled with the original
    values, ensuring that existing data is not unintentionally
    overwritten.
2.  Comprehensive validation checks to ensure data integrity.
3.  Ability to append to, instead of overwrite, existing data. Useful
    for ‘comment’ columns, for instance.  
4.  Ability to preserve existing notes and formatting in the original
    data file.
5.  Creates a human readable changelog showing exactly what was updated
    and when.

A video demo and step-by-step example can be found in `01_example` in
the [documentation](https://pyronone.github.io/update_xl/example.html).
