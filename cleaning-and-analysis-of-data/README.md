# Practice cleaning and analyzing datasets.
This is the folder where I took a bunch of datasets and just practiced cleaning and doing an analysis of them.

## Steps to take when cleaning data

### Fix Rows and Columns
To fix rows we do the following
- delete summary rows
- delete incorrect rows - like unnecessary header rows, or footer rows
- delete extra rows

Too fix Columns
- rename column names to make more convenient
- delete columns that are not needed
- Split columns such that you can get more data (for example)
    - date can be split into year, month, day
    - address can be split
    - From a name a title can be extracted
- merge some columns
    - name from last name and first name
    - state district from state and district
    - This is mostly done to create more unique values in one column, over having repetition in two or more columns

### Missing values
What can you do?
- try to find that information from external sources
- fill with values like median, or average (idk how to decide)
- leave as that are

### Standardisation
- see if you need to remove outliers
- convert units/formats appropriately
- scale values if required
- set precision to the appropriate amounts, mostly because when you represent it you should show your accuracy of measurement accurately
To standardise text do the following
- remove extra characters, like extra spaces and shit
- standardise case
- standardise format (like dd/mm/yyyy or whatever)

### fix invalid values
- convert strings to dates or numbers wherever
- Correct non-existant countries or pin codes or whatever
- Correct things that seem to be wrong as they are out of their valid range
- internal rules like date of manufacturing < date of selling etc.


