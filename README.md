Problem Inline Method  :
remove the original method declaration for insertUpdate(),removeUpdate(),changeUpdate() 
to inline in the desierd place insted of declrate a function of one line code only.
 
Problem: Deeply Nested code
(double for loop with inner if
statement)
Solustion: better encapsulation
using extract method for the
second loop extract it to intrest
function.
extract new function called actionNew() also actionSaveFile()

Problem: comment in used code
delete un wanted code.

Problem: Long method in buildEditMenu() and buildFileMenu()
solution: sub task the long method or adding comments but for a along code 
or than 10 lines it should sub into smaller method depends on the use 
so in buildEditMenu() break the whole function into smaller function for actions (EDIT,CUT,COPY,PASTE,FIND,SELECT ALL)
also for buildFileMenu() break the whole function into smaller function for actions (NEW, OPEN,SAVE,SAVE AS,QUIT)
