# Barnett-Zehnwirth-Spreadsheet
Loss Reserving Regression Model on a Spreadsheet

## Model

This spreadsheet fits a model with trends in up to three directions: accident (origin) year, development year, and calendar (valuation) year. Each cell of the triangle looks like

$p(i,j) = \alpha_i+\sum_{m=1}^j \gamma_m + \sum_{n=1}^{i+j} \iota_n + \epsilon_{i,j}$

The error terms are assumed to be normal with fixed, finite variance.

## Usage
Paste a triangle onto the Triangle sheet (top left at B2). Coefficients are outputted on the Regression sheet. Illustrative graphs to come later.

## Papers
This model is described across multiple papers authored by this repository's namesakes.

https://www.casact.org/sites/default/files/database/forum_08fforum_3barnett_zehnwirth.pdf 

https://www.casact.org/sites/default/files/database/proceed_proceed00_00245.pdf

## Compatibility
This spreadsheet relies heavily on lambda functions. Excel 365 is recommended; Maybe Excel 2021 and later will work.

## Stuff that Needs work
1. Graphs
2. Full (predicted) triangles
3. Better support for blank cells
4. This readme
