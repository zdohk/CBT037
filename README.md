~~~~~~~~~~~~~~~~

//***FILE 037 IS AN MVS VERSION OF COPYCAT TO MOVE, SPLIT,          *   FILE 037
//*           AND/OR REORGANIZE CVOL CATALOGS.  THIS VERSION        *   FILE 037
//*           RUNS UNDER MVS AND THE RESULTANT CVOL MAY BE          *   FILE 037
//*           LISTED WITH IEHLIST.  THIS VERSION HAS 3380 AND       *   FILE 037
//*           3375 SUPPORT ADDED FROM UCLA.  THIS FILE IS IN        *   FILE 037
//*           IEBUPDTE SYSIN FORMAT SEE THE MEMBER CALLED $$DOC     *   FILE 037
//*           FOR ADDITIONAL INFORMATION.                           *   FILE 037
//*                                                                 *   FILE 037
//*         $CBTJCL .. THE JCL USED AT CBT TO INSTALL               *   FILE 037
//*         $MANUAL .. THE COPYCAT MANUAL                           *   FILE 037
//*         $UCLAJCL.  THE JCL USED AT UCLA TO INSTALL              *   FILE 037
//*         COPYCAT .. COPYCAT CODE ITSELF                          *   FILE 037
//*         FIX1    .. FIX ESATE01 - CONVERTS COPYCAT FROM STAE TO  *   FILE 037
//*                    ESTAE USE AND CORRECTS AN S30A ABEND THAT    *   FILE 037
//*                    OCCURS FOLLOWING AN X37 ABEND.               *   FILE 037
//*         FIX2 ..... FIX XCP200  - CORRECTS AN S200 ABEND THAT    *   FILE 037
//*                    INTERMITTENTLY OCCURS IN COPYCAT AFTER AN    *   FILE 037
//*                    'X37' ABEND, DUE TO ALL OF THE I/O NOT       *   FILE 037
//*                    HAVING COMPLETED BEFORE SVC55 IS ISSUED      *   FILE 037
//*                    FOR AN END-OF-VOLUME INDICATION.             *   FILE 037
//*         OAC1 ..... FIX DEV3380 - ADDS 3380 SUPPORT TO COPYCAT   *   FILE 037
//*         OAC2 ..... FIX HASH001 - UCLA LOCAL MODE.  SEE MEMBER   *   FILE 037
//*                    FOR ADDITIONAL INFORMATION.                  *   FILE 037
//*                                                                 *   FILE 037
~~~~~~~~~~~~~~~~

