# PX-file-format
A new version of the PC-Axis file format

|Keyword            |Mandatory|Multiplicity|Language dependent|Default value |
|-------------------|---------|------------|------------------|--------------|
|AGGREGALLOWED      |No       |0-1         |No                |YES           |
|AXIS-VERSION       |No       |0-1         |No                |              |
|BASEPERIOD         |No       |0-?         |Yes               |              |
|CELLNOTE           |No       |0-?         |Yes               |              |
|CELLNOTEX          |No       |0-?         |Yes               |              |
|CFPRICES           |No       |0-?         |No                |              |
|CODES              |Yes      |0-16        |No                |              |
|CONTACT            |No       |0-?         |Yes               |              |
|CONTENTS           |Yes      |1           |Yes               |              |
|CONTVARIABLE       |Yes      |0-1         |Yes               |              |
|COPYRIGHT          |No       |0-1         |No                |NO            |
|CREATION-DATE      |Yes      |0-1         |No                |              |
|DATA               |Yes      |1           |No                |              |
|DATANOTE           |No       |0-?         |Yes               |              |
|DATANOTECELL       |No       |0-?         |Yes               |              |
|DAYADJ             |0-1      |0-?         |Yes               |NO            |
|DECIMALS           |Yes      |1           |No                |              |
|DESCRIPTION        |No       |0-1         |Yes               |              |
|DESCRIPTIONDEFAULT |No       |0-1         |No                |              |
|DOMAIN             |No       |0-16        |No                |              |
|ELIMINATION        |No       |0-16        |Yes               |NO            |
|HEADING            |Yes      |(0)-1       |Yes               |              |
|LANGUAGE           |Yes      |1           |No                |              |
|LANGUAGES          |No       |0-1         |No                |              |
|LAST-UPDATED       |No       |0-1         |No                |              |
|MATRIX             |Yes      |1           |No                |              |
|META-ID            |No       |0-?         |Yes               |              |
|NOTE               |No       |0-?         |Yes               |              |
|NOTEX              |No       |0-?         |Yes               |              |
|OFFICIAL-STATISTICS|No       |0-1         |No                |NO            |
|PRESTEXT           |No       |0-16        |No                |TEXT          |
|REFPERIOD          |No       |0-1         |Yes               |              |
|SEASADJ            |No       |0-?         |No                |NO            |
|SHOWDECIMALS       |No       |0-1         |No                |              |
|SOURCE             |No       |0-1         |Yes               |              |
|STOCKFA            |No       |0-?         |Yes               |              |
|STUB               |Yes      |0-1         |Yes               |              |
|SUBJECT-AREA       |Yes      |1           |Yes               |              |
|SUBJECT-CODE       |Yes      |1           |No                |              |
|SYNONYMS           |No       |0-1         |No                |              |
|UNITS              |Yes      |1-?         |Yes               |              |
|UPDATE-FREQUENCY   |No       |0-1         |No                |              |
|VALUENOTE          |No       |0-?         |Yes               |              |
|VALUENOTEX         |No       |0-?         |Yes               |              |
|VALUES             |Yes      |1-16        |Yes               |              |
|VARIABLE-CODES     |Yes      |1           |No                |              |
|VARIABLE-TYPE      |No       |0-16        |No                |              |
|VARIABLES          |Yes      |0-16        |Yes               |              |
