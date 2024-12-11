java c
BPE   Senior   Seminar
Fall   2024
Third   assignment   (100   points)
INSTRUCTIONS:   This assignment is due on December 8th    by 11.59 p.m. Please use the following guidelines   to complete the   assignment and submit our work through   NYU   Brightspace.For this assignment, you are required to work   in groups of three students. At the beginning   of your write-   up,   clearly   state   the   full   names   and   net   IDs   of   all   three   members   of   your   group.   It's   essential   that   the   members of your group   remain the   same throughout the semester.
You have the option to   use either Stata or   R   software for this   assignment.   Once you've   made your   choice,   please stick with that software for the entirety   of the semester.Your main write-up should   be formatted using the Times   New   Roman font at a   12pt   size with   1.5   spacing.   If   you're   including   any   code   in   your   assignment,   place   it   at   the   end   in   a   section   titled   "Appendix."   This   section   should   be   formatted      using   the   Courier    New   font,   which    is    best   suited   for    displaying    code   in   documents.It's   important   to   note   that   each   member   of   the   group   must   upload   the   assignment   separately.   When   you're   ready to submit, go to the Assignments tab   in   BrightSpace.   Make sure your document   is saved   and   uploaded   as   a   PDF   file. An   important   detail to   remember   is to   name your file   using   your   network   ID.   For   example, if   your net ID is "rcd306", the file you upload should be named "rcd306.pdf". Although your code   will   not   be graded, you are   required to submit it.   One   or two groups   will   be   randomly   selected   to   present   their code.
The files for completing this assignment are available   on   Brightspace   and   Dropbox
1.          Plotting the   Raw   Data (20   points)Download the   Excel file announcement_replication.xlsx.   In a do-file or R-file write down code that   can perform. the following tasks.   Remember that you need to use the foreign package to open the   excel file.
We are going to replicate   Figure 2A from   “The Rise and Persistence of   Illegal Crops: Evidence   from   a Naïve Policy Announcement” (Prem,   Vargas, and Mejia, 2023)   (page 348).
•          Use the group_by   and   summarize   commands to   get   an   average   of the   suitability   for   coca   and   non-coca   areas for each year.   Don't forget to call   library(dplyr)   (5   points).
•          Replicate the   plot.   You   must   distinguish   between   the   two   areas   based   on   their   suitability   on   the   plot.   Use a   legend as   in the   paper   (10   points).
•          What   is this   plot   suggesting?   (5   points)
2.          Replicating Table   1 (30   points)Write   down the   code   that   r代 写BPE Senior Seminar Fall 2024 Third assignmentR
代做程序编程语言eplicates   only   columns   1,   2,   and   3   of Table   1.   The   standard   errors   in this   case   will   be   the   same   as   in   the   papers   because   the   code   automatically   clusters   at   the   municipality   level, so don't worry   about   it.
•          Replication of the main table   (30   points)   (Hint: You   need to   include different fixed effects   and   controls depending on the specification.       Your outcome is coca_area_grid and       your   independent   variable   is   suit_announce.   Read   what   is   included   in   the   specification   of   each   column.    For example, column    2    includes not only Municipality FE and Year FE, but also   Department   Year FE. Thus, you need to interact    -using    *-    coddepto    with time      FE. The   specification of column    3      also      includes      the      following      controls:      indrural_announcement,   discapital_announcement, IPM_announcement,   lpobl_tot_announcement;    which are   interactions   of   these   with   a   cease   fire   dummy   that    identifies   the    period   after    2013.   Just   include these you don't   need to   interact anything with the controls).
3.          Interpretation (50   points)
•          What is the   control group?   What   is   the   treatment group?   What   is   the   pre-treatment   period?   What is the   post-treatment   period? (10   points)
•          What is   b capturing   in all   of these   three   cases?   (5   points)
•          Explain what does the suit_announce   variable   measures   in   this   setup?      (5   points)
•          Why    do   the   authors   mention   that   the   controls   (municipality   characteristics)   are   measured   before the announcement?    (10   points)
•          Why   do the   authors   include   FE   departments   in   column   2?   If they   include   these   FE,   what   are   we comparing when we get our   b?   (10   points)
•          We   know that the   parallel trends assumption   is   crucial   in   a   diff-in-diff   setup.
o   What resources do the authors use in the   paper to   provide some suggestive evidence   that   low   and   high   coca-suitable   municipalities   follow   similar   trends?   Be   specific   (5   points).
o   What   resources   do the   authors   use   in the   paper to   provide   formal evidence that   low   and   high coca-suitable communities follow similar trends?   Be specific   (5   points).
4.          Extra   (25   points)
•          Do   a    placebo    regression   in   which   you   change   the    date   of   the   announcement.   Run   the   same   regressions   as   you   did   in   columns   1,   2,   and   3.   Show   your   results   using   a   table   (20   points).
•          Are these   result consistent with what we should   have   expected?   (5   points)

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
