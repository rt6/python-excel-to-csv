# python-excel-to-csv

Excel does not have a in-built feature to export as csv file with double quotes.

Formatting cells with custom format of `\“@\”` does not result in csv file that is platform independent (eg. export Excel on Windows and use csv file on Unix).

## Installation
```sh
pip install xlrd
# or 
conda install xlrd
```

## Usage
```sh
python excel_to_csv input-spreadsheet.xlsx "Sheet 1" output-csv.csv
```
