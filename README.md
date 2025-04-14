# CBT378
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 378 is from Steve Kowalski of the Johannesburg Stock      *   FILE 378
//*           Exchange, and contains SORTTRAK, a program to         *   FILE 378
//*           report information from DFSORT SMF records.           *   FILE 378
//*                                                                 *   FILE 378
//*                Szczepan (Steve) Kowalski                        *   FILE 378
//*                The Johannesburg Stock Exchange                  *   FILE 378
//*                17 Diagonal St., Johannesburg                    *   FILE 378
//*                Republic of South Africa                         *   FILE 378
//*                email: stevek@jse.co.za                          *   FILE 378
//*                                                                 *   FILE 378
//*  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  *   FILE 378
//*                                                                 *   FILE 378
//*                        SORTTRAK                                 *   FILE 378
//*                                                                 *   FILE 378
//*                 DFSORT Tuning Reporter                          *   FILE 378
//*                                                                 *   FILE 378
//*      SORTTRAK is reading the SMF records Type 16 -              *   FILE 378
//*               DFSORT Statistics.                                *   FILE 378
//*                                                                 *   FILE 378
//*      Record type 16 is written to record information about      *   FILE 378
//*      events and operations of the DFSORT program.               *   FILE 378
//*                                                                 *   FILE 378
//*      Depending on the option specified at initialization        *   FILE 378
//*      (and whether DFSORT run successfully), a short record,     *   FILE 378
//*      full record, or no record is produced.                     *   FILE 378
//*                                                                 *   FILE 378
//*      Some information in the SMF record will not be             *   FILE 378
//*      provided for certain types of abnormal endings.            *   FILE 378
//*                                                                 *   FILE 378
//*      SORTRAK is performing the following functions:             *   FILE 378
//*                                                                 *   FILE 378
//*      1.  Read SMF records.                                      *   FILE 378
//*      2.  Eliminate non-Type 16 records.                         *   FILE 378
//*      3.  Process records Type 16.                               *   FILE 378
//*      4.  Produce a report.                                      *   FILE 378
//*                                                                 *   FILE 378
//*      The SORTTRAK report contains the following information:    *   FILE 378
//*                                                                 *   FILE 378
//*        1.   Jobname.                                            *   FILE 378
//*        2.   Stepname and step sequence number.                  *   FILE 378
//*        3.   Performance Group Number.                           *   FILE 378
//*        4.   DFSORT started processing: date and time.           *   FILE 378
//*        5.   Sort CPU time used in hundredths of a second.       *   FILE 378
//*        6.   Type of operation performed: Sort, Merge, Copy      *   FILE 378
//*        7.   Method of sorting used: Hiperspace, Dataspace,      *   FILE 378
//*             Work Dataset.                                       *   FILE 378
//*        8.   Was sorting completed in memory (work data sets     *   FILE 378
//*             were not needed) ?                                  *   FILE 378
//*        9.   Were the sort work tracks dynamically allocated?    *   FILE 378
//*       10.   Was Cache Fast Write used ?                         *   FILE 378
//*       11.   Final number of extents.                            *   FILE 378
//*       12.   Final number of Sortwork data set tracks            *   FILE 378
//*             allocated.                                          *   FILE 378
//*       13.   Total number of Sortwork data set tracks used       *   FILE 378
//*             (watch the difference!).                            *   FILE 378
//*                                                                 *   FILE 378
```
