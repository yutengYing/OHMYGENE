# Functionality

## Initialize input:
**Requirement 1:** users can upload one file in form of .txt or .xls

**Rationale 1:** the program processes data and requires the support of the file to generate a sequence representation scatter plot.

**Test scenario:** add the document extraction boxes to the initial interface so that the user can submit the document.

**Priority:** high

## Default output:
**Requirement 2:** after processing files, the program will automatically generate the scatter diagram of gene expression , so that users can make visual analysis, and provide the scatter correlation coefficient for reference.

**Principle 2:** internal processing of the program to generate the scatter diagram in the default state, as well as related data.

**Test scenario:** the gene is selected by default to draw the scatter plot and describe the characteristics.

**Priority:** high

## Go back to the main page:
**Requirement 4:** when one set of genetic files is analyzed and the user wants to test another set of genetic files, he jumps back to the file upload page in the page.

**Rationale 4:** meet the functional needs when users have multiple sets of genetic test files.

**Test scenario:** add the option of returning the home page to the interface for returning.

**Priority:** low

##  Exception handling:
**Requirement 5:** users need feedback when uploading invalid, lost, and abnormal files.

**Rationale 5:** exception handling reduces extra time for the user in order to provide a better user experience.

**Test scenario:** when the user uploads invalid, corrupted, and abnormal files, a popup window will prompt.

**Priority:** medium
