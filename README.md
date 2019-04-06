# Christopher H. Todd's Python Lib for CSV Files

The ctodd-python-lib-csv project is responsible for interacting with .csv files and .csv formatted data. This includes converting to and from .csv format, reading .csv files, writing .csv files, and other general CSV related tasks.

## Table of Contents

- [Dependencies](#dependencies)
- [Libraries](#libraries)
- [Example Scripts](#example-scripts)
- [Notes](#notes)
- [TODO](#todo)

## Dependencies

### Python Packages

-

## Libraries

### [csv_general_helpers.py](https://github.com/ChristopherHaydenTodd/ctodd-python-lib-csv/blob/pypi/csv_helpers/csv_general_helpers.py)

CSV General Helpers. This library is used to interact with .csv files not specificlly related to reading or writing them.

Functions:

```
def convert_csv_file_to_json_file(csv_filename, json_filename=None, seperator=","):
    """
    Purpose:
        Convert .csv File to .json
    Args:
        csv_filename (String): .csv file to convert to .json
        json_filename (String): filename for the resulting .json
        seperator (String): String seperator of fields in the .csv
    Return:
        json_filename (String): filename for the resulting .json
    """
```

### [csv_reading_helpers.py](https://github.com/ChristopherHaydenTodd/ctodd-python-lib-csv/blob/pypi/csv_helpers/csv_reading_helpers.py)

CSV Reading Helpers. This library is used to aid in reading with .csv files

Functions:

```
N/A
```

### [csv_writing_helpers.py](https://github.com/ChristopherHaydenTodd/ctodd-python-lib-csv/blob/pypi/csv_helpers/csv_writing_helpers.py)

CSV Writing Helpers. This library is used to aid in writing with .csv files

Functions:

```
N/A
```

## Example Scripts

Example executable Python scripts/modules for testing and interacting with the library. These show example use-cases for the libraries and can be used as templates for developing with the libraries or to use as one-off development efforts.

### N/A

## Notes

 - Relies on f-string notation, which is limited to Python3.6.  A refactor to remove these could allow for development with Python3.0.x through 3.5.x

## TODO

 - Unittest framework in place, but lacking tests
