# Jetwave_parser
Jetwave parser


Automatically searches each log file only from the latest date in the file back to the entered date (max 30 days) or 10 days prior if bad date entered.

NOTE: logs must be pulled in latest first convention or the tool would not run properly at this time.

Sorts the “Mx Recommendations” for all 4 logs together and dims the usage log info that helps for context (ex. ‘in Air’, ‘Out of Network)

Combined the Parse, Format, and Scan for mxRec in one feature, while leaving the highlight for manual analysis only. This saves some time and allows all processed logs to be easily read in more detail as we work to improve the recommendations lookups
