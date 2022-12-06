---
layout: page
title: Homework 2
subtitle: T4,T5, TA2, A2, A3, A4

---

# Theory
## T4
### Concept of distribution. Univariate and multivariate. Conditional and marginal distributions.

A distribution in statistics is a function that shows the possible values for a variable and how often they occur. The distribution of an event is made up of all possible values. Infact, we are sure that we have exhausted all possible values whe the sum of probabilities is equal to 1 (or 100% if we are using the percentage). Lets do an example to understand better: we are observing a class composed by 100 students and we want to know the distribution of the hair’s color.

|Hair’s color	| Relative Frequency
|:------|:------
|Brown	| 15/100
|Red	|35/100
|Blond	|40/100
|Black	|10/100
|Total	|100/100

A distribution can be univariate, multivariate, marginal and conditional depending on how many variables the distribution refers to and on conditions on these variables.

Univariate analysis is the simplest form of analyzing data.”Uni” means “one”, so in other words univariate analysis explores each variable in a data set,separately. We have the observation on only a single charateristic or attribute.

Multivariate analysis is defined as a process of involving multiple dependent variables resulting in one outcome. Another definition for multivariate analysis,similar to the precedent, is the statistical study of data where multiple measurements are made on each experimental unit and where the relationships among multivariate measurements and their structure are important.Multivariate analysis is one of the most useful methods to determine relationships and analyse patterns among sets of data.

Conditional distribution represents the likelihood of an event to occur given a particular outcome of another event. It is a distribution of values for one variable that exists when we specify the values of other variables.This type of distribution allows you to assess the dispersal of your variable of interest under specific conditions, hence the name. It is usually represented as P(x|y).

A marginal distribution gives information about the various values a set of variables can take, without reference to the values of the other variables, while in a conditional distribution there is conditioning of some variables’ values on other variables’ values.

**References:**
Enciclopedia Treccani (https://www.treccani.it/enciclopedia/distribuzione)
Statistics lecture notes (06/10/2022)
Statistical distribution – IBM Documentation: (https://www.ibm.com/docs/en/cognos-analytics/11.1.0?topic=terms-statistical-distribution)


# Applications
## A2: 
### Make a simple demo program which uses the objects RANDOM and TIMER in C# and VB.NET
The proposed solution is in the ZIP file that can be found at [this GitHub link](https://github.com/pulell-af/StatisticsHomeworks/tree/main/Homework2.1Csharp)).


## A3: 
### Make a simple CSV parser that can ead a CSV file
The proposed solution is in the ZIP file that can be found at [this GitHub link](https://github.com/pulell-af/StatisticsHomeworks/tree/main/Homework2.2Csharp).


## A4: 
### Compute a univariate distribution of a variable after reading a variable from a CSV file [optional: give the user the possibility to choose any of the column of the CSV file]
The proposed solution is in the ZIP file that can be found at [this GitHub link](https://github.com/pulell-af/StatisticsHomeworks/tree/main/Homework2.3VisualBasiccorrect).



# Research on app
## TA2 
### What are the main differences between C# and VB.NET?
CSV, Comma Separated Values (strict form as described in RFC 4180)
**Description**	
CSV is a simple format for representing a rectangular array (matrix) of numeric and textual values. It an example of a "flat file" format. It is a delimited data format that has fields/columns separated by the comma character %x2C (Hex 2C) and records/rows/lines separated by characters indicating a line break. RFC 4180 stipulates the use of CRLF pairs to denote line breaks, where CR is %x0D (Hex 0D) and LF is %x0A (Hex 0A). Each line should contain the same number of fields. Fields that contain a special character (comma, CR, LF, or double quote), must be "escaped" by enclosing them in double quotes (Hex 22). An optional header line may appear as the first line of the file with the same format as normal record lines. This header will contain names corresponding to the fields in the file and should contain the same number of fields as the records in the rest of the file. CSV commonly employs US-ASCII as character set, but other character sets are permitted.
Widely used as an exchange format for tabular data. Although very limited in functionality, there are many data exchange or data preservation contexts for which it is adequate, particularly when the syntax and semantics of fields are described in ancillary documentation that is also exchanged or preserved. CSV files can be imported and exported by almost any software designed for storing or manipulating data, including relational database systems, spreadsheet software, and statistical analysis software.
**Adoption**
CSV is a preferred format for interchange in many contexts because it is so easy to process. Recommended Data Formats for Preservation Purposes in the Florida Digital Archive lists CSV as a format with a high confidence level of providing ongoing access in a usable form. CSV is a recommended format for data deposit with Library and Archives Canada, a supported format in MIT's DSpace implementation, and a recommended format for long-term retention by the State Archives of North Carolina. CSV was one of the primary formats into which the UK National Archives converted datasets that were selected for the National Digital Archive of Datasets between 1997 and 2010 (after which a government initiative promoting open data eliminated the need for such conversion by the National Archives). It is the preferred format for preparing tabular environmental data at the Oak Ridge National Laboratory and its use for tabular data is a best practice for the DataONE (Data Observation Network for Earth) project. Most government open data initiatives have CSV as one of the primary formats in which data can be downloaded. For example, CSV is one of the formats in which data from the U.S. Data.gov can be downloaded. Others include XML, ESRI shapefiles (ESRI_shape), and KML. The last two are for geospatial data.
**References:**
(https://www.loc.gov/preservation/digital/formats/fdd/fdd000323.shtml)
