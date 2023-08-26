# sanjesh.org-auto-fill
Auto fill from exel file to sanjesh.org

## Description

This project is designed to automate the process of filling data from an Excel file into the website "sanjesh.org." It saves time and effort by eliminating the need for manual data entry.

## Installation and Usage (Windows)

- Edge browser (you can use another browsers but you must edit line 27 of `konkur.py`)
- Install [python](https://www.python.org/) (and pip)
- with pip install [selenium](https://pypi.org/project/selenium/) : `pip install selenium` and [openpyxl](https://pypi.org/project/openpyxl/) : `pip install openpyxl`
- provide an Excel file and enter the University codes in each row of column A, from A1 to A150, in sequential order.
- download `konkur.py` file and provide your Excel file path on line 12, as well as your Excel sheet name on line 17.
- Run konkur.py : `python konkur.py`
