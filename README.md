java c
DATA1002 /   1902 -   Informatics:   Data and Computation
2024 Sem2
Project Stage   1   (Notes)
Due: 11:59pm on Sunday at the end of week 6
Value: 5% of the unit


TASK   1: IDENTIFY    TOPIC:
For example, it   is   not   a   good   to   ask   just   “which   country   has   the   highest   level   of   wealth?”   but   it   is   a   good   choice   of   question   to   ask   “what   influences   the   level   of   wealth   in   a   community?”   .   You   might look   at   datasets   that   relate   to   the   economy, climate, education, type   of   government   etc.
TASK 2: OBTAIN    DATASETS    AND   METADATA:
While   you   can   choose   datasets   as   you   wish,   there   are   some   extra   requirements   if   you   aim   for   higher marks,   not   just   Pass   level.
•             If   the   group   is   hoping   to   score   above   Pass   level,
•          The   different   datasets   (from   the   different   members) should   all   “have   independent   origin”   .
•          Note   that   this   refers   to   the   origin   or   primary   source   of   the   datasets;   it   is   ok   for   the   data   to have   been   obtained   from   the   same    data-providing   website,   as    long   as   the   origins   are   different.
•          For   example,   data.gov.au   offers the   possibility   to   download   many   datasets,   similarly,   the   various      competitions      at    kaggle.com    often    have    datasets   from    quite    different   origins.
•             You      also      should         ensure      that         each      dataset      has      “   medium         volume      of      data”,    so      that   automation of processing becomes crucial.
•          For defining   volume,   we   will   consider   the   number   of   “values”: for the   most   common   case,   rectangular   data   e.g., CSV. The   contents   of   a   field   for   an   item   would   be   a   value. A   dataset   is   considered   as   medium   volume   if   it   contains   at    least      1,000   values.    If   we visualise   the   data   loaded   into   a   spreadsheet   with   100   rows   and   10   columns,   it   will have   1,000 values   (excluding   the   column   headers).
•             Finally,   it   isn’t   graded   in   this   stage,   but   to   score   well   in   later   stages, your   integrated   dataset needs   to   contain   both   the   following:
•          at   least   one   attribute   whose   value   is   either   a   count   or   a   measurement   (a   number   in   terms   of   some   unit), and
•          at   least   one   attribute   whose   value   is   a   string   (or   numeric   identifier   where   the   values   a代 写DATA1002 / 1902 - Informatics: Data and Computation 2024 Sem2 Project Stage 1Python
代做程序编程语言re   not meaningful as   numbers,   like the student   id).




TASK 3: ENSURE    DATA    QUALITY:
For example, the work   needed   may   be   removing instances that   have corrupted or   missing values   or   filling   in   those   missing   values   in   some   sensible   way;   you   may   be   correcting   obvious   spelling   mistakes   or   bringing   different   date formats   to   a   common   standard;   maybe   you   need   to   remove   duplicate   rows, or deal with inconsistent   information (e.g., two   different values for   population of   the same country).
TASK 4: PRODUCE    SOME    DATA   SUMMARIES:
   For example, you might calculate (and show the code in your report) the highest value of wealth   among   all   the   countries,   or   the   number   of   countries   in   the   Asia   region.   This   is   not   intended   to   be   a   detailed   exploration   of   the   data   (that   will   come   in   Stage   Two),   but   it   is   simply   a   demonstration   that   the dataset is now in a form. where you can work with it, and that you have the required skills   in Python   coding.
   TASK 5: INTEGRATE    THE    DATA   SETS:
For example, we might want to integrate climate data from different locations. It is easiest when   the   datasets share   a structure   (for   example, they   may   represent   climate   data   in   different states,   all      with      the      same      schema      such      as      “city,      date,    maxtemp,      mintemp,    rainfall      (mm)”),      so      that   integration is   nothing   more than combining the   rows one after another   (perhaps   adding   an   extra   attribute   to distinguish which dataset each row came   from). However, if   the datasets do   not share   a structure, then there   is a   lot of decisions   needed to   find   a   common   structure   into   which   all   can   be   placed (and   how to deal with eg   missing values   etc).Another case is where the datasets contain different attributes for the same entities; for example,   one   might   have   climate   data   for   cities   on   dates,   and   another   dataset   has   transport   data   for   the   same   cities   and   dates.   In that case, the   integration   can simply   make   a   longer   row for each   entity,   with   all   the   different   attributes   from   the   datasets   (eg   city   and   date,   followed   by   climate   attributes and   then by transport attributes).    However, care is needed, if the entities are described      with different   formats   etc,   so   that   transformation   is   needed   to   allow   them   to   be   matched   up   across   data sets.
   





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
