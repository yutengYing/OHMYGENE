# Intro
In biology, the expression of genes may be influenced by the external enviroment.This docs show the requirements of the gene expression visualization scatter plot program to satisify biologists for more intuitive description of gene expression.

## Purpose
It is desirable to visualized analysis differential expression of genes.

## Summary
The program requires users to upload one file with .txt or .xls as file name extensions.The file must contain three columns, gene id, control sample, and treatment sample.After uploading the file, the software will return to the user the gene expression scatter diagram whose X-axis is control and Y-axis is treatment.If the user submits an incorrect file or an incomplete file, the program will prompt the user to correctly upload the relevant file.

## User characteristics
Users should be biologists, biological researchers, university professors and so on who need to automatically generate gene expression scatter plot visualization through the network.Visualizing the data will be more conducive to intuitive analysis by the user, and the user would prefer to complete this work through a simple and friendly interface.

## Terminologies
Control sample - A cell sample prepared in its normal condition.

Treatment sample - A cell sample treated by special chemicals, or in which some genes are altered.

Differentially expressed genes - The genes which have significantly different expression levels between two samples.

Up-regulation - A gene is said to be up-regulated if it has higher expression in treatment than in control.

## Abbreviations

OMG - Oh My Genes, which is the name of this project.

logFC - log fold change of gene expression. log_2 [T/C], where T is the gene expression level from a treatment sample, while C is the gene expression level
