# atypical_Parkinson

For the atypical Parkinson project, I am using the output from Perseus to run the analyses. The output from Perseus is a cleaned dataset (normalized, transformed, filtered, imputed). The differential abudancy analysis is also done with Perseus. I was not involved in this part of the analysis, this was Ana's work (ana.galhoz@helmholtz-munich.de).

The analyses I performed:
- pathway analysis (GSEA) using signed p-value ranked input that I take from the Perseus differential abundancy analysis
- supervised learning to identify signatures for the aPS, PD, and ctrl (lasso regression, SVM, RF)

The code can be found in the Rmd file. The knitted RMarkdown file can be found in the file ending in html.
