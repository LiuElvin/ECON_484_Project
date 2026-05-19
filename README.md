# ECON_484_Project

## Merge Using Family Data Added Sequentially To CrossYear Individual Data (https://psidonline.isr.umich.edu/Guide/FileStructure.pdf)

We always need variables `ER30001` and `ER30002` (family Interview Number and Person Number respectively).

Suppose we are only interested in years 1999 to 2023. To merge using family data:

Simply run starter_code with the J361958.xlsx file. Alternatively, if you want to acquire the files yourself:

1. Go to https://psidonline.isr.umich.edu/default.aspx
2. Click Data -> Data Center -> Variable List
3. Copy-paste the below into the box:

```
ER30001 ER30002
```

Also copy-paste your year variables into the box (dependent on which years you are interested in):

```
ER13002 ER33501
ER17002 ER33601
ER21002 ER33701
ER25002 ER33801
ER36002 ER33901
ER002 ER34001
ER47302 ER34101
ER53002 ER301
ER60002 ER34301
ER66002 ER34501
ER72002 ER34701
ER78002 ER34901
ER82002 ER35101
```

These can be found on page 3 of https://psidonline.isr.umich.edu/Guide/FileStructure.pdf. 

4. Click Add Variables -> Cart -> Checkout

Note that before you click Submit, it is probably best to toggle Microsoft Excel Spreadsheet for the Data Output Type.

5. Click Submit
6. Download the .xlsx file
7. Run starter_code
