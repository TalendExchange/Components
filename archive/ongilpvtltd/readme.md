# ongilpvtltd
  <nospam+contact@ongil.io>

## <a href='./components/Ongil Fuzzy Match/readme.md'><img src='./components/Ongil Fuzzy Match/logo.jpg' width='40' height='40'> Ongil Fuzzy Match</a>
 :warning: Compatibility not known

Ongil Fuzzy Match allows you to find duplicates in your given data by checking in multiple columns and combining the results together,thus finding duplicate rows in the data instead of just duplicate column values

## Usage

Add a tRowGenerator, the OngilSmartFuzzyMatch component and a tLogRow component to the job, and connect them.
Double click the tRowGenerator and add one column of any type.
Set the number of rows to 1. 
Click ok to propagate the schema to OngilSmartFuzzyMatch and tLogRow components.
Run the job.

## Parameters


### Input Path:
Absolute path of the input csv or excel file. [Other file formats cannot be processed currently.]

### Weights Dictionary:
A dictionary with column names as keys and their weights (positive numbers indicating relative importance) as values.  Example:
\t\t\t“{first_name:10, last_name:5, middle_name:0.5}”
Note: no quotations (“ or ‘) required inside the dictionary. The weights for all columns will be normalized before use. In this case, the weights will be 1, 0.5 and 0.05 respectively.

### Threshold:
A value between 0 and 1. Records are identified as duplicates if their similarity scores are greater than this number. We recommend that you try the default value of 0.7 before fine-tuning this parameter for better results

### Mandatory Match:
A list of column names containing those columns in which only exact matches must be considered as duplicates.  Example:
“[first_name, last_name]”
Note: no quotations (“ or ‘) required inside the array. 

### Delimiter:\t
Delimiter used in the input csv/excel file.

### Output Path:\t
Absolute path of the directory in which output files must be downloaded.
<img src='./components/Ongil Fuzzy Match/sample.jpg'>
