# cobol-dynamic-tables-api
Dynamic Capacity Tables API for IBM Enterprise COBOL

The 2014 ISO COBOL standard ( INCITS/ISO/IEC 1989:2014 [2014] ) contains a feature known as "dynamic-capacity tables" (described in section 8.5.1.6.3 of the standard document).  As of this writing I do not believe that any implementor of a COBOL compiler has implemented even part of this feature.  IBM has already rejected a Request For Enhancement for this feature.

My goal with this API is two-fold.

1) To get around the fact that Enterprise COBOL does not currently offer this feature, and perhaps never will.

2) To demonstrate how such a feature may work (at run-time, not syntactically).
