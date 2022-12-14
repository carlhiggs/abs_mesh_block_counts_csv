# ABS 2021 Mesh Block dwelling counts to CSV

As of 31 August 2022, the Australian Bureau of Statistics has only released the [2021 census Mesh Block dwelling counts](https://www.abs.gov.au/census/guide-census-data/mesh-block-counts/2021) as an [Excel file](https://www.abs.gov.au/census/guide-census-data/mesh-block-counts/2021/Mesh%20Block%20Counts%2C%202021.xlsx), with data stratified across 12 worksheets.  This is inconvenient for users who wish to link this data with digital boundaries, and not useful for data posterity.  In addition to completing a feedback survey for the ABS, suggesting that a CSV download should be provided (which the Excel file itself suggests is the case in its Explanatory Notes, and was the case with the 2011 and 2016 census releases), I thought it would be useful to take the time to compile these and make them public for myself and others until an official release is produced.

Code to retrieve and process the Mesh Block count data and output it as national and State/Territory-specific CSVs is contained in the [Jupyter Notebook](https://github.com/carlhiggs/abs_mesh_block_counts_csv/blob/main/ABS%20Mesh%20Block%20counts%20to%20CSV.ipynb) in this repository.

The resulting datasets are located on RMIT FigShare at https://doi.org/10.25439/rmt.20746609 .

This has also been written up as an article on [Medium](https://medium.com/@carlhiggs/census-data-released-as-excel-files-6d22da9dc09d).

Carl Higgs
31 August 2022
