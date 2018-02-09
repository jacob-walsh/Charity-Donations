# Charity-Donations
Targetting Potential Donors to Maximize Donations

## Introduction

An important goal for any organization is to use its resources in the most efficient and economical way possible.  This is especially pertinent for non-profit and charitable firms.  Entities such as these are relying on donated funds and, as such, should put additional focus on maximizing available resources.  The objective of this research is to study data of a charitable organization in an effort to determine the most cost-effective methods of fund-raising when it comes to targeting donors for a direct marketing campaign.  

The research will first focus on evaluating models for classification based to a data set of a recent marketing campaign.  The goal will be to identify the set of donors that will yield the highest expected net return after factoring mailing and other costs.  The research will then shift to a prediction model in which the objective will be to estimate donation amounts for a given individual based upon that individual’s characteristics.  

## Data Information
The data set available contains a total of 8,009 observations.  These data are split into three groups of a training data set with 3,984 records, a validation data set with 2,018 records, and a test data set with 2,007 records.  There is present in the data file a weighting scheme that impacts the training and validation data.  The weighting has the effect of equalizing the amount of donors and non-donors in these two data sub-sets.  Due to the weighting in these two data sub-sets, there must be appropriate adjustments to account for a 10% response rate when analyzing the data.
The primary variable of interest for the classification model is DONR.  This variable indicates the status of either Donor or Non-donor for an individual.  The primary variable of interest for the prediction model is the DAMT variable.  This data point indicates the amount contributed by an individual.  There are twenty other independent predictors that will be measured including; REG1, REG2, REG3, REG4, HOME, CHLD, HINC, GENF, WRAT, AVHV, INCM, INCA, PLOW, NPRO, TGIF, LGIF, RGIF, TDON, TLAG and AGIF.
