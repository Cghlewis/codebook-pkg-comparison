I started this table as a way to compare existing r packages that assist in codebook creation. The criteria I am looking for include the following variable level metrics (specifically for working with `haven::labelled()` data):

- Name
- Label
- Type
- Values (if categorical)
- Value labels (if categorical)
- NA values (Missing values: for example -99 and -98)
- NA labels (Missing value labels: for example -99 = No response, -98 = Unclear response)
- Total valid N
- Total missing N
- N per value (if categorical)
- % per value (if categorical)
- N per NA value (User-defined labelled missing value)
- % per NA value (User-defined labelled missing value)
- Range (if continuous)
- Mean (if continuous)

A table of all packages I reviewed can be found here: https://cghlewis.github.io/codebook-pkg-comparison/

If you see that I have mistakenly marked any category for any package, please let me know and I will update!

Ultimately I have narrowed the table down to these 5 packages. I removed several packages from this final table because they do not work well with `haven::labelled()` data and/or they do not meet enough of the criteria above.

*Note: `dataMaid` has been renamed to `dataReporter`. You can read more about it [here](https://github.com/ekstroem/dataMaid)

![](https://github.com/Cghlewis/codebook-pkg-comparison/blob/main/img.PNG)

Other helpful resources: 

- https://www.researchgate.net/publication/333153930_How_to_Automatically_Document_Data_With_the_codebook_Package_to_Facilitate_Data_Reuse/fulltext/5cde1601299bf14d959f792e/How-to-Automatically-Document-Data-With-the-codebook-Package-to-Facilitate-Data-Reuse.pdf?origin=publication_detail
